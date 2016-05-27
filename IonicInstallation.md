Ionic Installation
================
> Ionic installation process

##Installation
* install `node.js`
[node.js](https://nodejs.org/dist/)

* install `cordova` and `ionic` by npm
```bash
  npm install -g cordova ionic
```
* or
```bash
  sudo npm install -g cordova ionic
```

* if NPM is blocked by the Chinese Great Firewall,you can set npm registry to taobao.org
```bash
  npm config set registry https://registry.npm.taobao.org
  npm cache clean
```

* if you want to rollback the default config,set registry as follow
```bash
  npm config set registry http://registry.npmjs.org/
  npm cache clean
```



##ISSUE
* NODE-SASS BUILD ERROR
* if you got an error when node-sass installation,you should download the binary file [https://github.com/sass/node-sass-binaries](https://github.com/sass/node-sass-binaries).Then run as follow
```bash
  npm -g install ionic --SASS_BINARY_PATH=D:/win32-ia32-46_binding.node
```

* WATCH ERROR ENOSPC
```bash
  echo fs.inotify.max_user_watches=524288 | sudo tee -a /etc/sysctl.conf && sudo sysctl -p
```
