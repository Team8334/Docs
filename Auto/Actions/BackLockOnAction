---
layout: default
title: BackLock on Action
nav_order: 4
---

# 
The back Lock on Action funtion is getting the current targeting, limelight, drivebase, and postion.
It is then setting the PID controller to the values stated above. 

The start function is starting the timer then setting the target and tolerance for the limelight.

The update function is making the new distance by subrtacting the starting distace to the target distance.
If the limelight knows the ID it will get how far away it is from the target then set the starting postion is where it is.
If not it would use previous knowledge to find the limelight.
If the the ID is known and it sees it from the back it will drive toward the April Tag
If not the same thing but backward
If not the there is no ID the drivetrain would stop
Else it would stop.

The is finished stopped if timer is greater than seconds or it is at the setpoint.
