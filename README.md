<div align=center><img width="450" height="450" src="https://github.com/christw16/Biped-Humanoid-Robot-Battle/blob/master/img/logo1.jpg"/></div>

This YZUEI Robot is a titanium alloy robot, which resembles human-beings body. Generally, a biped humanoid robot have a torso, a head, two arms, as well as two legs. The robot requires a combination of hardware and software knowledge, integrating the expertise of the electrical, mechanical, and software knowledge. It is the best learning element for interdisciplinary learning. On the hardware side, we will learn how to operate and fix various sensors and motors. In software, we will use the Visual-basic like programming language. Here, we are going to design the battle robot. We can design the robot with our need. This robot is bought from [Robosmart Technology](http://robosmart.com.tw/zh-tw/classes_con.php?id=NDU=). It provides us an opportunity to build our own robot!

<div align=center><img width="450" height="450" src="https://github.com/christw16/Biped-Humanoid-Robot-Battle/blob/master/img/3.jpg"/></div>

# Content

  * [Component](#Component)
  * [Installation](#Installation)
  * [Robot_Action_Programming](#Robot_Action_Programming)
  * [Preliminary_prepare](#Preliminary_prepare)
  * [Check_and_start](#Check_and_start)
  * [Discussion](#Discussion)
  * [Video](#Video)
  * [Code](#Code)
  * [Reference](#Reference)
  * [Members](#Members)
  * [Gratitude](#Gratitude)
 
  
# Component

The Biped-Humanoid-Robot mainly consists of:
 * Robot
 * Innovati Servo Commander 16 control module
 * IQ4516HV Servomotor
 * CC2541 2.4-GHz Bluetooth
 * USB Mini-B
 * PS2 wireless controller
 
Battery:
 * Desire Power V8 11.1V 1300mAh 35C-70C 3S LiPo Battery
 * Balance Battery Charger
 
# Installation

1. Operating system: Microsoft Windows 10<br/>
Install [innoBASIC Workshop 2](http://www.innovati.com.tw/website/down/html/?113.html) commander for execute the code
![pic1](https://github.com/christw16/Biped-Humanoid-Robot-Battle/blob/master/img/21.jpg)

The system is composed of several different parts.The innoBASIC Workshop environment which is a software utility running in the PC. The user’s program is edited with the innoBASIC editor. After editing, the program is compiled and downloaded from within this environment. Also, a Terminal Window is available as the Human Interface or Debug console. Then via the USB interface, the finished program code is downloaded to the BASIC Commander Single Board Computer. <br/>

There are three kinds of resources can be used. First is the General-Purpose I/Os, for which built-in commands are provided for sophisticated functions; second is the cmdBUSTM, where up to 32 Innovati featured Peripheral Modules can be connected. Thirdly is the debug interface, where information can be exchanged between the BASIC Commander and the innoBASIC Workshop Terminal Window.
 ![pic25](https://github.com/christw16/Biped-Humanoid-Robot-Battle/blob/master/img/25.jpg)

This system needs IBM or Compatible PC running under Windows 98 or above version/2000/ME/XP/Vista/10. A USB 1.1 /2.0 port is a must, which is essential for your program downloading and debugging. 

# Robot_Action_Programming
 
1. Open the InnoBASIC Workshop 2 commander in Windows search <div align=center><img width="300" height="500" src="https://github.com/christw16/Biped-Humanoid-Robot-Battle/blob/master/img/17.jpg"/></div><br/>
 
Inside the commander is the code editor.
![pic12](https://github.com/christw16/Biped-Humanoid-Robot-Battle/blob/master/img/20.jpg)
 
2. Open the InnoBASIC Workshop 2 commander, we click   <div align=center><img width="100" height="100" src="https://github.com/christw16/Biped-Humanoid-Robot-Battle/blob/master/img/5.jpg"/></div><br/>

3. It will show up a window. We choose "Default" in the kit preset, and choose "Servo commander 16" in the Left used module. Press "OK".
![pic27](https://github.com/christw16/Biped-Humanoid-Robot-Battle/blob/master/img/27.jpg)

Then, it will pop up a warning sign to warn you to check to servo motors's position. Press "OK".

![pic28](https://github.com/christw16/Biped-Humanoid-Robot-Battle/blob/master/img/28.jpg)

4. Below is the step of using Innovation motion editor to edit the servo motors value.

(I) It represent the frame ID from 1 to 200.

(II) CH0, CH1, ....to CH15 represent individual servo motor ID. (Click the ID will activate that corresponding servo motor).

(III) It can alter the servomotor angle by adjusting the value. The angle range is from 800 to 2200.

(IV) "Time" represents the duration of the change of servo motor. The time unit is in milli-second(ms).

(V) Save the action value of the action to the PC as a ftxt file or read ftxt file from PC.

(VI) Save the action value in Innovati Servo Commander 16 control module or read the action value from Innovati Servo Commander 16 control module.

 ![pic25](https://github.com/christw16/Biped-Humanoid-Robot-Battle/blob/master/img/29.jpg)


5. After editing the program, using USB Mini-B to connect computer and robot, as well as clicking "build" in the InnoBASIC Workshop 2 commander to transmit program to the robot
<div align=center><img width="100" height="100" src="https://github.com/christw16/Biped-Humanoid-Robot-Battle/blob/master/img/11.jpg"/></div><br/>

# Preliminary_prepare
(1) servo motor

This is the picture of servo motor. (Attention: servo motor angle's range 800 to 2200)
<div align=center><img width="300" height="300" src="https://github.com/christw16/Biped-Humanoid-Robot-Battle/blob/master/img/7.jpg"/></div><br/>

  * Maintainance:<br/>
     If the servo motor works unusual. For example: Smoke appear or stuck. Please stop using it immediately. You may condsider changing the new one or fix it.
     
  * Position:<br/>
     There are 15 servos motors in the robot.<br/>
     The picture below is for the each servo motor corresponding to the robot.<br/>
     <div align=center><img width="300" height="300" src="https://github.com/christw16/Biped-Humanoid-Robot-Battle/blob/master/img/10.jpg"/></div><br/>
     
(2) Battery

This is the picture of battery. (Attention: battery voltage's range 10.0 to 12.60V)

![pic24](https://github.com/christw16/Biped-Humanoid-Robot-Battle/blob/master/img/34.jpg)
    
 Charging
   
   Connect the battery with the charger
       <div align=center><img width="300" height="300" src="https://github.com/christw16/Biped-Humanoid-Robot-Battle/blob/master/img/35.jpg"/></div><br/>
   
   1.Press "Stop" and choose "Lipo" 
   
   2.Press"+" to choose the mode balance.
   
   3.Press "Start". When it is fully charged, the charger will ring. Please press"Stop"
   
   <div align=center><img width="300" height="300" src="https://github.com/christw16/Biped-Humanoid-Robot-Battle/blob/master/img/36.jpg"/></div><br/>

## Warnings

 * 1. When we are doing robot action programming or using the robot, we should observe the temperature of servo motors whether is too high. If it is too high, stop using it or the servo motors might damaged or crashed.
 * 2. The servo motors angle is from 800 to 2200. Please prevent beyonding the range.
 * 3. When you observe that the servo motors cannot do action or abnormally do some weird action. Please immediatley stop using it. Try to replace a new one.
 * 4. Every time before using the robot, ㄣlease verify all screws have been properly fastened to avoid damages which may be caused by loosened parts.
   5. Before using the battery, please checking the battery voltage. If the voltage is less than 10V, use balance battery charger to charge it. The full voltage is 12.60V.
	

# Check_and_start
Check the battery whether is fully charged.

<div align=center><img width="600" height="450" src="https://github.com/christw16/Biped-Humanoid-Robot-Battle/blob/master/img/31.jpg"/></div>

Holding the PS2 controller near the robot.

<div align=center><img width="450" height="450" src="https://github.com/christw16/Biped-Humanoid-Robot-Battle/blob/master/img/32.jpg"/></div>

Connect the battery with the robot.

  <div align=center><img width="600" height="450" src="https://github.com/christw16/Biped-Humanoid-Robot-Battle/blob/master/img/18.jpg"/></div><br/>

Press "START" button on the PS2 controller to connect with the robot. If the robot is connected, the servo motors will be fixed. If it is not connected, the indicator red light on the PS2 controller will flash on the controller.
 
<div align=center><img width="600" height="450" src="https://github.com/christw16/Biped-Humanoid-Robot-Battle/blob/master/img/33.jpg"/></div>


  
Here we use PS2 wireless controller to control our robot.

![pic24](https://github.com/christw16/Biped-Humanoid-Robot-Battle/blob/master/img/24.jpg)


When it is conntected sucessfully, the robot will be stiff and the motor will be fixed as well.

Notice: These buttons can be set by ourselves!

# Discussion

 1.  * Q: If the robot cannot walk properly in different grounds, how should I do?

     * A: Currently, we are learning how to design a robot which can adapt different kinds of environment. Now, we can adjust the robot manually.

2.   * Q: Is it possible to do any action we want?
  
     * A: Yes, You can design any action and accomplish your ideas on your own.

3.   * Q: What is the robot's application?
  
     * A: There exist a great numbers of applications. Currently, we complete gymnastics and so far work on the application with computer vision
 
 
4.   * Q: What programming language is used?

     * A: Visual basic-like programming language.
     
     
5.   * Q: How do I assembly the robot?

     * A: Please visit the website and follow the instructions.
     


# Video

Let's try some difficult action!

Gymnastics

[One-handed handstand](https://www.youtube.com/watch?v=5fRVJbHhV6Q)
	   
[Jump rotation](https://www.youtube.com/watch?v=VnRADacrUuY)
    
[Backwards rotation](https://www.youtube.com/watch?v=si86ftxEGCs)
  
  
# Code

Code will be uploaded after the end of the competition

# Reference

https://en.wikipedia.org/wiki/Humanoid_robot

http://robosmart.com.tw/zh-tw/classes_con.php?id=NDU=


# Members
Team members: 

 Yuan Ze University - International program in electrical and communication engineering department

   Yuan Ze University - International program in electrical and communication engineering department

  Ching-Hsien Hsu - Yuan Ze University - International program in electrical and communication engineering department
   
Advisor:

  Po-Chiang Lin - Yuan Ze University - Professor of Electrical engineering department program B

# Gratitude

We appreciate Prof. Po-Chiang Lin as our advisor.

We also appreciate those who helped us along the way
