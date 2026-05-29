# 晨晨's Blog

赛博朋克风格的个人技术博客，基于纯 HTML + CSS 构建，无需后端，可直接部署至 GitHub Pages。

## 快速部署到 GitHub Pages

1. **创建仓库**
   登录 GitHub → 点击右上角 `+` → New repository
   仓库名设置为 `你的用户名.github.io`，例如 `lsyf2003.github.io`

2. **上传文件**
   把 `chenchen-blog` 文件夹里的所有文件上传到仓库根目录

3. **开启 GitHub Pages**
   仓库 → Settings → Pages → Source 选择 `main` 分支 → Save

4. **访问你的网站**
   等待 1-2 分钟，访问 `https://你的用户名.github.io`

## 文件结构

```
├── index.html        # 首页（文章列表）
├── about.html        # 关于页面
├── categories.html   # 分类页面
├── style.css        # 样式表（赛博朋克主题）
└── README.md         # 说明文档
```

## 自定义修改

- **名字/标题**：编辑各页面的 `<h1 class="glitch-title">` 和 footer 中的姓名
- **文章列表**：编辑 `index.html` 中的 `<article class="post-card">` 区块
- **分类标签**：编辑 `categories.html` 中的 `<a class="category-item">` 区块
- **联系方式**：编辑 `about.html` 中的联系信息
- **配色**：编辑 `style.css` 顶部的 `:root` 变量

## 主题颜色说明

```css
--neon-pink:   #ff00ff;   霓虹粉（强调色）
--neon-cyan:   #00ffff;   霓虹青（主标题色）
--neon-purple:  #bf00ff;   霓虹紫（标签色）
--neon-green:   #39ff14;   霓虹绿（成功/分类色）
--bg-dark:      #0a0a0f;   深色背景
```

## 后续写文章

每次写新文章，在 `index.html` 的 `<div class="post-list">` 最前面添加一个 `<article class="post-card">` 即可。
