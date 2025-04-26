# linux-fonts
## 安装linux下必要的字体
- 解决WPS字体问题
- 提供命令行字体
- 安装部分windows下的字体
- 其他字体

完整的WIN10字体，可从[这里](https://gitee.com/atomlong/ttf-ms-win10)下载。

WPS字体[传送门](https://github.com/pengphei/wps-font-symbols)。

## 安装方法
```sh
sudo ./install.sh
```

字体将会安装在`/usr/share/fonts/linux_fonts`里面


如果运行mkfontscale命令时终端提示mkfontscale: command not found，则需要首先安装这个命令，安装方法如下：
```sh
# 使mkfontscale和mkfontdir命令正常运行
sudo apt-get install ttf-mscorefonts-installer
# 使fc-cache命令正常运行
sudo apt-get install fontconfig
```
