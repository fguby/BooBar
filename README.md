# BooBar

**BooBar is a native macOS AI Dynamic Island for people who live in AI coding tools, browsers, files, and tiny context switches all day.**

It stays at the top of your screen, watches the work that normally hides across apps, and turns Codex, Claude Code, downloads, files, web pages, weather, GitHub activity, screenshots, bookmarks, and productivity signals into one calm control center.

> This public repository is for distribution only. It contains the latest DMG, release metadata, and product documentation. BooBar source code is not open source.

[Download BooBar.dmg](https://github.com/fguby/BooBar/raw/main/BooBar.dmg) · [Latest Release](https://github.com/fguby/BooBar/releases/latest) · [Report Bug](https://github.com/fguby/BooBar/issues/new?labels=bug) · [Send Feedback](https://github.com/fguby/BooBar/issues/new?labels=feedback)

---

## English

### Why BooBar

BooBar is designed for a modern desktop where AI agents, browser workflows, files, terminals, and notifications are constantly moving in parallel. Instead of forcing you to jump between windows, BooBar gives you a lightweight status surface and an expandable task panel that keeps the important things visible and actionable.

It is not a launcher and not a generic dashboard. It is a focused AI work companion for macOS.

### Highlights

- **Native macOS Dynamic Island**
  - Compact top bar with task status, token usage, weather, and priority activity.
  - Expandable task center for AI sessions, downloads, web pins, files, and alerts.
  - Custom width, panel height, panel width, font size, display selection, and notch height controls.
  - Full-screen hiding, auto-hide when idle, click-outside collapse, and detail/compact task display modes.

- **Codex and Claude Code Session Monitor**
  - Tracks active Codex and Claude Code sessions.
  - Distinguishes running, finished, stopped, and confirmation-needed sessions where possible.
  - Reads local session files when app-server data is not precise enough.
  - Opens the original related session or terminal when action is needed.
  - Shows current task text, command calls, progress snippets, and recent output context.
  - Uses real Codex and Claude Code icons.

- **Codex Usage**
  - Shows remaining 5-hour and 7-day usage instead of raw used quota.
  - Avoids showing fake 100% while data is still loading.
  - Keeps token and usage status visible in the island and settings sidebar.

- **AI File Sorting**
  - Watches selected folders for new files.
  - Optional recursive or non-recursive folder monitoring.
  - Sends folder structure context to AI to avoid duplicate semantic directories.
  - Handles images, documents, videos, text-like unknown extensions, and readable exported config files.
  - Supports confirm, re-analyze, ignore, undo, and review workflows.
  - Includes an organized file history window and mind-map style viewing mode.

- **Video-Aware Organization**
  - Analyzes new video files without sending the full video to AI.
  - Extracts lightweight metadata, thumbnails, sampled frames, and summaries where possible.
  - Reduces token usage while still giving meaningful file classification.

- **Desktop Review Window**
  - Replaces the old browser-based admin console with a larger native desktop review window.
  - Review all analyzed file records.
  - Confirm, ignore, re-analyze, undo, and inspect archived results.

- **Chrome Extension**
  - Bridges browser tasks into BooBar.
  - Monitors new download progress only, not every historical downloaded file.
  - Download rows can be dismissed manually from BooBar.
  - Provides browser resource detection for images, PDFs, videos, audio, and page assets.
  - Allows selected resources to be downloaded individually.
  - Reuses browser context and headers where possible.
  - Supports optional helper tools such as yt-dlp and future crawler integrations.

- **Web Pin**
  - Pin a selected web region and monitor for changes.
  - Supports real-time or refresh-based monitoring modes.
  - Summarizes page changes into readable text instead of raw noisy DOM text.
  - Deduplicates repeated notifications for the same change.
  - Opens the original pinned tab or bookmark target when possible.

- **Resource Downloader**
  - Detects downloadable resources on the current browser page.
  - Shows counts such as images, videos, audio, PDFs, and article content.
  - Supports download images, download video, download PDFs, save article, and pin page workflows.
  - Built as a Chrome extension skill so users can inspect and select resources before downloading.

- **Bookmark Intelligence**
  - Syncs Chrome bookmarks.
  - Supports automatic incremental sync for new bookmarks.
  - Uses the configured AI provider to deeply summarize bookmark pages.
  - Makes bookmarks searchable by keywords, summaries, and page meaning.

- **Terminal Panel**
  - Idle expanded panel can show terminal statistics, GitHub activity, or focus and wellness cards.
  - Refreshes only the selected panel type at the user-configured frequency.
  - Avoids unnecessary high-frequency sampling when GitHub or wellness panels are selected.

- **GitHub Activity Panel**
  - Shows GitHub profile stats, contribution heatmap, recent events, repositories, followers, following, streaks, and sync time.
  - Designed as a terminal-style panel for the expanded island.
  - Uses GitHub authentication where available.

- **Focus and Wellness Panel**
  - Shows practical focus signals such as current focus time, screen usage, interruption count, and wellness reminders where the data can be measured reliably.
  - Avoids showing metrics that cannot be calculated accurately.

- **Weather**
  - Shows concise weather in the compact island.
  - Shows richer details in expanded views and settings.
  - Supports WeatherKit where available and fallback weather lookup.
  - Supports current location and manual city input.

- **Terminal Pet**
  - Plays a pet animation inside the expanded terminal chart area.
  - Supports custom WebP pets, ZIP pet packs with `pet.json`, and user-controlled animation interval.
  - Can sync Codex pets and switch between imported pets in settings.

- **AI Screenshot**
  - Global shortcut for selection-based screenshot capture.
  - Dark overlay outside the selection region.
  - Action bar after capture: save image, extract text, extract colors, save as note, and AI summarize.
  - Designed to use modern macOS screen capture APIs.

- **Smart Clipboard**
  - Clipboard enhancement features including long-text translation workflows.
  - Designed for quick AI-assisted transformations without opening a separate editor.

- **AI Enhance**
  - Configurable AI provider modes.
  - Supports local, cloud, Codex, and Claude Code based workflows depending on user configuration.
  - File analysis uses the selected provider by default.

- **Subscription and Trial**
  - Two-day trial flow.
  - License activation.
  - In-app purchase and license dialog.
  - Activation success effects and collectible subscription card display.

- **Privacy and Distribution**
  - This repository only distributes BooBar binaries and update metadata.
  - Source code is not included.
  - AI providers and browser integrations are controlled by the user's local configuration and permissions.

### Install

1. Download [BooBar.dmg](https://github.com/fguby/BooBar/raw/main/BooBar.dmg).
2. Open the DMG.
3. Drag BooBar into Applications.
4. Launch BooBar from Applications.

If macOS blocks the app, open **System Settings > Privacy & Security** and allow BooBar manually.

### Updates

BooBar checks this repository for updates:

- `latest.json` contains the current version and download URL.
- `BooBar.dmg` is the latest installer.
- GitHub Releases are also published for each public version.

Current release: [v1.0.2](https://github.com/fguby/BooBar/releases/tag/v1.0.2)

### Support

- Bug reports: [GitHub Issues](https://github.com/fguby/BooBar/issues/new?labels=bug)
- Feedback and ideas: [GitHub Issues](https://github.com/fguby/BooBar/issues/new?labels=feedback)
- Community discussions: [GitHub Discussions](https://github.com/fguby/BooBar/discussions)

---

## 中文

### BooBar 是什么

BooBar 是一款原生 macOS AI 灵动岛工具。它常驻在屏幕顶部，把 Codex、Claude Code、文件整理、浏览器下载、网页钉图、天气、GitHub 活动、截图、书签和桌面工作流提醒集中到一个轻量、可展开的任务中心里。

它不是启动器，也不是普通仪表盘。BooBar 更像一个专门为 AI 工作流设计的桌面状态层：让你不用频繁切窗口，也能知道哪些任务正在运行、哪些需要确认、哪些已经完成。

### 核心亮点

- **原生 macOS 灵动岛**
  - 顶部紧凑状态栏，显示任务状态、Token、用量、天气和优先任务。
  - 展开后成为统一任务控制中心。
  - 支持设置顶部宽度、展开面板宽度、最大面板高度、字体大小、主显示器和刘海高度。
  - 支持全屏隐藏、空闲隐藏、点击外部收起、详情任务模式和紧凑模式。

- **Codex / Claude Code 会话监控**
  - 监控 Codex 和 Claude Code 会话状态。
  - 尽量区分运行中、已完成、已终止、需要确认等状态。
  - app-server 状态不精准时，可回退读取本地会话文件。
  - 支持打开对应会话或跳回对应终端。
  - 展示当前任务、命令调用、代码片段、进度文本和最近输出。
  - 使用真实 Codex 与 Claude Code 图标。

- **Codex 用量统计**
  - 显示 5 小时和 7 天剩余用量。
  - 数据未获取前显示加载状态，不再假显示 100%。
  - Token 和用量可在灵动岛及设置侧栏查看。

- **AI 文件整理**
  - 监听指定目录的新文件。
  - 支持递归或非递归监控。
  - 分析时会把当前目录结构一起提供给 AI，减少语义重复目录。
  - 支持图片、文档、视频、文本类未知扩展名、可读配置导出文件等。
  - 支持确认、二次分析、忽略、撤销、查看记录。
  - 提供已整理文件列表和脑图展示方式。

- **视频归纳整理**
  - 对新增视频进行轻量分析。
  - 不会把整个视频直接丢给 AI。
  - 尽量通过元数据、缩略图、抽帧和简要摘要完成分类，降低 Token 消耗。

- **桌面文件审阅窗口**
  - 去掉旧 Web 管理台，改为更大的原生桌面窗口。
  - 可以查看所有整理记录。
  - 支持确认、忽略、二次分析、撤销和查看归档路径。

- **Chrome 增强**
  - 通过浏览器插件连接 BooBar。
  - 只监听新增下载任务的进度。
  - 下载任务可在灵动岛中手动删除，删除后不再显示。
  - 支持网页资源识别：图片、PDF、视频、音频、文章内容等。
  - 支持单独选择资源下载。
  - 尽量复用浏览器 Header 和上下文。
  - 支持集成 yt-dlp 等辅助下载能力。

- **网页钉图**
  - 框选网页区域并监控变化。
  - 支持实时监听和刷新监听。
  - 将网页变化提炼成可读文本，而不是直接展示冗长 DOM。
  - 对相同变化做去重，避免重复通知。
  - 打开时尽量跳回原网页或原书签位置。

- **资源自动下载**
  - 在浏览器插件中识别页面可下载资源。
  - 可统计图片、视频、音频、PDF 和文章内容。
  - 支持下载全部图片、下载视频、下载 PDF、保存文章、Pin 当前网页等操作。
  - 用户可以先查看资源列表，再选择需要下载的内容。

- **书签归纳检索**
  - 同步 Chrome 书签。
  - 支持新增书签后的自动增量同步。
  - 使用用户配置的 AI 增强提供商进行深度总结。
  - 支持通过关键词、摘要和语义检索书签。

- **终端面板**
  - 空闲展开时可展示终端统计、GitHub 活动、专注与健康卡片。
  - 只按用户选择的面板类型和刷新频率更新数据。
  - 当选择 GitHub 或健康面板时，不再高频刷新网络、负载、磁盘等无关数据。

- **GitHub 活动面板**
  - 展示 GitHub 个人资料、贡献热力图、最近事件、仓库数、粉丝数、关注数、连续贡献和同步时间。
  - 以终端风格展示在灵动岛展开面板中。

- **专注与健康面板**
  - 展示可可靠统计的专注时间、屏幕使用、打断次数和健康提醒。
  - 无法准确统计的指标不会强行展示。

- **天气**
  - 灵动岛紧凑状态显示短版天气。
  - 展开和设置里显示更完整的天气信息。
  - 支持 WeatherKit，也支持失败后的备用天气查询。
  - 支持当前位置和手动输入城市。

- **终端宠物**
  - 在展开终端图表区域播放宠物动画。
  - 支持导入 WebP、导入包含 `pet.json` 的 ZIP 宠物包。
  - 支持设置动作切换间隔。
  - 支持同步 Codex 宠物并在设置中切换。

- **AI 截图**
  - 使用快捷键触发区域截图。
  - 截图区域外显示深色遮罩。
  - 截图后提供保存图片、提取文字、提取颜色、保存为笔记、AI 总结等操作。
  - 面向现代 macOS 截图 API 设计。

- **智能剪贴板**
  - 提供剪贴板增强能力。
  - 支持长文自动翻译等 AI 辅助处理。

- **AI 增强**
  - 支持配置不同 AI 分析模式。
  - 可根据用户配置使用本地、云端、Codex 或 Claude Code 等工作流。
  - 文件分析默认走用户选择的 AI 增强配置。

- **订阅和试用**
  - 支持两天试用。
  - 支持 License 激活。
  - 支持应用内订阅/购买窗口。
  - 激活后展示礼花效果和订阅卡片。

- **隐私与分发**
  - 本仓库只用于分发 BooBar 安装包和版本信息。
  - 不包含 BooBar 源代码。
  - AI 服务、浏览器插件和系统权限均由用户本地配置与授权控制。

### 安装

1. 下载 [BooBar.dmg](https://github.com/fguby/BooBar/raw/main/BooBar.dmg)。
2. 打开 DMG。
3. 将 BooBar 拖入 Applications。
4. 从 Applications 启动 BooBar。

如果 macOS 阻止启动，请打开 **系统设置 > 隐私与安全性**，手动允许运行 BooBar。

### 更新

BooBar 会从本仓库读取更新信息：

- `latest.json`：当前版本和下载地址。
- `BooBar.dmg`：最新安装包。
- GitHub Releases：每个公开版本的发布记录。

当前版本：[v1.0.2](https://github.com/fguby/BooBar/releases/tag/v1.0.2)

### 支持

- 报告问题：[GitHub Issues](https://github.com/fguby/BooBar/issues/new?labels=bug)
- 反馈建议：[GitHub Issues](https://github.com/fguby/BooBar/issues/new?labels=feedback)
- 社区讨论：[GitHub Discussions](https://github.com/fguby/BooBar/discussions)
