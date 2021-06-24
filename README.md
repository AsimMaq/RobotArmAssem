# RobotArmAssem
Assembly of Robot Arm:
NOTE: I used SolidWorks to assemble this arm, insert meshes as solid bodies from (Open> Options> Solid bodies), you'll notice that they're "imported" shapes.

Defining shapes:
1) starting with the base: define the diameter of the base by a construction geometry to mate base with other elements later
2) afterwards, open "wrist" and define the diameter of its base and the middle circle by the same way
3) then, define the big circle of "arm 01" from both ends. do so on "arm 02".
4) finally, define the big circle in the "gripper".

Connecting:
1) After that: mate the "base" and the "wrist" by concentric both diameters and distance mate of 0mm.
2) Mate "arm 01" with "wrist" by concentric one of the end with the defined circle in the "wrist" and and distance mate of 0mm.
3) Mate "arm 01" with "arm 02" by concentric the circular end of "arm 02" with "arm 01" and distance mate of 0mm.
4) mate "arm 02" with "gripper" by concenrating the other end of the arm with circle of the "gripper".
