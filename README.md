# Research on Autonomous Driving Technology
基于设施园艺场景开发自动驾驶技术的研究探讨

## 入门
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
   
### 3. solidworks to urdf/xacro 模型
   #### 2.1 导出urdf文件
   #### 2.2 修正urdf文件误差（对称、惯性）
   #### 2.1 了解urdf结构（link、joint）
   1.了解Inertial
   2.了解collsion
   3.掌握xacro函数
### 5. 4ws_control(four wheel steering)
   4.1 Parameters 了解必要参数
     wheel_base（前后轮距离）
     wheel_seperation（左右轮距离）
     wheel_radius（车轮半径）
     wheel_steering_offset_y（转向轴和车轮中心的偏差）
   4.2 Three mode 三种模式
     In-phase（前后轮同相）
     Opposite phase（前后轮反向）
     Rviot turn （绕四轮中心圆周运动）
   4.3 ros2_control 控制器
### 7. 

## 仿真环境

## 自动驾驶开源数据集
1. nuscenes
2. kitti
3. 

## 鸟瞰图

## 雷达

## 端到端的自动驾驶算法
