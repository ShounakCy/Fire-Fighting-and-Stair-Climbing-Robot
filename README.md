# Fire-Fighting-and-Stair-Climbing-Robot

ABSTRACT OF BACHELOR THESIS

In today&#39;s world, robots are increasingly being integrated into working tasks to replace
humans. They are currently used in many fields of applications including office, military
tasks, hospital operations, industrial automation, security systems, dangerous environment
and agriculture. Several types of mobile robots with different dimensions are designed for
various robotic applications. The robot has been designed for the purpose of aiding rescue
people. Common situations that employ the robot are urban disasters, hostage situations, and
explosions. This paper describes the construction and design of a “Fire-Fighting Stair-
Climbing Industrial Robot (FFSCIR)”.
In 2016, many European nations faced the wrath of wildfires, and there my inquisitive nature
tempted me to designed FFSCIR for my undergraduate thesis. In this project, I proposed to
design an autonomous robot that can climb stairs as well as extinguish fire. The robot is
designed to reach un-accessible areas like stairs, uneven path and would douse fire for
humans risking their life daily. Thus, our approach is to combine Stair Climbing with the use
of elevated wheels and continuous track belts and chains with Fire Fighting mechanism using
flame sensors to detect fire and douse fire using water-pump. Thereafter, we have look
forward to Image processing using camera which will capture the image of fire at larger scale
instead of sensors and make it more efficient for the surveillance.
The robot maneuvered using advanced navigational algorithms like A-star and PID control.
The system controls two optically isolated D.C. geared motors. For this, infrared QTR
sensors are used as the input sensor which is connected at different levels of the chassis.
Flame sensors which are connected to an L-shaped plank, which rotates with the help of
servo motors, senses the infrared rays coming out of the fire and it feeds the signal to the
respective microcontroller. The extinguishing system is comprised of a D.C. water pump and
a water container. The microcontroller in turn controls the water-extinguishing system. It is
used to dispense water and control the fire. The water pump is actually a sucker that has a
water tank from which it sucks water and then throw it through the sprinkler. This is a fully
automated system and no manual interference is required.
In this paper, a microcontroller board based on the ATmega2560 and dual bidirectional motor
driver based on L298 Dual H-Bridge Motor Driver Integrated Circuit is used, which
performed a set of operations and controls the movement of the robot. To curb the
disadvantages of using the IR Fire sensors which may cause due to environment changes and
range limitations, computer vision mechanism was deployed over raspberry pi using a USB
camera to detect the flames. The two-layer fire detection makes the fire detection system in
our robot more robust and reduces the error. Various image processing algorithms like
Gaussian Blur, Filter2D and CNN algorithms were used to draw contours around the detected
flame. Upon implementation, the ordinate and abscissa of the image is successfully obtained.
Experimental results are carried out for a six-wheel mobile robot to illustrate the proposed
methodology. The results show that the proposed robot model is successfully implemented.

This project was also amongst the top two projects in the College to be represented at
NCRDE-2017.

