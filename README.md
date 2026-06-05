# BooBar

BooBar 是一个原生 macOS 桌面 AI 灵动岛工具。它把顶部常驻的动态状态栏作为入口，帮助你查看和处理 Codex / Claude Code 会话、文件整理、下载任务、网页钉图、天气、终端面板和桌面工作流提醒。

## 下载

从本仓库下载最新安装包：

- [BooBar.dmg](https://github.com/fguby/BooBar/raw/main/BooBar.dmg)

下载后打开 DMG，把 BooBar 拖到 Applications 即可安装。

## 更新

BooBar 的应用内更新会从本仓库读取：

- `latest.json`：当前版本信息
- `BooBar.dmg`：最新安装包

如果后续发布 GitHub Release，应用会优先读取 Release；没有 Release 时会使用本仓库根目录的 `latest.json`。

## 功能概览

- 顶部灵动岛：集中展示当前任务、状态、用量和提醒。
- AI 会话监控：查看 Codex 与 Claude Code 会话状态。
- 文件整理：监听新增文件，辅助分析、归档和确认。
- 网页钉图：监控网页区域变化并提醒。
- Chrome 增强：下载任务、网页资源识别和浏览器相关能力。
- 终端面板：展示终端统计、GitHub 活动、专注与健康卡片。
- AI 截图：截取屏幕区域并进行 OCR、颜色提取、笔记和总结。

## 隐私说明

本公开仓库只用于分发 BooBar 安装包和版本信息，不包含 BooBar 的源代码。
