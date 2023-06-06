## 自我介绍 

------

欢迎来到我的主页！<img src="https://raw.githubusercontent.com/MartinHeinz/MartinHeinz/master/wave.gif" width="30px">

![image](https://github.com/REAL-LXJ/REAL-LXJ/blob/main/picture/中央台.gif)

------

我是罗行健，东北大学机器人科学与工程学院**环境感知与自主导航实验室**硕士二年级，研究方向为**视觉SLAM**、**VIO**、**多传感器融合**。

本科就读于大连交通大学机械工程学院机械工程+软件工程专业，**TOE创新实验室成员**，负责能量机关的制作、视觉及步兵机器人的嵌入式控制。

|                     竞赛名称                     |             荣誉             |
| :----------------------------------------------: | :--------------------------: |
| 2021全国大学生机器人大赛ROBOMASTER机甲大师对抗赛 | **北部赛区冠军，国家一等奖** |
| 2020全国大学生机器人大赛ROBOMASTER机甲大师对抗赛 |        **国家一等奖**        |
|           2020全国大学生计算机设计大赛           |        **国家一等奖**        |
|    2019辽宁省普通高等学校本科大学生机器人竞赛    |         **省二等奖**         |

## **我的项目**

------

### **Structural Point And Line Aided Tightly-Coupled Visual-Depth-Inertial Odometry** 

利用室内结构环境信息和消费级相机D435i实现基于结构点线的RGBD惯性里程计SPLVDIO，并通过对算法模块进行优化，使其能够以纯视觉里程计PLVDO部署在四足机器人载体的NX平台上实时运行。（蓝色部分为去掉的模块）。

![image](https://github.com/REAL-LXJ/REAL-LXJ/blob/main/picture/SPLVDIO系统框图.png)

![image](https://github.com/REAL-LXJ/REAL-LXJ/blob/main/picture/市场.gif)

------

### IIR_IMU_Filter

基于**iir**实现**IMU**实时滤波算法，能够过滤IMU原始数据特定频率的噪声。

![image](https://github.com/REAL-LXJ/REAL-LXJ/blob/main/picture/四足机器人imu分析.png)

![image](https://github.com/REAL-LXJ/REAL-LXJ/blob/main/picture/imu滤波.gif)

------

### 环视相机地面语义SLAM

利用汽车环视鱼眼相机IPM拼接图的语义分割结果，基于车道线、车位线、箭头等地面语义标识，在RTK和轮速计的辅助下，生成一个全局的视觉语义地图，并在泊车时用语义信息进一步完成车辆定位。

![image](https://github.com/REAL-LXJ/REAL-LXJ/blob/main/picture/IPM_SLAM.png)

![image](https://github.com/REAL-LXJ/REAL-LXJ/blob/main/picture/东软IPM_SLAM.gif)

------

### 城市场景多传感器融合车辆位姿估计

融合视觉、IMU和轮速计实现复杂城市场景下低漂移的车辆位姿估计，并利用GPS的定位信息松耦合VIWO消除累积漂移。

![image](https://github.com/REAL-LXJ/REAL-LXJ/blob/main/picture/VIWO.gif)

------

### Low-drift Visual Inertial Odometry for Underground Parking

![image](https://github.com/REAL-LXJ/REAL-LXJ/blob/main/picture/东软地下停车场.gif)

------

### 能量机关识别

![image](https://github.com/REAL-LXJ/REAL-LXJ/blob/main/picture/能量机关.png)

![image](https://github.com/REAL-LXJ/REAL-LXJ/blob/main/picture/能量机关识别.gif)

------

### 能量机关实物

![image](https://github.com/REAL-LXJ/REAL-LXJ/blob/main/picture/能量机关.gif)

------

### 装甲板识别

![image](https://github.com/REAL-LXJ/REAL-LXJ/blob/main/picture/装甲板识别.gif)

------

### 步兵机器人嵌入式控制

