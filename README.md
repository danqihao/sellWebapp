基于vue的仿饿了吗外卖web app
============================
This is a senior project for vue1.0.
----------------------------

## 运行项目

```
#install dependencies
npm install
#start the server http//localhost:8080 and run the code
npm run dev
```

使用用技术：vue1.x＋webpack1.x＋es6＋vue-resource＋vue-router＋css3＋html5
<br>

## 项目创建步骤

### 安装vue-cli脚手架工具

运行如下命令，即可创建项目sellwebapp，并通过本地8080端口启动项目
<br>
```
#see node version
node -v
#install vue-cli
npm install -g vue-cli
#see if vue - cli is installed successfully
vue
#check the vue template
vue list
#create the project sellwebapp using the webpack template and specify the use of vue1.0
vue init webpack#1.0 sellwebapp
#to the project directory
cd sellwebapp
#view all directories
ls -l -a
#install various dependencies on the project
npm install
#run the project
npm run dev
```

在运行 vue init webpack#1.0 sellwebapp后，需要依次输入以下配置项：
<br>
```
* 项目名称
* 项目描述
* 作者
* 选择vue构建项目
* 是否安装vue-router
* 是否使用ESLint
* 是否使用Karma + Mocha的单元测试
* 是否使用Nightwatch e2e测试
```

安装成功后，即可执行npm run dev运行项目。
<br>

## 项目功能模块

```
* 商品列表模块
* 商品详情模块
* 评价列表模块
* 商家详情模块
```

## License

The sellwebapp is available under the MIT license. See the LICENSE file for more info.


