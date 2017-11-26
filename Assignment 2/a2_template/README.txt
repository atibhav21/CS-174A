The game is a first person shooting game, where the aim is to shoot down the helicopter.
The player can move his arm using the keys i,k,l and o. The player shoots using the "p"
key. Once the helicopter is hit with 5 bullets, it goes down, and the game ends.

Mechanics:
The path of the bullets shot is computed using Euler's method using forward computation.
This gives the bullets a parabolic path when fired, as gravity and drag force are the only
forces acting on the bullet.
Hierarchical Objects:
The player has 4 levels of hierarchy, each of which can be moved separately using the keys.
