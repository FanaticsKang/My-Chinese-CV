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
- 环境组主管, 负责模块: Bev静态, BEV动态（泊车），定位，标定;
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
### __端到端研发项目（泊车）__ `长安 2025`
- 计划搭载车型启源E07；
- 负责OCC数据全链路工作，包括设备选型，采集方案，建图算法，标注规则，验收规则等；
- 负责端到端数据数据的收集和打包；
- 负责泊车端到端模型算法的研发。

### __单目半稠密建图（泊车）__ `长安 2024`
- 搭载车型启源Q07；
- 使用单目完成目标车位周边半稠密建图（替代OCC）;
- 算法有效解决悬空障碍物检测难题，精准识别雨伞、乒乓球桌等极端Case，提升泊车安全性；
- 精度12cm(2σ)，行业首创，无需训练数据，无需多增加芯片或相机，需要6秒月70%CPU。

### __高速/城区/停车场静态感知BEV后处理（行泊）__ `长安 2024`
- 计划搭载车型启源E07，启源Q07；
- 基于长安单Orin平台, Thor平台，单J6平台设计BEV静态实时建图；
- 以BEV模型输出为主，融合多模态信息，构建包括车道线，路沿，锥桶，停止线，红绿灯，车道中心线等信息；

### __量产标定__ `长安 2024`
- 搭载车型启源E07，启源Q07；
- 标定交付第一责任人，主导量产车型的全车下线标定，售后标定和在线标定;
- 测试车辆负载，老化，传感器重装导致的标定参数变化，确定范围和标定算法；
- 带领长安汽车标定方向0-1-N.

### __结构化道路众包建图与定位__ `长安 2023`
- 搭载车型启源E07；
- 作为车端众包建图算法总负责人，主导从车端传感器数据实时构建类高精地图的技术方案与落地。
- 实现单次成图全覆盖停车场、高速、城区等全结构化道路场景，​支持行泊一体功能。
- 带领长安汽车众包建图方向0-1.

### __基于高精度地图的定位算法__ `长安 2022`
- 搭载车型深蓝SL03, s7;
- 设计基于ICP的车道线匹配算法，包括数学模型与误差方程构建，提升定位精度与鲁棒性。
- 带领长安汽车高精度定位方向0-1-N.

### __停车场自动泊车系统__ `长安 2022`
- 搭载车型深蓝SL03, s7;
- 基于环视图像的停车场车端建图和定位;

### __多目视觉SLAM__ `纵目 2021`
- 负责多目视觉系统的建图与定位算法;
- 负责多目视觉系统的在线标定工作;

## 其他经历

### __中国汽车工业协会委员__ `长安`
- 2023.10.19 成为[中国汽车工业协会传感器分会委员](https://www.sae-china.org/branch/366);
- 牵头IMU和GNSS相关7个团体标准的制定;
- 牵头车载坐标系国家标准的制定, 目前完成[标准化调研](http://www.catarc.org.cn/upload/202312/25/202312251456042419.pdf).

### __无人配送车(ROVER 5.0)__ `京东`
- 负责开发激光视觉里程计算法模块;
- 负责编写第五代无人配送车定位算法和系统之间的线程调度模块;
- 修复了相关的OpenCV Bug, Pull Request #14583.

### __开源贡献__
- g2o Pull Request #402.
- OpenCV Pull Request #14583.
- msckf Pull Request #116.

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
