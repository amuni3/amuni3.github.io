---
layout: page
title: Safe Policy Search in Higher Dimensions
description: Learning and Adaptive Systems Group, ETHZ
img: /project_pics/quad_traj_blue.png
---

For my masters thesis, I collaborated with Prof. Dr. Andreas Krause in the <a href="https://las.inf.ethz.ch/" target="blank">Learning and Adaptive Systems Group</a> at ETHZ.

Parameters for robotics algorithms need to be tuned in order to maximize performance on the real system. Bayesian Optimization (BO) has been used to automate this process. However, in case of safety-critical systems, evaluation of unsafe parameters during the optimization process should be avoided. Recently, a safe BO algorithm, <a href="https://arxiv.org/pdf/1509.01066.pdf" target="blank">S<font size="2">AFE</font>O<font size="2">PT</font></a>, was proposed; it employs Gaussian Processes to only evaluate parameters that satisfy safety constraints with high probability.

Even so, it is known that BO does not scale to higher dimensions (d > 20). To overcome this limitation, I  developed the S<font size="2">AFE</font>O<font size="2">PT</font>-HD algorithm that identifies relevant domain regions that efficiently trade-off performance and safety, and restricts BO search to this preprocessed domain. By employing cheap (and potentially inaccurate) simulation models, offline computations allow identifying domain subspaces that are likely to yield optimal policies, thus significantly reducing domain size. When combined with S<font size="2">AFE</font>O<font size="2">PT</font>, we obtain a safe BO algorithm applicable for problems with large input dimensions. To alleviate the issues due to sparsity of the non-uniform preprocessed domain, a method to systematically generate new controller parameters with desirable properties is implemented. The efficacy of S<font size="2">AFE</font>O<font size="2">PT</font>-HD is illustrated by optimizing a 48-dimensional control policy to execute full position control of a quadrotor, while guaranteeing safety.

I am currently working on testing the S<font size="2">AFE</font>O<font size="2">PT</font>-HD pipeline on a quadrotor system.


<!---A detailed description and the source code for this project will be made public soon.-->
