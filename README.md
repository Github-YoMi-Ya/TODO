# rm_verison TODO

## auto_aim

### minpc电源
> - [  &#x2716;  ] 降压模块24-19 6.32A，20 6A 
> - [  &#x2716;  ] nuc电源诱骗线              
> - [  &#x2714;  ] nuc显示器欺骗器，无线/远程调车 get             

### 工业相机标定
> - [工业相机标定参考教程](https://zhuanlan.zhihu.com/p/488925991?utm_id=0)
> - [  &#x2714;  ] 工业相机标定

### 自瞄调参
> - [  &#x2716;  ] (得装甲板搞完后才能调)

### ch34x补丁
> - [  &#x2714;  ] 每次开机得手动make load加载一下，有解决方案 &#x2714; 


### Boradc_serrial
> - [  &#x2716;  ] 学习验证C板串口上下机位通型

### 哨兵导航
> - [  &#x2716;  ] 导航nv2框架融合

### 目前建图方案:

#### 1.深度相机加工业相机(目前有设备)
融合D345i深度相机点云建图
工业相机自瞄
> - ubuntu20.04 LTS + Real-Time Kernel ROS2 Galactic
> -  [沈阳航空航天大学TUP战队2023年哨兵导航模块](https://github.com/tup-robomaster/TUP2023-Sentry-Nav/tree/02b77a72ef0a05879c58c0b785b2c7aabacc46c1)
> - [沈阳航空航天大学TUP战队2023年哨兵框架](https://github.com/tup-robomaster/TUP2023-Sentry-Framework/tree/main#rx)

#### 2.3D雷达+工业相机
> - 适配君瞄
> - [中南大学FYT机器人战队哨兵机器人上位机算法（定位与导航部分）](https://github.com/baiyeweiguang/CSU-RM-Sentry)

#### 3.2D+工业相机
> -Ubuntu20.04 + ros Noetic
> - [rm2023_auto_sentry_ws](https://github.com/SCAU-RM-NAV/rm2023_auto_sentry_ws)

### 哨兵仿真搭建
> - Ubuntu22.04 + ros2 Humble
> - [深圳北理莫斯科大学 北极熊战队 哨兵导航仿真包](https://github.com/LihanChen2004/PB_RMSimulation)

