# DivineComedy
Andreas Karpasitis

The team:
Gawlowski Witold, Veselov	Nikita, Hlabangana	Khulamuzi, Burton Edward, Karpasitis Andreas

Divine Comedy is based on a 2D Action shooter game called Downwell. The objective of the Downwell is to descend chasms and caves and blast your way across blocks and enemies to reach the end goal. We liked the idea of falling and shooting, so we decided to take that element of Downwell and turn it into a 3D FPS game.

The essence of Divine Comedy is to fall and shoot at the same time, while maintaining the right altitude and speed so that you can collect halos and reach the end of each level with as many halos as possible. The gun mechanics devised by Witek allowed the player to fire the gun and generate knock back. That allowed the player to navigate through the level. Damage to platforms and to the character if the player landed too harshly was also added, in order to add a sense of danger. The player's view was rotated on its access so that the character seemed like he was always falling instead of the traditional eyes forward camera standard FPS games used. That's immediately noticeable as you leap off platforms and blasting down at blocks.

The entire project proved to be quite the challenge for our team. There were many obstacles that we managed to overcome to produce what we have now. Given that the five of us had never worked with each other in a project in the past, I'm actually pleased with what we created. However, I think given more favourable circumstances, our project could have been much better, which is why I plan on adding a few more details in the near future to further realise our vision.

Our team's most significant issue, were the demands of Unreal Engine 4 on all of our systems. Even during the early stages of development, the performance issues were staggering. On my 6 year old MacBook Pro, Unreal would crash at least nine to ten times during  8 hours of working on the project. My teammates also had similar issues, so that limited the number of caves, produced by Nikita's cave generation code, we could put in the game level. Masking levels off didn't help, as I could only add one or two 15x15x70 caves before the lag was crippling. Reducing the texture resolution for meshes wasn't that much of a help either. I even took out enemies, and various special effects that I had done for landing and shooting. That is evident in video tech demo, where the game barely runs at 20 FPS with its bare bones.

Our first problem as a team was getting sourcetree to work properly. Witek spent hours learning the ins and outs of sourcetree so that we could get it to work. Working on a Mac it was quite different than working on a PC so Witek and I tried to get everything organized and face all the errors head on. Nikita assisted where he could, subbing for Witek when he was not available. 

The biggest kink in our team dynamic was getting everyone together in one room. The holidays got in the way for all of us. I had a flight booked weeks before the project was announced to go back home for the holidays, so did Eddy and Nikita at some point. Khula worked during the holidays, so he wasn’t always available. However, I maintained constant communication between the artists and programmers through Facebook and Skype, acting as a sort of liaison between the team. There was only one instance of total silence the week after Christmas. Aside from the holiday hangovers, I got a tooth infection and had to get a root canal and was on antibiotics for a week. Thankfully, beyond those mishaps, most of the time I could reach everyone. While the programmers had finished the majority of the code before Christmas, us artist had to coordinate models and textures, as well as level design. We were a bit overzealous with our expectations of the game and focused too much on asset creation than level design up until Christmas. Unfortunately, I learned that level design should precede content creation a bit too late in the development stage.


Thankfully, we did manage to work together. Even though most of the coding was done by Witek and Nikita, they allowed me add some minor tasks relating to the visual elements of the game. I created several blueprint instances for materials. I added emissive properties and used blueprint to have pickups and halos rotate and glow.
https://s29.postimg.org/53kndeamf/gun_material_instance.png
https://s29.postimg.org/57egtng3r/halo_material_instance.png
I also edited the DivineCharacter blueprint that Witek was working to swap out the gun mesh and add a custom animation clip to it so that it played every time the player fired.
https://s29.postimg.org/sta3238zr/gun_animation.png
The hardest for me to add was the blueprint for the halo pick-ups. Aside from adding a collision parameter where the halo disappears when colliding with the character, I also made it so that if the player fired their weapon at a halo, it would be destroyed instead of being picked up. The halos that the player collected by colliding with them would stack up and displayed as score at the top of the screen.
https://s29.postimg.org/g4fsif2vb/halo_collection.png
https://s29.postimg.org/6xxhv4xmv/halo_collision.png
I tried not to ask for Nikita and Witek's help with my blueprints, but anytime there was an issue I couldn't identify, such as destructible meshes and incorrect collisions, they were there to help.

All in all, it was a good experience, albeit a rocky one. Knowing what I know now, I am sure that if I could do it over with better equipment, the final product would look drastically different.
