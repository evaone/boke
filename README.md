# Boke

基于 GitHub Pages + Hugo 的个人博客。

## 目录结构

```
boke/
├── content/posts/      # 文章（Markdown）
├── archetypes/         # 文章模板
├── static/             # 静态资源
├── .github/workflows/  # CI/CD 部署
└── hugo.toml           # Hugo 配置
```

## 发布流程

1. 在 `content/posts/` 下新建 Markdown 文章
2. frontmatter 必须包含 `title` / `date` / `tags` / `author`
3. 提交 PR 到 main 分支
4. 合并后 GitHub Actions 自动构建并部署到 GitHub Pages

## 本地预览

```bash
hugo server -D
```
