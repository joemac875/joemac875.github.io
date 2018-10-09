---
title:  "Lane Following with Autonomous Vehicles"
date:   2018-08-07 18:00:00 -0400
categories:	research, autonomous-vehicles 
---

Over the summer I participated in the University of Arizona's [CAT Vehicle REU](http://catvehicle.arizona.edu) funded by the National Science Foundation. During this 10 week experience, I and two other students worked with our graduate mentor to develop a lane detection and following system for the University's Cognitive Autonomous Testing (CAT) Vehicle.

The CAT Vehicle is a hybrid Ford Escape configured for drive-by-wire and containing the neccessary computer systems to control the car using the Robotics Operating System.

![The Catvehicle REU Participants.]({{site.baseurl}}/assets/catvehicleTeam.jpg)

My team and I developed a controller for  the car to follow lanes using input from a front facing camera combined with GPS odometry. Along the way, we created a new way to model the path of the lane by improving upon an existing sliding window algorithm. We submitted a short paper detailing this work to the IEEE IRC 2019 conference ([Github repo](https://github.com/catvehicle/Lanefinder) with paper and code).

Below is a short video to describe the entirety of my team's work.

<iframe width="100%" height="315" src="https://www.youtube.com/embed/fkqQqAvVHJE" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
