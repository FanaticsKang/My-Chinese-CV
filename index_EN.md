---
layout: cv
title: Yifei Kang
phone: +86 18049665058
email: ccyclonel@gmail.com
---
# Yifei Kang

<!--
include contact information from the front matter
Supported arguments:
    - homepage: url, text
    - phone
    - email
-->
{% include cv-contact.html %}

## Work & Education Experience

### __Changan Automobile__ `2020.11 - Present`
- Modules: BEV Static, BEV Dynamic (Parking), Localization, Calibration
- Team Size: 68

### __Zongmu Technology__ `2019.7 - 2020.10`
- Senior Localization Algorithm Engineer

### __JD X-Division Autonomous Driving Team__ `2018.7 - 2019.7`
- Autonomous Driving Algorithm Engineer

### __Hualu Engineering Technology Co., Ltd.__ `2015.7 - 2018.6`
- Automation & Instrumentation Engineer
- Software Product Development

### __Beijing Jiaotong University__ `2006.9 - 2015.7`
- Automation Department `Bachelor's Degree`
- Ph.D. in Transportation Information Engineering and Automation
- Key Courses: Multiple View Geometry in Computer Vision; FastSLAM

## Project Experience

### __Parking End-to-End__`Changan 2026`
- Led parking end-to-end new pipeline design: full AI coding, new DAG architecture, 360x efficiency improvement over driving end-to-end pipeline
- Contributed to parking end-to-end model development: modified PlanR1 Geometry deep learning network; responsible for pruning traffic light modules for parking scenarios
- Agent Development:
    - Completed: fully automated weekly report agent; automated commit summary agent
    - In progress: fully automated engineering agents including code refactoring, testing, and graphical verification agents

### __Intelligent Driving Perception System Technical Lead__`Changan 2024-2025`
- **Core Achievements**: Real-time semi-dense Mapping [Industry's Only Mass Production], OCC Mapping Accuracy 2.78cm [Target <5cm Achieved, Industry-Leading], Real-time LiDAR Odometry 3.5‰ [Best-in-Class Mass Production]
- Led mass production vehicle calibration, after-sales calibration, and online calibration; **[Mass Production: CHANGAN NEVO  E07, Q07]**
- Led Real-time crowdsourced mapping and localization, from vehicle sensor data real-time construction of HD-map-like maps; **[Mass Production: CHANGAN NEVO  E07]**
- Led **industry's only mass-produced real-time semi-dense mapping** (replacing OCC). Real-time semi-dense mapping around target parking spaces, effectively solving suspended obstacle detection challenges, precisely identifying umbrellas, ping-pong tables and other extreme cases; **[Mass Production: CHANGAN NEVO  Q07]**
- Led large-scale high-precision OCC data pipeline design: **mapping accuracy 2.78cm (achieving <5cm design target, industry-leading)**, benchmarked against Tesla 10cm; involved in sensor selection, bracket design, multi-LiDAR large-scale Bundle Adjustment (5 LiDARs, 600 frames, ~30 million point clouds, single LiDAR accuracy 2.5cm)
- Led design of **best-in-class mass production real-time high-precision LiDAR odometry**: mass production LiDAR accuracy 5cm, odometry achieving **3.5‰ accuracy** (only 3.5cm error per 10m, FastLio 7cm and LOAM 12cm), benchmarked against Huawei SuperOdom; **[Mass Production: CHANGAN NEVO  Q07]**
- Led BEV network ground height estimation module design for better PV collaboration; **[Mass Production: CHANGAN NEVO  Q07]**
- Led BEV network static and dynamic model post-processing; **[Mass Production: CHANGAN NEVO  Q07]**

### __Intelligent Driving Localization System Technical Lead__`Changan 2022-2023`
- Real-time visual ICP with wheel odometry and imu localization algorithm based on HD maps, supporting mass production highway assisted driving; **[Mass Production: Deepal SL03, S07]**
- Multi Camera feature point-based SLAM underground parking garage mapping and localization algorithm, supporting mass production AVP; **[Mass Production: Deepal SL03, S07]**

## Academic Research & Open Source Contributions

#### __Multi-Camera Vision SLAM System__ `Zongmu 2021` **【IROS 2021 First Author Paper Engineering Implementation】**
- Led multi-camera vision system mapping and localization algorithm development
- Led multi-camera vision system online calibration
- Published at IROS 2021, the top robotics conference, as first author

#### __Open Source Core Contributions__
- **OpenCV Pull Request #14583**: Fixed critical bug, improving computer vision core library stability
- **g2o Pull Request #402**: Optimized graph optimization library performance, contributing to SLAM core algorithm library
- **msckf Pull Request #116**: Improved visual SLAM algorithm implementation, enhancing localization accuracy

## Other Experience

### __China Association of Automobile Manufacturers Committee Member__ `Changan`
- 2023.10.19 Became [Member of Sensor Subcommittee, China Association of Automobile Manufacturers](https://www.sae-china.org/branch/366)
- Led formulation of vehicle coordinate system national standard, completed [standardization research](http://www.catarc.org.cn/upload/202312/25/202312251456042419.pdf)
- Led national standard formulation for "Intelligent Connected Vehicle Coordinate System"
- Competition advisor for Beijing Jiaotong University robotics competitions for two years

## Selected Publications

### [1] __Yifei Kang__, Yu Song, WuWei Ge and Tong Ling, Robust Multi-Camera SLAM with Manhattan Constraint Toward Automated Valet Parking. International Conference on Intelligent Robots and Systems (__IROS__), 2021, 7592-7599.
### [2] __Yifei Kang__, Yongduan Song, Yu Song, and Deli Yan, Stereo Visual Odometry Algorithm with Rotation-Translation Decoupling for Dynamic EnvironmentsSquare-Root Cubature Kalman Filter and Its Application to SLAM of a Mobile Robot. Robot,2014, 36(3), 758-768;
### [3] __Yifei Kang__, Yongduan Song, Yu Song, and Deli Yan, Square-Root Cubature Kalman Filter and Its Application to SLAM of a Mobile Robot. Robot,2013, 35(2),186-193;
### [4] __Yifei Kang__, Yongduan Song, Yu Song, and Deli Yan, SLAM without odometer. Journal of ZHEJIANG University, 2014, 48(3): 414-422.
### [5] Y Song, Q L Li, __Y F Kang__ and Y D Song, CFastSLAM: a new Jacobian free solution to SLAM problem. International Conference on Robotics and Automation (__ICRA__), 2012, 3063-3068.
### [6] Y Song, Q L Li, __Y F Kang__ and Deli Yan. Effective cubature FastSLAM: SLAM with Rao-Blackwellized particle filter and cubature rule for Gaussian weighted integral, Aug 2013.
### [7] Y Song, Q L Li, Deli Yan and __Y F Kang__, Robust Visual Tracking with Classifier-like appearance Model and Entropy Particle Filter, Processing of the 10 th World Congress on Intelligent Control and Automation, 2012, 4853-4858.
### [8] Y.D Song, W.C Cai, __Y F Kang__ and Danyong Li, A System to Prevent the Controller from the Impact, invention patent.
### [9] Y.D song, __Y F Kang__ and Lei Wang, Real-Time Localization System without GPS for High Speed Train, invention patent.


<!-- ### Footer

Last updated: May 2013 -->
