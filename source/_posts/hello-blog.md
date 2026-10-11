---
title: 博客搭起来了
date: 2026-10-11 04:37:59
categories:
  - 随笔
tags:
  - 建站
---

这是 RichardZ 的第一篇文章。博客用 Hexo + Fluid 主题搭建，托管在 GitHub Pages 上，每次推送代码后会自动重新构建发布。

## 之后怎么写新文章

在博客目录下执行：

```bash
npx hexo new post my-new-post
```

会在 `source/_posts/` 下生成 `my-new-post.md`，文件名建议用英文（它会变成网址的一部分），标题写在文件顶部的 `title:` 里，中文没问题。

写完本地预览：

```bash
npx hexo server
```

然后打开 http://localhost:4000 。

确认没问题就提交推送，几分钟后线上就更新了：

```bash
git add .
git commit -m "新文章：xxx"
git push
```
