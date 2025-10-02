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
### __长安汽车__ `2020.11-至今`
- 负责模块: Bev静态, BEV动态（泊车），定位，标定;
- 团队规模: 68人

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

## 项目经历

### __自动驾驶高精度定位技术总负责人__`长安 2022-2025`
- 基于高精度地图的定位算法; **【量产：深蓝SL03, S7】**;
- 带领长安汽车高精度定位方向0-1-N，实现从算法研发到量产落地的完整技术体系建设;
- 主导量产车型的全车下线标定，售后标定和在线标定; **【量产：启源E07, Q07】**
- 带领长安汽车标定方向0-1-N，建立完整的量产标定技术体系.

### __自动驾驶高精度建图技术总负责人__`长安 2023-2025`
- 结构化道路众包建图与定位负责人，主导从车端传感器数据实时构建类高精地图的技术方案与落地; **【量产：启源E07】**
- 带领长安汽车众包建图方向0-1，建立行业领先的车端建图技术体系;
- 使用单目完成目标车位周边半稠密建图（替代OCC）。算法有效解决悬空障碍物检测难题，精准识别雨伞、乒乓球桌等极端Case，提升泊车安全性;**【量产：启源Q07】**
- 停车场自动泊车系统（建图模块）。基于环视图像的停车场车端建图算法研发，实现低成本、高精度的场内地图构建，解决GPS信号缺失环境下的高精度定位难题，支持AVP功能量产落地。**【量产：深蓝SL03, S7】**

### __智能驾驶感知系统技术负责人__`长安 2024-2025`
- 基于长安单Orin平台、Thor平台、单J6平台设计BEV静态实时建图系统, 实现行泊一体的静态环境感知全场景应用。**【量产：启源E07, Q07】**

## 学术研究与开源贡献

#### __多目视觉SLAM系统__ `纵目 2021` **【IROS 2021第一作者论文工程实现】**
- 负责多目视觉系统的建图与定位算法研发
- 负责多目视觉系统的在线标定工作
- 相关研究成果发表于机器人领域顶级会议IROS 2021，担任第一作者

#### __开源社区核心贡献__
- **OpenCV Pull Request #14583**：修复关键Bug，提升计算机视觉核心库稳定性
- **g2o Pull Request #402**：优化图优化库性能，贡献SLAM领域核心算法库
- **msckf Pull Request #116**：改进视觉SLAM算法实现，提升定位精度

## 其他经历

### __中国汽车工业协会委员__ `长安`
- 2023.10.19 成为[中国汽车工业协会传感器分会委员](https://www.sae-china.org/branch/366);
- 牵头IMU和GNSS相关7个团体标准的制定;
- 牵头车载坐标系国家标准的制定, 目前完成[标准化调研](http://www.catarc.org.cn/upload/202312/25/202312251456042419.pdf).

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
