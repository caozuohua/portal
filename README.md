# Portal — 个人项目统一门户

> **在线地址：[https://caozuohua.github.io/portal/](https://caozuohua.github.io/portal/)**

## 简介

个人 GitHub 开源项目的统一 Landing Page，集中展示所有核心项目和工具。暗色主题 + 渐变动画设计，响应式布局适配桌面和移动端。

## 结构

- **Featured 核心项目** — 5 个重点项目的详细介绍卡片
  - ⚡ 电力数字化案例集（483 案例 · 交互式世界地图）
  - 💰 基金组合分析（AI 驱动 · 每周自动报告）
  - 🎁 免费资源聚合（97 资源 · 自动验证）
  - 📝 技术博客（Hugo 驱动）
  - 🎮 克劳德克拉夫特（MMO 网页游戏）
- **全部项目** — 12 个 GitHub 仓库小卡片网格
- **关于** — 个人介绍 + 统计数据

## 技术栈

- 纯静态 HTML/CSS/JS，零依赖
- Google Fonts（Noto Sans SC）
- CSS 自定义属性 + 动画
- GitHub Pages 自动部署

## 本地开发

```bash
# 直接用浏览器打开
open index.html

# 或启动本地服务器
python3 -m http.server 8080
```

## 部署

推送到 `main` 分支后 GitHub Pages 自动构建：

```bash
git add -A
git commit -m "update"
git push
```

访问地址：`https://caozuohua.github.io/portal/`

## 关联项目

| 项目 | 地址 | 说明 |
|------|------|------|
| 电力数字化案例集 | [caozuohua.github.io/power-digital-cases](https://caozuohua.github.io/power-digital-cases/) | 全球电力行业数字化案例 |
| 基金组合分析 | [caozuohua.github.io/fund-portfolio-analyzer](https://caozuohua.github.io/fund-portfolio-analyzer/) | AI 驱动基金持仓分析 |
| 免费资源聚合 | [caozuohua.github.io/free-resources](https://caozuohua.github.io/free-resources/) | 全球免费资源精选 |
| 技术博客 | [caozuohua.github.io](https://caozuohua.github.io) | Hugo 博客 |
| 魔兽世界游戏 | [world-of-claudecraft.vercel.app](https://world-of-claudecraft.vercel.app) | Three.js MMO 游戏 |

## License

MIT
