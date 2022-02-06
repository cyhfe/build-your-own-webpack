---
sidebar_position: 1
---

# 自己实现一个打包工具

## 准备我们的 example ，作为打包的目标

```
├── bundle.js
└── example
  ├── entry.js
  ├── message.js
  └── name.js
```

```js title="entry.js"
import message from "./message"

console.log(message)
```

```js title="message.js"
import message from "./message"

console.log(message)
```

```js title="name.js"
import name from "./name"
export default `hello ${name}`
```

## 打包工具实现

```js title="bundle.js"

```
