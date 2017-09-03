---
layout: page
title: Quadruped
description: IVALab, Georgia Tech
img: /project_pics/quadruped.PNG
---

This semester long project was part of Dr. Patricio Vela's "Introduction to Automation and Controls" class.
Along with another teammate, I used forward and inverse kinematics to emulate the walking gait of quadrupeds
found in nature, like cheetah. This was written in MATLAB.

Another walking gait was generated using an open source nonlinear optimization solver, Optragen. We then
deployed it on a physical model. See <a href="https://www.youtube.com/watch?v=9Xl9mlDTPZg" target="blank"> video </a> here.

<div class="img_row">
	<img class="col one" src="{{ site.baseurl }}/project_pics/cat_front.png" alt="" title="Front view"/>
	<img class="col two" src="{{ site.baseurl }}/project_pics/torso.jpg" alt="" title="3D CAD model"/>
</div>
<div class="col three caption">
	Front view of robotic quadruped and CAD model of torso with spine joint.
</div>

Several robots were studied to design the next version of a quadruped with an actuated backbone/spine,
using AutoDesk Inventor. The torso can now move the body sideways to facilitate turning and the spine
can bend the body for hopping and leaping gaits.  
