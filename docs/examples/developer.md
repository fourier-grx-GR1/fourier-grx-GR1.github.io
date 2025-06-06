---
layout: default
title: Developer 接口
nav_order: 2.2
parent: 示例代码
toc: true          # 启用目录
toc_min_header: 2  # 最小显示标题层级（如 H2）
toc_max_header: 3  # 最大显示标题层级（如 H3）
---

# 示例代码 Developer 接口

Developer 接口目前提供的开发示例有：

- `demo_print_state`: 打印机器人状态信息。
- `demo_servo_on`: 机器人全关节上电使能。
- `demo_servo_off`: 机器人全关节下电失能。
- `demo_set_home`: 设置机器人全关节零位位置为当前位置，用于标定机器人关节零位。
- `demo_set_pid`: 设置机器人关节 PID 参数。
- `demo_ready_state`: 机器人运行到 **准备状态**，为微曲膝关节的站立姿态。
- `demo_walk`: 机器人运动到 **行走状态**，可以用手柄控制机器人行走。

## demo_walk

该代码展示如何通过调用 policy.pt 文件来完成机器人的行走运动控制。

关于 policy.pt 文件的生成和使用，请参考 [模型训练](/docs/training) 的相关内容。

> ℹ **注意**：
> 
> 内容准备中。。。

