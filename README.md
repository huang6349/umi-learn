# umi-learn

[![](https://img.shields.io/badge/umi-^1.0.0-blue.svg?style=flat-square)](https://github.com/facebook/react)

学习umi

## 目录

- [初始化项目](./docs/初始化项目.md)

## 项目结构说明

```bash
├── dist/                          // 默认的 build 输出目录
├── mock/                          // mock 文件所在目录，基于 express
├── src/                           // 源码目录，可选
│ ├── assets/                      // 静态资源，编译时copy至dist目录
│ ├── components/                  // UI组件及UI相关方法
│ ├── models/                      // 全局数据模型(默认加载)
│ ├── pages/                       // 页面目录，里面的文件即路由
│ │ ├── .umi/                      // dev 临时目录，需添加到 .gitignore
│ │ └── .umi-production/           // build 临时目录，会自动删除
│ ├── services/                    // 数据接口
│ ├── utils/                       // 工具函数
│ │ └── request.js                 // 异步请求函数
│ ├── global.css                   // 约定的全局样式文件，自动引入，也可以用 global.less
│ └── global.js                    // 可以在这里加入 polyfill
├── .eslintrc                      // Eslint配置
├── .gitignore                     // Git配置
├── .umirc.js                      // umi 配置
├── LICENSE                        // 开源协议
├── package.json                   // 项目信息
├── README.md                      // 项目描述
└── yarn.lock                      // 项目信息
```

## 相关教程

- [官网 - UmiJS](https://umijs.org/)
- [官网 - Yarn](https://yarnpkg.com/zh-Hans/)
- [官网 - DvaJS](https://dvajs.com/)
- [官网 - Ant Design](https://ant.design/index-cn/)
- [官网 - React](https://reactjs.org/)
- [中文网 - React](https://doc.react-china.org/)
- [Github - UmiJS](https://github.com/umijs/umi/)
- [Github - DvaJS](https://github.com/dvajs/dva/)
- [Github - roadhog](https://github.com/sorrycc/roadhog/)

## 开源协议

[MIT](https://tldrlegal.com/license/mit-license)
