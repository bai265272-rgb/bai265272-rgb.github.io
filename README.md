# 白士博的技术博客

个人技术博客与作品集，纯静态站点，托管在 GitHub Pages：https://bai265272-rgb.github.io/

内容是网络工程、Linux 运维与 Kubernetes 的真实实验记录：课堂实验周记、实训复盘与项目详情。

## 目录结构

- `index.html` / `about.html` / `portfolio.html` — 首页、关于、作品集
- `posts/` — 博客文章
- `projects/` — 项目详情页（报告目录、关键截图与复盘）
- `assets/` — 全站样式与图片（图片使用 WebP）
- `feed.xml` / `sitemap.xml` — RSS 订阅与站点地图

## 新增一篇文章

1. 在 `posts/` 下新建 HTML，套用现有文章页的结构（导航、正文、作者卡）
2. 在首页文章区、`feed.xml`、`sitemap.xml` 中各加一条
3. 图片放 `assets/img/`，正文引用与点击大图都指向 WebP 文件
