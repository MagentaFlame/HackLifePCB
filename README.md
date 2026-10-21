Hello!
This is a spin-off of the Starbie starter PCB project for Half Life.
I didn't have much experience, so I started off going step-by-step. However, after gaining some confidence, I made the following changes:
- changed the PCB base layer design to be the mastery symbol from League of Legends
- added sprite statuses for my poro (regular = 1 type of sprite, when sleeping, the sprite icon changes to a sleeping one, when interacting and having hearts with it, the sprite changes again)
- added a switch that would change between sprites (I'm thinking poro and soori for LOL and HLE or maybe a diff character, but yeah two different characters with unique sprites, habits, etc)

Ahead of the LOL World Championships, I hope I can create some fun things that will embody my excitement! After assembling the parts, I'll check out how the sparkle trails look - I might change them to be lines to represent rainbows or something.

Let's start with schematic.
<img width="1042" height="646" alt="image" src="https://github.com/user-attachments/assets/cc5ab7f3-fc82-4a7a-8941-0ca10cb46d72" />
Other than the starter project parts, I added a switch so I could change between sprites. I just connected an IO to the switch one - a simple SPST slide switch.

Next is PCB.
<img width="687" height="614" alt="image" src="https://github.com/user-attachments/assets/f123316d-f916-48c2-b78d-7157660c39a7" />
I made it into a mastery symbol (LOL) shape, and used the pcb routing to form the front layer's detailing while adding silkscreen on the back to make the wings and gem pop out. 

I plan to get a solder from the shop b/c I have no hardware tools basically. I have the basic arduino code modified to include sprite 1, but I plan to research a bit more during build week on how to use the switch to switch between sprites - should be just a variable connecting to the switch + a new set of variables and a few if statements, hopefully.

Here's my BOM, links can be found in my project page in Half Life and the BOM.md in github.
<img width="907" height="613" alt="image" src="https://github.com/user-attachments/assets/3fb65d8a-a949-492b-9e68-93be30d61eec" />
