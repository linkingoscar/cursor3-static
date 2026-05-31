# Cursor 3.x 完整功能介绍 (纯静态版)

> 🖥️ 一个精美的 Cursor 3.x 功能介绍静态网站，支持中英文切换、暗色模式、PWA 离线访问

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

## ✨ 特性

- 🌙 暗色模式（自动跟随系统 + 手动切换）
- 🌐 中英文双语支持
- 🍎 Apple 风格滚动动画
- 📱 响应式设计（桌面 / 平板 / 手机）
- ⚡ PWA 离线支持
- 🖨️ 打印优化样式
- ♿ 无障碍访问（ARIA 标签）
- 🔍 SEO 优化（Open Graph、结构化数据）

## 📁 文件结构

```
cursor3-static/
├── index.html              # 中文首页 (40KB)
├── en/
│   └── index.html          # 英文首页
├── assets/
│   ├── css/style.css       # 样式
│   └── js/main.js          # 脚本
├── manifest.json           # PWA 配置
├── sw.js                   # Service Worker
├── README.md               # 项目说明
├── CHANGELOG.md            # 修改日志
└── LICENSE                 # MIT 许可证
```

## 📋 内容板块

| 板块 | 说明 |
|------|------|
| 🎯 Hero | 产品定位、官方链接 |
| ✨ 亮点速览 | Agents Window、Design Mode、MCP 等 |
| 🆕 新功能 (3.1-3.2) | Canvases、Multitask、Worktrees、SDK |
| 🎬 影像 | B 站教程、官方文档链接 |
| 📅 版本演进 | 1.x → 2.0 → Composer 2 → 3.0 时间线 |
| 💰 定价方案 | Hobby / Pro / Pro+ / Ultra / Teams |
| ⚔️ 竞品对比 | Cursor vs Copilot vs Claude Code (14 维度) |
| 🚀 如何体验 | 快速上手指南 |

## 🚀 快速开始

### 本地预览（最简单）

直接双击 `index.html` 用浏览器打开即可。

### 本地服务器

```bash
# Python
python -m http.server 8000

# Node.js
npx serve .

# PHP
php -S localhost:8000
```

然后访问 http://localhost:8000

## 🌐 部署指南

### GitHub Pages（推荐）

1. 进入仓库 **Settings** → **Pages**
2. Source 选择 `Deploy from a branch`
3. Branch 选择 `main`，文件夹选择 `/ (root)`
4. 点击 **Save**
5. 等待 1-2 分钟，访问 `https://linkingoscar.github.io/cursor3-static/`

### Netlify

1. 登录 [Netlify](https://netlify.com)
2. 点击 **"New site from Git"**
3. 选择 GitHub 仓库 `cursor3-static`
4. Build command 留空
5. Publish directory 填写 `.`
6. 点击 **Deploy site**

### Vercel

1. 登录 [Vercel](https://vercel.com)
2. 点击 **"New Project"**
3. 导入 GitHub 仓库 `cursor3-static`
4. Framework Preset 选择 **"Other"**
5. 点击 **Deploy**

### Cloudflare Pages

1. 登录 [Cloudflare Dashboard](https://dash.cloudflare.com)
2. 进入 **Pages** → **Create a project**
3. 连接 GitHub 仓库
4. Build settings 留空（纯静态）
5. 点击 **Save and Deploy**

## 🌍 浏览器支持

| 浏览器 | 版本 |
|--------|------|
| Chrome | 90+ |
| Firefox | 88+ |
| Safari | 14+ |
| Edge | 90+ |

## 📊 性能

- ⚡ 首屏加载 < 1s
- 📦 总资源大小 < 100KB
- 🎯 Lighthouse 评分 95+

## 🤝 贡献

欢迎提交 Issue 和 Pull Request！

1. Fork 本仓库
2. 创建特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交改动 (`git commit -m 'Add AmazingFeature'`)
4. 推送分支 (`git push origin feature/AmazingFeature`)
5. 打开 Pull Request

## 📝 数据来源

- [Cursor Changelog](https://cursor.com/changelog) - 官方更新日志
- [Cursor Blog](https://cursor.com/blog) - 官方博客
- [Cursor Pricing](https://cursor.com/pricing) - 官方定价
- [Cursor Docs](https://cursor.com/docs) - 官方文档

## 📄 许可证

本项目基于 MIT 许可证开源 - 详见 [LICENSE](LICENSE) 文件

---

⭐ 如果觉得有用，给个 Star 支持一下！
