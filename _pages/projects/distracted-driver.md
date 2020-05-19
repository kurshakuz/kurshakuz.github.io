---
title: Distracted Driver Identification
layout: archive
permalink: /projects/distracted-driver/

classes: wide

sidebar:
  nav: "docs"

---

During the Fall 2019 in my junior year, I have taken a Machine Learning with Applications class. Although I already had some prior knowledge of ML and DL algorithms learned in my spare time both from books and MOOCs, I wanted to get more exposure to real-world applications. For my midterm project, I have found a challenging task for Distracted Driver identification. For this purpose, I used the transfer learning technique to use a pre-trained ResNet model on the ImageNet dataset to save time, computation resources, and preserve a generalization property. As was shown further the total accuracy of 91% was successfully achieved on driver activity classification. However, I found distraction classification only from posture images a limitation of the work and proposed to the professor and my team to additionally use driver frontal images for classification. For this purpose, I suggested collecting our own synchronized two camera dataset. Finally, we collected data for 11 people on 7 different classes. Training for separate images was conducted on my modified ResNet architecture separately which were finally concatenated and followed by other fully connected layers. This is usually called a multimodal approach. The accuracies obtained are 92% and 80% for both frames, but the multimodal approach has shown worse accuracy of 84%. 

<i class="fab fa-fw fa-github"></i> [**Distracted Driver Detection**](https://github.com/kurshakuz/distracted_driver_detection)
{: .notice--info}

Trained and tested two ResNet50 using transfer learning for distracted driver identification using multimodal learning