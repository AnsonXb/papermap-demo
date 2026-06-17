# PaperMap - AI驱动的论文知识图谱生成器

> **TRAE AI 创造力大赛 · 学习工作赛道参赛作品**

输入研究关键词，3分钟自动生成论文引用关系图谱 + AI阅读路径推荐 + 综述大纲。

## ✨ 在线演示

👉 **[点击查看 PaperMap Demo](https://ansonxb.github.io/papermap-demo/)**

## 🎯 解决什么问题

- 面对上百篇论文不知道从哪篇读起
- Connected Papers 只画图不解读，看完图谱仍然迷茫
- 读完十几篇论文后不知道怎么组织综述框架

## 🔥 核心亮点

| 能力 | 说明 |
|------|------|
| 一键生成图谱 | 输入关键词 → 自动抓取 120+ 篇相关论文 |
| AI 深度解读 | 每篇论文 3 句话核心观点（TRAE API） |
| 智能阅读路径 | PageRank 权重排序，告诉你"先读哪 3 篇" |
| 一键跳转原文 | 点击节点直接跳转 arxiv 原文 |
| 综述大纲导出 | Markdown 格式，直接用于开题报告 |

## 🏗️ 技术栈

- **Semantic Scholar API** — 学术数据源
- **Neo4j** — 图数据库存储引用关系
- **Cytoscape.js** — 交互式可视化
- **TRAE API** — AI 论文总结与解读
- **PageRank** — 论文学术影响力权重计算
- **Louvain** — 社区发现算法识别研究分支

## 📊 与竞品对比

| 维度 | Connected Papers | ResearchRabbit | PaperMap |
|------|:---:|:---:|:---:|
| 引用网络可视化 | ✅ | ✅ | ✅ |
| 中文关键词搜索 | ❌ | ⚠️ | ✅ |
| AI 论文深度解读 | ❌ | ❌ | ✅ |
| 智能阅读排序 | ❌ | ⚠️ | ✅ |
| 一键导出综述 | ❌ | ❌ | ✅ |

## 📅 MVP 开发计划

- **Week 1** — 数据层 + 后端（API 对接、Neo4j、PageRank）
- **Week 2** — 前端 + 可视化（Next.js、Cytoscape.js、交互）
- **Week 3** — AI 增强 + 打磨（综述导出、分享功能、部署）

---

*Built with ❤️ for TRAE AI 创造力大赛 2026*
