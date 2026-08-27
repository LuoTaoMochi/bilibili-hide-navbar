# Bilibili 隐藏顶栏并修复布局

[English](#bilibili-hide-navbar)

隐藏 Bilibili 顶部导航栏，并修复隐藏顶栏后产生的页面布局空白。本 UserStyle 专为 [Wider Bilibili](https://greasyfork.org/zh-CN/scripts/474507-wider-bilibili) 配套设计。

## 使用

本 UserStyle 依赖 **Wider Bilibili**。使用前请先安装并启用 Wider Bilibili。

本 UserStyle 不属于 Wider Bilibili 官方项目，也不是 Wider Bilibili 官方发布的组件、插件或附属脚本。

可直接从 [UserStyles.world页面：Bilibili 隐藏顶栏并修复布局](https://userstyles.world/style/29767/bilibili) 安装本 UserStyle，或将 [`bilibili-hide-navbar.user.css`](./bilibili-hide-navbar.user.css) 安装到支持 UserCSS 的样式管理器（如 Stylus）中。

## 更新说明

### 1.0.1

- 将样式适用范围从整个 `bilibili.com` 限制为播放相关 URL
- （普通视频、移动视频、特殊视频入口、Festival、番剧、课程、播放列表、连续播放、音频以及直播相关页面的 URL 匹配）

## 代码来源与修改说明

本 UserStyle 由 **LuoTaoMochi** 整理、修改并重新组合。

其中部分 CSS 规则取自并修改自 **[Bilibili-Evolved](https://github.com/the1812/Bilibili-Evolved)** 的 `customNavbar` 组件。

本 UserStyle 仅提取与隐藏 Bilibili 原版顶栏及调整相关页面布局有关的部分 CSS 规则，不包含原 `customNavbar` 组件的自定义顶栏界面及其他功能。

### 上游项目

- 项目：[Bilibili-Evolved](https://github.com/the1812/Bilibili-Evolved)
- 相关文件：[custom-navbar.js](https://raw.githubusercontent.com/the1812/Bilibili-Evolved/preview/registry/dist/components/style/custom-navbar.js)
- 上游许可证：MIT License

上游项目的版权与许可证信息请以其仓库及相关许可证文件为准。

## Wider Bilibili

- [Wider Bilibili（Greasy Fork）](https://greasyfork.org/zh-CN/scripts/474507-wider-bilibili)
- [Wider Bilibili（GitHub）](https://github.com/posthumz/wider-bilibili)

## UserStyles.world

- [Bilibili 隐藏顶栏并修复布局](https://userstyles.world/style/29767/bilibili)

---

# bilibili-hide-navbar

Hide the Bilibili top navigation bar and fix the layout spacing caused by hiding it. This UserStyle is designed to work with [Wider Bilibili](https://greasyfork.org/zh-CN/scripts/474507-wider-bilibili).

## Usage

This UserStyle depends on **Wider Bilibili**. Please install and enable Wider Bilibili before using this UserStyle.

This UserStyle is not an official project, component, plugin, or companion script published by Wider Bilibili.

You can install this UserStyle directly from [UserStyles.world页面：Bilibili 隐藏顶栏并修复布局](https://userstyles.world/style/29767/bilibili), or install [`bilibili-hide-navbar.user.css`](./bilibili-hide-navbar.user.css) in a UserCSS-compatible style manager such as Stylus.

## Changelog

### 1.0.1

- Restrict the style's scope from the entire `bilibili.com` domain to playback-related URLs
- (Regular videos, mobile videos, special video entry points, Festival, anime/series, courses, playlists, continuous playback, audio, and live-related pages)

## Code Sources and Modifications

This UserStyle was organized, modified, and recombined by **LuoTaoMochi**.

Some CSS rules were taken from and modified from the `customNavbar` component of **[Bilibili-Evolved](https://github.com/the1812/Bilibili-Evolved)**.

This UserStyle only extracts the CSS rules related to hiding the original Bilibili top navigation bar and adjusting the related page layout. It does not include the custom navigation interface or other functionality of the original `customNavbar` component.

### Upstream Project

- Project: [Bilibili-Evolved](https://github.com/the1812/Bilibili-Evolved)
- Related file: [custom-navbar.js](https://raw.githubusercontent.com/the1812/Bilibili-Evolved/preview/registry/dist/components/style/custom-navbar.js)
- Upstream license: MIT License

Please refer to the upstream repository and its license files for the copyright and license information of the upstream project.

## Wider Bilibili

- [Wider Bilibili (Greasy Fork)](https://greasyfork.org/zh-CN/scripts/474507-wider-bilibili)
- [Wider Bilibili (GitHub)](https://github.com/posthumz/wider-bilibili)

## UserStyles.world

- [Bilibili 隐藏顶栏并修复布局](https://userstyles.world/style/29767/bilibili)
