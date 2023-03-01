#### 自我介绍

------

我是罗行健，东北大学机器人科学与工程学院**环境感知与自主导航实验室**硕士二年级，研究方向为**视觉SLAM**、**VIO**、**多传感器融合**。

本科就读于大连交通大学机械工程学院机械工程+软件工程专业，**TOE创新实验室成员**，负责步兵机器人的电控、视觉，能量机关的制作。

|                     竞赛名称                     |             荣誉             |
| :----------------------------------------------: | :--------------------------: |
| 2021全国大学生机器人大赛ROBOMASTER机甲大师对抗赛 | **北部赛区冠军，国家一等奖** |
| 2020全国大学生机器人大赛ROBOMASTER机甲大师对抗赛 |        **国家一等奖**        |
|           2020全国大学生计算机设计大赛           |        **国家一等奖**        |
|    2019辽宁省普通高等学校本科大学生机器人竞赛    |         **省二等奖**         |

#### **我的项目**

------

#### **SPLVDIO**

利用室内结构场景下的**点**、**线**、**消失点**几何特征和**RGBD**、**IMU**传感器实现的基于结构点线的RGBD视觉惯性里程计**SPLVDIO**，能够在室内长走廊、白墙等弱纹理和动态干扰等挑战性场景下保持系统鲁棒性并提高位姿估计的精度。同时通过对算法模块的优化，使其能够以**PLVDO**部署在**NX**平台上并实时运行（蓝色部分为去掉的模块）。

[SPLVDO_室内办公室场景3circle实验_哔哩哔哩_bilibili](https://www.bilibili.com/video/BV1S3411S7j3/?spm_id_from=333.999.0.0&vd_source=234694b5b771ca97335316572a2146ee)

[PVDO-PLVDO-SPLVDO_室内办公室场景3circle实验_哔哩哔哩_bilibili](https://www.bilibili.com/video/BV1N34119752/?spm_id_from=333.999.0.0&vd_source=234694b5b771ca97335316572a2146ee)

[PLVDO_动态场景实验2_哔哩哔哩_bilibili](https://www.bilibili.com/video/BV1yA41167u3/?spm_id_from=333.999.0.0&vd_source=234694b5b771ca97335316572a2146ee)

![image0](https://github.com/REAL-LXJ/REAL-LXJ/blob/main/picture/系统框架.png)

- **基于IIR的IMU实时滤波模块**
- **基于点线特征的轻量级前端**
- **路标的分类及固定**

------

#### IIR_IMU_Filter

基于**iir**实现的**IMU**实时滤波算法，能够过滤IMU原始数据特定频率的噪声。

[imu原始数据实时滤波_哔哩哔哩_bilibili](https://www.bilibili.com/video/BV1k84y1C7Ts/?spm_id_from=333.999.0.0&vd_source=234694b5b771ca97335316572a2146ee)

![image1](https://github.com/REAL-LXJ/REAL-LXJ/blob/main/picture/四足机器人imu分析.png)

------

#### IPM_SLAM

------



