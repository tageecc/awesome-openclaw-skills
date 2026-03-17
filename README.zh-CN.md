# Awesome OpenClaw Skills（中文）

> 本文档是 `README.md` 的中文说明版，重点覆盖项目定位、安装方式、收录标准与安全声明。由于主列表包含数千条技能条目且持续更新，技能清单请以英文主文档为准：[`README.md`](./README.md)。

## 项目简介

OpenClaw 是一个在本地运行的 AI 助手，可直接在你的设备上执行任务。Skill（技能）用于扩展 OpenClaw 的能力，使其能够连接外部服务、自动化工作流，并完成更专业的场景任务。

这个仓库是一个「精选技能导航」，帮助你快速发现并安装适合自己需求的技能，也可作为 OpenClaw 应用场景的灵感库。

本列表中的技能来源于 ClawHub（OpenClaw 的公开技能注册表），并按类别组织，便于检索。

## 安装方式

### 1) 使用 ClawHub CLI

```bash
clawhub install <skill-slug>
```

### 2) 手动安装

将技能文件夹复制到以下任一目录：

| 安装范围 | 路径 |
|---|---|
| 全局 | `~/.openclaw/skills/` |
| 当前工作区 | `<project>/skills/` |

优先级：`Workspace > Local > Bundled`

### 3) 另一种方式

你也可以直接把技能对应的 GitHub 仓库链接粘贴给助手，并要求它使用该技能。助手会在后台自动处理安装与配置。

## 为什么需要这个列表？

截至 2026-02-28，OpenClaw 官方公开注册表（ClawHub）中有 **13,729** 个社区技能；而本仓库是经过筛选后的精选列表，当前收录 **5,366** 个技能。

该列表会排除如下内容：

- 疑似垃圾提交（批量账号、机器人账号、测试/无效内容）
- 重复项或高度相似命名
- 低质量或非英文描述
- Crypto / Blockchain / Finance / Trade 相关技能
- 研究者公开安全审计中标记为恶意的技能（不含仅基于 VirusTotal 的单一依据）

## 如何提交你的技能

本仓库**仅收录已发布到 `github.com/openclaw/skills` 的技能**。

不接受个人仓库、gist 或其他外部来源链接。若你的技能尚未发布到 OpenClaw 官方技能仓库，请先完成发布，再提交 PR 到本仓库。

提交 PR 时请在描述中提供以下两类链接：

- ClawHub 链接，例如：`https://clawhub.ai/steipete/slack`
- GitHub 链接，例如：`https://github.com/openclaw/skills/tree/main/skills/steipete/slack`

详细规范见：[`CONTRIBUTING.md`](./CONTRIBUTING.md)

## 安全声明

本列表是 **Curated（人工筛选）**，不是 **Audited（逐项安全审计）**。

技能被收录后，原维护者仍可能随时更新、修改或替换实现。安装或使用任何技能前，请自行评估风险并核验来源。

OpenClaw 与 VirusTotal 有合作，可在 ClawHub 对应技能页面查看安全扫描结果与风险标记。

## 分类与完整技能清单

- 英文完整清单（持续更新）：[`README.md`](./README.md)
- 中文分类导航：[`categories/README.zh-CN.md`](./categories/README.zh-CN.md)
- 分类分表目录：[`categories/`](./categories)

> 说明：技能名称、slug、外链地址建议保持原文，避免因翻译造成检索偏差或链接歧义。

## 贡献与社区

- 贡献指南（英文）：[`CONTRIBUTING.md`](./CONTRIBUTING.md)
- 贡献指南（中文）：[`CONTRIBUTING.zh-CN.md`](./CONTRIBUTING.zh-CN.md)
- Issues：<https://github.com/VoltAgent/awesome-openclaw-skills/issues>
