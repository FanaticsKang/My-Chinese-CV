---
layout: cv
title: 康轶非 
phone: 18049665058
email: ccyclonel@126.com
---
# 康轶非

<!--
include contact information from the front matter
Supported arguments:
    - homepage: url, text
    - phone
    - email
-->
{% include cv-contact.html %}

## 工作及教育经历
### __长安汽车__ `2020.11-`
- 高精度定位技术室负责人，高精度地图技术主管

### __纵目科技__ `2019.7-2020.10`
- 定位算法高级工程师   

### __京东X事业部无人车团队__ `2018.7 -2019.7`
- 自动驾驶算法工程师

### __北京交通大学__ `2010.9 - 2015.7`
- 交通信息工程及自动化专业 `博士学位`
- 主修课程: Multiple View Geometry in Computer Vision; FastSLAM.

### __北京交通大学__ `2006.9 - 2010.7`
- 自动化系 `学士学位`

## 项目及研究经历
### __多目视觉SLAM (已量产)__ `纵目`
- **成果被 IROS 2021 收录**;
- 负责多目视觉系统的建图与定位算法;
- 负责多目视觉系统的在线标定工作;
- 指导多目视觉SLAM的半稠密建图;
- 完善g2o功能， Pull Request #402.

### __城区场景众包建图__ `长安`
- 设计用于城区场景的众包建图方案；
- 使用众包地图进行城区场景的定位；
- 打通城区场景，高速场景和停车场场景的定位。

### __语义定位算法__ `长安`
- 设计基于高速场景的语义定位算法;
- 设计基于停车场环境的语义定位算法.

### __多传感器融合定位算法(量产中)__ `长安`
- 设计Error state Kalman Filter模型和工程;
- 增加了轮速尺度因子，进一步提高定位精度;
- 测试long-term场景下的定位效果;
- 负责EsKF设计和工程实现.

### __无人配送车(ROVER 5.0)__ `京东`
- 负责开发激光视觉里程计算法模块;
- 负责编写第五代无人配送车定位算法和系统之间的线程调度模块;
- 参与编写第五代无人配送车部分系统模块编写;
- 修复了相关的OpenCV Bug, Pull Request #14583.

### __视觉SLAM算法研究__ `北京交通大学`
- 通过 SURF 角点提取/匹配提高视觉 SLAM 的匹配准确性;
- 通过 Cubature Kalman Filter 减少 SLAM 中非线性计算的误差;
- 提出 Cubature (Quadrature) FastSLAM 算法, 提高的定位结果;
- 完成 iSAM 算法和 G2O 算法在 ROS 环境下的 SLAM算法测试.

## 其他经历

### __担任北京交通大学Robocon小组指导老师__ `北京交通大学`
```
2011-2013
```
- 指导设计基于激光雷达的全局定位算法框架;
- 指导设计基于视觉识别的跟踪算法框架.

## 获奖情况

### 长安汽车科技贡献奖 `2021`

### 西安市D类人才 `2018`

### 研究生电子设计大赛华北赛区一等奖 `2014`


## 发表论文

### [1] __Yifei Kang__, Yu Song, WuWei Ge and Tong Ling, Robust Multi-Camera SLAM with Manhattan Constraint Toward Automated Valet Parking. International Conference on Intelligent Robots and Systems(IROS), 2021, 7592-7599.
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
