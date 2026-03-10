# CG-Lab

## 项目简介
本项目基于 Taichi 实现二维粒子引力模拟，通过并行计算模拟粒子之间的引力相互作用，并实时可视化显示粒子群运动效果。

## 项目结构
```text
CG-Lab
├─ README.md
├─ pyproject.toml
├─ .gitignore
├─ demo.gif
└─ src
   └─ Work0
      ├─ __init__.py
      ├─ config.py
      ├─ physics.py
      └─ main.py


## 运行方法

在项目目录运行：

```bash
py -3.11 -m src.Work0.main

## 运行效果演示

![Particle Simulation](demo.gif)
