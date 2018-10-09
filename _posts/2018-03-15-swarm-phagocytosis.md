---
title:  "Simulated Phagocytosis Using Swarm Robotics"
date:   2018-03-15 18:00:00 -0400
categories:	research, swarm 
---

For my junior undergraduate research project, I chose to focus on swarm intelligence. In particular, I simulated the process of phagocytosis - when one cell eats another - by using a swarm of Kilobots. These robots are developed by Harvard and designed to be used in swarm robotics applications.



Alone, each Kilobot is unable to perform any meaningful function, but as a group they perform emergent behavior matching that of a phagocyte. My simulation fully captures the  searching, movement, and engulfing behavior of a phagocyte, but not the actual destruction of foreign bodies. 

For a much more detailed description of my, you can checkout my [GitHub repo](https://github.com/joemac875/phagobot) which has my research paper and code. Otherwise, the following videos show off some of the results. 

Each is an example of my code running in the Kilombo simulator for Kilobots. Because the simulator can't render the light gradient (closest analog I could get to bacteria's chemical gradients) I had to draw it in as well as the source (which I label 'harmful bacterium' for reference.

It might be worth describing the colors of the bots in the following videos as well, as each indicates a separate role:

**Blue** &rarr; Kilobots that have the highest light reading in the swarm. These bots call the others towards them.

**Green** &rarr; "middle-of-the-pack" Kilobots that know they don't have the highest reading, but also aren't at the "back" of the swarm.

**Red** &rarr; Kilobots that know they are at the "back" of the swarm and need to move. These bots attempt to follow the edge of the swarm.

### Single Target

<iframe width="100%" height="315" src="https://www.youtube.com/embed/gZEhmxaNgRU" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

### Two Targets
<iframe width="100%" height="315" src="https://www.youtube.com/embed/uT4GUHJlITg" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

### Adaptability and Scalability
This video just shows that a member of the swarm can be ripped out and the swarm will adapt. That is, new Kilobots will emerge as the blue, highest-light-reading bots. Also, dropping the old bot back in doesn't cause any issues.

<iframe width="100%" height="315" src="https://www.youtube.com/embed/M9F4gqi3x0Q" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
