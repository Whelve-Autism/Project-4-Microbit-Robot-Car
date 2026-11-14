<div align="center">

# Project 4 · micro:bit Robot Car

**Tinybit · MicroPython · Motion and line following**

A coursework demonstration for a BBC micro:bit and Tinybit robot car, covering basic movement, speed levels, infrared line following, and predefined responses to sign labels.

**English** · [简体中文](./README.zh-CN.md)

</div>

[Robot program](./Project%20Semester%204/ProjectRobot1_2026/main.py) · [Setup](#setup) · [Detailed guide](./Project%20Semester%204/ProjectRobot1_2026/README.md)

## Repository layout

| Entry | Description |
| --- | --- |
| [Integrated script](./Project%20Semester%204/ProjectRobot1_2026/main.py) | Movement, speed limits, infrared input, sign commands, and the on-board demo. |
| [Direction](./direction%20control.py), [speed](./speed%20control.py), and [path control](./Pathcontrol.py) | Separate exercises for the individual tasks. |
| [Project planning](./Project%20Semester%204/plot_burndown.py) | Coursework burndown-chart script. |

<a id="setup"></a>
## Hardware and controls

1. Prepare a BBC micro:bit, the Tinybit chassis, USB cable, a battery pack, and the `tinybit` MicroPython library for the kit.
2. Flash the [integrated script](./Project%20Semester%204/ProjectRobot1_2026/main.py) in micro:bit mode using Mu or an equivalent editor. Check the kit's infrared API before trying line-following mode.
3. Press **A** to start the scripted demo. **B** stops the car when the main loop can poll the button. Test first with the wheels clear of the surface.

The sign demo passes predefined labels to the robot control code. For API and flashing details, see the [hardware guide](./Project%20Semester%204/ProjectRobot1_2026/README.md).
