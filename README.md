# 📚 Coze Guide

> 将本地 PDF 教程文档一键转换为可在线访问的网页站点

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Enabled-brightgreen)]()
[![Cloudflare Pages](https://img.shields.io/badge/Cloudflare%20Pages-Deployed-blue)]()

## 🚀 在线预览

- **GitHub Pages**: https://anita-zq9jv.github.io/coze_guide/
- **Cloudflare Pages**: https://bcbebbba.cozeguide.pages.dev/

## 📖 项目简介

Coze Guide 是一个轻量级静态网页项目，用于把本地的教程、手册、文档类 PDF 内容转化为在线可浏览的网页形式。

**核心价值**：
- 无需服务器、无需数据库
- 免费部署，生成专属分享链接
- 解决 PDF 传输麻烦、移动端阅读体验差的问题

## ✨ 功能特性

- **纯静态部署** —— 零后端、零成本，加载速度快
- **响应式适配** —— 自动适配电脑、平板、手机
- **一键部署** —— GitHub Pages / Cloudflare Pages 免费上线
- **目录导航** —— 长文档快速定位
- **轻量无依赖** —— 原生 HTML/CSS/JS

## 📂 项目结构

```
.
├── index.html          # 主页面入口
├── _redirects          # Cloudflare Pages 路由配置
├── media/              # 图片资源
├── docx_extract/       # 文档提取工具
└── README.md           # 项目说明
```

## 🛠️ 本地运行

```bash
# Python 内置服务器
python -m http.server 8080

# 或 Node.js
npx serve .
```

访问 `http://localhost:8080`

## 📄 License

MIT License
