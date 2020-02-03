---
layout: page
title: Predictive Modeling
description: Food Processing Technology Division, GTRI
img: /project_pics/chicken_scan.png
---

For my undergraduate thesis, I worked on weight estimation problem in poultry houses,
with Colin Usher in <a href="http://www.fptd.gatech.edu/robotics/grobot.html" target="blank"> FPTD</a>
at Georgia Tech Research Institute.

The initial stage involved collecting 3D scans of various birds to find a correlation
between a bird's weight and volume. Methods such as ICP (Iterative Closest Point) from
PCL (Point Cloud Library) and sphere fitting in MATLAB were employed to prove this theory.

<div class="img_row">
	<img class="col two" src="{{ site.baseurl }}/project_pics/icp.png" alt="" title="ICP matching"/>
	<img class="col one" src="{{ site.baseurl }}/project_pics/sphere_fit.png" alt="" title="Sphere fitting"/>
</div>
<div class="col three caption">
	ICP and maximum size sphere fitting to correlate volume and weight.
</div>

The problem with using 3D reconstruction softwares like
<a href="https://msdn.microsoft.com/en-us/library/dn188670.aspx" target="blank"> KinectFusion</a>,
is that they are designed for modeling static scenes. This makes it harder to model chickens. I am working on an
algorithm that would undo this motion to robustly generate 360 degree view models.

I have been awarded the <a href="http://www.undergradresearch.gatech.edu/content/presidents-undergraduate-research-awards" target="blank">
President's Undergraduate Research Award</a> for Spring 2018 to continue this work. Moreover, I presented my work at the 13th Annual Undergraduate Research <a href="https://oue.gatech.edu/2018-undergraduate-research-symposium" target="blank">Symposium</a> at Georgia Tech and
was awarded the <a href="http://urop.gatech.edu/sites/default/files/images/spring_symposium_awards_0.pdf" target="blank">3rd Best Oral Presentation</a> under
the College of Engineering.
