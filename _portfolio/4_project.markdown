---
layout: page
title: Predictive modelling
description: Food Processing Technology Division, GTRI
img: /project_pics/chicken_scan.png
---

For my undergraduate thesis, I am currently working on weight estimation problem in poultry houses,
with Colin Usher in <a href="http://www.fptd.gatech.edu/robotics/grobot.html" target="blank"> FPTD</a>
at Georgia Tech Research Institute.

The initial stage involved collecting 3D scans of various birds to find a correlation
between a bird's weight and volume. Methods such as ICP (Iterative Closest Point) from
PCL (Point Cloud Library) and sphere fitting in MATLAB, were employed to prove this theory.

<div class="img_row">
	<img class="col two" src="{{ site.baseurl }}/project_pics/icp.png" alt="" title="ICP matching"/>
	<img class="col one" src="{{ site.baseurl }}/project_pics/sphere_fit.png" alt="" title="Sphere fitting"/>
</div>
<div class="col three caption">
	ICP and maximum size sphere fitting to correlate volume and weight.
</div>

The problem with using 3D reconstruction softwares like
<a href="https://msdn.microsoft.com/en-us/library/dn188670.aspx" target="blank"> KinectFusion</a>,
is that they are designed for modelling static scenes. This makes it harder to model chickens. I am working on an
algorithm that would undo this motion to robustly generate 360 degree view models.
