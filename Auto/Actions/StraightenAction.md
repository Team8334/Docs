---
layout: default
title: StraightenAction
nav_order: 2
---

Turns robot to desired degrees

start function:
  start timer and set tolerance and desired degrees into the PID calculator
update function:
  turns robot to desired degrees
isFinished function:
  function stops if timer is greater than seconds
done function:
  stops all robot code and movement for this action
