Here is a breakdown of how to build this thing (there are quite a few steps):

1 - GETTING THE PARTS READY FOR PRINTING:

The wing may be too large to be printable, therefore you must slice it along the wing chord, in order to maintain printability with lightweight pla. Doing this, the fuselage with also have to be cut. Print the wing in sections, then glue then back together with model glue. No spars are required, they will make the plane too heavy, its the reason why I didnt decide to put them in. You must print the servo horns with normal PLA, to maintain structural integrity.

2 - ASSEMBLE CONTROL SURFACES

Insert hinges into all control surfaces (2 per control surface) and glue them with super glue. Then, glue them into the plane via the designated hingle insertions. Then you must super glue the servo horns into their designated insertion slots that have been cut out.

3 - ATTACHTING MOTOR ONTO PLANE

Screw the motor through the front of the plane, into a 4cm cube of polyurethane foam, securing it tightly onto the airframe. (I have spare polyurethane foam at my school)

4 - MOUNTING SERVOS ONTO AIRFRAME

Hot glue the servos into their designated areas on the airframe. Yes, you must use hot glue, as it will cover the most surface area across the servo and wing.

5 - CONNECTING SERVOS TO CONTROL SURFACES

By using the steel push rods, you can make a connection between the servos and the control surfaces. Please make sure that the servo and control surface is set at a roughly neutral position for easy calibration.

6 - TRANSMITTER

3D print the controller using normal PLA and any colour you choose. Then you must follow the wiring diagram found at the bottom of this document, once complete, you may copy past the transmitter code (Written in C++), and program your Arduino Nano V3.

7 - RECIEVER SETUP AND FINAL CHECKS

Follow the wiring diagram found below, then connect you ESC to your motor, and your ECS to your circuitboard. You may now program your Arduino Nano with the reciever code. Because my controller is simple, and does not have its own trim, it is important that you manually trim through your coding platform, by inserting different starting values until your servo is in the correct position.


8 - FLY THE PLANE

This plane does not have landing gear. You must let the motor run at full speed, before gracefully aiming at the sky, and chucking it. It will fly, and the rest will be up to your piloting skills.




WIRING DIAGRAMN FOR TRANSMITTER: 

<img width="511" height="662" alt="{FBBC17E1-562B-4FEB-A5EE-D416031D5EBE}" src="https://github.com/user-attachments/assets/106ceafe-f290-4d04-86ff-bbbb9289cf2f" />

WIRING DIAGRAM FOR RECIEVER:

<img width="936" height="502" alt="{1FAE48FF-3401-4459-8045-4B942B8E1FB7}" src="https://github.com/user-attachments/assets/cf6bbd9c-7c71-4c23-8bef-41adbab90ef1" />



PLEASE NOTE: 

I have not been able to test whether the transciever setup and code works (because I dont own one yet), however, the input and output code is definitly functional.

