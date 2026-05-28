## 大虾条 · 学术主页

基于Jekyll的个人学术主页，用于博士申请及工作展示。

设计风格基于 stormzhang 原博客主题，秉承"simple is beautiful"原则。

## 本地运行

```bash
# 安装依赖
gem install jekyll bundler
bundle install

# 启动本地服务
jekyll serve

# 访问 http://localhost:4000
```

## 部署

- **GitHub Pages**: 推送到 `yourusername.github.io` 仓库即可
- **Vercel**: 连接GitHub仓库，自动部署（已配置 vercel.json）

## 项目结构

- `index.md` — 首页（研究概览）
- `research.md` — 研究方向
- `publications.md` — 论文成果
- `projects.md` — 项目经历
- `about.html` — 个人简介
- `_posts/` — 博客文章（Markdown）
- `_config.yml` — 站点配置