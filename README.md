# FGCT4007: Interactive Narratives

FGCT4007: Interactive Narratives

Keisha Byrne

2401317

## Research

### What sources or references have you identified as relevant to this task?

I identified some sources that would have been that would be beneficial for this project and I decided to explore written sources like forums about bank heist games. I just explored what the feedback was from them and what people would find interesting in bank heist games after having played a few. I felt like if I looked at like reviews then it would relate to the brief as it's an interactive game so I wanted to make sure that all the details were there and that we wasn't missing any details in the environment as well as in the mechanics as I wanted the game to feel immersive as well as having fun.

 I wanted to avoid YouTube reviews on these games because some of those reviews can be quite biased and I just wanted it from players perspective rather than a content creator perspective as the player is the target audience in this case so I found that would have given us the most genuine responses and be able to tailor the game exactly to those needs that people will have wanted to be met.


## Sources

I found two sources that I ended up really enjoying what they had spoken about. One source (What Would Make The Perfect Bank Robbing Game? - News & General Discussion, 2015) was someone who said that when they look around the game world there's not a lot of people and a world of  500 shouldn't have 500,000 cops. This was quite important because it meant that we had to focus on making the right amount of police AI in the game in comparison to the population so that it felt like more realistic. This impacted the amount of AI that we chose to have in the end.

 There was also another comment saying that hiest games shouldn't just be a run in game, that there should be some planning involved.(What Would Make The Perfect Bank Robbing Game? - News & General Discussion, 2015) When we were deciding our game and how it would run we made sure that there was different steps involved before the player could get to the Vault where the money is. For example we decided on the players having to go talk to the NPCs to get a key card to unlock the vault and a password that they had to find out through security or the CCTV. This just makes it feel  that there's more to do in the game rather than just running in  straight for the money as they have to work for it. This creates a bit of a challenge for the player, making the game more enjoyable. 
 
  There was also another quote that someone said in response to a bank heist escape room they played (Mairi, 2021). Mairi said that they never felt like they were actually in a high security vault. So we took this upon ourselves and made sure that the design and the surrounding areas of that actual building we're in had a lot of assets on them. For example picture frames which told a story. This makes the player feel like they are in the game rather than it just being an empty room with money on the floor. So this impacted the design of the level layout in order to make it more immersive.

I found these sources beneficial as a developer because it allowed me to broadcast to the designers the aspects we need to make the game more immersive and more fun and make sure that we wasn't missing anything so that the player had a really positive experience. These sources in my opinion were very good and I agree with them as well especially the the number of the AI. 



## Implementation

### What was the process of completing the task? What influenced your decision making?



When we were given this project I started by making a figma board (Figma, s.d.) and I was given a flowchart on how the game would exactly plan out. Then from this flow chart, I broke it down and found the game mechanics that we would need and I wrote it on a sticky note on the side of the flow chart so that I could see exactly what needed to be done. I then just went through the list 1 by 1 allowing myself to have enough time to be able to implement all these mechanics and plan accordingly to what I would do each week so that we were on track.
<img src="https://raw.githubusercontent.com/kdogz9/FGCT4007Framework/refs/heads/main/image-1.png?token=GHSAT0AAAAAADELGQG4KAOFCXQSVLVQFNRO2BPF4QA" alt="Figma board">
<p>Figure 1. Figma board of game mechanics and flow chart.<p>

 We also had a Milanote (Campbell, s.d.) where we have all of our sources and our ideas and our planning down as well so that we were all on the same track. This avoided miscommunication which allowed the group to flow quite well when it came to making the game.

 <img src="https://raw.githubusercontent.com/kdogz9/FGCT4007Framework/refs/heads/main/image-3.png?token=GHSAT0AAAAAADELGQG4CZD6ZICJV64L56ZI2BPF4ZA" alt="Milanote">
<p>Figure 2. Milanote for each week of the project.<p>

