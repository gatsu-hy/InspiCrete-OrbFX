<div align="center">

# InspiCrete-OrbFX

**现代化跨品牌实时图形增强平台**

为游戏与桌面应用提供高性能、实时的图像增强体验。

[English](README.md) | [简体中文](README.zh-CN.md) | [日本語](README.jp.md)

![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)
![C++](https://img.shields.io/badge/C%2B%2B-20-00599C.svg?logo=cplusplus)
![Qt](https://img.shields.io/badge/Qt-6-41CD52.svg?logo=qt)
![Platform](https://img.shields.io/badge/Platform-Windows-0078D6.svg?logo=windows)
![Status](https://img.shields.io/badge/Status-开发中-orange)

</div>

---

## 📖 项目简介

InspiCrete-OrbFX 是一款基于 **C++20** 与 **Qt 6** 开发的现代化图形增强软件，旨在为游戏和桌面应用提供高性能、实时的图像处理与后期增强能力。

不同于依赖显卡厂商生态的软件，InspiCrete-OrbFX 致力于构建一个统一、开放、可扩展的图形增强平台，为 **NVIDIA、AMD、Intel** 等不同品牌显卡提供一致的使用体验。

我们的目标不仅仅是开发一款「显卡滤镜」，而是打造一个专业、现代且易于扩展的图形增强平台。

---

## ✨ 功能特性

### 已完成

- Modern Fluent UI 界面设计
- 基于 C++20 的原生架构
- Qt 6 用户界面
- 模块化项目结构

### 开发计划

- 🎨 实时图像滤镜
- 🎞 LUT（.cube）支持
- 🌈 Camera Raw 风格调色
- 💡 HDR 增强
- ✨ Bloom 泛光
- 🔍 图像锐化
- 🎭 自然饱和度（Vibrance）
- 🎮 游戏自动识别
- 💾 预设管理
- 🔌 插件系统
- 🌍 多语言支持
- 🌙 深色 / 浅色主题
- 🤖 AI 图像增强

---

## 🛠 技术栈

| 模块 | 技术 |
|------|------|
| 编程语言 | C++20 |
| UI 框架 | Qt 6 |
| 图形接口 | DirectX 11 / DirectX 12 |
| 着色器 | HLSL |
| 构建系统 | CMake |
| 开发环境 | Visual Studio 2022 |
| 开源协议 | Apache License 2.0 |

---

## 📂 项目结构

```text
OrbFX
│
├── .github/
│   ├── workflows/
│   ├── ISSUE_TEMPLATE/
│   └── PULL_REQUEST_TEMPLATE.md
│
├── docs/
├── src/
├── include/
├── ui/
├── shaders/
├── resources/
├── tests/
├── third_party/
│
├── README.md
├── README.zh-CN.md
├── LICENSE
├── NOTICE
├── CHANGELOG.md
├── CONTRIBUTING.md
├── CODE_OF_CONDUCT.md
├── SECURITY.md
├── CMakeLists.txt
└── .gitignore
```

---

## 🚀 开发路线图

### 第一阶段：基础架构

- [x] 创建项目仓库
- [ ] 搭建项目架构
- [ ] Modern Fluent UI
- [ ] 设置系统
- [ ] 预设管理

### 第二阶段：渲染引擎

- [ ] 桌面画面采集
- [ ] GPU 渲染
- [ ] Shader 管线
- [ ] DirectX 11 支持

### 第三阶段：图像增强

- [ ] HDR 增强
- [ ] LUT 支持
- [ ] Bloom 泛光
- [ ] 图像锐化
- [ ] 色彩校正
- [ ] Camera Raw 风格调节

### 第四阶段：生态建设

- [ ] 插件 SDK
- [ ] 社区预设
- [ ] AI 图像增强
- [ ] DirectX 12 优化

---

## 📷 软件截图

当前仍处于开发阶段。

首个公开预览版本发布后将在此展示软件截图。

---

## ⚡ 编译项目

### 环境要求

- Windows 11
- Visual Studio 2022
- Qt 6
- CMake
- Git

### 克隆仓库

```bash
git clone https://github.com/gatsu-hy/InspiCrete-OrbFX.git
```

### 编译

```bash
mkdir build
cd build

cmake ..

cmake --build . --config Release
```

---

## 📦 安装

请前往 **Releases** 页面下载最新版本。

解压后运行：

```text
OrbFX.exe
```

即可开始使用。

---

## 🤝 参与贡献

欢迎任何形式的贡献。

如果你希望参与 InspiCrete-OrbFX 的开发，请先阅读以下文档：

- CONTRIBUTING.md
- CODE_OF_CONDUCT.md

欢迎提交：

- Bug 报告
- 功能建议
- Pull Request
- 文档改进

---

## 📜 开源协议

本项目基于 **Apache License 2.0** 开源。

详细内容请参阅项目根目录中的 **LICENSE** 文件。

---

## 🎯 项目愿景

InspiCrete-OrbFX 希望成为一个现代化、专业化、开放且可扩展的图形增强平台。

我们的目标包括：

- 🚀 极致性能
- 🎨 现代 Fluent Design 界面
- 🔧 高度可扩展
- 🖥 跨品牌显卡兼容
- 🎞 专业级图像质量

InspiCrete-OrbFX 并非旨在取代各显卡厂商的软件，而是希望为不同品牌的 GPU 提供统一、稳定且一致的图形增强体验。

---

## ❤️ 致谢

感谢所有优秀的开源项目以及开发者社区。

特别感谢：

- Qt
- Microsoft
- CMake
- LLVM
- Dear ImGui
- 所有开源贡献者

---

<div align="center">

**Made with ❤️ by the InspiCrete Studio**

Copyright © 2026 InspiCrete Studio

Licensed under the Apache License 2.0.

</div>
