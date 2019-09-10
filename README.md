ChaZD
=====

ChaZD 查字典，简洁易用的英汉字典扩展程序，支持划词哦:)
翻译结果和发音朗读由**有道翻译**驱动。

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

使用方法
-----------
下载仓库中的 ChaZD.crx，并拖拽到 chrome 页面，选择安装插件

如果遇到 提示 "crx required proof missing" 这样的错误，是因为高版本 chrome 提高了安装等级。可以按照如下步骤解决：

1.将 ChaZD.crx 改为 ChaZD.zip，然后解压缩到 "ChaZD" 目录

2.进入 chrome 扩展程序页面，选择开发者模式，选择 "加载已解压的扩展程序"，选中刚才解压缩的 ChaZD 目录，稍等几秒钟之后，插件就会安装了
