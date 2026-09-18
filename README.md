# 菲比 Phoebe · Wuthering Waves

时间变化效果、窗帘与微尘动态、真实时钟。支持 Wallpaper Engine 和 Lively。

![壁纸预览](preview.jpg)

鼠标靠近右下角显示入口，点击展开控制面板。支持手动时间与系统时间，内嵌面板支持中文 / English。

## 下载哪个版本？

到本仓库 **Releases** 下载完整 ZIP：

| 版本 | 文件 | 使用要求 | 音乐 |
| --- | --- | --- | --- |
| Wallpaper Engine | Pheobe-WE-0.2.1.zip | 已安装 Steam 版 Wallpaper Engine | 无 BGM |
| Lively | Pheobe-Lively-0.2.1-win-x64.zip | Windows x64，单独安装 Lively 桌面版 | 自带音乐文件可播放，包内无音乐 |

不要下载 GitHub 自动生成的 Source code ZIP 来安装壁纸；它只包含本仓库的页面和说明。

### Wallpaper Engine

解压后把 phoebe-web 文件夹放入 WE 的 projects/myprojects/，重新打开 WE 后选择作品。也可在编辑器导入 phoebe-web/index.html。详见 [安装说明](docs/WE-Install.md) 和 [操作说明](docs/Wallpaper-Engine.md)。

### Lively

从 [Lively 官方网站](https://www.rocksdanister.com/lively/) 安装桌面版，解压完整包并双击 Start.cmd。控制器中选择 Lively.exe，再点击“应用此壁纸”。附带 .NET 运行时，无需 Python、Node 或开发 SDK。详见 [使用说明](docs/Lively.md)。

Lively 面板滚轮和曲库更新需要控制器保持运行；控制器窗口可以关闭到托盘。退出控制器后仍可拖动面板滚动条。托盘控制器目前为中文。音乐放入 Music 后点击“更新曲库”，不会自动播放。

## 功能与反馈

- 清晨、正午、黄昏、原画夜晚和午夜；支持保留原画色彩。
- 真实时钟显示时、分、秒，颜色随壁纸昼夜变化。
- 可调窗帘、微尘、光照和帧率。
- 右下角隐藏入口与右侧面板；时间滑块连续拖动，设置保存在本机。

纯 GPT Astra 许愿产物，如您遇到 bug 或不适请反馈，🙏

目前主要在作者个人电脑上验证。其他显卡、超宽屏、多屏、不同 DPI 和睡眠恢复未全面覆盖。反馈请写明 Windows/宿主版本、显卡、屏幕分辨率和复现步骤；不要上传个人配置、私人音乐或账号凭据。

## 权利与发行范围

本仓库用于分发成品与使用文档，不包含完整开发工程。原画和角色权利属于各自权利人；第三方库许可不代表对原画授权。见 [CREDITS.md](CREDITS.md)。本作品不是游戏或壁纸宿主官方发行产品。
