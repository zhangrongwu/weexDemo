# **weexDemo**
####安装
* 安装 node.js   brew install node，使用淘宝的npm源
* cocoapods安装  [sudo gem install cocoapods](http://code4app.com/article/cocoapods-install-usage) 

* [Xcode IDE安装](https://developer.apple.com/)

* weexpack安装 npm install -g weexpack
* 创建一个应用 weexpack create weexDemo
* 安装依赖：cd appName && npm install
* 创建一个android应用 weexpack platform add android
* 创建一个iOS应用  weexpack platform add ios
* [嵌入已有项目](https://weex.apache.org/cn/guide/integrate-to-your-app.html)
 


####首次使用坑：
###Weex SDK 只提供渲染，而不是其他的能力，如果你需要 像网络，图片，URL跳转这些特性，需要自己动手实现他们
https://weex.apache.org/cn/v-0.10/advanced/index.html（这个文档比较全）
例如，如果你想实现一个url地址跳转函数，你可以按照如下步骤实现一个 Module
需要自己注册代理与实现代理回调


