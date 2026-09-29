<div align="center">
  <img src="https://raw.githubusercontent.com/simpleapples/InkControl/refs/heads/main/resource/app_icon.png" width="256" height="256" alt="InkControl Logo" />
  <h1>InkControl - 墨控</h1>
  <p><strong>适用于 macOS 的 大上墨水屏控制中心</strong></p>

  <a href="https://github.com/simpleapples/InkControl/releases/latest"><img src="https://user-images.githubusercontent.com/37590873/219133640-8b7a0179-20a7-4e02-8887-fbbd2eaad64b.png" width="180" alt="Download for macOS"/></a>
  &nbsp;&nbsp;

  <a href="https://buy.stripe.com/4gMaEXcWX3oe4Du62063K00"><img src="https://img.shields.io/badge/购买正版授权-¥18.99-success?style=for-the-badge&logo=stripe" height="40" alt="购买授权" /></a><br/>
  
  [![macOS](https://img.shields.io/badge/macOS-15.0%2B-black?style=flat-square&logo=apple)](https://www.apple.com/macos/)
  [![Release](https://img.shields.io/github/v/release/simpleapples/InkControl?style=flat-square&color=blue)](https://github.com/simpleapples/InkControl/releases/latest)
  [![License](https://img.shields.io/badge/License-Proprietary-red?style=flat-square)](#)
</div>

<p align="center">
  <strong>简体中文</strong> | <a href="README.md">English</a>
</p>

---

## 关于 InkControl - 墨控

**InkControl - 墨控** 是一款 macOS 原生应用，用于控制 **大上 (Dasung)** 电子墨水显示器。它是一个常驻菜单栏的小工具，可以替代显示器上的实体按键，直接在系统界面中调整屏幕参数。

<img src="https://raw.githubusercontent.com/simpleapples/InkControl/refs/heads/main/resource/app_screenshot_cn.png" width="931" height="565" alt="InkControl Screenshot" />

## 核心功能

### 🎛 硬件调整
直接通过软件调整显示器参数，无需点击实体按键：
- **显示模式**: 切换自动、文本、图像、活跃等模式。InkControl 会识别显示器型号，只显示该型号支持的模式。
- **刷新速度**: 在 1 到 5 档之间调整刷新速度。
- **文字增强**: 在支持的型号上让文字更清晰。
- **前光调节**: 在带前光的型号上调整冷暖光强度。
- **防止抖动**: 关闭 macOS 对显示器的抖动处理，文本显示更稳定。

|启用时序抖动|禁用时序抖动|
|---|---|
|<img src="https://raw.githubusercontent.com/simpleapples/InkControl/refs/heads/main/resource/enable_dithering.gif" width="360" height="480" alt="启用时序抖动" />|<img src="https://raw.githubusercontent.com/simpleapples/InkControl/refs/heads/main/resource/disable_dithering.gif" width="360" height="480" alt="禁用时序抖动" />|

- **自动清屏**: 设置时间间隔自动刷新屏幕，减少残影。

- **一键清屏**: 随时手动清除残影，支持自定义全局快捷键。
    <div align="center">
        <img src="https://raw.githubusercontent.com/simpleapples/InkControl/refs/heads/main/resource/one_click_refresh_demo.gif" width="400" height="845" alt="One Key Cleaning Demo" />
    </div>

### 🎨 原生设计
完全遵循 macOS 设计规范，如同系统自带应用一般自然：
- **菜单栏应用**: 常驻顶栏，随时待命，绝不打扰。
- **液态玻璃**: 在 macOS 26 上使用系统的液态玻璃效果，macOS 15 上使用半透明材质。

## 下载与使用

应用提供 **7天全功能试用**，无功能限制，无需绑定信用卡。

### 📥 [下载最新版本](https://github.com/simpleapples/InkControl/releases/latest)

如果您觉得好用，可以购买永久授权支持开发：

<div align="center">
  <a href="https://buy.stripe.com/4gMaEXcWX3oe4Du62063K00">
    <img src="https://img.shields.io/badge/购买正版授权-¥18.99-success?style=for-the-badge&logo=stripe" height="80" alt="Buy Now" />
  </a>
  <br>
  <em>一次付费，终身使用。</em>
</div>

### 激活步骤
1. 点击上方链接购买。
2. 激活码将发送至您的邮箱 (格式: `INK-XXXX-XXXX...`)。
3. 打开 InkControl，在 **设置** > **许可证** 中输入激活码。

## 设备支持

我们针对 Dasung Paperlike 系列显示器开发。

### ✅ 已实机测试
- **Dasung Paperlike HD**

### 🧪 可识别，尚未实机测试
InkControl 能识别以下型号，模式设置与大上官方客户端一致，但我们还没有在实机上测试过：
- **Dasung Paperlike 253**（彩色 / 黑白）
- **Dasung Paperlike 13.3K**（彩色 / 黑白）
- **Dasung Paperlike 103**

其他使用相同协议的 Paperlike 显示器也能连接和清屏，但在确认模式设置之前，模式切换会保持禁用。如果您有这些设备，欢迎[提交 Issue](https://github.com/simpleapples/InkControl/issues) 帮我们完善支持。

### 系统要求
- **macOS**: macOS 15 (Sequoia) 或更高版本。
- **处理器**: 完美支持 **Apple Silicon (M1/M2/M3/M4/M5)**

## 多语言

InkControl 目前完美支持以下语言，并将自动跟随系统语言设置：
- 🇨🇳 **简体中文**
- 🇬🇧 **英文**

---

## 💬 反馈

如有任何问题或建议，欢迎联系我们：

- **邮件**: [inkcontrol@simpleapples.com](mailto:inkcontrol@simpleapples.com)
- **Issues**: [Github Issues](https://github.com/simpleapples/InkControl/issues)

<p align="center">
  <small>© 2026 simpleapples. All rights reserved.<br>InkControl is not affiliated with Dasung Tech.</small>
</p>
