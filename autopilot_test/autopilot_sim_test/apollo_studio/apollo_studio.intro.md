# 1. Apollo Studio简介

Apollo开放平台为开发者提供开放、完整、安全的自动驾驶平台。其中`仿真平台`：拥有大量场景数据，基于大规模云端计算，形成迭代闭环。

# 1.1 Apollo Studio作用

- 体验 Apollo 仿真调试功能
- 自由创建适合调试算法的个人测试场景
- 将云端场景、数据、动力学模型同步至本地进行调试
- 可以将设备接入管理，并查看对应的使用指南

# 2. Apollo Studio仿真平台介绍

## 2.1 仿真场景

Apollo Studio仿真场景由`Worldsim`和`Logsim`构成。

![Apollo Studio仿真平台](image/sys_scene.png)

![](image/Apollo%20Studio%20%E4%BB%BF%E7%9C%9F%E5%B9%B3%E5%8F%B0.png)

## 2.2 任务评测

![任务评测](image/task_evalu.png)

点击`详情`，可看到：

![](image/worldsim_1.png)

点击运行结果栏所在列：`通过`

![](image/evalu_content.png)

操作中的`回放，Log, Bag`：回放可以查看视频效果，Log-日志，Bag，通过这三者可以对失败的测试进行问题分析以及对测试结果优化等。

```
举例：人行道刹车避让
```
<iframe height=498, width=510 src="video/1.mp4">

# 参考

[Apollo Studio使用文档](https://apollo.baidu.com/Apollo-Homepage-Document/Apollo_Studio/)