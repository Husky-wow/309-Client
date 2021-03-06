# vue

>前台

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).

配置信息
|-- build       // 项目构建(webpack)相关代码  
| |-- build.js              // 生产环境构建代码  
| |-- check-version.js      // 检查node、npm等版本  
| |-- utils.js              // 构建工具相关  
| |-- webpack.base.conf.js  // webpack基础配置  
| |-- webpack.dev.conf.js   // webpack开发环境配置  
| |-- webpack.prod.conf.js  // webpack生产环境配置  
|-- config    // 项目开发环境配置  
| |-- dev.env.js            // 开发环境变量  
| |-- index.js              // 项目一些配置变量  
| |-- prod.env.js           // 生产环境变量  
|-- src // 源码目录  
| |-- assets                // 图片样式文件  
| |-- components            // vue公共组件  
| |-- pages                 // 页面  
| |-- router                // 路由文件  
| |-- store                 // vuex的状态管理  
| |-- util                  // 公共js文件  
| |-- App.vue               // 页面入口文件  
| |-- main.js               // 程序入口文件，加载各种公共组件  
|-- static                  // 静态文件，比如一些图片，json数据等  
|-- .babelrc                // ES6语法编译配置  
|-- .editorconfig           // 定义代码格式  
|-- .gitignore              // git上传需要忽略的文件格式  
|-- README.md               // 项目说明  
|-- favicon.ico             // logo图标  
|-- index.html              // 入口页面  
|-- package.json            // 项目基本信息  

//image文件下的图片是用来展示在Readme.md文件下的，可忽略。

关于项目详细介绍   请参考以下博客，博客地址为：https://www.cnblogs.com/tzy1997/p/10963403.html

部分截图如下：


![Image](https://github.com/tzy13755126023/309-Client/blob/master/images/login-Client.png)

![Image](https://github.com/tzy13755126023/309-Client/blob/master/images/register-Client.png)

![Image](https://github.com/tzy13755126023/309-Client/blob/master/images/mine-Client.png)

![Image](https://github.com/tzy13755126023/309-Client/blob/master/images/client5.png)

![Image](https://github.com/tzy13755126023/309-Client/blob/master/images/我的收藏.png)

![Image](https://github.com/tzy13755126023/309-Client/blob/master/images/client1.jpg)

![Image](https://github.com/tzy13755126023/309-Client/blob/master/images/client2.png)

![Image](https://github.com/tzy13755126023/309-Client/blob/master/images/client3.jpg)

![Image](https://github.com/tzy13755126023/309-Client/blob/master/images/client4.png)
