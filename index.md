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
- 自动驾驶高精度定位专家，高精度定位算法总监 

### __纵目科技__ `2019.7-2020.10`
- 定位算法高级工程师   

### __京东X事业部无人车团队__ `2018.7 -2019.7`
- 自动驾驶算法工程师

### __华陆工程科技有限责任公司__ `2015.7 - 2018.6`
- 自控及仪表工程师
- 软件产品开发岗

### __北京交通大学__ `2010.9 - 2015.7`
- 交通信息工程及自动化专业 `博士学位`
- 主修课程: Multiple View Geometry in Computer Vision; FastSLAM.

### __北京交通大学__ `2006.9 - 2010.7`
- 自动化系 `学士学位`

## 项目及研究经历
### __语义定位算法__ `长安`
- 设计基于高速场景的语义定位算法;
- 设计基于停车场环境的语义定位算法.

### __多传感器融合定位算法(量产中)__ `长安`
- 设计Error state Kalman Filter模型和工程;
- 增加了轮速尺度因子，进一步提高定位精度;
- 测试long-term场景下的定位效果;
- 负责EsKF设计和工程实现.

### __基于视觉的停车场定位与建图(量产中)__ `长安`
- 使用车轮里程约束尺度;
- 测试long-term场景下的定位效果.
- 负责SLAM的方案设计和工程实现.

### __多目视觉SLAM (已量产)__ `纵目`
- 负责多目视觉系统的建图与定位算法;
- 负责多目视觉系统的在线标定工作;
- 指导多目视觉SLAM的半稠密建图;
- 完善g2o功能， Pull Request #402.

### __基于Manhattan世界的视觉SLAM研究__ `纵目`
- 对于停车场场景进行Manhattan世界估计;
- 全新的算法加速Manhattan世界估计;
- 估计的姿态约束多目视觉SLAM, 提升一个数量级的建图精度;
- Audi A2D2数据集验证, 3公里, 0.37% 水平误差比例.

### __基于已知轨迹的高精地图语义图层构建__ `纵目`
- 负责停车位语义信息的多帧融合算法;
- 根据已知图层轨迹构建语义图层;
- 多目视觉进行停车场, (半)稠密建图.

### __多传感器融合定位算法__ `纵目`
- 融合IMU, 轮速作为预测输入;
- 融合视觉特征图层, 语义图层, 毫米波图层的观测结果;
- 自建误差状态模型进行Kalman Filter.

### __无人配送车(ROVER 5.0)__ `京东`
- 负责开发激光视觉里程计算法模块;
- 负责编写第五代无人配送车定位算法和系统之间的线程调度模块;
- 参与编写第五代无人配送车部分系统模块编写;
- 修复了相关的OpenCV Bug, Pull Request #14583.

### __超市购物机器人(Version 2.0)__  `京东`
- 负责车辆跟随功能的编写和调试.
- 参与视觉建图模块的编写和调试;
- 参与激光建图模块的编写和调试.

### __视觉SLAM算法研究__ `北京交通大学`
- 通过 SURF 角点提取/匹配提高视觉 SLAM 的匹配准确性;
- 通过 Cubature Kalman Filter 减少 SLAM 中非线性计算的误差;
- 提出 Cubature (Quadrature) FastSLAM 算法, 提高的定位结果;
- 完成 iSAM 算法和 G2O 算法在 ROS 环境下的 SLAM算法测试.

### __立体视觉里程计和 RGB-D 视觉里程计的算法研究__ `北京交通大学`
- 通过解耦摄像机旋转-平移矩阵,提高算法在动态环境中的定位效果。

### __车辆转向的容错控制的算法研究__ `北京交通大学`
- 提出自适应 back-step 控制算法用于车辆转向应对来自地面的未知阻力的极端情况.

## 其他经历

### __完善g2o代码__ `纵目`
- g2o Pull Request #402, g2o::EdgeSim3::linearizeOplus.

### __修复opencv部分代码bug__ `京东`
- Opencv Pull Request #14583, cv::undistortPoint bug;
- 撰写定量评估相机标参数的程序.

### __担任北京交通大学Robocon小组指导老师__ `北京交通大学`
```
2011-2013
```
- 指导设计基于激光雷达的全局定位算法框架;
- 指导设计基于视觉识别的跟踪算法框架.

### __参与西门子旧工厂改造项目__  `西门子`
```
实习
```
- 参与旧工厂的数字化改造工作.

## 主要编程工具
- C, C++, C#;
- okvis, orb-slam, dso;
- opencv, opengv, g2o, ceres, pcl;
- blade, cmake;

## 获奖情况

### 西安市D类人才 `2018`

### 研究生电子设计大赛华北赛区一等奖 `2014`

## 发表论文

### [1] __Yifei Kang__, Yongduan Song, Yu Song, and Deli Yan, Stereo Visual Odometry Algorithm with Rotation-Translation Decoupling for Dynamic EnvironmentsSquare-Root Cubature Kalman Filter and Its Application to SLAM of a Mobile Robot. Robot,2014, 36(3), 758-768;
### [2] __Yifei Kang__, Yongduan Song, Yu Song, and Deli Yan, Square-Root Cubature Kalman Filter and Its Application to SLAM of a Mobile Robot. Robot,2013, 35(2),186-193;
### [3] __Yifei Kang__, Yongduan Song, Yu Song, and Deli Yan, SLAM without odometer. Journal of ZHEJIANG University, 2014, 48(3): 414-422.
### [4] Y Song, Q L Li, __Y F Kang__ and Y D Song, CFastSLAM: a new Jacobian free solution to SLAM problem. International Conference on Robotics and Automation (__ICRA__), 2012, 3063-3068.
### [5] Y Song, Q L Li, __Y F Kang__ and Deli Yan. Effective cubature FastSLAM: SLAM with Rao-Blackwellized particle filter and cubature rule for Gaussian weighted integral, Aug 2013.
### [6] Y Song, Q L Li, Deli Yan and __Y F Kang__, Robust Visual Tracking with Classifier-like appearance Model and Entropy Particle Filter, Processing of the 10 th World Congress on Intelligent Control and Automation, 2012, 4853-4858.
### [7] Y.D Song, W.C Cai, __Y F Kang__ and Danyong Li, A System to Prevent the Controller from the Impact, invention patent.
### [8] Y.D song, __Y F Kang__ and Lei Wang, Real-Time Localization System without GPS for High Speed Train, invention patent.


<!-- ### Footer

Last updated: May 2013 -->
