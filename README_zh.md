# PM Chief Naysayer

[English](./README.md)

产品逻辑压力测试 AI Skill —— 在资源浪费之前，找到产品推理中的裂缝。

## 它做什么

当有人提出一个产品想法、功能概念或产品方案时，PM Chief Naysayer 不会给你鼓励，不会帮你规划，不会说"这个想法不错"。它只做一件事：**用层层递进的追问，暴露逻辑漏洞。**

## 三阶段压力测试

| 阶段 | 测试什么 | 核心问题 |
|------|---------|---------|
| **Stage 1: Foundation** | 第一性原理 | 剥离所有竞品引用和行业惯例后，底层逻辑是否自洽？ |
| **Stage 2: Truth** | 证据审查 | 你声称的事实，有没有具体、可验证的证据支撑？ |
| **Stage 3: Pruning** | 奥卡姆剃刀 | 如果工程只有一小时上线，最小可验证的核心是什么？ |

三个阶段严格顺序执行，不可跳过，不可合并。只有当前阶段通过，才进入下一阶段。

## 什么是 Skill

Skill 是遵循 [Agent Skills](https://agentskills.io) 开放标准的结构化指令集，由包含指令、脚本和参考资源的文件夹组成，用于扩展 AI Agent 的能力边界。Agent 会在相关场景下自动加载对应的 Skill，你也可以通过 `/pm-chief-naysayer` 手动调用。

## 安装

### 通过 Agent 安装

在 Claude Code、OpenCode 等支持 Skill 的 Agent 中，直接对话：

```
安装这个 skill：https://github.com/Trient/pm-chief-naysayer
```

### 手动安装

将本仓库中的 `SKILL.md` 放入对应工具的 Skills 目录下，重命名文件夹为 `pm-chief-naysayer/`：

| 工具 | 路径 |
|------|------|
| Claude Code | `~/.claude/skills/` |
| OpenCode | `~/.config/opencode/skills/` |

## 在线体验

- [SkillHub](https://skillhub.cn/skills/pm-chief-naysayer)
- [ClawHub](https://clawhub.ai/trient/pm-chief-naysayer)

## 触发方式

当你提出产品想法时，Agent 会自动加载此 Skill。也可以手动触发：

- "帮我挑战一下这个想法"
- "压力测试一下我的产品方案"
- "这个想法有什么漏洞"
- "审查一下我的 PRD"

## License

[MIT](./LICENSE)
