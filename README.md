# vue
2.0


|目录/文件|说明|
|:-:|:-:|
|build|项目构建(webpack)相关代码|
|config|配置目录，包括端口号等。我们初学可以使用默认的|
|node_modules|npm 加载的项目依赖模块|
|src|这里是我们要开发的目录，基本上要做的事情都在这个目录里。里面包含了几个目录及文件：<br>- assets:放置一些图片，如logo等<br>- components:目录里面放了一个组件文件，可以不同<br>- App.vue:项目入口文件，我们也可以直接将组件写这里，而不使用components目录<br>- main.js:项目的核心文件|
|static|静态资源目录，如图片、文字等|
|test|初始测试目录，可删除|
|.xxxx文件|这些是一些配置文件，包括语法配置，git配置等|
|index.html|首页入口文件，你可以添加一些meta信息或统计代码啥的|
|package.json|项目配置文件|
|Readme.md|项目的说明文档，markdown格式|

创建vue项目
npm install -g vue-cli
vue init webpack vue_demo
cd vue_demo
npm install
npm run dev
访问: http://localhost:8080/