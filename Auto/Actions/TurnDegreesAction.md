---
layout: default
title: TurnDegreesAction
nav_order: 2
---

Turns robot a certain amount of degrees in auto

start function:
  starts timer and puts desired and target degrees into the PID calculator
update function:
  PID calculates turn and turns robot
isFinished function:
  stops this function if timer is greater than endAfterSeconds variable
done function:
  stops all robot code and movement for this action
