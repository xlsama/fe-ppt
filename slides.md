---
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://cover.sli.dev
# some information about your slides (markdown enabled)
title: 前端技术分享
# apply UnoCSS classes to the current slide
class: text-center
# https://sli.dev/features/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/features/mdc
mdc: true
monaco: true
fonts:
  sans: Roboto
  serif: Roboto Slab
---

# 前端技术分享

---

# 什么是前端?

前端（Front-end） 指的是互联网产品中直接面向用户的部分。它是用户能看到、听到、触摸到并进行交互的界面总和，也被称为“客户端”。

## 前端的应用领域

<div class='grid grid-cols-2'>
<div>

- <span v-mark="{ type: 'circle', color: 'orange', at: 1 }">Web</span>

- <span v-mark="{ type: 'circle', color: 'orange', at: 6 }">移动端 App</span>

- <span v-mark="{ type: 'circle', color: 'orange', at: 8 }">桌面端 App</span>

- <span v-mark="{ type: 'circle', color: 'orange', at: 10 }">小程序</span>

- <span v-mark="{ type: 'circle', color: 'orange', at: 11 }">CLI(命令行界面)</span>

- <span>游戏</span>

</div>

<div>

<div 
  v-click 
  v-show="$clicks === 1" 
  v-motion   
  :initial="{ x: 80 }"
  :enter="{ x: 0 }"
  :leave="{ x: -80 }"
>

管理系统

![Web Screenshot](https://static.wildfirechat.cn/user-list.png)

</div>

<div 
  v-click 
  v-show="$clicks === 2" 
  v-motion   
  :initial="{ x: 80 }"
  :enter="{ x: 0 }"
  :leave="{ x: -80 }"
>

ChatGPT、豆包等 AI 助手

![Web Screenshot](https://static.wildfirechat.cn/user-list.png)

</div>

<div 
  v-click 
  v-show="$clicks === 3" 
  v-motion   
  :initial="{ x: 80 }"
  :enter="{ x: 0 }"
  :leave="{ x: -80 }"
>

官网

![Web Screenshot](https://static.wildfirechat.cn/user-list.png)

</div>

<div 
  v-click 
  v-show="$clicks === 4" 
  v-motion   
  :initial="{ x: 80 }"
  :enter="{ x: 0 }"
  :leave="{ x: -80 }"
>

电商平台

![Web Screenshot](https://static.wildfirechat.cn/user-list.png)

</div>

<div 
  v-click 
  v-show="$clicks === 5" 
  v-motion   
  :initial="{ x: 80 }"
  :enter="{ x: 0 }"
  :leave="{ x: -80 }"
>

娱乐、直播、流媒体

![Web Screenshot](https://static.wildfirechat.cn/user-list.png)

</div>

<div 
  v-click 
  v-show="$clicks === 6" 
  v-motion   
  :initial="{ x: 80 }"
  :enter="{ x: 0 }"
  :leave="{ x: -80 }"
>

移动端 App1

![Web Screenshot](https://static.wildfirechat.cn/user-list.png)

</div>

<div 
  v-click 
  v-show="$clicks === 7" 
  v-motion   
  :initial="{ x: 80 }"
  :enter="{ x: 0 }"
  :leave="{ x: -80 }"
>

移动端 App2

![Web Screenshot](https://static.wildfirechat.cn/user-list.png)

</div>

<div 
  v-click 
  v-show="$clicks === 8" 
  v-motion   
  :initial="{ x: 80 }"
  :enter="{ x: 0 }"
  :leave="{ x: -80 }"
>

桌面端 App1

![Web Screenshot](https://static.wildfirechat.cn/user-list.png)

</div>

<div 
  v-click 
  v-show="$clicks === 9" 
  v-motion   
  :initial="{ x: 80 }"
  :enter="{ x: 0 }"
  :leave="{ x: -80 }"
>

桌面端 App2

![Web Screenshot](https://static.wildfirechat.cn/user-list.png)

</div>

<div 
  v-click 
  v-show="$clicks === 10" 
  v-motion   
  :initial="{ x: 80 }"
  :enter="{ x: 0 }"
  :leave="{ x: -80 }"
>

小程序

![Web Screenshot](https://static.wildfirechat.cn/user-list.png)

</div>

<div 
  v-click 
  v-show="$clicks === 11" 
  v-motion   
  :initial="{ x: 80 }"
  :enter="{ x: 0 }"
  :leave="{ x: -80 }"
>

CLI(命令行界面)

![Web Screenshot](https://static.wildfirechat.cn/user-list.png)

</div>

<div 
  v-click 
  v-show="$clicks === 12" 
  v-motion   
  :initial="{ x: 80 }"
  :enter="{ x: 0 }"
  :leave="{ x: -80 }"
>

CLI(命令行界面)2

![Web Screenshot](https://static.wildfirechat.cn/user-list.png)

</div>

</div>
</div>

---

# 前端技术栈

- HTML
- CSS
- JavaScript
- TypeScript
- React
- Vue
- Angular
- Svelte
- Next.js
