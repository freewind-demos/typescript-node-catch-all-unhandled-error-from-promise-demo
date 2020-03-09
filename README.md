TypeScript Node Catch All Unhandled Error From Promise Demo
===========================================================

通过捕获`unhandledRejection`事件来捕获来自promise的未处理的error和rejection.

注意：
1. `throw new Error`和`reject()`效果一样
2. `setTimeout`中throw error不能被捕获，需要使用`uncaughtException`

```
npm install
npm run demo
```
