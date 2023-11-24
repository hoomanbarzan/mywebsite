---
title: 'Markerless Surgical Navigation.'
subtitle: "From intraoperative RGB-D imaging to marker-less surgical navigation!"
date: 2023-11-10 12:07:23
description: "A fully intraoperative approach for automatic registration of spinal 3D models with contineus pose updates."
featured_image: '/images/projects/spinedepth2/1.jpg'
---

Established surgical navigation systems for pedicle screw placement have been proven to be accurate, but still reveal limitations in registration or surgical guidance. Registration of preoperative data to the intraoperative anatomy remains a time-consuming, error-prone task that includes exposure to harmful radiation. Surgical guidance through
conventional displays has well-known drawbacks, as information cannot be presented in-situ and from the surgeon’s perspective. Consequently, radiation-free and more automatic registration methods with subsequent surgeon-centric navigation feedback are desirable. 

In this work, we present a marker-less approach that automatically solves the registration problem for lumbar spinal fusion surgery in a radiation-free manner.

<div class="gallery" data-columns="2">
    <img src="/images/projects/spinedepth2/1.jpg">
    <img src="/images/projects/spinedepth2/2.jpg">
</div>

A deep neural network was trained to segment the lumbar spine and simultaneously predict its orientation, yielding an initial pose for preoperative models, which then is refined for each vertebra individually and updated in real-time with GPU acceleration while handling surgeon occlusions. An intuitive surgical guidance is provided thanks to the integration into an augmented reality based navigation system. 

<img src="/images/projects/spinedepth2/3.jpg" style="width:400px;height:600px;">


The registration method was verified on a public dataset with a median of 100% successful registrations, a median target registration error of 2.7 mm, a median screw trajectory error of 1.6° and a median screw entry point error of 2.3 mm. Additionally, the whole pipeline was validated in an ex-vivo surgery, yielding a 100% screw accuracy and a median target registration error of 1.0 mm. 

<iframe src="https://www.youtube.com/embed/gFEjqcSd9nw" width="640" height="360" frameborder="0" allowfullscreen></iframe>

Our results meet clinical demands and emphasize the potential of RGB-D data for fully automatic registration approaches in combination with augmented reality guidance.

---

**Citation**

```
Liebman F, von Atzigen M, Stütz D, Wolf J, Zingg L, Suter D, Cavalcanti NA, Leoty L, Esfandiari H, Snedeker JG, Oswald MR, Polleyfeys M, Farshad M, Fürnstahl P. 
Automatic registration with continuous pose updates for marker-less surgical navigation in spine surgery. 
Medical Image Analysis. 2023 (Preprint). 
```

<a href="https://www.sciencedirect.com/science/article/pii/S1361841523002876" class="button button--small">Find the paper here</a>