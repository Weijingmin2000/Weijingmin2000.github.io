---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---


<h2> 2023 </h2>

<p><u>Language-Driven 3D Stylization</u><br>
Advisor: Prof. Yue Wang<br>
Course Project<br>
<a href="https://github.com/Weijingmin2000/Language-Driven-3D-Stylization" class="btn btn--warning">Code</a></p>
<ul>
    <li>Developed a language-driven 3D stylization pipeline.</li>
    <li>Trained a radiance field model for 3D object rendering.</li>
    <li>Applied GroundingedSAM to generate segmentation masks for any given object query inputs, allowing object-level selection for targeted stylization.</li>
    <li>Applied masked NNFM to fine-tune the pretrained radiance field to achieve 3D stylization.</li>
</ul><p>

<p><u>Multi-object Robust Tracking</u><br>
Advisor: Prof. Ram Nevatia<br>
Research Program<br>
<ul>    
    <li>Developed a defense pipeline to address multi-object tracking challenges against adversarial attacks.</li>
    <li>Implemented the RAFT optical flow detector combined with homography on localized patch regions, inverted optical flow to original frames to enhance downstream tracker's target detection within patch regions.</li>
    <li>Achieved robust detection and association accuracy in comparison to patch detectors used in object detection.</li>
</ul><p>

<p><u>Multi-modal Masked Adapter</u><br>
Advisor: Prof. Jesse Thomason<br>
Course Project, Score A<br>
<a href="https://github.com/YinzhenWang/Real_CLIP_Adapter" class="btn btn--warning">Code</a><br>
<ul>
    <li>Developed a masked Adapter for fine-tuning the pre-trained CLIP model.</li>
    <li>Applied LoRA Adapter to downstream multimodal tasks.</li>
    <li>Trained with masked image modeling, masked language modeling and masked image & language modeling to achieve better multimodal representation.</li>
    <li>Achieved comparable performance to fully fine-tuning with only 10% parameters and reduced training time.</li>
    <li>Proved that knowledge acquired from unimodal Adapters can support and assist multimodal tasks.</li>
</ul><p>


<h2> 2022 </h2>
<p><u>Robust Object Detection Against Adversarial Attacks</u><br>
Advisor: Prof. Ram Nevatia<br>
Research Program<br>
<ul>    
    <li>Developed a defense pipeline for RGB-depth object detection against different adversarial attacks (nonadaptive attacks, adaptive attacks).</li>
    <li>Formulated the patch defense problem as a segmentation task for RGB channel to detect adversarial patch.</li>
    <li>Maked an identical mapping for depth channel to leverage depth features and fused with RGB defense outcomes.</li>
    <li>Applied the defense patch detector against various attack initializations, like stars and gems, and different attack optimizers, like PGD and Adam, to test the adaptability of the defense method.</li>
    <li>Achieved robust detection accuracy and cross-optimizer robustness.</li>
</ul><p>

<p><u>Emotion Assessment System Based on Facial Language Understanding</u><br>
Advisor: Prof. Sheng Zhong<br>
Research Program, Team leader<br>
<ul>
    <li>Developed a emotion assessment system based on facial language analysis and understanding.</li>
    <li>Completed the training and validation of YOLO v5 and Dual Path Network on PC side, which involves processing multi-frame data, targeting and classifying facial emotion, creating a visualization UI, and utilizing time series methods to predict emotions.</li>
    <li>Deployed the model on embedded platform, accelerate model inference speed in a GPU-free environment, addressing challenges in detection accuracy and model efficiency.</li>
</ul><p>


<h2> 2021 </h2>

<p><u>PIV Based on Stereoscopic Gesture Information</u><br>
Advisor: Prof. Yang Xiao<br>
Course Project, Full Mark<br>
<ul>
    <li>Implemented PIV task by using RGB and 3D depth gesture information.</li>
    <li>Trained and tested on 3 different models: two-stream ResNet for blur and detail images, two-stream ResNet for RGB and depth images, and PointNet for depth images</li>
    <li>Optimized result by combining some classic methods: guided filter & edge extraction, stacking ensemble algorithm.</li>
</ul><p>


<p><u>Peeping Camera Recognition and Detection</u><br>
Advisor: Prof. Jie Ma<br>
Course Project, Score A+<br>
<ul>
    <li>Developed a peeping camera recognition and detection system.</li>
    <li>Collected natural and infrared light images, identified bright spots of camera through algorithms like image difference, OTSU threshold segmentation, region growth and clustering.</li>
    <li>Developed a visualization UI based on MFC.</li>
</ul><p>


<p><u>Research on Semantic Segmentation of Remote Sensing Image</u><br>
Big Data Competition, National First Prize (30 out of 1000 teams)<br>
<ul>
    <li>Implemented the semantic segmentation of remote sensing images through K-mean clustering, watershed, mean-shift, graph cuts.</li>
    <li>Focused on improving accuracy by considering more complex semantic segmentation networks, achieved the best segmentation result by applying FCN, U-Net and SegNet.</li>
    <li>Optimized the model by some morphological operations. </li>
</ul><p>


<h2> 2019 </h2>

<p><u>Embedded Machine Vision Design</u><br>
Control Innovation Base Class of Qiming College of HUST<br>
Competition Program, Score A+<br>
<ul>
    <li>Joined the Control Innovation Base Class of Qiming College of HUST.</li>
    <li>Implemented the object recognition for a small intelligent car based on color recognition and PID control algorithm.</li>
</ul><p>

<p><u>Securities Quantitative Trading Software</u><br>
Advisor: Prof. Dingxin He<br>
Course Design, Full Mark<br>
Second prize in the C Software Design Competition<br>
<a href="https://github.com/Weijingmin2000/STOCK" class="btn btn--warning">Code</a></p>
<ul>
    <li>Conducted feasibility analysis, demand analysis, system function design, code implementation, software advantages and shortcomings analysis, and integration testing in the process of software design.</li>
    <li>Set functions into the software, including market condition analysis, market information display, recent ten years’ stock data switching and scientific visualization, fundamental and technical stock selection, user operations, dynamic stock update, etc.</li>
    <li>Completed the software with a report which defined the software system architecture design, software structure and data structure design, interface and call between each module, system interface design, system function design (function listing), specific algorithm design, etc.</li>
    <li>Got the only full mark of the school in the final evaluation, and won the second prize in the C Software Design Competition.</li>
</ul><p>