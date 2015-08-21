title: Debug node.js addons in Visual Studio 2013
date: 2015-08-21 15:38:33
tags:
---
From to [site](http://computer-vision-talks.com/articles/how-to-debug-nodejs-addons-in-visual-studio/)!

## 安装
```
npm install node-gyp -g
```
```
npm install nan -g
```
下载 [nodejs code](https://nodejs.org/dist/v0.12.7/node-v0.12.7.tar.gz/)
```
vcbuild.bat debug nosign x64
```
![1](/img/debugnodejsaddons/compile.png)  
```
node-gyp configure rebuild --nodedir="D:\node-v0.12.7" --debug
```
![2](/img/debugnodejsaddons/node-gyp.png)  
After node-gyp finishes, a *.node file will be generated in /build/Debug/ folder.
![3](/img/debugnodejsaddons/vs-seting.png)    