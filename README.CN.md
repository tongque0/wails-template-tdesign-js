
# Wails 模板 TDesign (JS)

[English](./README.md)

## 关于

- 这个项目是 [Wails](https://wails.io/) 的模板。
- 它使用了 [TDesign](https://tdesign.tencent.com/) 框架。
- 以下选项用于生成前端：
    - Vite 5
    - Vue 3
    - JavaScript
    - Vue Router
    - Pinia 用于状态管理
    - TDesign UI 组件
    - Axios 用于 HTTP 请求
    - ESLint 用于代码检查
    - Prettier 用于代码格式化

## 实时开发

要以实时开发模式运行，首先在项目目录中运行 `wails dev`。然后，在另一个终端中，导航到 `frontend` 目录并运行 `npm run dev`。前端开发服务器将在 http://localhost:34115 上运行。您可以在浏览器中连接到此地址以访问您的应用程序。

> 注意：TDesign 开发服务器手动配置为在端口 :5173 上运行，以便与 Wails 正常工作。如果需要更改，请相应地调整 `vite.config.js` 和 `wails.json` 中的配置。

## 构建

要构建可分发的生产模式包，请使用 `wails build`。
