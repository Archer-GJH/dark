# 我的个人博客

这是我基于 Hugo 搭建的个人博客，使用 PaperMod 主题。

## 技术栈

- **框架**: [Hugo](https://gohugo.io/) - 快速、现代的静态网站生成器
- **主题**: [PaperMod](https://github.com/adityatelange/hugo-PaperMod) - 简洁、响应式的 Hugo 主题
- **部署**: GitHub Pages + Vercel (用于全球 CDN 加速)

## 本地开发

```bash
# 启动本地开发服务器
hugo server -D

# 构建静态文件
hugo
```

## 部署流程

本博客通过 GitHub Actions 自动部署到 GitHub Pages，同时也连接了 Vercel 进行全球 CDN 加速。

## 许可证

MIT 