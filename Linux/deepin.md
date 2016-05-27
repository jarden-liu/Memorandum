deepin
================
>大多数软件可以参考ubuntu安装办法


##nodeJs安装
```bash
  sudo apt-get install curl
  curl -sL https://deb.nodesource.com/setup_4.x | sudo -E bash -       (nodeJs 4.x)
  curl -sL https://deb.nodesource.com/setup_6.x | sudo -E bash -       (nodeJs 6.x)
  sudo apt-get install --yes nodejs
```

##Atom
* 深度商店提供应用，版本较低。
* 从github下载高版本，Atom Atom-amd64.deb，双击安装或者`sudo dpkg --install atom-amd64.deb`
* 下载ubuntu的deb包安装即可
* [Atom](https://github.com/atom/atom)

##lantern
* 翻墙神器
* [lantern](https://raw.githubusercontent.com/getlantern/lantern-binaries/master/lantern-installer-beta-64-bit.deb)
* 安装完成运行会报错`/.lantern/bin/lantern: error while loading shared libraries: libappindicator3.so.1: cannot open shared object file: No such file or directory`
* 安装依赖
```bash
  sudo apt-get install libappindicator3-1
```

##chrome 谷歌浏览器 wps 搜狗输入法
* 默认应用


##网易云音乐
* `网易云音乐` 官网下载deepin deb安装包。
