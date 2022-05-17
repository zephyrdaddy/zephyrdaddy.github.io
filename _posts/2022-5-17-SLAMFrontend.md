---
layout: post
title:  "SLAM Frontend (En)"
date:   2022-5-17 20:39:36 +0530
categories: SLAM 
---
Frontend System consists of the modules.
Tracking, Matching, 

Memory Management.


State Space Reperesentation of a System

In a system, observability is a measusure of how well internal states can be inferred from knowledge of its external outputs.

what's measured through the sensors are outputs of the system. 

SISO system with n state variables 

\(E=mc^2\)，$$x_{1,2} = \frac{-b \pm \sqrt{b^2-4ac}}{2b}.$$


Using image features -> unobservable state occurs 

What's the observability matrix in this case?

가관측성 
완전 가관측성 특성

Total/ stripped observability matrix 
Eigenvalue analysis

Bearing and Elevation from camera sensor

dynamics model of the state 

Observability can be analyzed only in the linear model.
So we linearize the observation model.

There may be some linearization error but 

How to linearize the vo vio model

Observation matrix data로 적어보기 

The observability gramian is defined as a function of the linearized measurement model H and the discrete time state transition matrix Phi.

from time step 1 to k.




Matrix derivatives 






SLAM


Check out the [article](https://webdiis.unizar.es/~raulmur/orbslam/) [article-link]

[article-link]: https://webdiis.unizar.es/~raulmur/orbslam/

