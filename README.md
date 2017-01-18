# DivineComedy
Andreas Karpasitis

The team:
Gawlowski Witold, Veselov	Nikita, Hlabangana	Khulamuzi, Burton Edward, Karpasitis Andreas

Divine Comedy is based on a 2D Action shooter game called Downwell. The objective of the Downwell is to descend chasms and caves and blast your way across blocks and enemies to reach the end goal. We liked the idea of falling and shooting, so we decided to take that element of Downwell and turn it into a 3D FPS game.

The essence of Divine Comedy is to fall and shoot at the same time, while maintaining the right altitude and speed so that you can collect halos and reach the end of each level with as many halos as possible. The gun mechanics devised by Witek allowed the player to fire the gun and generate knockback. That allowed the player to navigate through the level. Damage to platforms and to the character if the player landed too harshly was also added, in order to add a sense of danger. The player's view was rotated on its access so that the character seemed like he was always falling instead of the traditional eyes forward camera standard FPS games used. That's immediately noticeable as you leap off platforms and blasting down at blocks.

The entire project proved to be quite the challenge for our team. There were many obstacles that we managed to overcome to produce what we have now. Given that the five of us had never worked with each other in a project in the past, I'm actually pleased with what we created. However, I think given more favorable circumstances, our project could have been much better, which is why I plan on adding a few more details in the near future to further realise our vision.

Our team's most significant issue, were the demands of Unreal Engine 4 on all of our systems. Even during the early stages of development, the performance issues were staggering. On my 6 year old MacBook Pro, Unreal would crash at least nine to ten times during  8 hours of working on the project. My teammates also had similar issues, so that limited the number of caves, produced by Nikita's cave generation code, we could put in the game level. Masking levels off didn't help, as I could only add one or two 15x15x70 caves before the lag was crippling. Reducing the texture resolution for meshes wasn't that much of a help either. I even took out enemies, and various special effects that I had done for landing and shooting. That is evident in video tech demo, where the game barely runs at 20 FPS with its bare bones.

Furthermore, the team wasn't quite as unified due to the holiday schedule. I had a flight booked weeks before the project was announced to go back home for the holidays, so did Eddy and Nikita at some point. However I maintained constant communication between the artists and programmers through facebook and skype, acting as a sort of liaison between the team. Thankfully most of the time I could reach everyone. While the programmers had finished the majority of the code before Christmas, us artist had to coordinate models and textures, as well as level design. We were a bit overzealous with our expectations of the game and focused too much on asset creation than level design up until Christmas. Unfortunately I learned that level design should precede content creation a bit too late in the deveolopment stage.


Thankfully, we did manage to work together. Even though most of the coding was done by Witek and Nikita, they allowed me add some minor tasks relating to the visual elements of the game. I created several blueprint instances for materials. I added emissive properties and used blueprint to have pickups and halos rotate and glow.
[url=https://postimg.org/image/ymk52nkn7/][img]https://s29.postimg.org/ymk52nkn7/halo_material_instance.png[/img]
[url=https://postimg.org/image/oy6oziptv/][img]https://s29.postimg.org/oy6oziptv/gun_material_instance.png[/img][/url]
I also edited the DivineCharacter blueprint that Witek was working to swap out the gun mesh and add a custom animation clip to it so that it played every time the player fired.
[url=https://postimg.org/image/hgxhkb0ar/][img]https://s29.postimg.org/hgxhkb0ar/gun_animation.png[/img][/url] 
The hardest for me to add was the blueprint for the halo pick ups. Aside from adding a collision parameter where the halo disappears when colliding with the character, I also made it so that if the player fired their weapon at a halo, it would be destroyed instead of being picked up. The halos that the player collected by colliding with them would stack up and displayed as score at the top of the screen.
[url=https://postimg.org/image/8ogiwmf5v/][img]https://s29.postimg.org/8ogiwmf5v/halo_collection.png[/img][/url]
[url=https://postimg.org/image/lh4mwjqrn/][img]https://s29.postimg.org/lh4mwjqrn/halo_collision.png[/img][/url]

