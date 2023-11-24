---
title: 'SpineDepth'
subtitle: "From intraoperative RGB-D imaging to direct anatomical 3D reconstruction"
date: 2023-10-17 12:07:23
description: "A multi-modal approach that enables acquisition of large clinical data, tailored to pedicle screw placement, using RGB-D sensors and a co-calibrated high-end optical tracking system was developed."
featured_image: '/images/projects/spinedepth/1.png'
---


Computer aided orthopedic surgery suffers from low clinical adoption, despite increased accuracy and patient safety. This can partly be attributed to cumbersome and often radiation intensive registration methods. Emerging RGB-D sensors combined with artificial intelligence data-driven methods have the potential to streamline these procedures. However, developing such methods requires vast amount of data. 

To this end, a multi-modal approach that enables acquisition of large clinical data, tailored to pedicle screw placement, using RGB-D sensors and a co-calibrated high-end optical tracking system was developed. The resulting dataset comprises RGB-D recordings of pedicle screw placement along with individually tracked ground truth poses and shapes of spine levels L1–L5 from ten cadaveric specimens.

<img src="/images/projects/spinedepth/1.png">

We found a mean target registration error of 1.5 mm. The median deviation between measured and ground truth bone surface was 2.4 mm. 

<div class="gallery" data-columns="2">
    <img src="/images/projects/spinedepth/2.png">
    <img src="/images/projects/spinedepth/3.png">
    <img src="/images/projects/spinedepth/4.png">
</div>

In addition, a surgeon rated the overall alignment based on 10% random samples as 5.8 on a scale from 1 to 6. 

<img src="/images/projects/spinedepth/animation.gif">

Generation of labeled RGB-D data for orthopedic interventions with satisfactory accuracy is feasible, and its publication shall promote future development of data-driven artificial intelligence methods for fast and reliable intraoperative registration.

---

**Citation:** 

```
Liebmann F, Stütz D, Suter D, Jecklin S, Snedeker JG, Farshad M, Fürnstahl P, Esfandiari H. 
SpineDepth: A multi-modal data collection approach for automatic labelling and intraoperative spinal shape reconstruction based on RGB-D data. 
J Imaging. 2021 Aug 27;7(9):164.
```

<a href="https://www.mdpi.com/2313-433X/7/9/164" class="button button--large">Find the paper here</a>