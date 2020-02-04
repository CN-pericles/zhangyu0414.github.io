# zhangyu0414.github.io.git

基于 React + React-router + ES6 前端项目

## 技术选型

* [react](https://github.com/facebook/react)
* [react-router](https://github.com/rackt/react-router)
* [webpack](https://github.com/webpack/webpack)
* [babel](https://github.com/babel/babel)
* [eslint](http://eslint.org)

## 目录结构

```
src/
  |-assets/             # 静态文件
     |- fonts/          # 字体
     |- images/         # 图片
     |- plugins/        # 插件
     |- styles/         # 样式
     |- ...
  |-components/         # 全局可复用的 UI 组件（presentational component）
     |- content.js
     |- footer.js
     |- navbar.js
     |- siderbar.js
     |- ...
  |-containers/         # 全局可复用的容器组件（container component）
     |- empty.js
     |- main.js
     |- notfound.js
     |- ...
  |-routes/             # 主路由和异步分割点
     |- index.js
     |- ...
  |-utils/              # 工具方法
     |- resume.js
     |- ...
  |- app.js             # 入口文件
  |- ...
```

## 使用方法

```sh
$ git clone https://github.com/zhangyu0414/zhangyu0414.github.io.git
$ cd zhangyu0414.github.io.git
$ npm install
$ npm start
```

|`npm run <script>`|描述|
|------------------|-----------|
|`start`|服务启动在 3000 端口，代码热替换开启。|
|`build`|编译程序到 build 目录下（默认目录 ~/build）。|
|`lint`|检查所有 .js 文件是否规范。[更多](http://eslint.org/docs/user-guide/command-line-interface.html#fix)|

## 贡献

有任何意见或建议都欢迎提 issue

## License

MIT
