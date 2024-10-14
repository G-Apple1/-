# Research on Autonomous Driving Technology
基于设施园艺场景开发自动驾驶技术的研究探讨

## 入门
推荐三个视频合集：  
[ROS2从初级到高级（LEVEL2）：使用 URDF 设计自定义机器人，在 Gazebo 中模拟机器人](https://www.bilibili.com/video/BV1my411e7sZ/?p=1&vd_source=27e70aced8c91cb9b37dc404a74db2fc)   
[古月居 古月·ROS2入门21讲 | 带你认识一个全新的机器人操作系统](https://www.bilibili.com/video/BV16B4y1Q7jQ/?spm_id_from=333.337.search-card.all.click&vd_source=27e70aced8c91cb9b37dc404a74db2fc)   
[鱼香ROS 动手学ROS2|ROS2基础入门到实践教程|小鱼带你手把手学习ROS2](https://www.bilibili.com/video/BV1gr4y1Q7j5/?spm_id_from=333.337.search-card.all.click&vd_source=27e70aced8c91cb9b37dc404a74db2fc)
### 1. ros2 学习
   #### 1.1 了解workspace
      (build install log) src
   #### 1.2 colcon build
     1.加上 --symlink-install 可以实时编译
     2.指定package编译 --select-package
   #### 1.3 rviz 可视化软件
     1.如果通过终端（代码）启动
     2.熟悉.rviz文件
     3.Global option 选项
     4.Dispaly 选项
     5.如何添加传感器（camera相机、lidar雷达）
   #### 1.4 gazebo 仿真软件
     1.如果通过终端（代码）启动
     2.查看contact接触点
     3.设置颜色
     4.控制静止（摩擦力、阻尼）
     5.绘制和保存地图（.world文件）
   #### 1.5 rqt_graph
   #### 1.6 
   
### 2. solidworks to urdf/xacro 模型
   #### 2.1 导出urdf文件
   #### 2.2 修正urdf文件误差（对称、惯性）
   #### 2.3 了解urdf结构（link、joint）
      1.了解Inertial
      2.了解collsion
      3.掌握xacro函数
### 3. 4ws_control(four wheel steering)  
推荐配套代码和视频学习：  
[代码：ThisUserTaken/ros2_code](https://github.com/ThisUserTaken/ros2_code/tree/master/humble/four_ws_ros2/src)    
[视频：【搬】使用 ROS2 控制和 Gazebo 模拟4舵轮小车](https://www.bilibili.com/video/BV1fY411y7xm/?spm_id_from=333.337.search-card.all.click&vd_source=27e70aced8c91cb9b37dc404a74db2fc)  
[C级车身A级操控，四轮转向来了【纸上谈车46】](https://www.bilibili.com/video/BV1yT4y1R7Vx/?spm_id_from=333.337.search-card.all.click&vd_source=27e70aced8c91cb9b37dc404a74db2fc)
   #### 3.1 Parameters 了解必要参数
     wheel_base（前后轮距离）
     wheel_seperation（左右轮距离）
     wheel_radius（车轮半径）
     wheel_steering_offset_y（转向轴和车轮中心的偏差）
   #### 3.2 Three mode 三种模式
     In-phase（前后轮同相）
     Opposite phase（前后轮反向）
     Rviot turn （绕四轮中心圆周运动）
   #### 3.3 ros2_control 控制器
      1.forward_velocity_pulisher/command
      2.forward_position_publisher/command
### 4. navigation2
推荐视频学习：
[机器人工匠阿杰](https://space.bilibili.com/411541289)
[ROS2 Nav2 - Navigation Stack in 1 Hour [Crash Course]](https://www.youtube.com/watch?v=idQb2pB-h2Q&t=1090s)

### 5. 雷达建图
#### Cartographer
文档学习：
[Cartographer纯雷达定位建图](https://bluesnie.github.io/Learning-notes/ROS2/Nav2%E5%AF%BC%E8%88%AA%E7%AF%87/%E7%AC%AC10%E7%AB%A0-SLAM%E5%BB%BA%E5%9B%BE/%E8%BF%9B%E9%98%B6/002-%E4%BD%BF%E7%94%A8%E7%BA%AF%E9%9B%B7%E8%BE%BE%E5%AE%9A%E4%BD%8D%E5%BB%BA%E5%9B%BE.html) 
 
[ROS2+cartorgrapher+激光雷达建图并保存](https://blog.csdn.net/scarecrow_sun/article/details/127978254)
#### scan-tools

## 仿真环境

## 自动驾驶开源数据集
1. nuscenes
2. kitti
3. 

## 鸟瞰图

## 雷达

## 端到端的自动驾驶算法
