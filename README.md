# 伞间岁月

> 一菇一世界，一伞一春秋

**🌐 博客地址**：[https://blog.realzhengxi.com](https://blog.realzhengxi.com)

---

## 关于

生命科学研究者的个人博客，记录微生物研究、基因组编辑（CRISPR / Prime Editing）、全栈开发与日常思考。

极简设计 · 白底英文 · 一页到底

---

## 目录结构

```
source/
├── _posts/          # 博客文章
├── about/           # 关于页面
├── categories/      # 分类归档
├── tags/            # 标签归档
├── photos/          # 摄影
├── links/           # 友链
├── tools/           # 在线工具
├── images/          # 图片资源
├── js/              # 自定义脚本
└── CNAME            # 域名绑定 (blog.realzhengxi.com)
```

---

## 技术栈

| 项目 | 说明 |
|------|------|
| **框架** | [Hexo](https://hexo.io) 静态博客 |
| **主题** | [Highlight](../themes/highlight)（自维护，极简风） |
| **部署** | GitHub Pages + GitHub Actions 自动构建 |
| **域名** | `blog.realzhengxi.com` |
| **文章链接** | [hexo-abbrlink](https://github.com/rosano/hexo-abbrlink) 短链 (`posts/:abbrlink/`) |

---

## 写作规范

- 文章放在 `source/_posts/` 目录下，使用 Markdown 编写
- Front-matter 示例：

```yaml
---
title: 文章标题
date: 2026-01-01
cover: /images/cover.jpg        # 封面图（可选）
tags:
  - 标签1
  - 标签2
categories:
  - 分类名
description: 文章摘要           # 搜索引擎 & SEO
---
```

- 支持的特性：
  - 📐 **Mermaid 图表** — 流程图、时序图等（直接写 Mermaid 代码块）
  - 💻 **代码高亮** — 带行号、复制按钮、薄荷绿主题
  - 🔗 **Wiki 链接** — Obsidian 风格 `[[文章名]]` 双向链接
  - ⚠️ **Callout 提示框** — 支持 tip / note / warning 等类型
  - 🖼️ **封面图** — 自动裁切圆角，悬停缩放动效

---

## 本地运行

```bash
# 安装依赖
npm install

# 本地预览
hexo server

# 生成静态文件
hexo generate

# 部署（推送到源码仓库后由 Actions 自动完成）
hexo deploy
```

---

## 联系方式

- 📧 Email: xi.z@outlook.com
- 🏠 主页: [www.realzhengxi.com](https://www.realzhengxi.com)

---

*Built with Hexo & Highlight Theme*
