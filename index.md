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
### __长线科技__ `2024.1至今`
- 环境组主管, 负责模块: 标定，运动估计，定位，SLAM，模型后处理，环境融合
- 团队规模: 68人

### __长安汽车__ `2020.11-2023.12.30`
- 高精度定位行政主管/技术主管
- 高精度地图技术主管
- 团队规模: 35人

### __纵目科技__ `2019.7-2020.10`
- 定位算法高级工程师   

### __京东X事业部无人车团队__ `2018.7 -2019.7`
- 自动驾驶算法工程师

### __华陆工程科技有限责任公司__ `2015.7 - 2018.6`
- 自控及仪表工程师
- 软件产品开发岗

### __北京交通大学__ `2006.9 - 2015.7`
- 自动化系 `学士学位`
- 交通信息工程及自动化专业 `博士学位`
- 主修课程: Multiple View Geometry in Computer Vision; FastSLAM.

## 牵头负责项目经历
### __模型后处理和环境标定__ `长安`
- 融合BEV静态模型, FC 2D感知模型，激光感知模型的输出，构建车辆周围bev视角环境，生成车道中心线及其相关的红绿灯，道路标志等;
- 锥桶及静态障碍物的位置;
- 空间车位的识别和安全释放。

### __高精度航迹推算__ `长安`
- 使用固态激光雷达(error < 10cm)和量产级IMU达成20m之内航迹推算精度<5cm的高精度航迹推算。

### __量产标定__ `长安`
- 量产车型CD701的下线标定功能;
- 量产车型CD701的在线标定模块;
- 长安采购的真值采集的标定功能。

### __全结构化道路众包建图与定位__ `长安`
- 结构化道路上实现**行泊一体**，即建图一套算法，定位一套算法完成;
- 通过采集的众包地图生成智驾地图。单次成图地图尺寸0.2mb/km, **单次成图覆盖停车场，高速，城区——全结构化道路**;
- 完成在智驾地图上的连续定位，即停车场，高速，城区;

### __基于高精度地图的定位算法__ `长安`
- 项目已于长安深蓝SL03, s7上搭载, 累计测试里程70万公里;
- 基于高精度地图的定位;
- 设计error-state Kalman Filter的滤波及误差模型;
- 设计ICP的车道线匹配算法, 包括模型和误差方程设计;

### __停车场自动泊车系统__ `长安`
- 项目已于长安深蓝SL03, s7上搭载, 全国测试停车场350个;
- 基于环视图像的停车场车端建图;
- 基于停车场地图的高精度定位;
- 解决单目相机尺度问题。

### __多目视觉SLAM__ `纵目`
- [**成果被 IROS 2021 收录**](https://ieeexplore.ieee.org/abstract/document/9636304/);
- 负责多目视觉系统的建图与定位算法;
- 全新的算法加速Manhattan世界估计;
- 负责多目视觉系统的在线标定工作;
- 完善g2o功能， Pull Request #402.

## 其他经历

### __中国汽车工业协会委员__ `长安`
- 2023.10.19 成为[中国汽车工业协会传感器分会委员](https://www.sae-china.org/branch/366);
- 牵头IMU和GNSS相关7个团体标准的制定;
- 牵头车载坐标系国家标准的制定, 目前完成[标准化调研](http://www.catarc.org.cn/upload/202312/25/202312251456042419.pdf).

### __无人配送车(ROVER 5.0)__ `京东`
- 负责开发激光视觉里程计算法模块;
- 负责编写第五代无人配送车定位算法和系统之间的线程调度模块;
- 参与编写第五代无人配送车部分系统模块编写;
- 修复了相关的OpenCV Bug, Pull Request #14583.

## 主要编程工具
- C, C++, C#;
- opencv, opengv, g2o, ceres, pcl;
- cmake;

## 获奖情况

### 长安汽车股份有限公司技术贡献奖 `2023`
### 西安市D类人才 `2018`

## 发表论文

### [1] __Yifei Kang__, Yu Song, WuWei Ge and Tong Ling, Robust Multi-Camera SLAM with Manhattan Constraint Toward Automated Valet Parking. International Conference on Intelligent Robots and Systems(__IROS__), 2021, 7592-7599.
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
