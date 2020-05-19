---
title: Driver Drowsiness Estimation
layout: archive
permalink: /projects/driver-drowsiness/

classes: wide

sidebar:
  nav: "projects"

single_layout_gallery:
  - image_path: /assets/images/projects/drowsiness/driver_state1.jpg
    alt: "Focused driver"
  - image_path: /assets/images/projects/drowsiness/driver_state2.jpg
    alt: "Drowsy driver"
  - image_path: /assets/images/projects/drowsiness/driver_contour.jpg
    alt: "Focused driver"

---

<i class="fab fa-fw fa-github"></i> [**Drowsiness Detection GitHub**](https://github.com/kurshakuz/drowsiness_detection)
{: .notice--info}

This is an open source implementations of the driver drowsiness estimation based on Blink Ratio and Contour Area methods. It computes driver drowsiness estimation in real-time and is based on C++ and OpenCV.

{% include gallery id="single_layout_gallery" caption="Driver drowsiness estimation using two methods" %}

In this projects, landmarks for feature identification followed by mask for region extraction, binarization, erosion and dilation for iris size estimation for further drowsiness estimation for contour area method. On the other hand, landmarks are directly used to find points of interest which are then directly used to compute eye blink ratio. The pipeline of both algorithm is as follows:
![](/assets/images/projects/drowsiness/two_methods.png){: .align-center}

Both of these methods outputs the average closed eye instances per given frame number, which is then used to compute average drowsiness. Yawning is used as an additional drowsiness indicator independently. The overall algorithm struture is as follows:
![](/assets/images/projects/drowsiness/Algorithm.png){: .align-center}
