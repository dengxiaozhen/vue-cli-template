# vue-cli-template

## 简介
由于官方脚手架构建环境比较单一，只有开发环境和生产环境，没有测试环境。如果测试环境的接口地址和生产环境接口不一致，在正式上线得手动修改接口地址前缀，极其不方便。

## 开发

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:7777
npm run dev

```
浏览器访问 http://localhost:8080

## 发布
``` bash
# 构建测试环境
npm run build:test

# 构建生产环境
npm run build
```

#### 目录

``` bash
├── build
│   ├── build.js
│   ├── check-versions.js
│   ├── logo.png
│   ├── utils.js
│   ├── vue-loader.conf.js
│   ├── webpack.base.conf.js
│   ├── webpack.dev.conf.js
│   └── webpack.prod.conf.js
├── config
│   ├── dev.env.js        # 开发环境配置
│   ├── index.js
│   ├── prod.env.js       # 生成环境配置
│   └── test.env.js       # 测试环境配置
|
├── src                   # 开发目录
│   ├── api               # 接口
│   ├── assets            # 静态资源
│   ├── components        # 组件
│   ├── router            # 路由
│   ├── utils             # 工具
│   ├── App.vue           # 根组件
│   └── main.js           # 入口文件
├── static
├── LICENSE
├── favicon.ico
├── index.html
└── package.json
```

## 其他
``` bash
# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
