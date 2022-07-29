---
nav:
  title: 开始使用
  order: 1
---

# 开始使用

Lazy Admin 是基于 Ant Design 和 ngx-formly 封装的一套中后台前端解决方案, 致力于在设计规范和基础组件的基础上，继续向上构建，提炼出典型模板/业务组件/配套设计资源，进一步提升企业级中后台产品设计研发过程中的『用户』和『设计者』的体验。

# 准备工作

由于国内网络和前端的特殊性，在安装依赖等方面可能会失败或导致无法启动，浪费大量的时间，因此我们推荐如下的技术栈来帮助我们顺畅的开发。

## 包管理器

推荐使用 yarn 来进行包管理，可以极大地减少 install 的时间和失败的概率，并且完全兼容 npm。

```shell
# 官方源
yarn config set registry https://registry.npmjs.org/

# 阿里源
yarn config set registry https://registry.npm.taobao.org/

# 腾讯源
yarn config set registry https://mirrors.tencent.com/npm/

# todo
```

# 初始化

安装依赖：

```shell
yarn
#
npm install
```

# 开发

### `server`

运行这个脚本会启动服务，自动打开默认浏览器展示你的页面。当你重新编辑代码后，页面还会自动刷新。

### `build`

运行这个脚本将会编译你的项目，你可以在项目中的 dist 目录中找到编译后的文件用于部署。

### `analyze`

analyze 脚本做的事情与 build 的相同，但是他会打开一个页面来展示你的依赖信息。如果需要优化性能和包大小，你需要它。

### `lint`

我们提供了一系列的 lint 脚本，包括 TypeScript，less，css，md 文件。你可以通过这个脚本来查看你的代码有哪些问题。在 commit 中我们自动运行相关 lint。

### `openApi`

运行这个脚本将会编译 swagger.json, 生成 angular client sdk。

### `text`

运行这个脚本将会执行测试用例。

### `source`

source 脚本和 analyze 脚本做的事情差不多, 都是用来分析项目的包大小, 以及相关依赖的大小
