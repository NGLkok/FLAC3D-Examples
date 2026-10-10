# FLAC3D-Examples

[English](README.md) | **简体中文**

**面向采矿工程的可复现数值模拟案例库**

本项目用于整理采矿工程中的 FLAC3D 与 FISH 数值模拟案例，逐步建立一个可复现、可扩展的工程计算案例库。

项目主要关注巷道开挖、岩石力学、围岩支护、应力分析以及采动变形等问题。

## 项目目标

- 建立可重复使用的 FLAC3D 数值模拟案例。
- 记录模型几何、材料参数、边界条件及求解过程。
- 探索巷道开挖与围岩支护数值模拟。
- 使用 FISH 脚本实现模型自动化与结果处理。
- 为工程研究和学习提供可复现案例。

## 主要内容

| 模块 | 说明 |
|---|---|
| 基础模型 | 模型几何、网格划分及边界条件 |
| 巷道开挖 | 巷道几何建模及分步开挖 |
| 岩石力学 | 本构模型及岩体力学参数 |
| 围岩支护 | 锚杆、锚索及支护系统 |
| 应力分析 | 应力重分布及位移分析 |
| 采矿模拟 | 采动变形及围岩响应 |
| FISH 脚本 | 模型自动化及自定义计算 |

## 仓库结构

```text
FLAC3D-Examples/
├── README.md
├── README.zh-CN.md
├── LICENSE
├── .gitignore
├── 01-basic-model/
├── 02-roadway-excavation/
├── 03-rock-mechanics/
├── 04-ground-support/
├── 05-stress-analysis/
├── 06-mining-simulation/
├── 07-fish-scripting/
└── docs/
