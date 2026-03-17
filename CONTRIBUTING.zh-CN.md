# 贡献指南（中文）

感谢你为 Awesome OpenClaw Skills 做出贡献！

本仓库是 OpenClaw 技能的精选导航列表，主要收录来自 [OpenClaw 官方技能仓库](https://github.com/openclaw/skills/tree/main/skills) 的技能链接。

> 这是一个“链接索引仓库”，不托管技能实现本体。每个被收录技能都**必须已发布**在官方技能仓库中。

## 添加技能

### 条目格式

请在 `README.md` 对应分类末尾追加条目：

```markdown
- [skill-name](https://github.com/openclaw/skills/tree/main/skills/author/skill-name/SKILL.md) - 对技能功能的简短说明。
```

如果同一作者在同一领域有多个技能，请优先使用作者目录聚合链接，避免逐条堆叠：

```markdown
- [author-skills](https://github.com/openclaw/skills/tree/main/skills/author) - 覆盖该作者技能集合的简要说明。
```

### 添加位置

- 在 `README.md` 中找到最匹配的分类，在该分类末尾添加。
- 如果没有完全匹配的分类，可添加到最接近分类，并在 PR 描述中说明新增分类建议。

### 收录要求

- 技能必须已发布到 [OpenClaw 官方技能仓库](https://github.com/openclaw/skills/tree/main/skills)
- 技能包含 `SKILL.md` 文档
- 描述简洁（建议不超过 10 个英文单词）
- 技能应具备实际社区使用基础
- 当前不收录 Crypto、Blockchain、DeFi、Finance 相关技能

## PR 描述要求

请在 PR 描述中同时提供：

- ClawHub 链接（例如：`https://clawhub.ai/steipete/slack`）
- GitHub 链接（例如：`https://github.com/openclaw/skills/tree/main/skills/steipete/slack`）

## PR 标题规范

```text
Add skill: author/skill-name
```

## 更新已有条目

你可以通过 PR 修复：

- 失效链接
- 拼写错误
- 过期描述

如果某技能已下线或弃用，也欢迎通过 Issue 或 PR 提议移除。

## 安全策略

本仓库仅收录在 [ClawHub](https://www.clawhub.ai/) 上未被标记为可疑的技能。

若你认为列表中的某个技能存在安全风险，请提交 Issue，维护者会评估并在必要时移除。

## 提交前检查清单

- 链接可访问且指向正确
- 分类选择合理
- 无重复条目
- 描述清晰、简洁、可核验

## 获取帮助

- 先查看现有 Issues / PR
- 如有疑问，提交新 Issue 讨论
- 技能自身用法请参考对应 `SKILL.md`
