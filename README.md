UnrealGame
==========

Game Dev Project 4

Verbs: Chase, Splice

Our game is a top-down rolling game in which the player controls a virus. The player's objective is to roll around and corrupt all the other cells before being caught by the white blood cells. By corrupting other cells you create more virus cells and buy yourself time in addition to getting closer to your win condition.

Programming Part:

Player:
-	Player state (power ups)
    Shockwave: push other cell back -----> explosion in UE4
    Invincibility: invincible for x seconds ------> turn off damage
    Speed: increase speed ---------> movement speed
    Rate of inflection: decrease loading process time ------> change process time
-	Infections
    Get close
    Press button, roll with you
    Loading progress bar, finish
    Press button, release
-	Change to another Eball
-	Animation

Other cells:
-	White Blood Cell chasing
    Sphere of detection/ speed increase 
-	Spawn Points
-	Eball AI
-	Victim Cell AI
-	Animation for them

System: 
-	Win/Lose Conditions: 
    Win: if critical mess hit
    Lose: no more other Eball
-	Camera
    Auto Adjust to player directions
-	GUI