After the planning had been done for this project, I started on making the code for a computer screen where the player presses E to interact with it and the UI comes up in the viewport to show the status of whether the Vault is locked or unlocked.(UNREAL ENGINE 5 HOW TO PICKUP AND READ NOTES TUTORIAL, 2023)
<iframe src="https://blueprintue.com/render/rs6p_6kl/" scrolling="no" allowfullscreen></iframe>

<img src="https://raw.githubusercontent.com/kdogz9/FGCT4007Framework/refs/heads/main/image-5.png?token=GHSAT0AAAAAADELGQG424SSR33SNXR2I7QG2BPF5LA" alt="Computer screen UI">
<p>Figure 3. Computer screen code for when the player interacts with it and the UI which appears.<p>

I then changed the UI of the existing dialogue system to make it match the theme of our game.

<img src="https://raw.githubusercontent.com/kdogz9/FGCT4007Framework/refs/heads/main/image-6.png?token=GHSAT0AAAAAADELGQG4HPDCB4DTB3O75VT42BPF5XA" alt="NPC UI">
<p>Figure 4. NPC UI

After this I thought it would be a good idea to make normal doors  be interactive by using the e key as well as also having a code door and a key card door. I wanted to make it feel a bit more immersive by being able to open the other doors as well.(Open and Close Door Tutorial in Unreal Engine 5, 2024)

<iframe src="https://blueprintue.com/render/viefp88e/" scrolling="no" allowfullscreen></iframe>

<p>Figure 5. Opening normal doors code </p> 

Doing this gave me experience with using timelines. When it came to making the key pad system for the code door it roughly used the same code apart from adding a widget and making the buttons interactive in the widget so this was easier to pick up and took me less time as I had an idea on what to do already. (Open Doors With A Password In Unreal Engine 5 Using Blueprints, 2023) 

<iframe src="https://blueprintue.com/render/_r-ylxjz/" scrolling="no" allowfullscreen></iframe>

<p>Figure 6. Key pad door code <p>

<iframe src="https://blueprintue.com/render/584gmedo/" scrolling="no" allowfullscreen></iframe>

<p>Figure 7. Widget buttons code <p>

Then I moved on to making CCTV cameras using a render target material (How To Create Dynamic CCTV/Security Cameras In Unreal Engine 5 (Tutorial), 2024) and made a button so that when it was pressed it added extra time onto the timer and changed the render target material to black to show that the cameras had been turned off and thus affecting the police arrival by adding extra time onto the timer.

<iframe src="https://blueprintue.com/render/wq2bphrt/" scrolling="no" allowfullscreen></iframe>
<p>Figure 8. Code to set the material of the camera screens.<p>

<iframe src="https://blueprintue.com/render/d0c_phwr/" scrolling="no" allowfullscreen></iframe>
<p>Figure 9. Code for the cameras to capture the scene and create the render target material<p>

<iframe src="https://blueprintue.com/render/4timtkh9/" scrolling="no" allowfullscreen></iframe>
<p>Figure 10. Code for the button to add extra time and change the material of the screens<p>

I added a gun system onto the first person character just to make it easier and neater for the code aspect and I experimented with the Niagara system in unreal to add particles to act as water to make it a water gun rather than adding bullets. This was quite a tricky system for me to implement so this took a bit longer for me to be able to do but I definitely learn a lot with using line traces and I feel a lot more comfortable with them now.

<iframe src="https://blueprintue.com/render/m3a5dw1b/" scrolling="no" allowfullscreen></iframe>
<p>Figure 11. Gun mechanic code in First person.<p>

Once that had been finished I was able to move on to the score system(Score system in Unreal Engine 5 in under 4 minutes, 2022) where the player sprays the money and can get a score up to 100 and then it changes the material of the money to look wet. Then the player can move on to the next set of money and add an extra increment of 100 to their score to be able to try and get the highest score before the police come and start searching for them.

<iframe src="https://blueprintue.com/render/gkkcxhu0/" scrolling="no" allowfullscreen></iframe>
<p>Figure 12. Score widget code <p>

<iframe src="https://blueprintue.com/render/2ho7g9tx/" scrolling="no" allowfullscreen></iframe>
<p>Figure 13. Money score system.<p>

