# 🕶️ HideRootBox - Android Root检测隐藏解决方案

   [![GitHub release](https://img.shields.io/github/v/release/huanmore/HideRootBox)](https://github.com/huanmore/HideRootBox/releases)
   [![License](https://img.shields.io/badge/license-GPLv3-blue)](https://github.com/huanmore/HideRootBox/blob/main/LICENSE)
   [![Android](https://img.shields.io/badge/Android-5.0%2B-brightgreen)](https://www.android.com/)
   [![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/huanmore/HideRootBox/graphs/commit-activity)

   > 多功能Root隐藏脚本，专为绕过各种Root检测设计

   ![HideRootBox 演示](docs/screenshots/demo.gif)

   ## 🌟 核心功能

   - **多模式切换**：shamiko黑白名单切换
   - **全检测覆盖**：
     - Native Test/Momo检测绕过
     - SafetyNet/Play Integrity API绕过
     - 调整SELinux状态
   - **模块化集成**：
     - TrickyStore v1.3.0
     - Zygisk-Next v1.2.9
   - **一键配置**：
     - 下载有效keybox.xml
     - 隐藏应用列表配置
     - 伪装加密状态

   ## 🚀 快速开始

   ### 前提条件
   - Rooted Android设备 (Magisk/KernelSU)
   - 终端应用 (Termux/ADB)

   ### 安装使用
   ```bash
   # 下载脚本
   curl -LO https://github.com/huanmore/HideRootBox/releases/download/v3.0.0/HideRootBox3.0.0.sh
