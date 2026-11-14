<div align="center">

# Project 4 · micro:bit 机器人小车

**Tinybit · MicroPython · 运动控制与巡线**

使用 BBC micro:bit 和 Tinybit 小车完成的课程演示，涵盖基础运动、速度档位、红外巡线，以及对预设路标标签的动作响应。

[English](./README.md) · **简体中文**

</div>

[小车程序](./Project%20Semester%204/ProjectRobot1_2026/main.py) · [硬件与操作](#setup) · [详细说明](./Project%20Semester%204/ProjectRobot1_2026/README.md)

## 目录导览

| 入口 | 内容 |
| --- | --- |
| [整合脚本](./Project%20Semester%204/ProjectRobot1_2026/main.py) | 运动控制、速度限制、红外输入、路标命令和板载演示。 |
| [方向](./direction%20control.py)、[速度](./speed%20control.py)和[路径控制](./Pathcontrol.py) | 各任务的独立练习。 |
| [项目计划](./Project%20Semester%204/plot_burndown.py) | 课程项目的燃尽图脚本。 |

<a id="setup"></a>
## 硬件与操作

1. 准备 BBC micro:bit、Tinybit 底盘、USB 线、电池组，以及套件对应的 `tinybit` MicroPython 库。
2. 用 Mu 的 micro:bit 模式或同类编辑器刷入[整合脚本](./Project%20Semester%204/ProjectRobot1_2026/main.py)。尝试巡线前，先核对套件的红外传感器接口。
3. 按 **A** 运行演示。主循环读取到 **B** 时会停车。第一次测试时，先让车轮悬空。

路标演示向控制程序传入预先设定的标签。接口和刷写步骤见[硬件说明](./Project%20Semester%204/ProjectRobot1_2026/README.md)。
