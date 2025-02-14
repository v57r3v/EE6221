java c
EE6221-ROBOTICS AND INTELLIGENT SENSORS
SEMESTER 2 EXAMINATION 2023-2024
1. A robotic manipulator with six joints is shown in Figure 1.

Figure 1
(a) Obtain the link coordinate diagram by using the Denavit-Hartenberg (D-H) algorithm. (12 Marks)
(b) Derive the kinematic parameters of the robot based on the coordinate diagramobtained in part (a). (8 Marks)
2. A Cartesian robot with two degrees of freedom is in contact with a workpiece, which is shown in Figure 2.

Figure 2
The dynamic equations of the robot, when it is not in contact with the workpiece, aredgiven as follows:

where ux, u, are the control inputs and dy,dy are the unknown constant disturbances.The stiffness of the workpiece in any direction is given as 50 N/m and the static positionof the workpiece in the v axis is 0.25 m. The system possesses unmodelled resonances at7 rad/s and 15 rad/s.
(a) Assume that dy=0 and dy=0. Design a hybrid position and force controller for the robot. The motion control subspace should be critically damped, and the force control subspace should be overdamped with a damping ratio of 1.25. The control gains should be chosen to be as high as possible and the system should not excite all the unmodelled resonances. (13 Marks)
(b) Assume that dy, dy are not negligible. Design an appropriate hybrid position and force controller and show that the steady state error can be eliminated.代 写EE6221 - ROBOTICS AND INTELLIGENT SENSORS SEMESTER 2 EXAMINATION 2023-2024
代做程序编程语言 In case that the stiffness of the workpiece is wrongly estimated as 49 N/m, discuss its effects on the controller. (7 Marks)
3. (a) A mobile robot platform. with a shape of an equilateral triangle (i.e., all three sideshave the same length) attached to a square is shown in Figure 3. The robot has onesteered standard wheel, two standard wheels and one castor wheel. A local referenceframe. (x yr) is assigned at the mid-point between the steered standard wheel andthe castor wheel. The radius of each standard wheel is 6 cm and the radius of thecastor wheel is 3 cm. Let the rotational velocities of the steered standard wheel, thetwo standard wheels and the castor wheel be denoted by фss, ds1, s2, and фc,respectively. Derive the rolling and sliding constraints of the mobile robot.

Figure 3
(10 Marks)
(b) A robot manipulator with three ioint variables g, g2. ga are mounted on a mobile robot. The link-coordinate homogeneous transformation matrix from the basecoordinate to the tool coordinate of the rohot maninulator is given as follows

where S1 = sin (q1), S2 = sin (q2), S23 = sin(q2 + q3), C1 = cos (q1), C2 =cos(q2), C23 = cos(q2+q3).
Solve the inverse kinematic problem using the analytic method toexpress (q1, q2, 93)T in terms of the position of the end effector (x, y, z)T(Note: the orientation is not required). (10 Marks)







         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
