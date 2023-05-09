## 自我介绍

------

我是罗行健，东北大学机器人科学与工程学院**环境感知与自主导航实验室**硕士二年级，研究方向为**视觉SLAM**、**VIO**、**多传感器融合**。

本科就读于大连交通大学机械工程学院机械工程+软件工程专业，**TOE创新实验室成员**，负责步兵机器人的电控、视觉，能量机关的制作。

|                     竞赛名称                     |             荣誉             |
| :----------------------------------------------: | :--------------------------: |
| 2021全国大学生机器人大赛ROBOMASTER机甲大师对抗赛 | **北部赛区冠军，国家一等奖** |
| 2020全国大学生机器人大赛ROBOMASTER机甲大师对抗赛 |        **国家一等奖**        |
|           2020全国大学生计算机设计大赛           |        **国家一等奖**        |
|    2019辽宁省普通高等学校本科大学生机器人竞赛    |         **省二等奖**         |

## **我的项目**

------

### **Structural Point And Line Aided Tightly-Coupled Visual-Depth-Inertial Odometry** 

利用室内结构场景下的**点**、**线**、**消失点**几何特征和**RGBD**、**IMU**传感器实现基于结构点线的紧耦合视觉深度惯性里程计**SPLVDIO**，能够在室内长走廊、白墙、玻璃反光等弱纹理、强曝光和动态干扰等挑战性场景下保持系统鲁棒性的同时提高位姿估计的精度，并通过对算法模块进行优化，使其能够以**PLVDO**部署在四足机器人载体的**NX**平台上实时运行（蓝色部分为去掉的模块）。

![image0](https://github.com/REAL-LXJ/REAL-LXJ/blob/main/picture/SPLVDIO系统框架.png)

------

### IIR_IMU_Filter

基于**iir**实现**IMU**实时滤波算法，能够过滤IMU原始数据特定频率的噪声。

![image](https://github.com/REAL-LXJ/REAL-LXJ/blob/main/picture/四足机器人imu分析.png)

------

### 环视相机地面语义SLAM

![image](https://github.com/REAL-LXJ/REAL-LXJ/blob/main/picture/IPM_SLAM.png)

![image](https://github.com/REAL-LXJ/REAL-LXJ/blob/main/picture/东软IPM_SLAM.gif)

------

### Low-drift Visual Inertial Odometry for Underground Parking

![image](https://github.com/REAL-LXJ/REAL-LXJ/blob/main/picture/东软地下停车场.gif)

------

### 能量机关识别

![image](https://github.com/REAL-LXJ/REAL-LXJ/blob/main/picture/能量机关识别.gif)

------

### 装甲板识别

![image](https://github.com/REAL-LXJ/REAL-LXJ/blob/main/picture/装甲板识别.gif)

------

### 能量机关

![image](https://github.com/REAL-LXJ/REAL-LXJ/blob/main/picture/能量机关.gif)
