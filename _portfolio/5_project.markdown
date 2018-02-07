---
layout: page
title: BlindEyes
description: MakeHarvard Hackathon Project
img: /project_pics/blindEyes.JPG
---

I participated in MakeHarvard, Harvard University's first ever Makeathon! Along with three other teammates, I developed a navigational
tool, BlindEyes, for the visually impaired. The tool provides haptic feedback to avoid obstacles, along with an audio output describing
the scene around the user. The entire project was completed within 24 hours.

Our team was awarded the <b><b><i>Best Overall Prize</i></b></b>, among 37 teams, for our innovative design. More information and video of our system working can be found on <a href="https://devpost.com/software/blindeyes" target="blank"> Devpost </a>.

<div class="img_row">
	<img class="col half" src="{{ site.baseurl }}/project_pics/blindEyes-head.JPG" alt="" title="Head piece design"/>
	<img class="col half" src="{{ site.baseurl }}/project_pics/blindEyes-back.JPG" alt="" title="Electronics for Head piece"/>
</div>
<div class="col three caption">
	BlindEyes - navigational tool for visually impaired.
</div>

The device consists of a head piece with integrated sonars, lidars, haptic feedback motors, EMIC2 (for text-to-audio) and
a Raspberry pi camera for landscape identification and obstacle avoidance. The sensors are controlled using an mbed whereas
the imaging and audio feedback are controlled through a Raspberry Pi 3.

Furthermore, a secondary device, an anklet with integrated lidars, is provided to detect smaller obstacles. This is operated
via an Arduino Uno. The two devices operate independently of each other, making the system modular and highly scalable.
