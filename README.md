# Clawd Animation Gallery

Clawd 是 Claude Code 的官方吉祥物——一只像素风的小螃蟹。这个项目包含一系列独立的 HTML 像素动画文件，展示 Clawd 在各种场景中的可爱动作。

## 动画列表

| 文件 | 场景 |
|------|------|
| `clawd-desk-work.html` | Clawd 在电脑前工作，灵感来时灯泡亮起 |
| `clawd-fishing.html` | Clawd 站在岸边用直鱼竿钓鱼 |
| `clawd-beach-walk.html` | Clawd 在沙滩上散步 |
| `clawd-bedtime.html` | Clawd 准备睡觉 |
| `clawd-birthday.html` | Clawd 庆祝生日 |
| `clawd-coconut-sip.html` | Clawd 喝椰子水 |
| `clawd-guitar.html` | Clawd 弹吉他 |
| `clawd-icecream.html` | Clawd 吃冰淇淋 |
| `clawd-kiss.html` | Clawd 送飞吻 |
| `clawd-lilypad.html` | Clawd 躺在睡莲上 |
| `clawd-treasure.html` | Clawd 挖宝箱 |
| `clawd-volleyball.html` | Clawd 打排球 |
| `gallery.html` | 合集展示页，所有动画同时播放 |

## 使用方式

每个 HTML 文件是自包含的（零外部依赖），直接在浏览器中打开即可观看动画。

```sh
open clawd-fishing.html
```

或打开 `gallery.html` 一次性浏览全部动画。

## 技术特点

- 纯 HTML/CSS/JavaScript，单文件自包含
- 像素风渲染（`image-rendering: pixelated`）
- Canvas 驱动，requestAnimationFrame 循环
- 5 秒循环动画，带缓动函数和粒子系统
- Clawd 造型：14×8 像素格，珊瑚橙 #CD6E58，扁平宽体

## 项目结构

```
clawd-animation/
├── clawd-beach-walk.html
├── clawd-bedtime.html
├── clawd-birthday.html
├── clawd-coconut-sip.html
├── clawd-desk-work.html
├── clawd-fishing.html
├── clawd-guitar.html
├── clawd-icecream.html
├── clawd-kiss.html
├── clawd-lilypad.html
├── clawd-treasure.html
├── clawd-volleyball.html
├── gallery.html
└── README.md
```
