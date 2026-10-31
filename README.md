# 白士博的技术博客

纯静态博客，无构建工具、无外部依赖。直接部署到 GitHub Pages / Cloudflare Pages 即可。

## 目录

- `index.html` — 首页（作品集精选 + 文章列表）
- `portfolio.html` — 作品集（2 段课程实训 + 6 份云平台/集群实验）
- `about.html` — 关于我
- `posts/` — 文章页（开博文、Kubernetes 离线部署踩坑、Nginx+Keepalived+HAProxy 高可用、企业网络实训复盘）
- `assets/style.css` — 全站样式
- `domain-application/` — is-a.dev 与 eu.org 的申请材料（文件已备好）

## 部署到 GitHub Pages（用日常号 bai265272-rgb）

1. 新建公开仓库，仓库名必须是 `bai265272-rgb.github.io`
2. 把本目录除 `domain-application/` 以外的文件上传到仓库根目录
   （index.html 必须在根目录）
3. 仓库 Settings → Pages → Source 选 `Deploy from a branch`，分支 `main`、目录 `/ (root)`
4. 等 1–2 分钟，访问 https://bai265272-rgb.github.io/ 确认打开
5. 之后按 `domain-application/README.md` 提交 is-a.dev 申请

## 新增一篇文章

1. 复制一篇现有 posts/*.html，改标题、日期和正文
2. 在 index.html 的文章列表里加一张卡片，链接指向新文件
3. 提交到仓库即可，GitHub Pages 会自动更新

## 隐私约定

本站不公开手机号和证书编号；公开联系方式只有求职邮箱和 GitHub。
