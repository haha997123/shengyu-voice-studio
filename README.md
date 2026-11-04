# 声屿

**仅供个人娱乐，严禁商用。**

Windows 本地配音软件。当前完整版本：**1.4.6**。

## 下载安装

**[下载安装助手 Install-Shengyu.exe](https://github.com/haha997123/shengyu-voice-studio/releases/download/v1.4.6/Install-Shengyu.exe)** · [完整发布页](https://github.com/haha997123/shengyu-voice-studio/releases/tag/v1.4.6)

1. 下载并双击 `Install-Shengyu.exe`。
2. 选择安装位置，点击“开始安装”。安装器自动下载资源、断点续传、校验和解压。
3. 安装完成后打开声屿，之后可从桌面快捷方式启动。

**新电脑无需安装 Python，也无需手动解压、合并文件。**

首次下载约 **5.70GB**，完整安装约 **7.79GB**。
下载缓存和安装位置在同一磁盘时，建议预留 **18GB**。已下载内容会保留，断网后重新运行安装器可继续。
适用于 Windows 10/11 64 位 Intel/AMD 电脑，建议 16GB 内存；NVIDIA 显卡可用于本地配音加速。

发布页中的 `ShengyuData-*.bin` 是安装器自动下载的资源，**一般只需下载安装 EXE**。
如果要离线传给别人，将安装 EXE 和全部 `.bin` 放在同一个文件夹，运行 EXE 即可。
GitHub 自动生成的 `Source code` 附件不是软件安装包。

## 功能

- 曼波、派蒙、晓辰：本地配音；晓晓、云希等在线音色需要联网。
- F5-TTS v1 Base 声音模仿：导入音频或录制样音，核对文字后保存。
- 新音色自动命名，可改名、删除；音色可隐藏，并通过“已隐藏”恢复。
- SenseVoice-Small 离线语音输入：直接在文案框出字，无录音弹窗；支持选择麦克风。
- 识别模型在后台预热并复用，**只有点击录音按钮才打开麦克风**。
- 样音逐字文本中的数字默认使用中文写法，例如“一百二十三元”。
- 支持 TXT 导入、文案清空、试听，以及 MP3/WAV 导出。
- 淡蓝紫水晶风桌面界面。

本完整包不包含作者的录音、自建音色、隐藏偏好、运行日志或缓存。
旧版用户可安装到新目录，关闭软件后将自己的 `data` 文件夹迁移过去；请保留自己的原目录直到确认正常。

## 来源与许可

第三方组件包括 [GPT-SoVITS](https://github.com/RVC-Boss/GPT-SoVITS)、[F5-TTS](https://github.com/SWivid/F5-TTS)、[SenseVoice](https://github.com/FunAudioLLM/SenseVoice) 等。
F5-TTS 模型按 CC-BY-NC-4.0 使用，其他代码、模型及参考音频分别适用各自的许可和权利要求；来源和许可文件随安装包提供。
“仅供个人娱乐，严禁商用”不修改第三方许可证，也不代表获得额外的角色音色或真人录音授权。

## 完整性

安装器检查每个资源和整体压缩数据的 SHA256。各附件校验值见 [SHA256SUMS.txt](SHA256SUMS.txt)。

整体压缩数据 SHA256：`d394cbd1860cd33622c7c66fdb00f71275f1189ff762ebb6df7fae9b21615195`。
