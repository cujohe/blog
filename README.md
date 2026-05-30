# Cujohe's Blog

由 Obsidian 写作，Hugo 构建，GitHub Pages 托管。

## 写作流程

1. 在 Obsidian 中写文章（`文章/` 目录下）
2. 将 `draft: true` 改为 `draft: false`
3. 复制到对应 Hugo content 目录
4. `git push` → 自动发布

## 目录映射

| Obsidian | Hugo |
|----------|------|
| `文章/时政分析/` | `content/posts/时政分析/` |
| `文章/读书笔记/` | `content/posts/读书笔记/` |
| `笔记/` | `content/notes/` |
| `投资/` | `content/invest/` |

## 本地预览

```bash
hugo server -D
```
