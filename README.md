**Moon Lander**

Moon Lander is a game based on the Atari 1979 game Lunar Lander. The object of the game is to safely navigate a moon lander to land on a platform on the moon. Horizontal thrusters are used to maneuver the ship lift and right and vertical thrusters are used to slow its descent.

**Game Play and Rules**
The following describes the rules and gameplay of Moon Lander:
The dimensions of the screen are: (-200, -200) to (200, 200).
The lander begins with 500 units of fuel.
To land successfully, the lander must:
have its center within the horizontal boundaries of the platform.
be within 4 pixels vertically, above the platform.
arrive at the platform with a velocity of no more than 3 pixels per frame in any direction.
Gravity on the moon can be modeled as 0.1 pixels per frame.
The left arrow key causes thrust on the left of the lander which propels it to the right (and similar for the right and down arrows).
The left and right thrust amounts are 0.1 pixels per frame and consume 1 unit of fuel.
The upward thrust (caused by the down arrow) amount is 0.3 pixels per frame and consumes 3 units of fuel.
The lander should have inertia, in other words, once it begins moving left, it should continue moving left unless additional thrust is made.
The lander should not continue to move after crashing or landing.
After successfully landing, the game should display, "You have successfully landed!"
After crashing, the game should display, "You have crashed."
After running out of fuel, the lander should not be able to apply thrusters (but can continue falling).
Any other contact with the ground or platform results in a crash.
This game was done as a project for an Object-Oriented Software Development class. Some of the 

**What I did**
I did not work on all the files. The game, point, ground, uiDraw, and uiInteract classes were provided. I implemented the lander and velocity classes.
