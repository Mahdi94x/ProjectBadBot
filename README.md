# ProjectBadBot

Developed with Unreal Engine 5.6.0

Based on the course Unreal Engine 5 Blueprints - The Ultimate Developer Course by Stephen Ulibarri  

This project is a third-person shooter game developed using Unreal Engine 5 Blueprints, focused on building a complete gameplay loop and learning core game development concepts. The player controls a drone equipped with a blaster to eliminate enemy bots and a boss in a sci-fi-themed level.

Features Implemented in ProjectBadBot  

Player Drone Mechanics  
* Custom 3D drone character with movement, camera control, and gravity-free flight.  
* Smooth third-person follow camera using spring arm and rotation logic.  
* Floating drone behavior and looping animation.  

Blaster Weapon System  
* Fully functional blaster beam created with Niagara VFX and Blueprints.
* Beam projectile setup with collision detection, sound effects, and damage application.

Shooting Logic  
* Implemented input handling to fire the blaster when the player clicks or presses a key.
* The beam is spawned from the drone's muzzle and travels forward using projectile motion.
* The beam use line trace by channel to ensure accurate hit event.

Enemy AI (Bad Bot)  
* Enemy bot that detects, pursues, and attacks the player using line of sight.
* Attack behavior controlled via AI Controllers.
* Damage response with hit reactions, sound, and health-based destruction.

Boss Fight  
* Larger, stronger bot with unique explosion VFX and higher health pool.
* Custom Niagara-based boss explosion using advanced particle tweaking.

UI & HUD  
* Cross Hair widget to help the player in aiming.

Sound & VFX  
* Integrated 3D spatial sound effects for shooting, explosions, and bot destruction.
* Multiple Niagara particle systems for shooting, sparks, and boss explosions.

Game Flow & Polish  
* Final win condition upon defeating the boss.
* Modular and scalable Blueprints for easy feature expansion.
