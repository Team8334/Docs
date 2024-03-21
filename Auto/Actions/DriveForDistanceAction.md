---
layout: default
title: DriveForDistanceAction
nav_order: 2
---

This Drive For Distance Action enables a person to make a distance for the robot to move, meausured in meters.

Start Function:
  It starts the timer and gets the desired distance
Update Function:
  It calculates the PID and moves the robot forward.
isFinished Function:
  stopped if timer is greater than seconds or it is at the setpoint.
done Function:
  stops all robot code and movement.
