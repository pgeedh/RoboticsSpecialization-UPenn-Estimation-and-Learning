<h1>Coursera Robotics Specialization- Aerial Robotics</h1>
<h4>Instructor</h4> 
<h5>Prof. Daniel Lee</h5>Nemirovsky Family Dean of Penn Engineering and Professor of Mechanical Engineering and Applied Mechanics
School of Engineering and Applied Science

This repository contains the solutions from all the programming assignements and quiz in this Coursera Course.

<h1>About This Course</h1>
How can we create agile micro aerial vehicles that are able to operate autonomously in cluttered indoor and outdoor environments?  You will gain an introduction to the mechanics of flight and the design of quadrotor flying robots and will be able to develop dynamic models, derive controllers, and synthesize planners for operating in three dimensional environments.  You will be exposed to the challenges of using noisy sensors for localization and maneuvering in complex, three-dimensional environments.  Finally, you will gain insights through seeing real world examples of the possible applications and challenges for the rapidly-growing drone industry.
Aerial Robotics concerns developping a 3d PD controller and a trajectory generator for a quadcopter.

<h1>Mathematical Prerequisites</h1>
Mathematical prerequisites: Students taking this course are expected to have some familiarity with linear algebra, single variable calculus, and differential equations.

<h1>Programming Prerequisite</h1>
Some experience programming with MATLAB or Octave is recommended (we will use MATLAB in this course.) MATLAB will require the use of a 64-bit computer.
You need to have Matlab installed if you want to run the programs on your machine with the appropriate libraries installed. The data used specifically for this course are not included but any similar data should work fine.

Modules are divided into:

* [Robotics: Estimation and Learning](https://github.com/smit585/Upenn-Robotics/tree/master/Robotics%20and%20Estimation)
    * Introduction to MATLAB and tools to sample from Single or Multivariate Gaussians. Week 1 Assignment required to Estimate and Target the Color in Dataset
<p align="center">
  <img width="200" height="200" src="https://raw.githubusercontent.com/smit585/Upenn-Robotics/master/Robotics%20and%20Estimation/Week%201/DemoImages/DemoGIFWeek1.gif">
</p>
    * Introduced to Kalman Filter and Maximum-A-Posterior Estimation. Week 2 Assignment required to track the ball in 2D space
    *  Week 3 introduces us to Mapping and crucial aspects of Localization. In Week 3 Assignment, we build an Occupancy Grid Map, that reads the Lidar Data off a Bot and using log loss data, designates certaininty to a discretized map. Darker the map -> Higher the Certainity of Free space.
    <p align="center">
  <img width="400" height="300" src="https://raw.githubusercontent.com/smit585/Upenn-Robotics/master/Robotics%20and%20Estimation/Week%203/DemoImages/Week3Demo.gif">
</p>
    * The final week wraps up the course by discussing about Particle filtering, a modified version of Unscented Kalman Filter. The Capstone project requires usage of Particle Filter to estimate the best Pose of Robot in accordance to the correlation of Lidar and Groundtruth Map Data. 
<p align="center">
  <img width="400" height="300" src="https://github.com/smit585/Upenn-Robotics/blob/master/Robotics%20and%20Estimation/Week%204/DemoImages/DemoWeek4.gif?raw=true">
<p align="center">
  <img width="400" height="300" src="https://raw.githubusercontent.com/smit585/Upenn-Robotics/master/Robotics%20and%20Estimation/Week%204/DemoImages/Final%20Image.png">

<h1>Authors</h1>
<h4>Pruthvi Omkar Geedh</h4>
This project is licensed under the MIT License - see the LICENSE.md file for details
