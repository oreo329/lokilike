+++
image = "img/research/vibeye-main.png"
showonlyimage = false
date = "2016-11-05T19:44:32+05:30"
title = "VibEye"
draft = false
weight = 1
+++

Vibration-Mediated Object Recognition for Tangible Interactive Applications<br>(CHI 2019)
<!--more-->

![Teasor][1]

#### Abstract
> We present VibEye: a vibration-mediated recognition system of objects for tangible interaction. A user holds an object between two fingers wearing VibEye. VibEye triggers a vibration from one finger, and the vibration that has propagated through the object is sensed at the other finger. This vibration includes information about the object’s identity, and we represent it using a spectrogram. 

> Collecting the spectrograms of many objects, we formulate the object recognition problem to a classical classification problem among the images. This simple method, when tested with 20 users, shows 92.5% accuracy for 16 objects of the same shape with various materials. This material-based classifier is also extended to the recognition of everyday objects. 

> Lastly, we demonstrate several tangible applications where VibEye provides the needed functionality while enhancing user experiences. VibEye is particularly effective for recognizing objects made of different materials, which is difficult to distinguish by other means such as light and sound.

<!-- {{< youtube id="zgzgOyxWXD8" autoplay="true">}} -->
{{< youtube id="rH7KywQ0Z-8" autoplay="true">}}

#### Publication
* **ACM CHI 2019**<br>**Seungjae Oh**, Gyeore Yun, Chaeyong Park, Jinsoo Kim, and Seungmoon Choi.<br>*[VibEye: Vibration-Mediated Object Recognition for Tangible Interactive Applications](https://doi.org/10.1145/3290605.3300906)*
* **IEEE World Haptics Demo 2019**<br>**Seungjae Oh**, Chaeyong Park, Jinsoo Kim, Gyeore Yun,and Seungmoon Choi.<br>*[VibEye: A System for Identification of Hand-held Object by Visualizing Vibration Propagation Dynamics](https://youtu.be/UFgp7A1IK7o?t=53)*
* **Domestic Patent**<br>**Seungjae Oh** and Seungmoon Choi. <br>*OBJECT IDENTIFICATION APPARATUS AND METHOD, SYSTEM COMPRISING THE SAME* <br>Application: 2019.11.29
<!-- * Link: [Full Paper](https://doi.org/10.1145/3290605.3300906) -->
* Video: [Overall](https://www.youtube.com/watch?v=yOi4Mv8VzTA) & [Application](https://www.youtube.com/watch?v=zgzgOyxWXD8&feature=youtu.be)

#### Figure
![Application][3]

![HW][4]
Hardware design of VibEye.

![Dataprocessing][2]
The overview of computational procedure for signal processing and object recognition.

![SampleSTFT][6]
Spectrograms of 16 standard objects. Objects are marked with material properties.<br>R: rigid, E: elastic, V: viscous, P: plastic, and S: stacked. 

![Possibility][5]
The further sensing possibiliteis of VibEye. The four sets of everyday objects and their PCA results (20 rep. each): (A) Liquid body products in soft tubes, (B) Candies in hard containers, (C) Stacked papers, and (D) A spray bottle.

#### Conclusion
>	In this work, we have presented a system for vibration-mediated object recognition. VibEye is simple: its hardware requires only a vibration emitter and a sensor, and its software processes the data using well-defined image-based methods. Essentially, VibEye transforms the object recognition problem to an image classification problem. We have validated the effectiveness of VibEye in several ways, using the cross-validation results for the standard objects of the same shape but different materials, and recognition performance for other users' data and other unseen various everyday objects' data. We envision tightly-coupled virtual and real environments that are seamlessly controlled by tangible objects. We hope that the concepts embodied by VibEye could pave the way.

#### Contribution
* Seungjae Oh: Idea, Implementation (HW&SW), Experiment, Analysis, Writing, and Graphics
* Others: Application Development, Graphics, and Video 
* Seungmoon Choi: Director

[1]: /img/research/vibeye-teaser.png
[2]: /img/research/vibeye-dataprocessing.png
[3]: /img/research/vibeye-app.png
[4]: /img/research/vibeye-hw.png
[5]: /img/research/vibeye-possibility.png
[6]: /img/research/vibeye-stft.png