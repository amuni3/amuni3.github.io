---
layout: page
title: ABB YuMi robot
description: Autonomous Systems Lab, ETH Zurich
img: /project_pics/yumi.jpg
---

I was awarded the <a href="http://thinkswiss.tumblr.com/awardees" target="blank"> ThinkSwiss Research Scholarship </a>
by the Swiss Embassy to get a research experience at the Autonomous Systems Lab, ETH Zurich with Dr. Roland Siegwart.

As a visiting student researcher at Autonomous Systems lab, I was assigned the task of developing a stacking
demo with ABB's Yumi robot. The robot should be able to recognize a stacking pattern formed using blocks and
then stack objects to build a similar structure.

<div class="img_row">
	<img class="col one" src="{{ site.baseurl }}/project_pics/yumi_rviz.png" alt="" title="ABB YuMi"/>
	<img class="col one" src="{{ site.baseurl }}/project_pics/yumi_gazebo.jpeg" alt="" title="ABB YuMi"/>
	<img class="col one" src="{{ site.baseurl }}/project_pics/yumi_objects.jpeg" alt="" title="Object segmentation"/>
</div>
<div class="col three caption">
	YuMi pick-place simulation in Gazebo and Rviz; Object segmentation output.
</div>

The goal of this project is to scan a prebuild object stack and then rebuild it with the YuMi robot. The overall design is
divided into two parts. First, a pick-place pipeline to move the robot arms. This was done using MoveIt! library
for planning, manipulation and grasping. The second part includes an object detection pipeline to identify location
of blocks required to build the stack. The PointCloud library was used to interpret data from ASUS PrimeSense sensor.

Here is a <a href="https://www.youtube.com/watch?v=iCcs-SbOtG4" target="blank"> video </a>
showing a single pick-place routine in Rviz and Gazebo.
