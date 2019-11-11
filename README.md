# Biped-Humanoid-Robot Battle

This Biped-Humanoid-Robot is a titanium alloy robot, which resembles human-beings body. Generally, a biped humanoid robot have a torso, a head, two arms, as well as two legs. The robot requires a combination of hardware and software knowledge, integrating the expertise of the electrical, mechanical, and software knowledge. It is the best learning element for interdisciplinary learning. On the hardware side, we will learn how to operate and fix various sensors and motors. In software, we will use the Visual-basic like programming language. Here, we are going to design the battle robot. We can design the robot with our need. This robot is bought from [Robosmart Technology](http://robosmart.com.tw/zh-tw/classes_con.php?id=NDU=). It provides us an opportunity to build our own robot!

<div align=center><img width="450" height="450" src="https://github.com/christw16/Biped-Humanoid-Robot-Battle/blob/master/img/3.jpg"/></div>

## Content

  * [Component](#Component)
  * [Installation](#Installation)
  * [Start](#Start)
  * [Servo-motor](#Servo-motor)
  * [Control](#Control)
  * [Discussion](#Discussion)
  * [Reference](#Reference)
 
  
## Component

The Biped-Humanoid-Robot mainly consists of:
 * Innovati Servo Commander 16 control module
 * IQ4516HV Servomotor
 * CC2541 2.4-GHz Bluetooth
 * USB Mini-B
 * PS2 wireless controller
 
Battery:
 * Desire Power V8 11.1V 1300mAh 35C-70C 3S LiPo Battery
 * Balance Battery Charger
 
## Installation

Operating system: Microsoft Windows 10<br/>
Install [innoBASIC Workshop 2](http://www.innovati.com.tw/website/down/html/?113.html) commander for execute the code
![pic1](https://github.com/christw16/Biped-Humanoid-Robot-Battle/blob/master/img/1.jpg)

## Start
 * First of all, we should check the controlloer and battery whether is fully charged.
 * Second, connect the battery with the robot.
 * Thirdly, observe the controller is whether connected to the robot.(red indicator light)
 <div align=center><img width="600" height="450" src="https://github.com/christw16/Biped-Humanoid-Robot-Battle/blob/master/img/15.jpg"/></div><br/>
 
Open the InnoBASIC Workshop 2 commander in Windows search<div align=center><img width="1/400" height="100" src="https://github.com/christw16/Biped-Humanoid-Robot-Battle/blob/master/img/17.jpg"/></div><br/>
 
Inside the commander is the code editor.
![pic12](https://github.com/christw16/Biped-Humanoid-Robot-Battle/blob/master/img/12.jpg)
 
Open the InnoBASIC Workshop 2 commander, we click   <div align=center><img width="100" height="100" src="https://github.com/christw16/Biped-Humanoid-Robot-Battle/blob/master/img/5.jpg"/></div><br/>

It can alter the servomotor angle by adjusting the value, it also can change the time and speed option on the servomotor.<br/>
CH0, CH1, ....to CH15 represent individual servo motor. <br/>

At the bottom, the left side allows us to save/load the file in our local computer. The right side allows us to save/load the file in the cmu on the robot.
<div align=center><img width="700" height="500" src="https://github.com/christw16/Biped-Humanoid-Robot-Battle/blob/master/img/4.jpg"/></div><br/>

After editing the program, using USB Mini-B to connect computer and robot, as well as clicking "build" in the InnoBASIC Workshop 2 commander to transmit program to the robot
<div align=center><img width="100" height="100" src="https://github.com/christw16/Biped-Humanoid-Robot-Battle/blob/master/img/11.jpg"/></div><br/>

## Servo-motor

This is the picture of servo motor. (Attention: servo motor angle's range 800~2200)
<div align=center><img width="300" height="300" src="https://github.com/christw16/Biped-Humanoid-Robot-Battle/blob/master/img/7.jpg"/></div><br/>

  * Maintainance:<br/>
     If the servo motor works unusual. For example: Smoke appear or stuck. Please stop using it immediately. You may condsider changing the new one or fix it.
  * Position:<br/>
     There are 15 servos motors in the robot.<br/>
     The picture below is the each servo motor corresponding to the robot.<br/>
     <div align=center><img width="300" height="300" src="https://github.com/christw16/Biped-Humanoid-Robot-Battle/blob/master/img/10.jpg"/></div><br/>
     

## Control
Here we use PS2 wireless controller to control our robot

<div align=center><img width="450" height="450" src="https://github.com/christw16/Biped-Humanoid-Robot-Battle/blob/master/img/14.jpg"/></div>

## Discussion

 1.  * Q: If the robot cannot walk properly in different grounds, how should I do?

     * A: Currently, we are learning how to design a robot which can adapt different kinds of environment. Now, we can adjust the robot manually.

2.   * Q: Is it possible to do any action we want?
  
     * A: Yes, You can design any action and accomplish your ideas on your own.

3.   * Q: What is the robot's application?
  
     * A: There exist a great numbers of applications. Currently, we complete gymnastics and so far work on the application with computer vision
## Reference

https://en.wikipedia.org/wiki/Humanoid_robot








We appreciate Prof. Po-Chiang Lin as our advisor.

