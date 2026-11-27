OpenDirector + Edge 本地 Pika · Windows 试用版

使用方法
1. 将安装程序与 edge-runtime.zip 下载到同一个文件夹；不要解压 edge-runtime.zip。
2. 双击安装程序。安装完成后打开 OpenDirector。
3. 首次设置时阅读模型许可、选择模型存放磁盘，并确认 Windows 管理员授权。
4. 等待原始模型下载及启动自检完成。模型约 146.82 GB，下载中断后可继续；请保持足够的磁盘空间和网络连接。
5. 在视频生成节点中选择本地 Pika，输入画面描述并提交。生成完成后可以播放，并将视频下载为 MP4。

无需安装 Python、输入终端命令或使用 Codex/Claude。首次设置需管理员授权；日常启动无需手动运行模型服务。
此试用版提供 480p、约 5 秒的文字生成视频与音频。它仍处于试用阶段，实际验证范围见随附 VALIDATION 文件；不要将其他显卡上的结果当作 RTX 4070 的性能保证。
关闭应用会请求停止其拥有的模型服务会话。Windows 应用卸载会保留机器级运行时、原始模型及用户项目；若需要清理或换版本，请联系提供此试用包的维护者。
若失败，请保留错误提示并反馈给维护者。不要删除模型目录或重复提交状态不明的生成任务。

OpenDirector + Edge local Pika · Windows preview

1. Download the installer and edge-runtime.zip into the same folder. Do not extract the ZIP.
2. Run the installer, then open OpenDirector.
3. Read the model license, select a model drive, and approve the Windows administrator prompt for initial setup.
4. Wait for the original model download and startup checks. Models occupy about 146.82 GB; interrupted downloads can resume.
5. Select local Pika in a video generation node, describe the scene, submit, then play and download the generated MP4.

No Python installation, terminal commands or AI coding assistant is required. Initial setup needs administrator authorization. Normal use does not require manually starting a model server.
The preview supports 480p text-to-video with audio, approximately five seconds. See VALIDATION for actual test coverage; results on other hardware do not qualify RTX 4070 compatibility or performance.
Closing the app requests retirement of its model-service session. Desktop uninstall preserves the machine runtime, original model files and projects. Contact the preview maintainer for cleanup or replacement. Preserve errors for diagnosis and do not blindly resubmit an unknown generation.
