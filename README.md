# Cursor 3.x 完整功能介绍 (纯静态版)

双击 `index.html` 即可打开预览，无需安装任何依赖。

## 文件结构

```
cursor3-static/
├── index.html              # 中文首页
├── en/
│   └── index.html          # 英文首页
├── assets/
│   ├── css/style.css       # 样式
│   └── js/main.js          # 脚本
├── manifest.json           # PWA 配置
├── sw.js                   # Service Worker
├── README.md               # 项目说明
└── CHANGELOG.md            # 修改日志
```

## 内容板块

| 板块 | 说明 |
|------|------|
| Hero | 产品定位、官方链接 |
| 亮点速览 | Agents Window、Design Mode、Agent Tabs、Worktree、Best-of-n、MCP |
| 新功能 (3.1-3.2) | Canvases、Multitask、Worktrees、Multi-root、SDK、Security Review、Team Marketplace、Bugbot |
| 影像 | B 站教程嵌入、官方文档链接 |
| 版本演进 | 1.x → 2.0 → Composer 2 → 3.0 时间线 |
| 定价方案 | Hobby / Pro / Pro+ / Ultra / Teams / Enterprise |
| 竞品对比 | Cursor vs Copilot vs Claude Code 14 维度对比 |
| 如何体验 | 快速上手指南 |

## 功能特性

- ✅ 暗色模式（右下角 🌙 按钮，自动跟随系统）
- ✅ 中英文切换（右上角 EN / 中文）
- ✅ Apple 风格滚动动画（Intersection Observer）
- ✅ 返回顶部按钮
- ✅ 响应式设计（桌面 / 平板 / 手机）
- ✅ PWA 离线支持
- ✅ 打印优化样式
- ✅ 无障碍访问（ARIA 标签、skip link）
- ✅ SEO 优化（Open Graph、结构化数据）

## 数据来源

- [Cursor Changelog](https://cursor.com/changelog) - 官方更新日志
- [Cursor Blog](https://cursor.com/blog) - 官方博客
- [Cursor Pricing](https://cursor.com/pricing) - 官方定价
- [Cursor Docs](https://cursor.com/docs) - 官方文档
- B 站视频为第三方创作者内容，非官方出品

## 使用方式

直接双击 `index.html` 用浏览器打开即可。

如需 PWA 离线功能，需要通过 HTTP 服务访问：

```bash
# Python
python -m http.server 8000

# 或 Node.js
npx serve .
```

## 浏览器支持

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

## 许可

本项目为静态演示站点，可自由修改与再发布。内容版权归原作者所有。
