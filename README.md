# coze_guide

> 将本地 PDF 教程文档一键转换为可在线访问的网页站点，生成永久分享链接，随时随地流畅阅读。

## 📖 项目简介
coze_guide是一个轻量级静态网页项目，用于把本地的教程、手册、文档类 PDF 内容转化为在线可浏览的网页形式。无需服务器、无需数据库，依托 GitHub Pages / Cloudflare Pages 即可免费部署上线，生成专属链接分享给他人查看，完美解决 PDF 文件传输麻烦、移动端阅读体验差的问题。

当前仓库示例内容为 **Coze 智能体搭建实战教程**。

## ✨ 功能特性
- **纯静态部署**：零后端、零服务器成本，所有内容静态渲染，加载速度快
- **响应式适配**：自动适配电脑、平板、手机等多端设备，阅读体验流畅
- **一键免费部署**：支持 GitHub Pages / Cloudflare Pages 等多个平台一键上线
- **目录快速导航**：支持文档目录跳转，长文档定位高效
- **轻量无依赖**：原生 HTML/CSS/JS 实现，无需安装复杂框架
- **自定义样式**：可灵活调整页面配色、排版、字体，适配不同内容风格

## 🚀 在线预览
👉 点击访问：[https://bcbebbba.cozeguide.pages.dev/)

## 🛠️ 本地运行
项目为纯静态页面，本地查看无需安装任何依赖，两种方式均可：

### 方式1：直接打开
直接双击项目根目录下的 `index.html`，用浏览器打开即可查看。

### 方式2：本地服务器预览（推荐）
如果需要模拟线上部署效果，可使用简易本地服务器：
```bash
# 方式A：Python 内置服务器
python -m http.server 8080

# 方式B：Node.js 内置 serve
npx serve .
```
启动后在浏览器访问 `http://localhost:8080` 即可。

## 📦 部署教程
### 方式一：GitHub Pages（推荐·免费）
1. 将本项目代码上传至你的 GitHub 仓库
2. 进入仓库页面，点击顶部 `Settings`
3. 左侧菜单选择 `Pages`
4. `Source` 选择 `Deploy from a branch`
5. `Branch` 选择 `main`，目录选择 `/ (root)`，点击 `Save`
6. 等待 1-2 分钟，即可获得 `https://你的用户名.github.io/仓库名/` 格式的在线访问链接

### 方式二：Cloudflare Pages（免费·速度更快）
1. 登录 Cloudflare Dashboard，进入 `Pages`
2. 点击 `Create a project` → `Upload your static files`
3. 将项目文件夹拖拽上传，或连接 GitHub 仓库自动部署
4. 构建命令留空，输出目录填写 `./`
5. 点击部署，完成后即可获得自定义子域名的访问链接

## 📂 项目结构
```
coze_guide/
├── index.html          # 主页面入口
├── _redirects          # Cloudflare Pages 路由配置
├── css/                # 样式文件目录
│   └── style.css
├── js/                 # 脚本文件目录
│   └── main.js
├── assets/             # 图片、文档等静态资源
├── .gitignore          # Git 忽略配置
└── README.md           # 项目说明文档
```

## 🎨 自定义修改
### 替换为自己的教程内容
1. 将你的教程内容整理为 HTML 格式，替换 `index.html` 内的正文部分
2. 相关图片、附件放入 `assets/` 目录，对应修改页面内引用路径
3. 修改页面标题、描述等元信息，适配你的教程主题

### 调整页面样式
在 `css/style.css` 中可自定义：
- 页面主色调、背景色
- 字体大小、行间距
- 目录栏样式、按钮样式

## 📄 许可证
MIT License
你可以自由使用、修改、分发本项目，保留版权声明即可。
