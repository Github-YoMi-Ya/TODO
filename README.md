# rm_verison TODO

## auto_aim

### 工业相机标定
> - [工业相机标定参考](https://zhuanlan.zhihu.com/p/488925991?utm_id=0)

### 自瞄调参
> - (得装甲板搞完后才能调)

### ch34x补丁
> - 目前打了一半，每次开机得手动make load加载一下

### 哨兵导航
> 导航nv2框架融合

### 目前建图方案:

#### 1.深度相机加工业相机(目前有设备)
融合D345i深度相机点云建图
工业相机自瞄
> - ubuntu20.04 LTS + Real-Time Kernel ROS2 Galactic[TUP2023-Sentry-Framework](https://github.com/tup-robomaster/TUP2023-Sentry-Framework/tree/main#rx)

#### 2.3D雷达+工业相机
> - 适配君瞄[中南大学FYT机器人战队哨兵机器人上位机算法（定位与导航部分）](https://github.com/baiyeweiguang/CSU-RM-Sentry)

#### 3.2D+工业相机
> -Ubuntu20.04 + ros Noetic
> [rm2023_auto_sentry_ws](https://github.com/SCAU-RM-NAV/rm2023_auto_sentry_ws)

### 哨兵仿真搭建
> - Ubuntu22.04 + ros2 Humble
> - [深圳北理莫斯科大学 北极熊战队 哨兵导航仿真包](https://github.com/LihanChen2004/PB_RMSimulation)

