---
title: 'Intraoperative C-arm base tracking'
subtitle: "From optical data to tracking a C-arm!"
date: 2017-10-17 12:07:00
description: "A single-camera odometry system for localization of C-arm devices."
featured_image: "/images/projects/basetracking/1.png"
---

This study provides a framework for a single-camera odometry system for localizing a surgical C-arm base. An application-specific monocular visual odometry system (a downward-looking consumer-grade camera rigidly attached to the C-arm base) is proposed in this research.

<img src="/images/projects/basetracking/1.png">

The cumulative dead-reckoning estimation of the base is extracted based on frame-to-frame homography estimation. Optical-flow results are utilized to feed the odometry. Online positional and orientation parameters are then reported.

<img src="/images/projects/basetracking/2.png">

Positional accuracy of better than 2% (of the total traveled distance) for most of the cases and 4% for all the cases studied and angular accuracy of better than 2% (of absolute cumulative changes in orientation) were achieved with this method. 

<img src="/images/projects/basetracking/3.png">

This study provides a robust and accurate tracking framework that not only can be integrated with the current C-arm joint-tracking system (i.e. TC-arm) but also is capable of being employed for similar applications in other fields (e.g. robotics).

---

**Citation**

```
Esfandiari H, Lichti D, Anglin C. 
Single-camera visual odometry to track a surgical X-ray C-arm base. 
Proc Inst Mech Eng H. 2017 Dec;231(12):1140-1151.  
```

<a href="https://journals.sagepub.com/doi/10.1177/0954411917735556" class="button button--small">Find the paper here</a>