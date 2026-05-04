# pycharm-arm64-deb

用于存放并发布 PyCharm arm64 .deb 的仓库。初始提交由脚本创建以便能发布 Release。
这个软件包将仅上传2026.1.1版本，如果需要最新版本的软件包，你可以自行修改软件包中内容并重新打包，别指望作者更新
更新步骤：
第一步，从官方网站中下载压缩包
第二步，解压压缩包
第三步，将压缩包的目录移动至opt目录并改名为pycharm-2026.1.1
卸载步骤：
第一步，执行sudo -i （可做可不做）
第二步，执行sudo apt purge pycharm -y
安装步骤：
第一步，下载安装包
第二步，假设存储安装包的目录在Download，运行sudo apt install ./Download/pycharm*.deb -y
彩蛋：在浏览器打开这个链接：https://v.douyin.com/Z4yhqxIUJ24/，包让你笑个不停
