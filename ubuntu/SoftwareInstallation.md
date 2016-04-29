Ubuntu Software Installation
================
> 乌班图64位常用软件安装备忘


##nodeJs 4.x安装
```bash
  wget -qO- https://deb.nodesource.com/setup_4.x | sudo bash -
  sudo apt-get install --yes nodejs
```

##Atom
* 从github的Atom链接下载Atom-amd64.deb，双击通过应用商店安装或者`sudo dpkg --install atom-amd64.deb`
* [Atom-amd64.deb](https://github-cloud.s3.amazonaws.com/releases/3228505/c9914f64-016c-11e6-9685-b660b0dc6b4e.deb?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAISTNZFOVBIJMK3TQ%2F20160414%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20160414T090923Z&X-Amz-Expires=300&X-Amz-Signature=52e8ee14d5a01bb1c29e050e6c5fa5003e8759a77f52ab780aadc07e51e4f93a&X-Amz-SignedHeaders=host&actor_id=11712343&response-content-disposition=attachment%3B%20filename%3Datom-amd64.deb&response-content-type=application%2Foctet-stream)

##lantern
* 翻墙神器
* [lantern](https://raw.githubusercontent.com/getlantern/lantern-binaries/master/lantern-installer-beta-64-bit.deb)

##chrome 谷歌浏览器
* [google-chrome-stable](https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb)

##搜狗输入法
* 百度`搜狗输入法forlinux`进入官网下载deb安装包。（需要fcitx）

##网易云音乐
* 先安装wine最新版
```bash
  sudo dpkg --add-architecture i386
  sudo add-apt-repository ppa:wine/wine-builds
  sudo apt-get update
  sudo apt-get install --install-recommends winehq-devel
```
* 需要修复一下wine的中文乱码问题，可以打开winehq app库里面的网易云音乐描述，根据描述配置一下就可以完美运行啦

##wps
* 百度下载安装包即可

##深度音乐及其百度插件
* 百度咯
