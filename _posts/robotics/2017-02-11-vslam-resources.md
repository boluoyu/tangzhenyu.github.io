---
layout: post
category: robotics
title: VSLAM
date: 2017-02-11
---

# SFM-AR-Visual-SLAM 

## Visual SLAM 

OKVIS: Open Keyframe-based Visual-Inertial SLAM
http://ethz-asl.github.io/okvis/index.html

Uncertainty-aware Receding Horizon Exploration and Mapping Planner
https://github.com/unr-arl/rhem_planner

##### S-PTAM: Stereo Parallel Tracking and Mapping
https://github.com/lrse/sptam

##### mcptam
MCPTAM is a set of ROS nodes for running Real-time 3D Visual Simultaneous Localization and Mapping (SLAM) using Multi-Camera Clusters. It includes tools for calibrating both the intrinsic and extrinsic parameters of the individual cameras within the rigid camera rig.

https://github.com/aharmat/mcptam

##### FAB-MAP
visual place recognition algorithm
https://github.com/arrenglover/openfabmap

##### rat-SLAM
https://github.com/davidmball/ratslam


### RGB-D Visual SLAM

##### Fast Odometry and Scene Flow from RGB-D Cameras 
https://github.com/MarianoJT88/Joint-VO-SF
was published in ICRA 2017

##### Real-Time Appearance-Based Mapping
http://wiki.ros.org/rtabmap_ros ...
Many Demos are available in the website with Several ROS bags

##### general and scalable framework for visual SLAM
https://github.com/strasdat/ScaViSLAM/

https://github.com/felixendres/rgbdslam_v2
ROS ready, It has PHD thesis from TUM 

##### SLAM in unstructed environments
https://github.com/tu-darmstadt-ros-pkg/hector_slam

##### Dense Visual Odometry and SLAM (dvo_slam)
https://github.com/tum-vision/dvo_slam

##### Coslam: Collaborative visual slam in dynamic environments
https://github.com/danping/CoSLAM

##### Real-time dense visual SLAM system  : ElasticFusion

https://github.com/mp3guy/ElasticFusion ...
it has nice gui and dataset , paper and video too . 

##### Real-time dense visual SLAM
https://github.com/mp3guy/Kintinuous

##### Deferred Triangulation SLAM
Based on PTAM and SLAM track 3d traingulated and 2d non triangulated features . 
https://github.com/plumonito/dtslam

##### Dense RGBD slam
https://github.com/dorian3d/RGBiD-SLAM


##### SceneLib2 - MonoSLAM open-source library
from oxford university c++ SLAM  
https://github.com/hanmekim/SceneLib2

##### next best view planner
https://github.com/ethz-asl/nbvplanner

### Augmented Reality

##### PTAM (Parallel Tracking and Mapping) :  
http://www.robots.ox.ac.uk/~gk/PTAM/

##### PTAM Android : 
https://github.com/damienfir/android-ptam


### Monocular SLAM

##### ORB-SLAM: A Versatile and Accurate Monocular SLAM System
https://github.com/raulmur/ORB_SLAM ....

its modification : ORB-SLAM2 is a real-time SLAM library for Monocular, Stereo and RGB-D cameras
https://github.com/raulmur/ORB_SLAM2

its modification to work on IOS : 
https://github.com/Thunderbolt-sx/ORB_SLAM_iOS

##### REMODE (REgularized MOnocular Depth Estimation)
https://github.com/uzh-rpg/rpg_open_remode ... 
Probabilistic, Monocular Dense Reconstruction in Real Time

##### Fast Semi-Direct Monocular Visual Odometry
https://github.com/pizzoli/rpg_svo

##### Fast Semi-Direct Visual Odometry for Monocular, Wide Angle, and Multi-camera Systems
no loop closure or bundle adjustment 
http://rpg.ifi.uzh.ch/svo2.html

##### LSD-SLAM: Large-Scale Direct Monocular SLAM
https://github.com/tum-vision/lsd_slam

