# novel-framework

自适应小说创作框架 — Claude Code skill。

你说"写小说"，框架自动评估项目类型，只启用你需要的功能，不浪费 token。

## 安装

```bash
git clone https://github.com/xinhui1916/novel-framework.git ~/.claude/skills/novel-framework
```

然后告诉 Claude Code "我想写小说" 即可触发。

## 功能

- 项目评估（篇幅/风格/AI味敏感度/一致性要求）
- Story Bible + 角色卡 + 角色声音库
- 大纲规划（三幕/非线性/自定义）
- 逐章写作（fresh context + 前情提要）
- 修订模式（回溯修改/调序/删减/合并）
- 审校（一致性检查 + 6 道去 AI 味门禁）
- 导出 docx/pdf

## 原则

- 灵感优先于流程
- Bible 是活的，随时可更新
- 所有功能按需加载，不预检不注入
- 默认全部跳过，只启用你确认需要的
