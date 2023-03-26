<p align="center">
<img src="/mpvnet.png" height="150">
</p>

<h1 align="center"> mpv.net-DW </h1>

<h3 align="center"> mpv.net_CM的💗DW版本💗 </h3>

<h4 align="center"> 定制了播放界面、右键菜单、缩略图、视频滤镜和着色器 </h4>

<p align="center">
<img src="https://api.visitorbadge.io/api/combined?path=https%3A%2F%2Fgithub.com%2Fdiana7127%2Fmpv.net-DW&label=Hello%20Visitors&countColor=%23e7818b">
<img src="https://img.shields.io/github/v/release/diana7127/mpv.net-DW?label=Latest%20Release&&style=for-the-badge&color=%238cc7ff">
</p>

<p align="center">
<img src="https://img.shields.io/github/downloads/diana7127/mpv.net-DW/total?&style=for-the-badge&color=%23e94556&logo=github">
<img src="https://img.shields.io/github/stars/diana7127/mpv.net-DW?&style=for-the-badge&color=%23756dab&logo=readme&logoColor=white">
<img src="https://img.shields.io/badge/Support-Windows%20x64-%230094ff.svg?style=for-the-badge&logo=Windows">
</p>

# 简介
🔳mpv.net-DW：mpv.net_CM的个人定制版

🔲mpv.net_CM：mpv.net的中文分支模组

🔲mpv.net：基于mpv开源播放器的Windows媒体播放器

# DW版本特点
> 基于上游，做出以下个人定制款

☑️修改播放界面为ModernX（cyl0/ModernX）

☑️集成缩略图引擎thumbfast（po5/thumbfast）

☑️集成旧版懒人包里的SVP补帧插件（hooke007/MPV_lazy）

☑️修改右键菜单  
- 修改部分翻译（参考potplayer）
- 修改排列顺序
- 修改预设组的vs滤镜和着色器方案，兼容更多显卡
		
☑️修改部分mpv设置  
- 默认硬件解码为auto-copy
- 默认OSD显示为建议方案
- 默认音量为100
- 默认开启interpolation
- 默认开启icc色彩管理
- 默认模糊识别音频与字幕
- 修改srt字幕样式
- 不显示mpv.net的logo和特别版logo（否则会闪现原始logo）
		
☑️修改部分快捷键设置（参考potplayer，用习惯了）  
- 文件详细信息 — TAB
- 打开字幕 — l

☑️自解压安装包封装

☑️一些其他细节

# 上游版本特点
> 引用自hooke007/mpv.net_CM

### 🔘mpv.net_CM：
- 界面汉化
- 编辑器选项修改
- 菜单条目+初始快捷键修改
- 集成Python+VapourSynth便携式组件
- 预设脚本与着色器
- 操作习惯移植自mpv-lazy
- 有更友好的界面操作性

### 🔘mpv.net：
- 几乎所有mpv的功能都可用，除去一些窗口行为
- 兼容几乎所有mpv脚本/着色器，除去部分具有特定依赖的项目
- 单实例/多实例切换
- 支持基础操作的播放列表、音轨字幕轨列表面板
- 图形化的设置修改与快捷键编辑器
- 可自定义的右键菜单
- 音量、窗口尺寸的退出时记忆

# 预览
### ⭕osc显示预览
![预览图01](https://user-images.githubusercontent.com/125502871/220343125-74366dd1-af9e-41a3-81e4-f1f06328a881.jpg)

### ⭕srt字幕预览
![预览图02](https://user-images.githubusercontent.com/125502871/224633362-a53dc9d0-aee6-4802-8213-daa1383febc9.jpg)

### ⭕右键菜单
![预览图03](https://user-images.githubusercontent.com/125502871/221334160-ce3310fa-b8bb-4258-a76c-992cd1467f39.jpg)
![预览图04](https://user-images.githubusercontent.com/125502871/221334168-57b9a765-2a77-4be5-ac54-e0f5abe7b82c.jpg)
![预览图05](https://user-images.githubusercontent.com/125502871/222751934-2ffc0619-381e-454c-93c7-82fd8b005300.jpg)

### ⭕设置界面
![预览图06](https://user-images.githubusercontent.com/125502871/220125827-6a33ee6d-14a9-40fa-ae0c-733f6760f7b4.jpg)
![预览图07](https://user-images.githubusercontent.com/125502871/220144657-50817726-37f3-41c5-87be-9e50ca5a4cca.jpg)
![预览图08](https://user-images.githubusercontent.com/125502871/224598109-f36722d6-ebca-4d44-9113-63fadb079be3.jpg)

# 更新
- libmpv-2-x86_64 [<shinchiro_20230312>](https://sourceforge.net/projects/mpv-player-windows/files/libmpv)
- MediaInfo [<v22.12>](https://mediaarea.net/en/MediaInfo/Download/Windows)
- Python-embed-amd64 [<3.10.9>](https://www.python.org/downloads)
- VapourSynth-portable [<git_R_61>](https://github.com/vapoursynth/vapoursynth/releases)
- yt-dlp [<git_2023.03.04>](https://github.com/yt-dlp/yt-dlp/releases)
- ModernX [<git_0.6.0>](https://github.com/cyl0/ModernX/releases)
- Thumbfast [<git_20221116>](https://github.com/po5/thumbfast)
- 视频滤镜与着色器 [<git_mpv-lazy-2023V2>](https://github.com/hooke007/MPV_lazy/releases)

# 安装
> 不可使用覆盖旧版文件的形式进行更新，请提前做好个人配置的备份

> 如需使用默认的srt字幕字体，请下载并安装[得意黑](https://github.com/atelier-anchor/smiley-sans)开源简体中字（不安装并不影响正常显示）

- 下载并安装[.NET framework 4.8](https://support.microsoft.com/zh-cn/topic/%E9%80%82%E7%94%A8%E4%BA%8E-windows-%E7%9A%84-microsoft-net-framework-4-8-%E8%84%B1%E6%9C%BA%E5%AE%89%E8%A3%85%E7%A8%8B%E5%BA%8F-9d23f658-3b97-68ab-d013-aa3c3e7495e0)运行库（win10 1903及之后版本的系统内已集成）
- 删除原有mpv.net-DW
- 下载并安装最新版mpv.net-DW
- 运行mpvnet.exe

# 下载
见网页端右侧Releases或移动端下方Releases

# 鸣谢
感谢hooke007编写的mpv.net_CM，和各项说明；感谢cyl0编写的ModernX osc；感谢po5编写的thumbfast；感谢tsl0922编写的ImPlay，使thumbfast可以在mpvnet上使用
