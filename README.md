# 我的技术博客

这是一个基于 Next.js 的个人技术博客，适合编程、技术分享，支持内容方便更新和扩展。

## 本地开发

```bash
npm install
npm run dev
```

## 构建与部署

1. 构建静态文件：
   ```bash
   npm run build
   npm run export
   ```
2. 将 `out` 目录上传到 GitHub。
3. 在 Cloudflare Pages 选择该仓库，设置构建命令为 `npm run build && npm run export`，输出目录为 `out`。

## 增加内容

在 `posts` 文件夹下添加 Markdown 文件即可自动生成新文章。 