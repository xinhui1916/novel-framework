---
name: novel-init
description: 小说项目初始化 — 收集设定，生成 story bible、角色卡、世界观
---

# Phase 1: Init — 项目初始化

## 流程

### 1. 需求收集（7 问）
- 书名/标题方向？
- 类型题材？（修仙/科幻/悬疑/言情/奇幻/现实主义...）
- 一句话梗概？
- 核心设定？（独特世界观、金手指、力量体系等）
- 主题内核？（故事想表达什么）
- 篇幅预期？（短篇/中篇/长篇/连载）
- 参考作品/文风？（可选）

如果用户没有明确想法 → 调 `brainstorming` skill 辅助构思。

### 2. 生成项目结构
创建项目目录：

```
project-name/
├── bible/
│   ├── story-bible.md
│   └── characters/
│       └── _index.md
├── plot/
│   ├── outline.md
│   └── timeline.md
├── chapters/
│   └── _index.md
├── progress.md
└── style-sample.md
```

### 3. 填充设定（按项目画像决定深度）

**短篇 / 即兴 → 极简版：**
- `bible/story-bible.md` — 只记核心设定，几句话
- `characters/_index.md` — 只记主要角色，每人两三句

**长篇 / 大纲党 / 复杂世界观 → 完整版：**
- `bible/story-bible.md` — 用 templates/story-bible.md 模板填充（按需跳过不相关的章节）
- `characters/_index.md` + 个人角色卡
- `worldbuilding/_index.md` + 地点卡（可选）
- `plot/timeline.md` — 时间线框架

**模板只是工具，不相关就跳过。** 比如不需要力量体系 → 不填那一段。

### 4. 用户确认
展示初始化摘要。确认后进 Plan 阶段，但注意：

> **设定是起点，不是枷锁。** 写着写着发现新方向 → 回头更新 bible 就行。
> 不需要"一次性把设定想全再动笔"。
