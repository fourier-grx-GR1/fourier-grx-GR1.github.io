---
layout: default
title: User 接口
nav_order: 2.1
parent: 示例代码
toc: true          # 启用目录
toc_min_header: 2  # 最小显示标题层级（如 H2）
toc_max_header: 3  # 最大显示标题层级（如 H3）
---

# 示例代码 User 接口

User 接口提供的开发示例有：

- `demo_servo_on`: 机器人全关节上电使能。
- `demo_servo_off`: 机器人全关节下电失能。
- `demo_clear_fault`: 清除机器人全关节报警。当机器人出现报警时，可以通过此接口清除报警。
- `demo_set_home`: 设置机器人全关节零位位置为当前位置，用于标定机器人关节零位。
- `demo_test_joint`: 机器人关节运动功能测试，用于检测机器人关节是否能够正常运动。
- `demo_ready_state`: 机器人运行到 **准备状态**，为微曲膝关节的站立姿态。
- `demo_walk`: 机器人运动到 **行走状态**，可以用手柄控制机器人行走。

## demo_walk

该示例代码展示如何通过调用 fourier-grx 内部 RL 行走算法完成机器人运动控制任务。

> ℹ **注意**：
>
> 内容准备中。。。

