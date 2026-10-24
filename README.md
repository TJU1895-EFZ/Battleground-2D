# 孤岛吃鸡 — 100人大逃杀

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![HTML5](https://img.shields.io/badge/HTML5-Game-orange)](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5)

> 100 人空降孤岛，只有 1 人能活到最后。

## 玩法

| 操作 | 按键 |
|------|------|
| 移动 | `W` `A` `S` `D` |
| 瞄准 | 鼠标 |
| 射击 | 鼠标左键 |
| 换弹 | `R` |
| 拾取武器 | `E` |
| 静音 | `M` |

## 特色

- **100 人 AI 混战** — 99 个智能人机互相厮杀，也会主动猎杀你
- **5 种武器** — 手枪、突击步枪、狙击枪、霰弹枪、冲锋枪，各有独特手感
- **毒圈机制** — 安全区逐轮收缩，逼迫玩家汇聚
- **程序化音频** — 零外部素材，Web Audio API 合成 BGM、枪声、音效
- **小地图** — 右下角实时显示全局态势

## 快速开始

### 本地运行

直接双击 `Battleground-2D.html` 用浏览器打开即可游玩，无需任何服务器或构建步骤。

### 在线预览

将 `Battleground-2D.html` 部署到任意静态托管（GitHub Pages、Vercel、Netlify 等）即可在线访问。

## 技术栈

| 层 | 技术 |
|----|------|
| 渲染 | HTML5 Canvas 2D |
| 音频 | Web Audio API（程序化合成） |
| 输入 | Keyboard + Mouse Events |
| 架构 | 单文件，零依赖 |

## 项目结构

```
Battleground-2D/
├── Battleground-2D.html   # 游戏主文件（全部逻辑 + 渲染 + 音频）
├── claude-tju.bat         # Claude Code 快捷启动脚本
└── README.md
```

## 许可

MIT License — 详见 [LICENSE](LICENSE) 文件。
