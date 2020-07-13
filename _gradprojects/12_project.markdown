---
layout: page
title: Safe Reinforcement Learning
description: Institute for Dynamic Systems and Control, ETHZ
img: /project_pics/rosenbrock.png
---

<!---Learning-Based Control for Constrained Systems using Thompson Sampling and Scenario Optimization-->
I recently completed my semester thesis under the supervision of Dr. Melanie Zeilinger at the
<a href="https://idsc.ethz.ch/research-zeilinger.html" target="blank">
Institute for Dynamic Systems and Control</a> at ETHZ. The motivation for the project comes from
the growing complexity of systems and increasing availability of data, giving rise to development of
data-enabled controller design methods. While there are numerous approaches to this problem, the
case of controller design for safety critical systems is a challenge.

With this in mind, this project aims to design safe learning-based controllers for constrained systems
using Thompson Sampling and Scenario Based Optimization. This goal is achieved in three parts.
First, a Bayesian optimization method is illustrated using a simple Thompson sampling algorithm to
efficiently balance between exploration and exploitation when learning to optimize actions.
This method is then extended for learning-based control using model-based reinforcement learning.
A constrained open-loop finite horizon control problem is solved to compute approximately optimal
input sequences while reinforcement learning optimizes close-loop performance. Finally, Scenario
Based Optimization is used to provide safety guarantees for the aforementioned model-based approaches.

I recently had the opportunity to present this work at the <a href="http://mlss.tuebingen.mpg.de/2020/" target="blank">
Machine Learning Summer School (MLSS), 2020 </a> in Tubingen.

{% include youtubePlayer.html id="ToeYuLxbwX0" %}

<!---A detailed description and the source code for this project will be made public soon.-->
<!--- TODO: Add trajectory figure and github code link-->
