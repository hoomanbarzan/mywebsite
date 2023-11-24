---
title: 'Pedicle Screw Pose Estimation'
subtitle: "From intraoperative fluoroscopy to implant pose"
date: 2018-10-17 12:07:00
description: "A framework for automatic segmentation and pose estimation of pedicle screws using deep learning."
featured_image: "/images/projects/pedicle-screw-pose-estimation/3.png"
---

Pedicle screw fixation is a challenging procedure with a concerning rates of reoperation. After insertion of the screws is completed, the most common intraoperative verification approach is to acquire anterior–posterior and lateral radiographic images, based on which the surgeons try to visually assess the correctness of insertion. Given the limited accuracy of the existing verification techniques, we identified the need for an accurate and automated pedicle screw assessment system that can verify the screw insertion intraoperatively. For doing so, this paper offers a framework for automatic segmentation and pose estimation of pedicle screws based on deep learning principles.

<div class="gallery" data-columns="1">
	<img src="/images/projects/pedicle-screw-pose-estimation/1.png">
</div>


Segmentation of pedicle screw X-ray projections was performed by a convolutional neural network. The network could isolate the input X-rays into three classes: screw head, screw shaft and background. Once all the screw shafts were segmented, knowledge about the spatial configuration of the acquired biplanar X-rays was used to identify the correspondence between the projections. 

<img src="/images/projects/pedicle-screw-pose-estimation/4.png">

Pose estimation was then performed to estimate the 6 degree-of-freedom pose of each screw. The performance of the proposed pose estimation method was tested on a porcine specimen.

<div class="gallery" data-columns="2">
    <img src="/images/projects/pedicle-screw-pose-estimation/3.png">
    <img src="/images/projects/pedicle-screw-pose-estimation/5.png">
</div>


The developed machine learning framework was capable of segmenting the screw shafts with 93% and 83% accuracy when tested on synthetic X-rays and on clinically realistic X-rays, respectively. The pose estimation accuracy of this method was shown to be 1.93<sup>o</sup> (std:0.64<sup>o</sup>) and 1.92<sup>mm</sup> (std:0.55<sup>mm</sup>) on clinically realistic X-rays.

<img src="/images/projects/pedicle-screw-pose-estimation/animation.gif">

The proposed system offers an accurate and fully automatic pedicle screw segmentation and pose assessment framework. Such a system can help to provide an intraoperative pedicle screw insertion assessment protocol with minimal interference with the existing surgical routines.

---

**Citation**

```
Esfandiari H, Newell R, Anglin C, Street J, Hodgson AJ.
A deep learning framework for segmentation and pose estimation of pedicle screw implants based on C-arm fluoroscopy.
Int J Comput Assist Radiol Surg. 2018 Aug;13(8):1269-1282.  
```

<a href="https://link.springer.com/article/10.1007/s11548-018-1776-9" class="button button--small">Find the paper here</a>