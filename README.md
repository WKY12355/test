<!-- README.md -->
# Configuration Specifications

> Quick deployment and debugging guide for Agilex demoA, Agilex FF, and ARX demoB platforms.

---

## 📑 Table of Contents

- [1. Agilex demoA](#1-agilex-demoa)
- [2. Agilex FF](#2-agilex-ff)
- [3. ARX demoB](#3-arx-demob)
- [4. Inference Host Configuration](#4-inference-host-configuration)

---

## 1. Agilex demoA

### 1.1 Key Components

| Component | Specification |
|:----------|:--------------|
| Robotic Arm Model | Agilex Piper |
| Camera System | Intel RealSense D435 (Triple Camera Setup) |
| 3D Printed Components | Left Wrist Camera Mount, Right Wrist Camera Mount, Center Camera Mount, Center Camera Base |

### 1.2 Positioning Specifications

| Parameter | Value |
|:----------|:------|
| Center Camera Height (from ground) | 93 cm |
| Left Secondary Arm → Table Front Edge Distance | 27 cm |
| Right Secondary Arm → Table Front Edge Distance | 27 cm |
| Center Base → Left Secondary Arm Center Distance | 16 cm |
| Center Base → Right Secondary Arm Center Distance | 16 cm |
| Left Primary Arm → Table Front Edge Distance | 18 cm |
| Right Primary Arm → Table Front Edge Distance | 11 cm |
| Left-Right Primary Arm Center Distance | 40 cm |

---

## 2. Agilex FF

### 2.1 Key Components

| Component | Specification |
|:----------|:--------------|
| Robotic Arm Model | Agilex Piper |
| Camera System | Intel RealSense D435 (Triple Camera Setup) |
| 3D Printed Components | Left Wrist Camera Mount, Right Wrist Camera Mount, Center Camera Mount, Center Camera Base |

### 2.2 Positioning Specifications

| Parameter | Value |
|:----------|:------|
| Center Camera Height (from ground) | 76 cm |
| Left Secondary Arm → Table Front Edge Distance | 18 cm |
| Right Secondary Arm → Table Front Edge Distance | 18 cm |
| Center Base → Left Secondary Arm Center Distance | 34 cm |
| Center Base → Right Secondary Arm Center Distance | 34 cm |
| Left Primary Arm → Table Front Edge Distance | 18 cm |
| Right Primary Arm → Table Front Edge Distance | 12 cm |
| Left-Right Primary Arm Center Distance | 39 cm |

---

## 3. ARX demoB

### 3.1 Key Components

| Component | Specification |
|:----------|:--------------|
| Robotic Arm Model | ARX X5 |
| Camera System | Intel RealSense D435 (Triple Camera Setup) |
| 3D Printed Components | Left Secondary Arm Gripper, Right Secondary Arm Gripper, Left Wrist Camera Mount, Right Wrist Camera Mount, Center Camera Mount, Center Camera Base |

### 3.2 Positioning Specifications

| Parameter | Value |
|:----------|:------|
| Center Camera Height (from ground) | 93 cm |
| Left Secondary Arm Base → Table Front Edge Distance | 45 cm |
| Right Secondary Arm Base → Table Front Edge Distance | 87 cm |
| Center Base → Left Secondary Arm Center Distance | 22 cm |
| Center Base → Right Secondary Arm Center Distance | 22 cm |
| Left Primary Arm → Table Front Edge Distance | 18 cm |
| Right Primary Arm → Table Front Edge Distance | 11 cm |
| Left-Right Primary Arm Center Distance | 53 cm |

---

## 4. Inference Host Configuration

| Component | Requirement |
|:----------|:------------|
| GPU | NVIDIA RTX 4090 (≥48 GB VRAM) |

---

---

# 配置清单

> 适用于松灵 demoA / 松灵 FF / 方舟 demoB 三套平台的快速部署与调试。

---

## 📑 目录

- [1. 松灵 demoA](#1-松灵-demoa)
- [2. 松灵 FF](#2-松灵-ff)
- [3. 方舟 demoB](#3-方舟-demob)
- [4. 推理主机配置](#4-推理主机配置)

---

## 1. 松灵 demoA

### 1.1 关键组件

| 关键组件 | 参数 |
|:--------|:-----|
| 机械臂型号 | Agilex Piper |
| 三路相机型号 | Intel RealSense D435 |
| 需打印结构件 | 左腕部相机支架、右腕部相机支架、中间相机支架、中间相机基座 |

### 1.2 摆放位置

| 项目 | 数值 |
|:-----|:-----|
| 中间相机离地高度 | 93 cm |
| 左从臂→桌子前沿距离 | 27 cm |
| 右从臂→桌子前沿距离 | 27 cm |
| 中间基座→左从臂中心距 | 16 cm |
| 中间基座→右从臂中心距 | 16 cm |
| 左主臂→桌子前沿距离 | 18 cm |
| 右主臂→桌子前沿距离 | 11 cm |
| 左右主臂中心距 | 40 cm |

---

## 2. 松灵 FF

### 2.1 关键组件

| 关键组件 | 参数 |
|:--------|:-----|
| 机械臂型号 | Agilex Piper |
| 三路相机型号 | Intel RealSense D435 |
| 需打印结构件 | 左腕部相机支架、右腕部相机支架、中间相机支架、中间相机基座 |

### 2.2 摆放位置

| 项目 | 数值 |
|:-----|:-----|
| 中间相机离地高度 | 76 cm |
| 左从臂→桌子前沿距离 | 18 cm |
| 右从臂→桌子前沿距离 | 18 cm |
| 中间基座→左从臂中心距 | 34 cm |
| 中间基座→右从臂中心距 | 34 cm |
| 左主臂→桌子前沿距离 | 18 cm |
| 右主臂→桌子前沿距离 | 12 cm |
| 左右主臂中心距 | 39 cm |

---

## 3. 方舟 demoB

### 3.1 关键组件

| 关键组件 | 参数 |
|:--------|:-----|
| 机械臂型号 | ARX X5 |
| 三路相机型号 | Intel RealSense D435 |
| 需打印结构件 | 左从臂夹爪、右从臂夹爪、左腕部相机支架、右腕部相机支架、中间相机支架、中间相机基座 |

### 3.2 摆放位置

| 项目 | 数值 |
|:-----|:-----|
| 中间相机离地高度 | 93 cm |
| 左从臂基座→桌子前沿距离 | 45 cm |
| 右从臂基座→桌子前沿距离 | 87 cm |
| 中间基座→左从臂中心距 | 22 cm |
| 中间基座→右从臂中心距 | 22 cm |
| 左主臂→桌子前沿距离 | 18 cm |
| 右主臂→桌子前沿距离 | 11 cm |
| 左右主臂中心距 | 53 cm |

---

## 4. 推理主机配置

| 组件 | 要求 |
|:-----|:-----|
| GPU | NVIDIA RTX 4090（≥48 GB VRAM） |

---
