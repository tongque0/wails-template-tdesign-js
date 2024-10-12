
# Wails Template TDesign (JS)

[中文](./README.CN.md)

## Use

```
wails init -n "Your Project Name" -t https://github.com/tongque0/wails-template-tdesign-js
```

## About

- This project is a template for [Wails](https://wails.io/).
- It utilizes the [TDesign](https://tdesign.tencent.com/) framework.
- The following options were used to generate the frontend:
  - Vite 5
  - Vue 3
  - JavaScript
  - Vue Router
  - Pinia for state management
  - TDesign UI components
  - Axios for HTTP requests
  - ESLint for code linting
  - Prettier for code formatting

## Live Development

To run in live development mode, first run `wails dev` in the project directory. Then, in another terminal, navigate to the `frontend` directory and run `npm run dev`. The frontend development server will run on http://localhost:34115. You can connect to this in your browser to access your application.

> Note: The TDesign development server is manually configured to run on port :5173 to work properly with Wails. If this needs to be changed, please adjust the configuration in `vite.config.js` and `wails.json` accordingly.

## Building

To build a redistributable production mode package, use `wails build`.

