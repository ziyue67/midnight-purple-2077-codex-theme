# Midnight Purple 2077 Codex Theme

High-contrast dark purple theme adaptation for Codex Desktop, inspired by the VS Code theme **Midnight Purple 2077**. Optimized for readable white chat text, Chinese UI fonts, and a clean programmer-focused Codex interface.

Keywords: Codex theme, Codex Desktop theme, Midnight Purple 2077, VS Code theme for Codex, dark purple Codex theme, Chinese UI font, high contrast white text.

中文 | [English](#english)

## 中文

这是把 VS Code 主题 **Midnight Purple 2077** 适配到 **Codex Desktop** 的高对比暗紫色主题配置。它保留了 Midnight Purple 2077 的暗紫色气质，同时针对 Codex 对话界面、中文 UI 字体和白色文字可读性做了优化。

关键词：Codex 主题、Codex Desktop 主题、Midnight Purple 2077、VS Code 主题适配 Codex、暗紫色 Codex 主题、中文 UI 字体、高对比白色文字。

## 来源

- [Visual Studio Marketplace: Midnight Purple 2077](https://marketplace.visualstudio.com/items?itemName=cybersamurai.midnight-purple-2077)
- [GitHub: tsomone/midnight-purple-theme](https://github.com/tsomone/midnight-purple-theme)

## 当前效果

- 暗色代码主题：`dracula`
- UI 字体：`Microsoft YaHei UI Bold, Noto Sans SC, Segoe UI Semibold, Microsoft YaHei UI, sans-serif`
- 代码字体：`Consolas, 'Courier New', monospace`
- UI 字号：`16`
- 代码字号：`14`
- 背景色：`#100718`
- 文字色：`#ffffff`
- 对比度：`88`
- 强调色：`#7c41c4`

## 如何使用

当前机器可以写入 Codex 配置：

`%USERPROFILE%\.codex\config.toml`

正常情况下只需要 **重启 Codex Desktop**，主题就会生效。

如果你想手动导入主题：

1. 打开 Codex Desktop。
2. 进入设置里的外观/主题导入位置。
3. 打开 `dist/midnight-purple-2077.codex-theme.txt`。
4. 复制里面以 `codex-theme-v1:` 开头的一整行。
5. 粘贴到 Codex 的主题导入框中。
6. 应用后重启 Codex。

## 文件说明

- `dist/midnight-purple-2077.codex-theme.txt`：Codex 可导入的一行主题字符串。
- `dist/midnight-purple-2077.codex.json`：同一份主题的可读 JSON 版本，方便查看和修改。
- `midnight-purple-2077.vsix`：原 VS Code 主题扩展包。

## 注意

Codex Desktop 目前不能直接完整读取 VS Code 主题里的全部 `tokenColors`。所以这个适配版使用 Codex 内置的 `dracula` 作为代码高亮基底，再把 Midnight Purple 2077 的暗紫 UI 色盘、字体和高对比白字效果适配到 Codex。

本仓库只提供 Codex Desktop 适配配置。原 VS Code 主题版权和维护归原作者所有，请参考上面的来源链接。

---

## English

This is a high-contrast dark purple **Codex Desktop theme** adapted from the VS Code theme **Midnight Purple 2077**. It keeps the original Midnight Purple 2077 mood while improving Codex chat readability, Chinese UI font rendering, and white text contrast.

Keywords: Codex theme, Codex Desktop theme, Midnight Purple 2077, VS Code theme for Codex, dark purple Codex theme, Chinese UI font, high contrast white text.

## Source

- [Visual Studio Marketplace: Midnight Purple 2077](https://marketplace.visualstudio.com/items?itemName=cybersamurai.midnight-purple-2077)
- [GitHub: tsomone/midnight-purple-theme](https://github.com/tsomone/midnight-purple-theme)

## Current Settings

- Dark code theme: `dracula`
- UI font: `Microsoft YaHei UI Bold, Noto Sans SC, Segoe UI Semibold, Microsoft YaHei UI, sans-serif`
- Code font: `Consolas, 'Courier New', monospace`
- UI font size: `16`
- Code font size: `14`
- Surface: `#100718`
- Text/ink: `#ffffff`
- Contrast: `88`
- Accent: `#7c41c4`

## How To Use

Codex can be configured at:

`%USERPROFILE%\.codex\config.toml`

Usually, you only need to **restart Codex Desktop** for the theme to take effect.

To import the theme manually:

1. Open Codex Desktop.
2. Go to the appearance/theme import area in settings.
3. Open `dist/midnight-purple-2077.codex-theme.txt`.
4. Copy the entire line that starts with `codex-theme-v1:`.
5. Paste it into the Codex theme import box.
6. Apply it and restart Codex.

## Files

- `dist/midnight-purple-2077.codex-theme.txt`: one-line Codex theme import string.
- `dist/midnight-purple-2077.codex.json`: readable JSON version of the same theme.
- `midnight-purple-2077.vsix`: original VS Code theme extension package.

## Note

Codex Desktop currently cannot directly consume all VS Code `tokenColors`. This adaptation uses Codex's built-in `dracula` code theme as the syntax highlighting base, then applies the Midnight Purple 2077-inspired dark purple UI palette, fonts, and high-contrast white text tuning.

This repository only provides the Codex Desktop adaptation config. The original VS Code theme belongs to its upstream author and maintainers. See the source links above.
