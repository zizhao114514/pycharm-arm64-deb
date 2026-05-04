# pycharm-arm64-deb

本仓库用于存放并对外发布 PyCharm for ARM64 (.deb) 安装包的备份与 Release。当前已上传：PyCharm 2026.1.1 (arm64)。

主要用途
- 提供可下载的 PyCharm ARM64 .deb 发行包（方便在无法通过 JetBrains Toolbox 或 官网直接下载时使用）。
- 记录打包/上传流程与版本信息。

已发布版本
- pycharm-2026.1.1 (arm64) —— Release: https://github.com/zizhao114514/pycharm-arm64-deb/releases/tag/pycharm-2026.1.1

安装（示例）
1. 下载 release 中的 .deb 文件到本地（例如 ~/Downloads）。
2. 在终端中运行：
   sudo apt install ./Downloads/pycharm-*-arm64.deb -y

卸载（示例）
1. 删除包并清理配置：
   sudo apt purge pycharm -y
2. 如需删除残留文件，请手动移除 /opt/pycharm-* 或相关目录。

打包与更新流程（简要）
1. 从 JetBrains 官网或授权渠道下载对应版本。
2. 解压并放置到 /opt/pycharm-VERSION（可选）。
3. 使用 dpkg-deb 或打包脚本生成 .deb，然后创建 GitHub Release 并上传资产与签名。

安全与许可
- 本仓库仅存放二进制安装包的镜像与说明，版权与许可以 JetBrains 官方发布为准。请确保所使用的软件符合其授权条款。

联系与贡献
- 如需我方协助更新包、签名或发布流程，请在 issue 中说明需求。

