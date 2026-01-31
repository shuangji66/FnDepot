BitMeteor(比特流星)是为BitComet(比特彗星)二进制运行文件设计的飞牛软件通用框架，不包含BitComet的代码和文件。<br>

安装后前往"https://download.bitcomet.com/linux/"下载对应架构的最新deb安装包，放在应用文件/BitMeteor/app下，然后启动程序，程序会自动安装/升级/修复。<br>

1.0.0：初始版本<br>

1.1.0：软件重构：重写启动命令，重写升级/修复安装命令，修复进程停止后软链接残留，修复status定期触发脚本，增加webui入口切换<br>

目前问题：webui入口切换似乎不太灵，总会进入文字ui，可能和webui本身跳转逻辑有关？。

