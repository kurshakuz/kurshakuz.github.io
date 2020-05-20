---
title: Autonomous truck project based on KAMAZ chassis
layout: archive
permalink: /projects/kamaz/

classes: wide

sidebar:
 nav: "projects"

single_layout_gallery:
  - image_path: /assets/images/projects/kamaz/10.png
    alt: "Webots"
  - image_path: /assets/images/projects/kamaz/11.png
    alt: "Webots"

# author_profile: true

---

**News!** Our resulting paper have been accepted to the IEEE 23rd International Conference on Intelligent Transportation Systems (ITSC)! The paper "Abilkassov S., Nurlybayev A., Soltan S., Kim A., Yesmagambet N., Yessenbayev Z., Shintemirov A., Facilitating Autonomous Vehicle Research and Development Using Robot Simulators on the Example of a KAMAZ NEO Truck" is going to be presented in September 20-23, 2020. Looking forward to see you!
{: .notice--warning}

Demo video of the research project:
{% include video id="8kWX87BLYQY" provider="youtube" %}

Recently we have finished our research project on the development of a robotized autonomous driving truck for cargo transportation in congested city environments. I was responsible for the development of a truck simulation model equipped with Velodyne LiDAR sensor, IMU, GPS, and cameras which passes this data to the main ROS core in Webots. My responsibility was the development of a pipeline for sending data from these sensors to global and local path planning algorithms for testing and evaluation of their performance. Moreover, I was responsible for the development of communication between main ROS module to the separate web-interface through WebSockets, which was used for visualization of truck’s global position in a special GUI interface, it’s local and global planner coordinates, and for the dispatch of location goals to the truck.

{% include gallery id="single_layout_gallery" caption="Autonomous truck navigation in Webots simulator" %}