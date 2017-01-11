# CheesyDrive
A replication of team 254's drive system, made by programming member Srihari Subramanian.

**NOTE: As of WPI 2017.1.1, the TalonSRXLib is no longer packaged with the WPILIB, so it must be downloaded from the [CTRE website](http://www.ctr-electronics.com/hro.html#product_tabs_technical_resources "CTRE website")**

## Building instructions
1. Pull or clone this repository.
2. Check the project build path and make sure that the variable "USERLIBS_DIR/TalonSRXLibJava.jar" points to the right directory. In most cases this path should be "%USERPROFILE%/wpilib/java/lib/TalonSRXLibJava.jar".
3. Run as a "WPILIB Java Deploy".
4. ...
5. Profit?

## Controls
Left Joystick: Throttle (forward or backward)

Right Joystick: Turn (left or right)



## Credits
Srihari Subramanian did most of the work with creating the equations to calculate how much voltage to regulate per side of the tank drive train to get the robot to turn while moving forward or backwards.

Other members helped with logic ladders and whatnot.
