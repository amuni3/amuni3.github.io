---
layout: page
title: GohBot
description: Food Processing Technology Division, GTRI
img: /project_pics/gohbot.png
---
I worked on autonomously driving the Grow-out House Robot (GohBot) with Colin Usher in
<a href="http://www.fptd.gatech.edu/robotics/grobot.html" target="blank"> FPTD</a>
at Georgia Tech Research Institute.  

I worked on localizing the GohBot using an indoor ultrasonic GPS, detecting obstacle using
depth data from Microsoft Kinect and designing path planning and obstacle avoidance
routines. This <a href="https://drive.google.com/file/d/0Bx0AJvW-lbnBY09HRV9XWVI5VGM/view?usp=sharingvideo" target="blank">video </a>
shows the robot driving autonomously while avoiding chickens.

<div class="img_row">
	<img class="col two" src="{{ site.baseurl }}/project_pics/gohbot2.JPG" alt="" title="Test chicken house"/>
	<img class="col one" src="{{ site.baseurl }}/project_pics/gohbot3.jpeg" alt="" title="Localization map"/>
</div>
<div class="col three caption">
	Testing algorithms in real poultry house environment.
</div>

I wrote a "Nudging" routine, where a bird in front of the robot will be bumped slightly,
in order to move it out of the way. A "Drive around" routine was written to recalculate the robots
path, in case the bird doesn't move, or if a static obstacle is encountered. Weekly tests were
conducted in a grow-out house with broiler-breeder chickens.
