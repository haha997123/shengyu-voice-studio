# 声屿

**仅供个人娱乐，严禁商用。**

Windows 本地配音软件，当前版本 **1.4.8**。

## 下载安装

**[下载安装助手 Install-Shengyu.exe](https://github.com/haha997123/shengyu-voice-studio/releases/download/v1.4.8/Install-Shengyu.exe)** · [发布页](https://github.com/haha997123/shengyu-voice-studio/releases/tag/v1.4.8)

1. 下载并双击安装助手。
2. 选择安装位置，点击“开始安装”。资源自动下载、续传、校验并安装。
3. 完成后打开声屿，之后可从桌面快捷方式启动。

新电脑无需安装 Python，无需手动解压或合并 BIN。
首次完整下载约 **5.82GB**，安装约 **7.93GB**；同一磁盘建议预留 **18GB**。
安装器会自动使用“基础运行资源”和本版数据。发布页只需下载安装 EXE。
离线安装时，将 EXE 和全部 BIN 放在同一文件夹，再运行 EXE。
GitHub 自动生成的 Source code 附件不用于安装。

支持 Windows 10/11 x64，建议 16GB 内存；NVIDIA 显卡可用于本地声音模仿加速。

## 1.4.8 更新

- 文案框新增剪切、复制、粘贴和全选右键菜单，支持快捷键、方向键及 Esc。
- 菜单采用浅色圆角、图标和悬停反馈，粘贴可替换选中文字，支持撤销。

以下功能延续上一版：

- 新增鱼鱼酱、鱼鱼姐：本地 CPU 音色，安装后无需 API Key，可离线使用。
- 声音模仿的样音录制一次点击开始，支持默认/指定麦克风，有计时和音量反馈。
- 麦克风区域采用清晰的青色，按钮采用蓝色焦点和按下反馈。
- 配音生成显示当前阶段和用时；播放结束自动停止并恢复播放按钮。
- 保留 F5-TTS 本地声音模仿、SenseVoice-Small 离线语音输入、MP3/WAV 导出、音色改名/删除/隐藏与恢复。

曼波、派蒙、晓辰、鱼鱼酱、鱼鱼姐为本地音色；晓晓、云希等在线音色需要联网。
个人录音、自建音色和偏好位于自己的 `data` 文件夹，发布包不包含作者的这些数据。
旧用户可安装到新目录，关闭软件后迁移自己的 `data`，确认正常后再处理原目录。

## 来源与许可

[GPT-SoVITS](https://github.com/RVC-Boss/GPT-SoVITS)、[F5-TTS](https://github.com/SWivid/F5-TTS)、[SenseVoice](https://github.com/FunAudioLLM/SenseVoice)。
鱼鱼酱/鱼鱼姐来自 [dsh-pet-voice-fishy](https://github.com/bbfang2025-cyber/dsh-pet-voice-fishy)，保留上游模型卡；鱼鱼姐为上游实验音色。
F5-TTS 模型按 CC-BY-NC-4.0 使用；鱼鱼音色基于 Piper 中文 Xiao Ya medium/BZNSYP，限个人非商业使用。
其余代码、模型和音频分别适用各自许可，许可文件随软件提供。

## 完整性

安装器校验每个资源及整体数据的 SHA256。附件校验值见 [SHA256SUMS.txt](SHA256SUMS.txt)。
整体安装数据 SHA256：`a37f8bcd298f5cea895e48ed4bebbb751ecfb8ebe12e699c88c97bed7598d8ec`。
