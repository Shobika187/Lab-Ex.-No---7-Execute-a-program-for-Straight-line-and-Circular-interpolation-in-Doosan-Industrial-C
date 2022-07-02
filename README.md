# Lab-Ex.-No---7-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-cobot
## Aim : To Execute a program for Straight-line and Circular interpolation in Doosan Industrial Cobot using DRL studio.

## Components Required:

*Doosan Industrial Collaborative Robot

*DRL (Doosan Robotics Language) Studio Software

### Theory 
INTERPOLATION

Interpolation, which is necessary for any type of programming, consists of generating data points between given coordinate axis positions. Within the Machine Control Unit (MCU), a device called an interpolator causes the drives to move simultaneously from the start to the end of the command. The interpolator is either an electronic hardware device for a NC system, or a software program for a CNC system. An interpolator provides two functions:

It calculates individual axis velocities to drive the tool along the programmed path at the given feed rate.

It generates thousands of intermediate coordinate points along the programmed path between the start point and the end point of the cut.

During positioning, all programmed axes move simultaneously at the specified feed rates until each axis has reached its destination. All drives start together, but without an interpolator individual destinations are reached successively according to the path traveled. However, an interpolator coordinates these axis motions in such a way that the programmed path is constantly maintained from the beginning to the end of the movement.

Linear and circular interpolation are most commonly used in CNC programming applications:

Linear interpolation is used for straight-line machining between two points.

Circular interpolation is used for circles and arcs.

Helical interpolation, used for threads and helical forms, is available on many CNC machines.

Parabolic and cubic interpolation are used by industries that manufacture parts having complex shape such as aerospace parts, and...

## Procedure:

Manipulate the end effector as per the given configuration. Movement Should Initiate in P1 and progress till the end point. Travel path should be in sequence as stated below.

Linear Interpolation








Circular Interpolation

## Output
![i1](https://user-images.githubusercontent.com/94508142/176996136-03f31ac8-0fbf-42e4-ba6f-d30102117ee1.png)
![i2](https://user-images.githubusercontent.com/94508142/176996145-d6e5883d-a688-4b2a-9423-937f409072fd.png)
![i4](https://user-images.githubusercontent.com/94508142/176996148-c2054036-4a38-4c27-9cec-6f2c9b3fbe14.png)
![i5](https://user-images.githubusercontent.com/94508142/176996160-b1056f67-d965-400c-b935-9f7aa5197783.png)
![i6](https://user-images.githubusercontent.com/94508142/176996169-8191d7e3-cf8a-4348-b745-c65578e89737.png)
![i7](https://user-images.githubusercontent.com/94508142/176996182-ec8b9287-c0de-4183-ba07-d0b5d2cec621.png)

![i8](https://user-images.githubusercontent.com/94508142/176996186-7e901e7d-91c1-478d-bfcb-ef31f8598c3d.png)
## Linear Interpolation:
![i9](https://user-images.githubusercontent.com/94508142/176996195-93b0249b-08cf-4f9e-a85c-d09cd4ade5ec.png)
## Circular Interpolation:
![i10](https://user-images.githubusercontent.com/94508142/176996202-2b4ad1f2-ab66-41d0-b416-05293a867c38.png)





### Results 
A program for Straight-line and Circular interpolation in Doosan Industrial Cobot using DRL studio has been executed successfully..



 
