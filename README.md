# vwn-综合后台框架
vwn-基于vuejs2.5-elementUI2.2-webpack3.9的一套前端综合后台框架

**本项目是后台管理框架，集成了权限管理、登录功能、UI组件、上传等功能，建议直接使用。**
> **注意**：便于前端调试，所以数据请求都是用了mockjs模拟。**在需要请求外部api时请移除mock文件**。

## Features 特性
```
- **工业化UI组件**（上手即用，无需自己造轮子）
- `登录/注销`
- `权限验证`
- **👉多TAB导航**（没有多TAB怎么能称为后台管理界面呢？）
- `Tinymce 编辑器`
- `Markdown 编辑器`
- `动态侧边栏`（支持多级路由）
- 面包屑导航
- JSON展示组件
- echartjs图表
- 404错误页面
- **表格数据直接导出cvs**
- mock数据
- 炫酷hover特效
```
## Run 开发 
```bash
    # 克隆项目
    git clone https://gitee.com/QCBZ/vwn.git

    # 安装依赖
    npm install
    //or # 建议不要用cnpm  安装有各种诡异的bug 可以通过如下操作解决npm速度慢的问题
    npm install --registry=https://registry.npm.taobao.org


    # 本地开发 开启服务
    npm run dev


```
浏览器访问 http://localhost:80

## Build 发布
```bash
    # 发布
    npm run build

```
## FileTree 目录结构
```shell
├── doc                        // 项目文档 
├── build                      // 构建相关  
├── config                     // 配置相关
├── src                        // 源代码
│   ├── api                    // 所有请求
│   ├── assets                 // 静态资源文件
│   ├── icons                  // ico图标
│   ├── components             // 全局UI组件
│   ├── mock                   // mock数据
│   ├── lang                   // 语言包
│   ├── vendor                 // 第三方包
│   ├── router                 // 路由
│   ├── store                  // 全局store管理
│   ├── utils                  // 全局公用方法
│   ├── styles                 // 全局样式
│   ├── views                  // view界面
│   │    ├── dashboard         //图表组件
│   │    ├── layout            //框架布局组件
│   │    ├── vwn               //示例
│   │    ├── login             //登录界面
│   │    ├── errorPage         //错误界面
│   │    └── permission        //权限测试界面
│   ├── App.vue                // 入口页面
│   └── main.js                // 入口 加载组件 初始化等
│   └── permission.js          // 权限 加载组件 初始化等
│   └── errorLog.js            // 错误日志 加载组件 初始化等
├── static                     // 静态资源
├── .babelrc                   // babel-loader 配置
├── eslintrc.js                // eslint 配置项
├── .gitignore                 // git 忽略项
├── favicon.ico                // favicon图标
├── index.html                 // html模板
└── package.json               // package.json

```

## Views 整体界面

!["整体界面"](https://gitee.com/QCBZ/vwn/raw/master/doc/images/1.png)
!["整体界面"](https://gitee.com/QCBZ/vwn/raw/master/doc/images/2.png)
!["整体界面"](https://gitee.com/QCBZ/vwn/raw/master/doc/images/3.png)



如果您觉得此项目对您有价值，给作者赏一杯咖啡钱吧，哈哈哈。

<img src="https://gitee.com/QCBZ/vwn/raw/master/doc/images/wechat.JPG" align="left" width="300" height="400" alt="打开微信扫码赞赏吧">
<img src="https://gitee.com/QCBZ/vwn/raw/master/doc/images/alipay.JPG" align="left" width="300" height="400" alt="打开支付宝扫码赞赏吧">
