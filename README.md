# Clawd Animation Skill

> **本项目来自 [mmguo.dev/clawd](https://mmguo.dev/clawd/)**

Clawd 像素风动画项目 — 用于生成以 Claude Code 吉祥物 Clawd（像素风小螃蟹）为主角的自包含 HTML 动画。

**首次提交时间**: 2026 年 3 月 31 日

## 这个项目是干嘛的

这是一套 Claude Code 的自定义 Skill（技能），让 Claude Code 可以根据自然语言描述，自动生成 Clawd 小螃蟹的像素风动画。比如你说"clawd 吃冰淇淋"，它就会生成一个完整的、可以在浏览器直接打开的 HTML 动画文件。

包含两个版本：
- **clawd-animation** — 完整版，支持 4-8 秒的多阶段叙事动画（吃东西、撑伞、收信等）
- **clawd-animation-lite** — 轻量版，1-3 秒的快速动画（害羞、蹦跳、打招呼等），生成更快、消耗 token 更少

## 项目结构

```
clawd-animation-skill/
├── clawd-animation/
│   ├── SKILL.md              # 完整版 Skill 定义（动画规范、工作流程、设计规则）
│   └── references/
│       ├── template.html      # 动画引擎模板（所有动画基于此生成）
│       ├── ice-cream.html     # 参考范例：clawd 吃冰淇淋（5秒9阶段）
│       └── clawd-kiss.html    # 参考范例：用腮红和爱心表达情绪
├── clawd-animation-lite/
│   └── SKILL.md              # 轻量版 Skill 定义（内嵌精简模板）
├── .gitignore
└── README.md
```

## 怎么用

将 `clawd-animation/` 或 `clawd-animation-lite/` 文件夹放到 Claude Code 的 skill 目录中，然后在对话中描述你想要的动画场景即可。
