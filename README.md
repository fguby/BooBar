# BooBar

**BooBar is a native macOS AI Dynamic Island for people who live in AI coding tools, browsers, files, and tiny context switches all day.**

It stays at the top of your screen, watches the work that normally hides across apps, and turns Codex, Claude Code, downloads, files, web pages, weather, GitHub activity, screenshots, bookmarks, and productivity signals into one calm control center.

> This public repository is for distribution only. It contains the latest DMG, release metadata, and product documentation. BooBar source code is not open source.

[Download BooBar.dmg](https://github.com/fguby/BooBar/raw/main/BooBar.dmg) · [Latest Release](https://github.com/fguby/BooBar/releases/latest) · [Report Bug](https://github.com/fguby/BooBar/issues/new?labels=bug) · [Send Feedback](https://github.com/fguby/BooBar/issues/new?labels=feedback) · [简体中文](README.zh-CN.md)

---

## Why BooBar

BooBar is designed for a modern desktop where AI agents, browser workflows, files, terminals, and notifications are constantly moving in parallel. Instead of forcing you to jump between windows, BooBar gives you a lightweight status surface and an expandable task panel that keeps the important things visible and actionable.

It is not a launcher and not a generic dashboard. It is a focused AI work companion for macOS.

<img width="1240" height="556" alt="image" src="https://github.com/user-attachments/assets/e094f3ca-25d3-466d-8a8e-cd30272dc1cd" />


## Highlights

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
 
<img width="1344" height="950" alt="image" src="https://github.com/user-attachments/assets/62ab9337-ba1b-410f-9a88-8774c6ad4afe" />


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

## Install

1. Download [BooBar.dmg](https://github.com/fguby/BooBar/raw/main/BooBar.dmg).
2. Open the DMG.
3. Drag BooBar into Applications.
4. Launch BooBar from Applications.

If macOS blocks the app, open **System Settings > Privacy & Security** and allow BooBar manually.

## Updates

BooBar checks this repository for updates:

- `latest.json` contains the current version and download URL.
- `BooBar.dmg` is the latest installer.
- GitHub Releases are also published for each public version.

Current release: [v1.0.2](https://github.com/fguby/BooBar/releases/tag/v1.0.2)

## Support

- Bug reports: [GitHub Issues](https://github.com/fguby/BooBar/issues/new?labels=bug)
- Feedback and ideas: [GitHub Issues](https://github.com/fguby/BooBar/issues/new?labels=feedback)
- Community discussions: [GitHub Discussions](https://github.com/fguby/BooBar/discussions)