I made a key card system for a door where the player has to pick up the key card and have it in their inventory to be able to open the door in front.This was quite easy to pick up in the tutorial that I followed as it explained it in depth.(How To Make Keycard Doors | Unreal Engine 5 Tutorial, 2024)

<iframe src="https://blueprintue.com/render/wlii91jo/" scrolling="no" allowfullscreen></iframe>
<p>Figure 14. Code which allows the player to pick up the keycard and destroys it once picked up<p>

<iframe src="https://blueprintue.com/render/dch6u-r5/" scrolling="no" allowfullscreen></iframe>
<iframe src="https://blueprintue.com/render/zr8slorw/" scrolling="no" allowfullscreen></iframe>
<p>Figure 15. code which checks for the keycard and allows player through<p>

Once all the game mechanics were pretty much done I then decided to work on the AI spawn system and the timer which when the timer ended the AI (police) were spawned.

<iframe src="https://blueprintue.com/render/is9xnb3o/" scrolling="no" allowfullscreen></iframe>

<iframe src="https://blueprintue.com/render/y38q9byq/" scrolling="no" allowfullscreen></iframe>
<p>Figure 16. Timer and spawn system.<p>

 I had to implement the AI to roam around(AI Random Roam | Basic Roaming - Unreal Engine 5 Tutorial, 2022) and also search for the player character (AI Sight Detection And Chase - Unreal Engine 5 Tutorial, 2022)
 <iframe src="https://blueprintue.com/render/rexdstv5/" scrolling="no" allowfullscreen></iframe>
 <p>Figure 17. AI roaming and searching code<p>

  If they found them then when they interacted with player a game over screen would appear on the game and the player would have to restart the game symbolising that they've been caught.(Player Catching AI UE5.1 | Unreal Simple Enemy AI 3 of 3, 2023).
  
  <iframe src="https://blueprintue.com/render/me271vei/" scrolling="no" allowfullscreen></iframe>
  <p>Figure 18. Game over screen displayed when AI catches player<p>
  
  <iframe src="https://blueprintue.com/render/dsrydfme/" scrolling="no" allowfullscreen></iframe>
  <p>Figure 19. Allows the player to press any button to restart<p>

   This was quite tricky to implement because the timer system had to link with spawning the AI and I struggled a little bit with that but now I feel a bit more confident and I feel like I would definitely explore this area more in the future.

I also added an enemy tag onto the AI so that when the particles came into contact with the AI it would kill them and set off a ragdoll physics to show that they had died and then it would destroy the AI. This is so that the player would be able to shoot back at the AI and any other NPCs they needed to shoot relating to the story of the game. 

<iframe src="https://blueprintue.com/render/7o3av1mu/" scrolling="no" allowfullscreen></iframe>
<p>Figure 20. Gun/particles checking for enemy tag and destroying the actor if they come into contact<p>

<iframe src="https://blueprintue.com/render/lr4mv7my/" scrolling="no" allowfullscreen></iframe>
<p>Figure 21. AI dying when particles hit them code<p>


### What creative or technical approaches did you use or try, and how did this contribute to the outcome?

Part of one of the game mechanics was we wanted a water gun instead of like a gun with bullet so this meant that I had to work with a new system in Unreal which was the Niagra system. I have never worked with particles before so I found this quite challenging at first so it took a bit longer for me to do as I had to do a lot of research into how the system actually works by watching some YouTube videos and looking up documentation but after a while I started slowly getting more comfortable with it and I feel like it came out really effective. I feel more comfortable with working with the Niagara system in the future as well.

### Did you have any technical difficulties? If so, what were they and did you manage to overcome them?

I had some difficulties with the water coming out the gun as it did not look like water so I had to change the particle effect that I used a couple of times until it represented water. This was a little bit time consuming but it didnt have an effect on the development process. I also had some difficulties with the AI detecting the particles when it hit them so I had to adjust my line trace and figure out where I was actually hitting by debugging it quite a lot. I also had to debug the button to turn off the CCTV cameras because the material was not working correctly and I realised that all it needed was an is valid node and that managed to fix that issue. 


