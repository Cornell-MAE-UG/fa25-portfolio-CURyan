---
layout: project
title: Mechatronics Robot Competition
description: MAE3780 Final Project - Spring 2026 | Cornell University
technologies: [Arduino]
image: /assets/images/robot.jpg
---

**Overview**

![Profile Picture]({{ "assets/images/robot.jpg" | relative_url }}){: class="profile-image"}

Our robot was designed around a simple philosophy: stay robust, stay consistent, and avoid unnecessary mechanisms. Since the competition rewarded cubes that ended fully inside the robot’s top-down perimeter, our strategy was to maximize passive collection area rather than build an active intake. The final robot used a wide, open-front “mouth” that allowed 1-inch cubes to pass underneath the chassis as the robot drove forward, enclosing them within the robot’s perimeter.

A major design choice was using the larger 3.5-inch wheels available from the lab. These wheels gave the robot enough ground clearance for cubes to enter underneath the frame while still fitting cleanly on the provided motor axles. We considered using 5-inch McMaster wheels, but they were unnecessarily large, had oversized bore holes, and would have required extra adaptation that could compromise reliability. We also considered a dually-wheel setup to increase traction, but instead added weight. This kept the drivetrain simpler while making the robot harder to push off course and less likely to be deflected by cube impacts or opposing robots.

The outer casing served as both the collection perimeter and a protective shell. We mounted the sensors inside the casing rather than on the outside, which protected them from collisions and preserved as much mouth width as possible. Electrically, the robot used the required Arduino, L9110H H-bridges, two modified continuous rotation servos, and onboard color/border sensors. The software followed a simple autonomous strategy: determine field color, drive into the cube zone, detect borders, recover by reversing and turning, and continue sweeping for cubes until the match ended.

Overall, our final design was not meant to be the most complex robot in the competition. It was meant to be a robot that worked repeatedly, survived contact, and gathered cubes through a mechanically forgiving geometry. 


