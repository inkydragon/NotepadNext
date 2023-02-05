# Notepad Next

[English Readme](README.md) | [Github Release][github-download] | [Github Repo][github-repo] | [Github issue (English only!)][github-issue]

[github-download]: https://gitee.com/dail8859/NotepadNext/releases/latest
[github-repo]: https://github.com/dail8859/NotepadNext
[github-issue]: https://github.com/dail8859/NotepadNext/issues?q=is%3Aissue+is%3Aopen+sort%3Aupdated-desc

Github 构建状态：![Build Notepad Next](https://github.com/dail8859/NotepadNext/workflows/Build%20Notepad%20Next/badge.svg)

**跨平台的 Notepad++ 实现**

开发版注意！尽管该程序总体上是稳定、可用的，但对于重要的任务来说，它不应被视为安全、可靠的。

目前代码中仍有许多 bug 和刚好能跑的实现。
我们非常欢迎去 github 进行提交请求。

![screenshot](/doc/screenshot.png)


# 安装

安装包在三大平台上均可用：Windows, Linux, 和 MacOS.

## Windows

Windows 平台有绿色版压缩包和 exe 安装程序可用：
- 绿色版压缩包：[`NotepadNext-v*-win64.zip`](https://gitee.com/woclass/NotepadNext/releases/latest)
- exe 安装程序：[`NotepadNext-v*-Installer.exe`](https://gitee.com/woclass/NotepadNext/releases/latest)  
    安装程序提供了额外的自动更新器、注册 win 右键菜单等功能。

或者也可以使用 winget 安装：
```powershell
winget install dail8859.NotepadNext
```

## Linux
Linux 平台有 AppImage 和 flatpak 可用：
- [`NotepadNext-x86_64.AppImage`](https://gitee.com/woclass/NotepadNext/releases/latest)
- [flatpak @ flathub.org](https://flathub.org/apps/details/com.github.dail8859.NotepadNext)  
    下载然后执行:
    ```bash
    flatpak install flathub com.github.dail8859.NotepadNext
    ```

## MacOS
MacOS 平台有 dmg 可用：
- [`NotepadNext.dmg`](https://gitee.com/woclass/NotepadNext/releases/latest)


# 开发
目前 Windows 上开发使用
- Visual Studio 2022 
- Qt v6.2+

Linux 和 macOS 可以参考 win 平台配置环境。
可能需要少量的修改。

如果你很熟悉 QT 的开发，并使用 Qt Creator，那么直接打开 `src/NotepadNext.pro` 就能编译运行本项目。

如果你刚接触 C++ Qt 的桌面项目，可以参考 [构建过程（英文）](/doc/Building.md)


# 版权
本项目使用 [GPL v3.0+](LICENSE) 协议授权.
```
// SPDX-License-Identifier: GPL-3.0-or-later
```

依赖项版权说明见：[THIRDPARTY.md](THIRDPARTY.md)
