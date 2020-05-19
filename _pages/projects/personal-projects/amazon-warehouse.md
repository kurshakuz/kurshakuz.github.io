---
title: Autonomous pallet distribution in Amazon warehouse
layout: archive
permalink: /projects/amazon-warehouse/

classes: wide

sidebar:
  nav: "projects"

# author_profile: true

single_layout_gallery:
  - image_path: /assets/images/projects/amazon-warehouse/amazon2.png
    alt: "Amazon robot"
  - image_path: /assets/images/projects/amazon-warehouse/amazon1.png
    alt: "Amazon robot"
  - image_path: /assets/images/projects/amazon-warehouse/amazon4.png
    alt: "Amazon robot"

---

<i class="fab fa-fw fa-github"></i> [**Amazon Warehouse GitHub**](https://github.com/TheRoboticsClub/colab-gsoc2019-Shyngyskhan_Abilkassov)
{: .notice--info}

In May 2019 I was selected to participate as an open-source contributor to the JdeRobot organization under the wonderful Google Summer of Code (GSoC) program! GSoC helped me to dive into the open-source development and spent a whole summer working on a great problems.

{% include gallery id="single_layout_gallery" caption="Amazon robot in warehouse in Gazebo simulator" %}

My task was to develop a robot that autonomously navigates, detects, picks and delivers the pallet with goods to the required position in simulation. The robot was simulated and operated in Gazebo through a ROS interface. Finally, by the end of summer I have successfully implemented the robot localization, mapping, navigation, global and local planner algorithms which were used for autonomous task completion of the robot. Additionally, I learned about SLAM algorithm and used it for map construction using LiDAR sensor and further integrated AMCL algorithm for real-time localization in the warehouse and developed a user-friendly GUI interface.

Autonomous pallet distribution algorithm is shown in video below:
{% include video id="T1-6Y4ulEnQ" provider="youtube" %}


More details about challenges I met on my way and the ways I approached them are discussed in [my blog](https://theroboticsclub.github.io/colab-gsoc2019-Shyngyskhan_Abilkassov/).

To proceed to the exercise review and completion please follow instructions in the JDERobot's Robotics Academy [documentation of the exercise](https://jderobot.github.io/RoboticsAcademy/exercises/MobileRobots/amazon_warehouse/).