---
layout: center
download: true
---

# React

<img id="react-logo" src="/react-logo.png" />


<style>
@keyframes react {
  to {
    transform: rotate(0deg);
  }
  from {
    transform: rotate(180deg);
  }
}
#react-logo {
  width: 100px;
  animation: react linear 3s infinite;
}
</style>

---

# 自我介紹

目前專研Kotlin, TypeScript\
每天承受Young佬的嘲諷\
目前正積極開發[`靠北南工+`](https://github.com/NTIHS-FK)\
與貢獻[`Deno_std`](https://github.com/xiaoxigua-1/deno_std)

---

# 使用前端框架的好處
- 更有邏輯的開發
  - 加入組件概念
- 加速開發速度
  - 現有library
- 好維護
  - 東西不用通通往JavaScript塞
- 提升效能
  - DOM更新統一由Farmework管理漸低無意義的DOM更新


---

# Node.js & Deno

## Node.js是什麼
- 運行JavaScript的環境

## Node.js & Deno的淵源
- 單純Ryan Dahl覺的Node.js非常不好用重新用Rust重寫
- Deno 是運行TypeScript & JavaScript的環境

---

# React 實做摟 ~~

打開[codesandbox.io](https://codesandbox.io/)

<img id="qrcode" src="/qrcode_codesandbox.io.png" />

<style>
#qrcode {
  width: 300px;
}
</style>


```jsx
// App.jsx
import React from 'react';

// Hello World component
export default function App() {
  return (
    <div>Hello World</div>
  );
}
```