---
layout: archive
title: ""
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Download Pdf](https://preritj.github.io/files/prerit.pdf)

Education
======
* B.Tech. in Engineering Physics, IIT Bombay, 2003-2007
* Ph.D in Theoretical Physics, Stony Brook University, 2007-2012

Work experience
======
* *Jan 2022 - Present*: ***Sr. Applied Scientist*** at **Amazon Web Services, Chime SDK**    
    *Amazon Chime SDK lets builders add real-time voice, video, and messaging powered by machine learning into their applications.*
   * Built new ML based features for video conferencing such as face relighting and face touch-up / skin smoothing. Trained face segmentation model with limited dataset and designed novel post-processing algorithms for real-time inference.
   * Optimized models to run on edge devices such as laptops and mobiles.
   * Implemented algorithms for background blur, skin smoothing and look-up tables in WebGL to further reduce run-time in the browsers.
   * Conducted Mean Opinion Scoring studies to evaluate the model performance and to identify any biases.

* *Jun 2021 - Dec 2021*: ***Sr. Machine Learning Engineer*** at **DeepMap**    
    *DeepMap (now part of **NVIDIA** builds HD maps for self-driving cars.*
   * Integrated traffic sign detection and classification models in pipeline for building HD maps for autonomous vehicles. Sensor fusion with LiDAR point cloud was used to get robust predictions.

* *Dec 2018 - May 2021*: ***Sr. Machine Learning Engineer*** at **Standard AI**    
    *Standard AI (formerly Standard Cognition) builds technology behind autonomous stores / cashier-less checkouts.*
    * Prototyped several deep learning models in Tensorflow and PyTorch. This includes multi-person human pose estimation including uncertainty estimates, transformer based action recognition and 2D-to-3D pose lifting for real-time shopper tracking and event detection in cashierless checkout technology.
    * Built pipeline for 3D reconstruction of shelves in the store using both classical methods such as SfM and SIFT as well deep models for multi-view reconstruction.
    * Built pipelines for data ingestion with data version control and created training dataflows with augmentation stacks.
    * Performed optimizations for real-time inference such as writing post-processing in cython/Rust and running TensorRT optimization on models for inference on edge device.
    * Implemented computer vision algorithms for 3D triangulation and camera projection in Rust (faster than OpenCV implementation).
    * Designed efficient deep model for semantic change detection of skus on shelves. Generated synthetic dataset for training in Blender through python scripting.
    * Implemented several real-time algorithms for assisting humans in the loop.
    * Built metrics for ML models that directly pertain to business.

* *March 2018 - Dec 2018*: ***Computer Vision Engineer*** at **AVAretail**    
    *AVAretail builds smart stores for retailers for frictionless experience.*
    * AI lead for development of cashier-less checkout systems at retail stores using computer vision and deep learning.
    * Designed multi-person human pose estimation and shopper re-identification (based on triplet loss) models in TensorFlow for real-time use in embedded devices.
    * Implemented object detection model for checkout technology using fully synthetic data.
    
    
Training / Courses
======
* *2017-2018*: **Udacity Self-driving Car Nanodegree**  
  Implemented models for traffic light detection and classification, path planning and control in an actual self-driving car.
* *2017*: **Udacity Deep Learning and Machine Learning Nanodegree**  
  SVM, decision trees, Reinforcement learning, Seq2Seq models, GANs 
    
  
Projects
======
* *Nov 2017 - Feb 2018*: **Didi Chuxing Self-Driving Car Challenge**  
  Implemented neural network for real- time vehicle and pedestrian 3D detection, by using camera, LiDAR and radar data. Placed 8th out of 2,000+ registered teams.  
