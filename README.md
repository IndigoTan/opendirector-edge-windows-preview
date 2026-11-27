# OpenDirector + Edge · Windows Pika Preview

[下载安装包 / Download the preview](https://github.com/IndigoTan/opendirector-edge-windows-preview/releases/tag/windows-pika-preview-20261127)

Windows 本地 Pika 试用包：无需安装 Python、输入命令或配置 Codex/Claude。

模型许可排除欧盟、英国、韩国和美国，详见随附模型许可。

请下载下面的 **OpenDirector-v0.1.6-win-x64-unsigned.exe** 和 **edge-runtime.zip**，放在同一个文件夹，保留文件名，不要解压 ZIP。双击安装程序，打开 OpenDirector；首次启动会自动下载并校验约 119 MB 的视频工具。按首次设置向导选择模型目录并确认管理员授权。模型约 **146.82 GB**，首次下载需要时间和足够磁盘空间。完成后点击“直接使用本地 Pika 创作”。

已在 Windows RTX 5090 / 64 GB 内存上完成真实 Pika 生成及中英文播放、MP4 导出；安装版另外验证首次进入、播放导出和正常关闭。客户的 RTX 4070 / 12 GB 显存 / 32 GB 内存尚未实机验证。安装包未签名。这是供试用和反馈的预发布版本。

请先阅读 README.txt 与 VALIDATION.md。SHA256SUMS.txt 提供下载校验值。

---

Model licenses exclude the EU, UK, Republic of Korea and USA; see the accompanying licenses.

Download the EXE and edge-runtime.zip below into the same folder; keep their names and do not extract the ZIP. Run the installer and follow initial setup. Model originals require about 146.82 GB and administrator approval for setup. First launch downloads and verifies approximately 119 MB of media tools from their official publisher. No Python, terminal or coding assistant is required.

Real generation and bilingual playback/MP4 export were verified on Windows RTX 5090 / 64 GB RAM. Installed desktop onboarding, playback/export and normal window-close retirement were verified separately. RTX 4070 / 12 GB VRAM / 32 GB RAM is not qualified. This unsigned prerelease is intended for customer trials. See README.txt and VALIDATION.md for scope and limitations.

Edge sidecar 内 PyAV、FFmpeg 库及依赖的对应源码、构建材料见 `third-party-source.zip`；通常使用无需下载该源码包。

Corresponding source and build materials for PyAV, FFmpeg libraries and dependencies inside the Edge sidecar are provided in `third-party-source.zip`; ordinary use does not require this source archive.
