# ROS 2 Learning Archive (ROS 2 学习与实践归档)

## 📖 项目简介

这是一个面向**具身智能仿真工程师**方向的 ROS 2 学习代码库。
记录了从零开始学习 ROS 2 (Humble) 的基础历程，涵盖了节点、话题、服务、参数、TF2、URDF/Xacro 机器人建模等核心模块。

代码基于 Ubuntu 22.04 + Python 3.10 + ROS 2 Humble 环境开发，目前已完成基础通信和建模阶段的全部实战。

## 🛠️ 技术栈
*   **OS**: Ubuntu 22.04 LTS (虚拟机环境)
*   **Middleware**: ROS 2 Humble
*   **Language**: Python 3.10
*   **Tools**: RViz2, Gazebo (基础了解), colcon, xacro, Git

## 📂 目录结构

```text
ROS2_backup/
├── chapt1_src/          # 环境配置与基础工具
├── chapt2_src/          # 节点编写与面向对象
├── chapt3_src/          # 话题通信、自定义消息、闭环控制
├── chapt4_src/          # 服务通信、自定义服务、参数、Launch
├── chapt5_src/          # TF2 坐标变换 (静态/动态广播)
├── chapt6_src/          # URDF/Xacro 机器人建模与物理属性配置
├── learn_git/           # Git 版本控制学习资料
├── motive_src/          # 运动学相关练习
└── 学习细碎点/           # 踩坑记录与心得笔记
