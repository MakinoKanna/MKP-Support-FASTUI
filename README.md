# MKP-Support-FastUI

A modern Web UI for [MKP Support](https://github.com/YZcat2023/MKPSupport), built with FastAPI and Vanilla JS.

## 声明与致敬 (Credits & Acknowledgement)

本项目是基于 [YZcat2023/MKPSupport](https://github.com/YZcat2023/MKPSupport) 开发的第三方可视化 Web 前端扩展版本。

原版 MKP Support 是一款优秀的 3D 打印辅助工具，其核心定位为：**"用于后处理 FDM 支撑结构，以提升打印质量并减少材料使用 (An application for post-processing FDM support structures to improve print quality and reduce material usage.)"**。

本项目的核心参数理念、数据结构与处理思路均完全源自原作者。本项目仅在前端表现层与后端服务层进行了重写，旨在利用现代 Web 技术为用户提供具有响应式布局和暗色模式的全新交互体验。感谢原作者为 3D 打印开源社区做出的杰出贡献。

## 项目特性 (Features)

* **现代化架构**: 采用 Python (FastAPI) 构建轻量级本地服务器，实现前后端分离与数据动态拉取。
* **响应式 UI**: 基于 Vanilla JavaScript 与 Tailwind CSS 构建的单页面应用 (SPA)，自适应不同尺寸的窗口显示。
* **视觉与交互**: 
  * 完整的暗色模式 (Dark Mode) 支持，支持跟随系统，并接入基于 View Transitions API 的原生平滑切换动画。
  * 优雅的折叠面板、分类导航与极简的视觉反馈。
* **配置解耦**: 抛弃硬编码，采用 JSON 格式统一管理机型库、品牌流及预设路径。

## 快速开始 (Quick Start)

### 1. 环境准备
确保您的计算机已安装 Python 3.8 或更高版本。

### 2. 克隆项目
```bash
git clone [https://github.com/你的用户名/MKP-Support-FASTUI.git](https://github.com/你的用户名/MKP-Support-FASTUI.git)
cd MKP-Support-FASTUI

```

### 3. 安装依赖

```bash
pip install fastapi uvicorn jinja2

```

### 4. 启动服务

```bash
python main.py

```

终端显示 `Application startup complete.` 后，在浏览器中访问 `http://127.0.0.1:8000` 即可进入界面。
