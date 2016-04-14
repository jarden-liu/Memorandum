Ubuntu Software Installation
================
> 乌班图64位常用软件安装备忘

##QQ
* 国际版wineQQ比longene wineQQ稳定（亲测），直接用wine装QQ各种爆炸（不信可以去试试）～～
* 下载 国际版wineQQ [wine-qqintl.zip](http://yun.baidu.com/share/link?shareid=2983202140&uk=202032639) 下载之后安装里面的三个deb包。找到usr/share/application下的`QQ国际版`运行即可。
* 该版本为国际版QQ 2012版很稳定。
* 感觉版本低的同学可以在windows下安装新版的国际版QQ，拷贝windows下的新版国际版QQ文件夹覆盖到ubuntu 用户文件夹下的 .deepinwine/qqintl/drive_c/Program Files/Tencent目录。
* 再重新运行上述应用,即可启动新版的国际版QQ（相对2012版功能一点）。

##wechat 微信
* wine 微信输入框有bug，也没用大神修，放弃吧。
* 网页版微信吧～～

##nodeJs 4.x安装
```bash
  wget -qO- https://deb.nodesource.com/setup_4.x | sudo bash -
  sudo apt-get install --yes nodejs
```

##Atom
* 从github的Atom链接下载Atom-amd64.deb，双击通过应用商店安装或者`sudo dpkg --install atom-amd64.deb`
* [Atom-amd64.deb] (https://github-cloud.s3.amazonaws.com/releases/3228505/c9914f64-016c-11e6-9685-b660b0dc6b4e.deb?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAISTNZFOVBIJMK3TQ%2F20160414%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20160414T090923Z&X-Amz-Expires=300&X-Amz-Signature=52e8ee14d5a01bb1c29e050e6c5fa5003e8759a77f52ab780aadc07e51e4f93a&X-Amz-SignedHeaders=host&actor_id=11712343&response-content-disposition=attachment%3B%20filename%3Datom-amd64.deb&response-content-type=application%2Foctet-stream)

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
  sudo apt-get install --install-recommends winehq-deve
```
* 需要修复一下wine的中文乱码问题，可以打开winehq app库里面的网易云音乐描述，根据描述配置一下就可以完美运行啦

##wps
* 百度下载安装包即可

##深度音乐及其百度插件
* 百度咯
