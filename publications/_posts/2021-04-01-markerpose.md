---
layout: publication
title: MarkerPose&#58; Robust Real-time Planar Target Tracking for Accurate Stereo Pose Estimation
authors: Jhacson Meza, Lenny A. Romero, and Andres G. Marrugo
date: 2021-04-01 10:00
main_url: https://arxiv.org/abs/2105.00368
venue: CVPR 2021
principal: Andres Marrugo
active: true
summary: Despite the attention marker-less pose estimation has attracted in recent years, marker-based approaches still provide unbeatable accuracy under controlled environmental conditions. Thus, they are used in many fields such as robotics or biomedical applications but are primarily implemented through classical approaches, which require lots of heuristics and parameter tuning for reliable performance under different environments. In this work, we propose MarkerPose, a robust, real-time pose estimation system based on a planar target of three circles and a stereo vision system. MarkerPose is meant for high-accuracy pose estimation applications. Our method consists of two deep neural networks for marker point detection. A SuperPoint-like network for pixel-level accuracy keypoint localization and classification, and we introduce EllipSegNet, a lightweight ellipse segmentation network for sub-pixel-level accuracy keypoint detection. The marker's pose is estimated through stereo triangulation. The target point detection is robust to low lighting and motion blur conditions. We compared MarkerPose with a detection method based on classical computer vision techniques using a robotic arm for validation. The results show our method provides better accuracy than the classical technique. Finally, we demonstrate the suitability of MarkerPose in a 3D freehand ultrasound system, which is an application where highly accurate pose estimation is required. Code is available in Python and C++ at <this https URL>.
---
