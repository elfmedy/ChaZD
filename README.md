ChaZD
=====

ChaZD 查字典，简洁易用的英汉字典扩展程序，支持划词哦:)
翻译结果和发音朗读由**有道翻译**驱动。

获取
-----------
+ [Chrome 网上应用商店](https://chrome.google.com/webstore/detail/chazd/nkiipedegbhbjmajlhpegcpcaacbfggp) 
+ [crx 文件](https://github.com/ververcpp/ChaZD/blob/master/ChaZD.crx?raw=true)  

**注**：安装扩展后，第一次使用请刷新要查词的页面，划词功能才会生效；  
**注2**：非中文版Chrome浏览器的用户，如出现插件弹出窗口字体无法正常显示的情况，麻烦请更改浏览器的最小字号为12px
（具体步骤: settings-->show advanced settings-->Web content中的Customize fonts... -->Minimum font     size将最小字号改为12px）。

主要功能
-----------
+ 支持在线英汉互译
+ 提供英文单词和语句的英音、美音真人发音朗读
+ 支持网页内英文划词翻译
+ 可通过快捷键（Ctrl+Shift+F）快速启动词典扩展，也可以自定义快捷键
+ 可设置开启与关闭划词功能，并可选择划词结果的显示位置

截图
-----------
![Screenshoot 1](/screenshoot/screenshoot1.jpg)  
---
![Screenshoot 2](/screenshoot/screenshoot4.png)

修改代码及部署
-----------

确保你已经安装了[Node.js](http://nodejs.org/)以及[grunt-cli](https://github.com/gruntjs/grunt-cli),

下载代码并部署
```shell
git clone https://github.com/ververcpp/ChaZD.git
cd ChaZD && npm install   #安装部署依赖的包
grunt                     #部署代码
```

进入Chrome的扩展程序设置页面，点击“加载正在开发的扩展程序”，选择ChaZD目录

可以使用`grunt watch`实时更新修改的js、css文件并部署，
每次修改代码之后直接在浏览器的扩展程序设置页面重新加载ChaZD即可

-----------
部分功能设计借鉴于[TransIt](https://github.com/GDG-Xian/crx-transit)

源码完全开放，欢迎Star、Fork、提交BUG，并提出您宝贵的意见与建议。

本人实际修改代码的步骤
-----------
1.确保已经安装了Node.js以及grunt-cli

2.下载代码，安装依赖
```shell
git clone https://github.com/ververcpp/ChaZD.git
cd ChaZD && npm install   #安装部署依赖的包
```
3.修改代码，并且部署
```shell
grunt                     #部署代码
```
4.chrome扩展页面，选择开发者模式，然后选择“打包扩展程序”，选择 ChaZD 目录，会生成 ChaZD.crx 文件，将此文件拖拽到扩展程序页面，就会提示安装插件

5.修改程序的话，先卸载插件，然后修改程序，重复 3-4 步