## Outcome

Here you can put links required for delivery of the task, ensure they are properly labelled appropriately and the links function. The required components can vary between tasks, you can find a definative list in the Assessment Information. Images and code snippets can be embedded and annotated if appropriate.



## Critical Reflection

### What did or did not work well and why?

I think that we managed to fit the briefing quite well with having four different NPCs that affected the progress in the game meaning the player has to talk to all of the NPCs and interact with them to be able to find out the codes and where the key card is to be able to get to the vault for the money for example. We made our own lore behind the game as well which made the game quite religion heavy. I think this makes it a lot more interactive and feel like that there's depth to the game rather than it just being you go in get money. I also feel as a group we can communicated really well and everything that was needed was on time so this didn't stop the development or slow us down in any way so we were able to work quite effectively and efficiently.I also think we planned quite well so we were never lost during this whole process which made us be able to stay on task and the things that we implemented we're also on the right track.

 I feel like I could have developed the Mechanics a lot further and I feel like we could have also looked more into the games sources and taken a bit more inspiration from them to make it a more realistic bank heist game. I also feel that although communication was strong for the majority of it, there were some parts that were a bit weaker which ended up getting parts of the game in the last week and this was an extra level of stress which couldve been avoided.

### What would you do differently next time?

In the time frame given for this project I wasn't able to implement as many mechanics as I would have liked. If I had the chance to do this again I would probably add moving cars, maybe a couple more cut scenes to make it feel more like a bank heist game rather than just shooting the money.I mean our game is quite in depth but I feel like with a bit more time I wouldve been able to develop it further.


## Bibliography

Open and Close Door Tutorial in Unreal Engine 5 (2024) At: https://www.youtube.com/watch?v=XYEhlkd3YNs (Accessed  17/05/2025).
 
 Open Doors With A Password In Unreal Engine 5 Using Blueprints (2023) At: https://www.youtube.com/watch?v=_PCp21x2pCI (Accessed  17/05/2025).

How To Create Dynamic CCTV/Security Cameras In Unreal Engine 5 (Tutorial) (2024) At: https://www.youtube.com/watch?v=WkOydCLTbVQ (Accessed  17/05/2025).
 
 Score system in Unreal Engine 5 in under 4 minutes (2022) At: https://www.youtube.com/watch?v=sAy-rCwJ8y8 (Accessed  17/05/2025).

How To Make Keycard Doors | Unreal Engine 5 Tutorial (2024) At: https://www.youtube.com/watch?v=d6PEmrdtUjM (Accessed  17/05/2025).

How To Create A Timer And Stopwatch In Unreal Engine 5 (Tutorial) (2024) At: https://www.youtube.com/watch?v=e_oNZAFfrbk (Accessed  17/05/2025).

AI Sight Detection And Chase - Unreal Engine 5 Tutorial (2022) At: https://www.youtube.com/watch?v=tKrBdxm4uxI (Accessed  17/05/2025).

AI Random Roam | Basic Roaming - Unreal Engine 5 Tutorial (2022) At: https://www.youtube.com/watch?v=Mi7r0LqUmOE (Accessed  17/05/2025).

Player Catching AI UE5.1 | Unreal Simple Enemy AI 3 of 3 (2023) At: https://www.youtube.com/watch?v=CnmQDqZLnlg (Accessed  17/05/2025).

What Would Make The Perfect Bank Robbing Game? - News & General Discussion (2015) At: https://discussions.unity.com/t/what-would-make-the-perfect-bank-robbing-game/588230 (Accessed  17/05/2025).

Mairi (2021) Escape Entertainment: Bank Heist | Review. At: https://theescaperoomer.com/escape-entertainment-bank-heist-review/ (Accessed  17/05/2025).



## Declared Assets

Chewy Bubble Font | dafont.com (s.d.) At: https://www.dafont.com/chewy-bubble.font (Accessed  17/05/2025).


The following assets were created or modified with the use of Voice Typer 4.7.4:

- Development Journal.html


