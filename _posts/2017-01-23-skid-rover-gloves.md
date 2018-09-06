---
title:  "Motion Controlled Skid Rover"
date:   2017-01-23 18:00:00 -0400
categories:	robotics 
---

This project allows a user to control a skid-steer rover using only hand angles. A pair of gloves - each with an accelerometer - attached to an Arduino Uno and wireless transceiver sends orientation information to a rover with controlled by an Arduino Mega with another wireless transceiver. Each glove and accelerometer pairing corresponds to one of the two motors on the rover. When both hands are level, the motors on the rover don't engage. If one hand angles downward, the corresponding motor causes its tread to move forward. If the hand angles upward, the tread moves in reverse.

<iframe width="100%" height="315" src="https://www.youtube.com/embed/xtq54M5oJJM" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
