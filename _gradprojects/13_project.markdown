---
layout: page
title: Planning Under Uncertainty
description: Autonomous Mobility on Demand, ETHZ
img: /project_pics/duckiebot-side.jpg
---

This project is part of the Autonomous Mobility on Demand course, commonly referred as "Duckietown" under the supervision of Dr. Andrea Censi with
the Institute for Dynamic Systems and Control at ETH. Along with three teammates, I worked on developing an algorithm that keeps track of
the uncertainty while driving in an unknown environment.

The goal of the project is to anticipate any future unseen obstacles and adjust velocity profile of the duckiebots accordingly. Each track in given
environment is divided into segments and nodes (see left image) and the uncertainty at each node is updated according to the observations from a RaspberryPi camera.

<div class="img_row_special">
	<img class="col half" src="{{ site.baseurl }}/project_pics/duckie-node.png" alt="" title="Duckietown track node view"/>
	<img class="col half" src="{{ site.baseurl }}/project_pics/duckie-track.png" alt="" title="Duckietown track"/>
</div>
<div class="col three caption">
	Duckietown track in the node view showing multiple duckiebots navigating simultaneously.
</div>

Unseen regions and areas where obstacles were observed previously, have high uncertainty illustrated by the red squares in the right image. As more observations are
collected, the uncertainty value is updated. Given the updated uncertainty values and a target location, a path along with corresponding velocity profile
is computed. Lower uncertainty regions allow the duckiebots to speed, depicted by red parts of trajectories in right image.

A video describing the overall project and our approach can be found <a href="https://vimeo.com/user92909741" target="blank">here</a> and
the corresponding source code is available on <a href="https://github.com/duckietown/duckietown-uplan" target="blank">github</a>.
