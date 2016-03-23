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
* if NPM is blocked by the Chinese Great Firewall,you can set npm config to taobao.org
```bash
  npm config set registry https://registry.npm.taobao.org
```
* if you want to rollback the default config,set the follow order
```bash
  npm config set registry http://registry.npmjs.org/
  npm cache clean
```
