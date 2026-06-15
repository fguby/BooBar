# BooBar

**BooBar 是一款原生 macOS 灵动岛工具。**

它常驻在屏幕顶部，把音乐播放、AI 任务、日历事项、待办事项、便利签、下载进度、系统通知、Terminal 状态、GitHub 活动和休息提醒集中到一个轻量、可展开的桌面状态层里。

> 本公开仓库只用于分发 BooBar 安装包、更新信息、版本说明和产品文档。BooBar 源代码不开源。

[下载 BooBar.dmg](https://github.com/fguby/BooBar/releases/latest/download/BooBar.dmg) · [最新版本](https://github.com/fguby/BooBar/releases/latest) · [English](README.md)

## 当前版本

当前版本：`v1.1.0`

安装方式：打开 DMG，然后把 BooBar 拖入 Applications。

## v1.1.0 更新内容

这是一个颠覆性的版本更新：

1. 灵动岛形状以及动画的全面优化。
2. 增加了轮盘按钮，请通过按下两个 `⌘` Command 来试试吧。
3. 优化了音乐卡片，现在支持包括 Apple Music、Spotify 在内的几乎所有音乐播放器。
4. 增加了日历卡片和待办事项。
5. 增加了便利签以及贴边功能。
6. 增加了 Terminal 卡片。
7. 现在支持更多的系统原生事件通知。
8. 增加了 Boo 休息器。
9. 更多的更新正在路上。

## 产品预览

<img width="784" height="158" alt="BooBar 灵动岛收起状态预览" src="https://github.com/user-attachments/assets/fa0f8e18-484c-435a-9b5c-76d2f13139ac" />

<img width="1240" height="556" alt="BooBar 任务中心预览" src="https://github.com/user-attachments/assets/e094f3ca-25d3-466d-8a8e-cd30272dc1cd" />

<img width="1368" height="602" alt="BooBar 展开面板预览" src="https://github.com/user-attachments/assets/26068306-d523-483e-a826-ad7818b87219" />

<img width="1240" height="860" alt="BooBar 设置和活动预览" src="https://github.com/user-attachments/assets/e2459707-d58f-4f98-8fc8-05b854e6bea6" />

<img width="1386" height="524" alt="BooBar 监控预览" src="https://github.com/user-attachments/assets/7a780250-07c9-41db-8856-a6ac03b2af2b" />

<img width="1436" height="488" alt="BooBar 工作流预览" src="https://github.com/user-attachments/assets/a82af056-00d2-4777-9b5c-31502c64ab9b" />

<img width="1344" height="950" alt="BooBar 浏览器和网页钉图预览" src="https://github.com/user-attachments/assets/62ab9337-ba1b-410f-9a88-8774c6ad4afe" />

## 核心功能

### 原生 macOS 灵动岛

BooBar 以紧凑灵动岛的形式停留在屏幕顶部。它会在有重要事项时展开，在任务结束后回到安静的顶部状态。

它可以展示音乐、任务、日历、待办、系统活动、系统原生通知、Terminal 状态、GitHub 信息和轻量电脑状态，减少你在多个窗口之间来回切换的次数。

### 轮盘按钮

按下两个 `⌘` Command 可以打开 BooBar 的轮盘按钮。你可以从任何地方快速调用常用操作和桌面工具。

### 音乐卡片

BooBar 支持几乎所有能够提供 Now Playing 信息的音乐播放器，包括 Apple Music 和 Spotify。展开后的音乐卡片会展示封面、播放状态、控制按钮、进度、歌词和相关状态。

### 日历卡片和待办事项

日历卡片可以展示即将到来的事项和选中日期的详情。待办事项卡片可以把轻量任务放在当前工作流旁边，并支持状态变更和快速查看。

### 便利签和贴边

你可以创建桌面便利签，也可以把便利签贴到屏幕边缘，让它在需要时出现，不需要时隐藏在边缘。

### Terminal 卡片

Terminal 卡片会把电脑状态、终端风格信息和工作流面板放进 BooBar 的展开面板里。

### AI 和编程任务状态

BooBar 可以展示 Codex、Claude Code 等 AI 工作流的运行状态、任务进度、确认请求、文件发现和完成提醒，让后台任务不再被窗口遮住。

### AI 文件整理

BooBar 可以监听 Downloads、Desktop 或你指定的文件夹。新文件会在置信度足够高时自动整理；不确定的项目会进入审阅流程，避免重要文件被误移动。

### 网页、下载和系统事件

BooBar 可以监控浏览器下载、网页变化、GitHub 活动以及更多 macOS 原生事件。重要状态会集中展示在灵动岛里，而不是散落在多个窗口中。

### Boo 休息器

Boo 休息器可以提醒你在工作中进行短暂、主动的休息。

## 安装

1. 下载 [BooBar.dmg](https://github.com/fguby/BooBar/releases/latest/download/BooBar.dmg)。
2. 打开 DMG。
3. 将 BooBar 拖入 Applications。
4. 从 Applications 启动 BooBar。

如果 macOS 阻止首次启动，请打开 **系统设置 > 隐私与安全性**，手动允许运行 BooBar。

## 更新

BooBar 会从本仓库读取更新信息：

- `latest.json`：当前版本、版本说明、校验值、文件大小和下载地址。
- `dist/BooBar.dmg`：最新公开安装包。
- GitHub Releases：每个公开版本的发布记录。

最新版本：[v1.1.0](https://github.com/fguby/BooBar/releases/tag/v1.1.0)

## 系统要求

- macOS 14 或更高版本

## 支持

- 报告问题：[GitHub Issues](https://github.com/fguby/BooBar/issues/new?labels=bug)
- 反馈建议：[GitHub Issues](https://github.com/fguby/BooBar/issues/new?labels=feedback)
- 社区讨论：[GitHub Discussions](https://github.com/fguby/BooBar/discussions)

## 了解更多

官网：<https://boobar.app>