##### A Robust and Versatile Monocular Visual-Inertial State Estimator
https://github.com/HKUST-Aerial-Robotics/VINS-Mono


## LIDAR based

##### LiDAR-based real-time 3D localization and mapping
https://github.com/erik-nelson/blam

##### segmatch
https://github.com/ethz-asl/segmatch
A 3D segment based loop-closure algorithm | ROS ready


## Visual Odometry

##### ROVIO
Robust Visual Inertial Odometry
https://github.com/ethz-asl/rovio

##### Dense Sparse odometry
https://github.com/JakobEngel/dso

##### monocular odometry algorithm
https://github.com/alejocb/dpptam
Dense Piecewise Planar Tracking and Mapping  from a Monocular Sequence IROS 2015

##### Kalibr
IMU camera calibration toolbox and more.
https://github.com/ethz-asl/kalibr

Camera-to-IMU calibration toolbox
https://github.com/hovren/crisp 

## SFM 

##### Structure from Motion (SfM) for Unordered Image Collections
https://github.com/TheFrenchLeaf/Bundle

##### Android SFM
https://github.com/danylaksono/Android-SfM-client

##### Five Point , 6,7,8 algorithms
open geometrical vision
https://github.com/marknabil/opengv

##### openSFM
Structure from Motion library written in Python on top of OpenCV. It has dockerfile for all installation on ubuntu 14.04
https://github.com/mapillary/OpenSfM

##### Unsupervised Learning of Depth and Ego-Motion from Video
An unsupervised learning framework for depth and ego-motion estimation from monocular videos 
https://github.com/tinghuiz/SfMLearner


https://github.com/mleotta/cvpr2015-opensfm

https://github.com/vrabaud/sfm_toolbox


concept in matlab 
http://vis.uky.edu/~stewe/FIVEPOINT/

Lorenzo Torresani's Structure from Motion Matlab code
https://github.com/scivision/em-sfm

OpenMVG C++ library
https://github.com/openMVG/openMVG

collection of computer vision methods for solving geometric vision problems
https://github.com/laurentkneip/opengv

#####

Multiview Geometry Library in C++11
http://theia-sfm.org/

## Others : 

#####Volumetric 3D Mapping in Real-Time on a CPU
https://github.com/tum-vision/fastfusion

##### SLAM with IMU on Android

https://github.com/knagara/SLAMwithCameraIMUforAndroid

##### IOS iphone 7 plus
https://github.com/HKUST-Aerial-Robotics/VINS-Mobile

##### Matlab
with some good documentation to how to read the image and so on from the kinect .
https://github.com/AutoSLAM/SLAM

# Dataset
##### EuRoC MAV Dataset
http://projects.asl.ethz.ch/datasets/doku.php?id=kmavvisualinertialdatasets

visual-inertial datasets collected on-board a Micro Aerial Vehicle (MAV). The datasets contain stereo images, synchronized IMU measurements, and accurate motion and structure ground-truth.

##### ICL NIUM
https://www.doc.ic.ac.uk/~ahanda/VaFRIC/iclnuim.html
benchmarking RGB-D, Visual Odometry and SLAM algorithms


# follow : 
## Robotics and Perception Group
https://github.com/tum-vision

## TUM VISION 
https://github.com/uzh-rpg
## handheld AR 
http://studierstube.icg.tugraz.at/handheld_ar/cityofsights.php

## Another Curated list
for SFM, 3D reconstruction and V-SLAM
https://github.com/openMVG/awesome_3DReconstruction_list

##  Universal grid map
https://github.com/ethz-asl/grid_map

## Real-Time Appearance-Based Mapping
Loop Closure Detection for Large-Scale Multi-Session Graph-Based SLAM (RGB-D Graph SLAM)
ros enabled 
https://github.com/introlab/rtabmap


## smoothing and mapping (SAM)
https://research.cc.gatech.edu/borg/download?destination=node%2F299
using factor graphs and Bayes networks as the underlying computing paradigm rather than sparse matrices.
and matlab also included in it 

**End!**
