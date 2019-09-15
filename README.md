# taroDemo

全局安装 Taro 开发工具 @tarojs/cli

npm install -g @tarojs/cli

在要创建项目的目录下，创建项目：

taro init test

以微信小程序为例，创建项目完毕，要运行项目,则如下：

npm run dev:h5

npm run dev:weapp

当项目在运行时，在项目目录下dist文件中可以看到编译的小程序代码，打开微信小程序开发工具，就可以边开发边在微信小程序开发工具中看到效果

打包项目：

npm run build:weapp
