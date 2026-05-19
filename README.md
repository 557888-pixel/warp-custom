<p align="center">
  <img width="512" alt="WarpCn - 中文汉化版 Warp 终端" src="https://storage.googleapis.com/warpdotdev-content/Readme.png" />
</p>

<h1 align="center">WarpCn — Warp 终端中文汉化版</h1>

<p align="center">
  <a href="https://github.com/SSYCloud/warp-cn/releases">下载</a>
  ·
  <a href="https://www.shengsuanyun.com">胜算云</a>
  ·
  <a href="https://github.com/warpdotdev/Warp">原版 Warp</a>
  ·
  <a href="https://docs.warp.dev">Warp 文档</a>
</p>

<p align="center">
  <a href="https://github.com/SSYCloud/warp-cn/releases"><img alt="GitHub Release" src="https://img.shields.io/github/v/release/SSYCloud/warp-cn?style=flat-square" /></a>
  <a href="LICENSE-AGPL"><img alt="License: AGPL-3.0" src="https://img.shields.io/badge/license-AGPL--3.0-blue?style=flat-square" /></a>
  <a href="https://github.com/warpdotdev/Warp"><img alt="Based on Warp" src="https://img.shields.io/badge/based%20on-Warp-orange?style=flat-square" /></a>
</p>

<h1></h1>

## 项目简介

**WarpCn** 是基于 [Warp](https://github.com/warpdotdev/Warp) 开源终端的中文汉化版本，由 [深圳市胜算云微科技有限公司](https://www.shengsuanyun.com) 维护。

[Warp](https://www.warp.dev) 是一款面向开发者的现代化终端，诞生于终端，却不局限于终端。它将传统终端带入了 21 世纪，提供了现代化的 UI 和代码编辑体验，并内置 AI 智能体（Agent）支持。你可以使用 Warp 内置的 Oz 智能体，也可以运行 Claude Code、Codex、Gemini CLI 等 CLI 编码智能体。

WarpCn 的目标是将这款优秀的终端工具完整地带给中文开发者社区，让中文环境下的开发者能够零障碍地使用 Warp 的所有功能。

### 主要改动

- **全量中文汉化**：界面文字、设置页面、提示信息、帮助文档等全部翻译为中文
- **胜算云 AI 接入**：默认集成 [胜算云](https://www.shengsuanyun.com) AI 后端服务，开箱即用
- **去除登录门控**：无需 Warp 账号即可使用全部功能
- **首次启动欢迎弹窗**：引导用户快速配置 AI 服务
- **支持 macOS 和 Windows**：提供 DMG（macOS）和 EXE（Windows）安装包

## 下载安装

从 [GitHub Releases](https://github.com/SSYCloud/warp-cn/releases) 下载最新版本：

| 平台 | 安装包 |
|------|--------|
| macOS (Apple Silicon / Intel) | `.dmg` |
| Windows | `.exe` |

安装后首次启动会弹出欢迎弹窗，引导你配置胜算云 AI 服务。

## 从源码构建

```bash
./script/bootstrap   # 平台依赖安装
./script/run         # 编译并运行 WarpCn
./script/presubmit   # 代码格式化、clippy 检查和测试
```

详细的工程指南请参阅 [WARP.md](WARP.md)。

## 与原版 Warp 的关系

| | Warp（原版） | WarpCn（汉化版） |
|---|---|---|
| 源码 | [warpdotdev/Warp](https://github.com/warpdotdev/Warp) | [SSYCloud/warp-cn](https://github.com/SSYCloud/warp-cn) |
| 界面语言 | 英文 | 中文 |
| AI 后端 | OpenAI / Anthropic 等 | 胜算云 AI |
| 登录要求 | 需要 Warp 账号 | 无需登录 |
| 协议 | AGPL-3.0 | AGPL-3.0 |

WarpCn 基于 Warp 开源代码库（AGPL-3.0 协议）进行二次开发和汉化，遵循 AGPL-3.0 协议的要求开放全部修改的源代码。我们对 Warp 原版团队的开源贡献表示感谢。

## 许可证

Warp 的 UI 框架（`warpui_core` 和 `warpui` crate）遵循 [MIT 协议](LICENSE-MIT)。

本仓库其余代码（包括 WarpCn 的汉化改动）遵循 [AGPL v3 协议](LICENSE-AGPL)。

## 开源依赖

Warp 的诞生离不开以下优秀的开源项目：

* [Tokio](https://github.com/tokio-rs/tokio)
* [NuShell](https://github.com/nushell/nushell)
* [Fig Completion Specs](https://github.com/withfig/autocomplete)
* [Warp Server Framework](https://github.com/seanmonstar/warp)
* [Alacritty](https://github.com/alacritty/alacritty)
* [Hyper HTTP library](https://github.com/hyperium/hyper)
* [FontKit](https://github.com/servo/font-kit)
* [Core-foundation](https://github.com/servo/core-foundation-rs)
* [Smol](https://github.com/smol-rs/smol)

## 反馈与贡献

- 提交 Issue：[GitHub Issues](https://github.com/SSYCloud/warp-cn/issues)
- 胜算云官网：[https://www.shengsuanyun.com](https://www.shengsuanyun.com)
- 原版 Warp 问题：[warpdotdev/Warp Issues](https://github.com/warpdotdev/Warp/issues)
