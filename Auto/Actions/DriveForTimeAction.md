---
layout: default
title: DriveForTimeAction
nav_order: 2
---

Drives the Robot for a certain amount of time.

start function:
  starts timer
update function:
  moves the robot forward
isFinished function:
  if: timer is greater than seconds, return true and stop function
  else: return false and keep the function going
done function:
  stops all robot code and movement for this action
