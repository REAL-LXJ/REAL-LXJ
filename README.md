#### **我的项目**

------

#### **SPLVDIO**

利用室内结构场景下的**点**、**线**、**消失点**几何特征和**RGBD**、**IMU**传感器实现的基于结构点线的RGBD视觉惯性里程计**SPLVDIO**，能够在室内长走廊、白墙等弱纹理和动态干扰等挑战性场景下保持系统鲁棒性的同时提高位姿估计的精度。同时通过对算法模块的优化，使其能够以**PLVDO**部署在**NX**平台上并实时运行。

![image0](https://github.com/REAL-LXJ/REAL-LXJ/blob/main/picture/系统框架.png)

- **基于IIR的IMU实时滤波模块**
- **基于点线特征的轻量级前端**
- **路标的分类及固定**

------

#### IIR_IMU_Filter

![image1](https://github.com/REAL-LXJ/REAL-LXJ/blob/main/picture/四足机器人imu分析.png)



