# Sayit

![Sayit hero](./assets/sayit-hero.png)

Push-to-talk voice dictation for macOS.

> 如果你只是想下载安装，直接点下面这个按钮。

<p>
  <a href="https://github.com/harperrrdesign/Sayit/releases/latest">
    <img alt="Download Latest" src="https://img.shields.io/badge/Download-Latest%20macOS%20build-black?style=for-the-badge">
  </a>
</p>

**支持系统：Apple Silicon + macOS 14+**

## 快速开始

1. 点击上面的下载按钮。
2. 下载最新 zip。
3. 解压后把 `Sayit.app` 拖到 `Applications`。
4. 从 `Applications` 打开 `Sayit.app`。

如果 macOS 拦截：

1. 打开 `系统设置 -> 隐私与安全性`
2. 在页面底部找到和 `Sayit` 相关的提示
3. 点击 `仍要打开`

## 这是什么

Sayit 是一个 macOS 菜单栏语音输入工具。

你按一次 `Fn` 开始录音，再按一次 `Fn` 结束录音。  
Sayit 会把识别出的文字直接输入到你当前正在使用的应用里。

支持的场景包括：

- 日常中文听写
- 中英夹杂输入
- AI / 设计 / 互联网工作流里的专业词
- 云端高精度听写
- 本地听写

## 适合谁

如果你经常在这些应用里输入文字，这个工具会比较合适：

- ChatGPT / Claude / Codex
- Notion / Obsidian
- Figma / FigJam
- 终端 / 编辑器 / IM

## 系统要求

- Apple Silicon Mac：M1 / M2 / M3 / M4
- macOS 14 或更高版本

当前不支持：

- Intel Mac
- macOS 13 及以下

## 第一次使用

第一次启动时，Sayit 会自动请求这些权限：

- 麦克风
- 输入监听
- 辅助功能

没有这些权限时：

- 不能录音
- 不能监听 `Fn`
- 不能把文字自动输入到当前应用

## 听写模式

Sayit 支持多条听写路线：

- 本地听写
- Groq
- ElevenLabs
- 豆包-2.0
- 豆包

默认包里**不内置本地模型**。  
如果你切到本地模式，第一次会自动下载所需模型。

## 改写模式

Sayit 支持：

- 原样直出
- 本地规则轻修正
- Groq 改写

如果你没有配置云端凭证，也可以直接用。

## 云服务凭证

如果你想用云端听写或改写，需要在 app 里填写你自己的凭证。

这份公开下载包：

- **不包含**作者自己的 API key
- **不包含**作者自己的本地术语库
- **不包含**作者自己的本地模型

## 更新方式

以后想拿最新版本，直接打开这个链接就行：

- [最新版 Release 页面](https://github.com/harperrrdesign/Sayit/releases/latest)

## 说明

这是一个持续迭代中的版本。  
如果你在某个特定应用里遇到输入异常，通常和该应用的输入框实现、权限或系统环境有关。
