## 自我介绍 

------

欢迎来到我的主页！<img src="https://raw.githubusercontent.com/MartinHeinz/MartinHeinz/master/wave.gif" width="30px">

![image](https://github.com/REAL-LXJ/REAL-LXJ/blob/main/picture/中央台.gif)

------

我是罗行健，📞18742543164，📧dulu2021@163.com

- 硕士就读于东北大学机器人科学与工程学院机器人科学与工程专业，**REAL实验室成员**，研究方向为**视觉SLAM**、**VIO**、**多传感器融合**。

- 本科就读于大连交通大学机械工程学院机械工程+软件工程五年制双专业，**TOE创新实验室成员**，主要负责**能量机关的制作、视觉及步兵机器人的嵌入式控制**。


|                     竞赛名称                     |             荣誉             |
| :----------------------------------------------: | :--------------------------: |
| 2021全国大学生机器人大赛ROBOMASTER机甲大师对抗赛 | **北部赛区冠军，国家一等奖** |
| 2020全国大学生机器人大赛ROBOMASTER机甲大师对抗赛 |        **国家一等奖**        |
|           2020全国大学生计算机设计大赛           |        **国家一等奖**        |
|    2019辽宁省普通高等学校本科大学生机器人竞赛    |         **省二等奖**         |

| 《**AML-VDIO**:Tightly-Coupled Visual-Depth-Inertial Odometry With Accuracy Multi-Modal Landmarks In Structural Environment》 |
| :----------------------------------------------------------- |
| **RA-L**一作在投，提出一个新颖的紧耦合视觉-深度-惯性里程计方法, 充分利用结构环境中精心筛选过的准确稳定的多模态路标来提高地面自主移动机器人在室内复杂结构场景下位姿估计的精度和鲁棒性，并显著降低后端BA耗时。 |

| 《Structural Lines aided Monocular VIWO with Online IMU-Wheel Extrinsic Optimization on Manifold S2 Manifold》 |
| ------------------------------------------------------------ |
| **TIV** **二作一审** **ABB**，针对复杂城市场景车辆位姿估计任务的鲁棒性问题，采用结构线辅助VIWO，并在S2流形上进行imu-wheel外参在线优化的方法，有效解决了城市场景地形变化和光照强度快速变化对VIWO造成的影响。 |

------

## **实习经历**

------

### **OPPO研究院光子Lab—定位算法实习生—室内结构场景视觉位姿估计** 

- 利用室内结构环境信息和消费级相机D435i实现基于结构点线的RGBD惯性里程计SPLVDIO，并通过对算法模块进行优化，使其能够以纯视觉里程计PLVDO部署在四足机器人载体的NX平台上实时运行（蓝色部分为去掉的模块）。
- 室内挑战性场景鲁棒性提高且 APE 定位误差减少 **40%**，相同约束下后端 BA 提速 **68%**。


![image](https://github.com/REAL-LXJ/REAL-LXJ/blob/main/picture/SPLVDIO系统框图.png)

![image](https://github.com/REAL-LXJ/REAL-LXJ/blob/main/picture/市场.gif)

------

### OPPO研究院光子Lab—IMU实时滤波

- 基于**iir**实现**IMU**实时滤波算法，能够过滤IMU原始数据特定频率的噪声。


![image](https://github.com/REAL-LXJ/REAL-LXJ/blob/main/picture/四足机器人imu分析.png)

![image](https://github.com/REAL-LXJ/REAL-LXJ/blob/main/picture/imu滤波.gif)

------

### 东软睿驰自动驾驶业务部—SLAM算法实习生—环视相机地面语义SLAM

- 利用汽车环视鱼眼相机IPM拼接图的语义分割结果，基于车道线、车位线、箭头等地面语义标识，在RTK和轮速计的辅助下，生成一个全局的视觉语义地图，并在泊车时用语义信息进一步完成车辆定位。
- 平均定位误差为 **6.23**cm。


![image](https://github.com/REAL-LXJ/REAL-LXJ/blob/main/picture/IPM_SLAM.png)

![image](https://github.com/REAL-LXJ/REAL-LXJ/blob/main/picture/东软IPM_SLAM.gif)

------

## **项目经历**

------

### 地库场景低漂移视觉惯性里程计

- 在gps拒止的地下停车场场景基于亚特兰大世界假设结合视觉、IMU 实现地库场景下低漂移的视觉惯性位姿估计。
- 100*100 平方米的地库场景，车辆运动轨迹 500m，始末端点累积漂移降低 **70%**。

![image](https://github.com/REAL-LXJ/REAL-LXJ/blob/main/picture/东软地下停车场.gif)

------

### 城市场景多传感器融合车辆位姿估计

- 融合视觉、IMU、轮速计和 GPS完成复杂城市场景下的车辆位姿估计任务，以解决地形变换和光照强度快速变化对VIWO 造成的影响。
- 在 KAIST Complex Urban Dataset 数据集表现出较好的鲁棒性和精度。
- ![image](https://github.com/REAL-LXJ/REAL-LXJ/blob/main/picture/VIWO.gif)

------

## **竞赛经历**

------

### 能量机关识别

![image](https://github.com/REAL-LXJ/REAL-LXJ/blob/main/picture/能量机关.png)

![image](https://github.com/REAL-LXJ/REAL-LXJ/blob/main/picture/能量机关识别1.gif)

------

### 能量机关实物制作

![image](https://github.com/REAL-LXJ/REAL-LXJ/blob/main/picture/能量机关.gif)

------

### 装甲板识别

![image](https://github.com/REAL-LXJ/REAL-LXJ/blob/main/picture/装甲板识别1.gif)

------

### 步兵机器人嵌入式控制

![image](https://github.com/REAL-LXJ/REAL-LXJ/blob/main/picture/机器人.gif)
