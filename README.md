# A-frame_physics

In this example I include objects that are intectuated and affected by physics.
In order to test it, it is necessary to use Oculus.
## Physics activated:
-Gravity
-Colitions

Adding basic physics to a scene using the physics system component. 

## Oculus controls:

- The "raycaster-extras" component adds graphical enhancements to the raycaster system, with an appearance similar to the Quest splash screen: the raycaster ray is a cylinder with a gradient texture applied, and the intersection point is indicated with a cursor. Entities with the new "raycaster-target" component class can set booleans that make an object glow when the raycaster points at it, and allow an object to be grabbed by holding the right grab button. While holding, an object can be pulled towards or pushed from the controller with the right joystick.

- The player-move component simplifies movement in a scene. A navigation mesh class can be set, in which case a marker will appear indicating when the beam points to the corresponding mesh, and the right trigger activates teleportation. In addition, the left joystick controls first-person navigation, forward/backward and left/right movement. Pressing the left trigger while moving increases the movement speed. While holding the left grip button, the left joystick causes the user to fly up/down and turn left/right.
