<p align="center"><img src="icon.svg" width="80" alt="SoundBox"></p>

# 声匣 SoundBox · 达芬奇插件与独立版下载

**支持独立运行的 DaVinci Resolve 音频素材管理与预览插件。**

Windows 64 位版本。可独立运行，也可从 DaVinci Resolve「工作流整合」启动。

## 下载与分享

- **[最新版本下载页](https://github.com/Pawaganti/SoundBox-Downloads/releases/latest)**：适合长期收藏和分享。
- [v1.1.2 版本记录](https://github.com/Pawaganti/SoundBox-Downloads/releases/tag/v1.1.2)
- **[直接下载 v1.1.2 Windows 运行包](https://github.com/Pawaganti/SoundBox-Downloads/releases/download/v1.1.2/SoundBox-v1.1.2-win32-x64.zip)**
- [SHA-256 校验文件](https://github.com/Pawaganti/SoundBox-Downloads/releases/download/v1.1.2/SHA256SUMS.txt)

本仓库及下载包公开可访问，访问者无需加入私有仓库；通常不需要登录 GitHub。

## 使用

1. 下载 ZIP 并完整解压到可写目录。
2. 双击 `SoundBox.exe`；保留旁边的运行库和 `resources` 文件夹，不要只复制 EXE。
3. 可运行包中的 `Create-Desktop-Shortcut.ps1` 可创建桌面快捷方式。
4. 需要达芬奇集成时，在声匣更多菜单中执行安装到 DaVinci Resolve，按提示完成安装并重启 Resolve，再从「工作区 → 工作流整合」打开。

独立试听、搜索及转码无需打开 Resolve。时间线插入需要先开启 Resolve 项目和时间线，并确认连接状态。现有用户更新程序时保留 `%APPDATA%/soundbox/AudioPreview/` 中的资料。

## 主要功能

- 文件夹树、列表／图标视图、目录底色与 Ctrl／Shift 多选。
- 子文件夹搜索、搜索历史、完整父目录路径排序、星级与颜色标签筛选。
- 悬停试听、波形点击定位、倍速／倒放、A-B 选区与导出。
- 导入达芬奇媒体池或播放头位置；优先复用可用轨道，重叠时新建 Stereo 轨道。
- 常见音频转码、同名保护、置顶与无阴影悬浮按钮。

## 界面预览

以下是 v1.1.2 演示素材库截图，波形为构造数据，不包含个人音频资料。

![列表与目录](screenshots/main-list.png)

| 图标与批量操作 | 搜索历史 |
| --- | --- |
| ![图标与多选](screenshots/grid-selection.png) | ![搜索历史](screenshots/search-history.png) |

悬浮按钮：![悬浮按钮](screenshots/widget.png)

## v1.1.2

- 去掉悬浮按钮普通、悬停、按下状态的阴影。
- 内部统一图标由 26px 放大到 40px，保留白色圆角按钮。
- 保留中性灰色「批量操作」栏及此前稳定性修复。
- 22 项界面回归通过。Resolve 插入经过隔离模拟，本次未在真实工程中逐项验收。

本仓库用于公开下载与版本说明，不提供单独的源码归档包。源码归档继续保留在私有仓库。
