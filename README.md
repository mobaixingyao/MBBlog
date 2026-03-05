# 墨白星耀 - 现代风格个人博客模板

> 一个纯前端实现的现代风格个人博客，支持部署到 Cloudflare Pages 等静态网页托管平台

[预览效果](https://mobaixingyao.dpdns.org/) 

---

## 项目预览

![项目预览](https://file.ljcdn.com/psd-sinan-file/prod/appeal_evidence/B45A9D5D4437429485C82C89AC1C84D5/qdqqd.png)

## 项目特点

- 🎨 **现代设计风格** - 简洁优雅的 UI 设计
- 🌙 **暗色模式支持** - 一键切换明/暗主题
- 📱 **响应式布局** - 完美适配各种设备
- 🎵 **内置音乐播放器** - 悬浮式音频播放功能
- 🔍 **文章搜索** - 快速查找所需内容
- 🚀 **即开即用** - 纯静态页面，无需后端

## 快速开始

### 1️⃣ 获取项目

```bash
git clone https://github.com/mobaixingyao/MBB.git
```

或下载 ZIP 文件解压

### 2️⃣ 基础配置

打开 [`index.html`](index.html) 文件，修改以下内容：

| 配置项 | 行号 | 说明 |
|--------|------|------|
| 网页图标 | 第 4 行 | 修改 `href` 为你的图标路径 |
| 网站标题 | 第 7 行 | 修改 `<title>` 内容 |
| 头像 | 第 80 行 | 修改头像图片路径 |
| 昵称 | 第 81 行 | 修改你的昵称 |
| 个性签名 | 第 82 行 | 修改个性签名 |
| 社交链接 | 第 85-96 行 | 修改为你的社交账号链接 |
| 页脚信息 | 第 216 行 | 修改版权信息 |

### 3️⃣ 配置文章

文章位于第 105-210 行，格式如下：

```html
<article class="article-card placeholder" id="article-0">
    <h2 class="article-title">文章标题</h2>
    <div class="article-meta">
        <span class="date">2026/3/1</span>
    </div>
    <div class="article-body markdown-content">
        文章内容（支持 Markdown）
    </div>
</article>
```

> ⚠️ **重要**：文章 ID 从 `article-0` 开始递增，影响搜索功能

**支持 Markdown 语法**：标题、粗体、列表、图片、视频等，详见示例文章

### 4️⃣ 替换资源

| 文件 | 用途 |
|------|------|
| `assets/images/b_6aa87abcf0e67e7541af23061ac46906.jpg` | 头像 |
| `assets/images/api.elaina.jpg` | 背景图 |

### 5️⃣ 部署上线

**Cloudflare Pages（推荐）**：
1. 登录 [Cloudflare Dashboard](https://dash.cloudflare.com/)
2. Pages → Create application → Connect to Git
3. 选择仓库，保持默认设置，点击 Deploy

**其他平台**：GitHub Pages、Vercel、Netlify 或直接上传到服务器

## 项目结构

```
MBB/
├── assets/              # 静态资源目录
│   ├── fonts/          # 字体文件
│   └── images/         # 图片资源
├── css/                # 样式文件
│   └── style.css       # 主样式表
├── index.html          # 主页面文件
└── README.md           # 项目说明文档
```

## 部署指南

### Cloudflare Pages 部署

1. 登录 [Cloudflare Dashboard](https://dash.cloudflare.com/)
2. 进入 Pages 服务
3. 连接你的 GitHub 仓库或直接上传项目文件
4. 配置构建设置（无需特殊配置）
5. 点击部署

### 其他平台部署

本项目为纯静态 HTML 项目，可部署到任何支持静态网页托管的平台：

- GitHub Pages
- Vercel
- Netlify
- 传统 Web 服务器（Nginx/Apache）

## 技术栈

- **HTML5** - 页面结构
- **CSS3** - 样式与动画效果
- **JavaScript (原生)** - 交互逻辑
- [Marked.js](https://github.com/markedjs/marked) - Markdown 解析库

## 自定义建议

### 修改主题颜色

编辑 [`css/style.css`](css/style.css) 文件中的 CSS 变量即可自定义主题色

### 添加更多功能

由于使用原生 JavaScript 开发，你可以通过修改 `index.html` 和 `css/style.css` 文件来扩展功能

## 注意事项

> ⚠️ **声明**：本项目由 AI 辅助开发，作者为非前端专业人士。如发现问题，欢迎提交 Issue 反馈。

- 请确保所有资源文件路径正确
- 建议在本地浏览器测试后再部署
- 音乐播放器需要有效的音频文件链接
- 社交链接请替换为你自己的账号地址

## 许可证

本项目采用 MIT 许可证 - 详见 [LICENSE](LICENSE) 文件

## 致谢

感谢所有为本项目提供帮助的开源社区成员！

---

**祝你使用愉快！** 🎉
