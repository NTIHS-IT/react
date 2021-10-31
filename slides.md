---
layout: center
theme: unicorn
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
layout: intro
introImage: https://cdn.discordapp.com/avatars/458988300418416640/bb29b06043a8d3fee0079190c42cfbad.webp?size=4096
---

# 自我介紹

目前專研Kotlin, TypeScript\
每天承受Young佬的嘲諷\
目前正積極開發[`靠北南工+`](https://github.com/NTIHS-FK)\
與貢獻[`Deno_std`](https://github.com/xiaoxigua-1/deno_std)\
我的個人[`網站`](https://xiaoxigua-1.github.io)

<img id="myWebsite" src="/qrcode_xiaoxigua-1.github.io.png" />

<style>

#myWebsite {
  width: 300px;
}
</style>
---

# 使用前端框架的好處
- 更有邏輯的開發
  - 加入組件概念
- 加速開發速度
  - 現有library
- 好維護
  - 東西不用通通往JavaScript塞
- 提升效能
  - DOM更新統一由Farmework管理，漸低無意義的DOM更新


---

# Node.js & Deno

## Node.js是什麼
- 運行JavaScript的環境

## Node.js & Deno的淵源
- 單純Ryan Dahl覺的Node.js非常不好用重新用Rust重寫一個
- Deno 是運行TypeScript & JavaScript的環境

---

# React 實作摟 ~~

打開[codesandbox.io](https://codesandbox.io/)

<img id="qrcode" src="/qrcode_codesandbox.io.png" />

<style>
#qrcode {
  width: 300px;
}
</style>

---

# Hello World
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

---

# Plus and Minus Button

```jsx
import React, {useState} from 'react';
export default function App() {
  const [count, setCount] = useState(0);
  return (
    <div>
      {count}
      <br />
      <button
        onClick={() => {
          setCount(count + 1);
        }}
      >
        plus
      </button>
      <button
        onClick={() => {
          setCount(count - 1);
        }}
      >
        Minus
      </button>
    </div>
  );
}
```

---

# React component library

- Material-UI
- Ant Design
- React Bootstrap
- Grommet
- Rebass
- Blueprint
- Semantic UI React
- Retool

