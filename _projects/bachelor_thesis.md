---
title: "Attitute-Aided Control of Leader-Follower UAV Formation"
excerpt: "My Bachelor Thesis<br/><img src='/images/500x300.png'>"
date: 2025-05-01
collection: projects
tags: [C++, Control, ROS]
# author profile: true
---
For my Bachelor's thesis at the Czech Technical University (CTU), I joined the Multi-robot Systems Group (MRS) and investigated the effect of utilizing attitude measurements (roll, pitch and yaw) of a leader quadrocopter in leader-follower formations.

I built a pipeline utilizing Linear Kalman Filter (LKF) for the state prediction of the leader UAV, which utilized both position and attitude measurements. 
The LKF was further used to predict the leader's short term trajectory, which was then inputed into a Model Predictive Control (MPC) algorithm on the follower drone.

The thesis included a real-world experiment, which was conducted on the MRS Summer Camp, where I learned that almost nothing goes smoothly when trying to move your software from simulation onto a real hardware.

I was awarded the Dean's award for outstanding Bachelor thesis.

The thesis is written in English and can be read at the MRS website [here](https://mrs.fel.cvut.cz/files/student_theses/BP-2025-Kahoun-Josef.pdf).
