# Python 项目加密部署及License生成和验证

---

#### 概要

旨在为基于python开发的各类工具、服务端的简单部署提供解决方案

**注：** 不适用于大型项目、商用部署

适用于各种操作系统以及基于docker的部署环境

具有保护源码、防止复制、时间控制等功能

实现的具体思路包括：
- **保护代码：** 通过Cython编译为pyd或so文件
- **防止复制：** 获取和验证部署机器的唯一标识
- **时间控制：** 在License中加入失效时间，并在验证时同当前时间对比

---
#### 具体实现
![Alt](https://github.com/sunchang272/python-license/blob/main/images/frame.png?raw=true)