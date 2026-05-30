# Cujohe's Blog

个人技术博客。Obsidian 写作 → Hugo 构建 → GitHub Pages 自动部署。

## 写作 & 发布流程

1. 在 Obsidian 中写文章
2. 将 `draft: true` 改为 `draft: false`
3. 复制到对应 Hugo content 目录
4. `git add && git commit && git push` → GitHub Actions 自动构建发布

## ⚠️ 隐私分界线

**推之前问自己：这内容我希望任何人免费看吗？**

| ✅ 可以推（公开） | ❌ 留在本地（私有） |
|---|---|
| 技术文章、学习笔记 | 投资记录、财务分析 |
| 读书笔记（可公开部分） | 日记、私密文档 |
| 项目经验、教程 | 个人数据 |

私密内容存在 Obsidian 本地 + NAS 备份，**绝不出现在这个仓库中**。

## 目录结构

```
blog/
├── content/
│   └── posts/          ← 博客文章放这里
├── .github/workflows/  ← 自动部署配置
├── hugo.toml           ← Hugo 配置（PaperMod 主题）
└── README.md
```

## 本地预览（可选）

```bash
hugo server -D
```
