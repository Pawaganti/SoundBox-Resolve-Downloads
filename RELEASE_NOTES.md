# 声匣 SoundBox v1.1.2

可独立运行的音频素材管理与预览工具，也可作为 DaVinci Resolve 工作流插件使用。支持音频搜索、波形试听、星级与颜色标签整理、批量转码，以及导入达芬奇媒体池和时间线。

## 下载

适用于 Windows 64 位系统，安装版与便携版的应用功能相同。

| 下载 | 使用方式 |
| --- | --- |
| [安装版 Setup.exe](https://github.com/Pawaganti/SoundBox-Resolve-Downloads/releases/download/v1.1.2/SoundBox-v1.1.2-Setup-x64.exe) | 双击运行安装向导，自动创建快捷方式和卸载入口。 |
| [便携版 ZIP](https://github.com/Pawaganti/SoundBox-Resolve-Downloads/releases/download/v1.1.2/SoundBox-v1.1.2-win32-x64.zip) | 完整解压后运行 `SoundBox.exe`，保留同目录的运行库和资源文件。 |
| [SHA-256 校验文件](https://github.com/Pawaganti/SoundBox-Resolve-Downloads/releases/download/v1.1.2/SHA256SUMS.txt) | 用于核验下载文件的完整性。 |

## 本版更新

- 提供带安装向导、快捷方式和标准卸载入口的 Windows 安装包。
- 悬浮按钮移除阴影，内部图标放大，保留白色圆角按钮外形。
- 多选时显示灰色「批量操作」栏，便于区分操作工具与选中素材。
- 包含目录搜索、波形定位、批量转码及 Resolve 音频插入相关修复。

## 安装与配置

- 重新安装保留当前 Windows 用户的配置、收藏、标签、搜索历史和素材索引。更新前建议备份 `%APPDATA%\soundbox\`。
- 检测到 DaVinci Resolve 或既有声匣集成目录时，安装版会配置工作流启动入口。安装后重启 Resolve，从「工作区 → 工作流整合 → 声匣」启动。
- 如安装目录或达芬奇公共插件目录提示权限不足，右键安装包选择「以管理员身份运行」。
- 独立搜索、试听和转码无需打开 Resolve；导入时间线前，请先打开 Resolve 项目及时间线，并确认声匣连接状态。
- 安装包暂未提供数字签名。

完整安装、便携使用和卸载步骤见[使用说明](https://github.com/Pawaganti/SoundBox-Resolve-Downloads#安装与使用)。
