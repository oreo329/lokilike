+++
showonlyimage = false
draft = false
image = "img/research/phantom-teasor.jpg"
date = "2016-11-05T18:25:22+05:30"
title = "Vibrotactile Illusion"
weight = 3
+++

Seamless Phantom Sensation Moving across a Wide Range of Body<br>(IEEE World Haptics 2019)
<!--more-->

![overview][1]

#### Abstract
>This paper reports experimental research aimed to provide seamlessly moving illusory tactile sensations across a large area of the body using a few vibration actuators. The human vibrotactile sensitivity differences among the body sites are calibrated using empirically-measured psychophysical magnitude functions. 

>We present a new phantom sensation rendering method that uses the Gaussian function emphasizing the spatial continuity of perceived movement and the temporal consistency of perceived intensity. We demonstrate that our rendering method outperforms previous methods for phantom sensations via a perceptual experiment. Our method is tailored to eliciting the perception of illusory tactile sensation moving in a long distance, from the thigh to the upper back.

{{< youtube id="PTAj4zyKdYs" autoplay="true" >}}

#### Publication
* **IEEE World Haptics 2019**<br>Gyeore Yun, **Seungjae Oh**, and Seungmoon Choi.<br>*[Seamless Phantom Sensation Moving across a Wide Range of Body](https://doi.org/10.1109/WHC.2019.8816104)*
<!-- * Link: [Full Paper](https://doi.org/10.1109/WHC.2019.8816104) -->
* **IEEE World Haptics Demo 2019**<br>Gyeore Yun, **Seungjae Oh**, and Seungmoon Choi.<br>*[Seamless Phantom Sensation Moving across a Wide Range of Body](https://youtu.be/UFgp7A1IK7o?t=141)*
* Video: [Overall](https://youtu.be/PTAj4zyKdYs)

#### Figure

![pi][7]
The results of the magnitude estimation experiment about vibration at four different body sites (Exp 1). The four psychophysical curves were fitted according to Steven's power law. Each curve represents the relationship between the amplitudes of physical stimulus and their perceived intensity.

![lin][3]
![log][4]
![pilin][5]
![pinorm][6]
Four rendering methods for phantom sensations. The first two are common rendering functions for phantom sensations, and the latter two are compensated by the results of the magnitude estimation experiment.

![Result][2]
The percieved qualities of phantom sensations with respect to the rendering methods and durations (Short: 0.75 s; Middle: 1.5 s; Long: 2 s).

#### Conclusion
>The work reported in this paper aimed to design a rendering method for dynamic phantom sensations that deliver realistic illusory tactile sensations moving across a wide range of the body, from the thigh to the upper back, with a few actuators. In order to compensate for the sensitivity differences across the body, we measured in Exp. I four psychophysical magnitude functions of vibrotactile stimuli at the four body sites of thigh, waist, hip, and upper back. Then we designed a new phantom sensation rendering method that uses the Gaussian function in the profile of perceived
intensity to support smoother transitions at even actuator locations. Our method was evaluated in Exp. II along with three other previous rendering methods. Results indicated that our method provides illusory motion of the best quality in terms of the spatial continuity of movement and the temporal consistency of intensity. Our findings can contribute to appropriate designs of tactile displays and rendering algorithms stimulating the body in a long distance.

#### Contribution
* Gyeore Yun: Idea, Implementation (HW&SW), Experiment, Experimental Design and Analysis, Graphics, and Video 
* Seungjae Oh: Idea, Ideation, and Experimental Design
* Seungmoon Choi: Director

[1]: /img/research/phantom-config.png
[2]: /img/research/phantom-res.png
[7]: /img/research/phantom-pi.png
[3]: /img/research/phantom-profilelinear.png
[4]: /img/research/phantom-profilelog.png
[5]: /img/research/phantom-profilepilinear.png
[6]: /img/research/phantom-profilepinormal.png
