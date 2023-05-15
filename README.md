# Awesome-Gait--Analysis
Include open source software and code for gait analysis

来源：以 `gait` 为关键词，在Github 上进行搜索，查看前 15页的搜索结果，进行整理。

## 步态分析

### 图像

- 2018 `Python`  https://github.com/sarweshshah/gait_analysis 使用 OpenCV 获得人在空间中移动的轨迹
- 2020 `Matlab` `No paper`  https://github.com/janstenum/GaitAnalysis-PoseEstimation 使用 OpenPose 进行无标记分析，有一个简要的文档进行介绍。
- 2020 `Python` `paper`https://github.com/cadop/pyCGM 开源软件，并合 Vicon 的步态分析软件进行分析比较。
- 2020 `Python` `paper` https://github.com/stanfordnmbl/mobile-gaitlab ⚡️斯坦福大学开发，使用手机进行步态分析。有论文介绍以及详细的数据集。

### 传感器

- 2022 `Python` https://github.com/ivanvajs1996/Open-source-application-for-gait-analysis 使用Xsens 传感器绘制足部支撑。

- 2022 `python` https://github.com/xioTechnologies/Gait-Tracking	绘制走路时的轨迹。启发：可以用来分析太极拳等运动的轨迹。

- 2020 `Python` `paper`https://github.com/mustafa-sarshar/SmartGait 使用LSTM 机器学习方法，对位于小腿脚踝处的两个传感器进行步态分析
- 2020 `Python` `paper` https://github.com/h-gokul/ParkinsonsGaitAssist 使用机器学习区分帕金森病人的步态，特点：使用 Microsoft India 's EgdeML models，模型大小只有 1.4 KB
- 2019 `Python` https://github.com/WPI-AIM/AIM_GaitAnalysisToolkit 联合Vicon 工具进行步态分析
- 2018 `Python` `paper`  https://github.com/matt002/GaitPy ⚡️使用腰部的加速度传感器垂直方向的变化进行步态周期划分。GaitPy 属于[scikit-digital-health](https://github.com/PfizerRD/scikit-digital-health) 的一个小功能，[scikit-digital-health](https://github.com/PfizerRD/scikit-digital-health) 还能使用加速度数据进行睡眠周期的划分等其他健康功能。

- 2018 `C++` `No paper` https://github.com/srinivas-6/Gait-Data-Acquisition-and-Analysis 使用足部的柔性传感器获取步态分期数据，使用大腿和小腿处的传感器获得关节角度，金标准使用 Kinovea 处理视频数据。可借鉴的软件特点能够显示足底压力实时变化。
- 2018 `Python`  `No paper`https://github.com/MeetGandhi/Gait-Analysis-using-Machine-Learning 使用机器学习技术，以便分别行走正常和经胫骨截肢的人之间的区别。软件没有过多的介绍。
- 2018 `Matlab` `paper` https://github.com/gait-tech/gaittoolbox 有详细的文档，步态分析有详细的图形界面展示以及数据分析，最近的更新为 2018 年。使用三个 IMU 传感器进行评估。 
- 2018 `Python` `Matlab ` `paper`https://github.com/daehwa/Gait-Tracking-With-x-IMU-Python 使用足部的传感器，获得足部在空间中的三维变化 原本的 Matlab 代码参见 https://github.com/xioTechnologies/Gait-Tracking-With-x-IMU

## 步态识别

步态识别可以参见   [Awesome-Gait- Recognition](https://github.com/BNU-IVC/Awesome-Gait-Recognition) 

- 2017 `Python` `paper` https://github.com/palewithout/Gait_Datasets 综合使用 RGBD 传感器以及手机惯性传感器获取步态
- 2020`Python` `paper`https://github.com/hongyonghan/GaitRecognition
- 2019 `Python` `paper` https://github.com/qinnzou/Gait-Recognition-Using-Smartphones 使用手机中的传感器进行步态分类的识别。步态峰值的识别可以作为参考。

