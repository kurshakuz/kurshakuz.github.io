---
title: Amazon Warehouse
permalink: /projects/amazon-warehouse/

# sidebar:
#   nav: "docs"
author_profile: true

---

In May 2019 I was selected to participate as an open-source contributor to the JdeRobot organization under the wonderful Google Summer of Code (GSoC) program! GSoC helped me to dive into the open-source development and spent a whole summer working on a great problems.

My task was to develop a robot that autonomously navigates, detects, picks and delivers the pallet with goods to the required position in simulation. The robot was simulated and operated in Gazebo through a ROS interface. Finally, by the end of summer I have successfully implemented the robot localization, mapping, navigation, global and local planner algorithms which were used for autonomous task completion of the robot. Additionally, I learned about SLAM algorithm and used it for map construction using LiDAR sensor and further integrated AMCL algorithm for real-time localization in the warehouse and developed a user-friendly GUI interface.

<i class="fab fa-fw fa-github"></i> [**Amazon Warehouse**](https://github.com/TheRoboticsClub/colab-gsoc2019-Shyngyskhan_Abilkassov)
{: .notice--info}

As part of Google Summer of Code 2019 I have completed the creation of the exercise infrastructure for the JdeRobot Robotics Academy. As a full time open source contributor, I have created robot model, introduced proper transformations for the sensors, intergrated global and local planners and created a map using SLAM in Gazebo using ROS.