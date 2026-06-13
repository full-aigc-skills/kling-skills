<div align="center">

# kling-skills

**可灵 (Kling) AIGC skills — text-to-video and image-to-video prompt engineering**

[![GitHub](https://img.shields.io/badge/github-full--aigc--skills%2Fkling-skills-green.svg)](https://github.com/full-aigc-skills/kling-skills)
[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](LICENSE)
[![Agent Skills](https://img.shields.io/badge/Agent%20Skills-Compatible-purple.svg)](https://agentskills.io)

English | [简体中文](./README.zh-CN.md)

[Introduction](#-introduction) · [Install](#-install) · [Skills](#-skills) · [Supported Agents](#-supported-agents) · [Ecosystem](#-ecosystem)

</div>

---

## 📖 Introduction

**kling-skills** is a curated collection of Agent Skills for AI coding agents, part of the [Full AIGC Skills](https://github.com/full-aigc-skills) ecosystem.

This package includes **2 skills**. Each skill is a self-contained `SKILL.md` file that AI agents load on-demand.

## 📦 Install

```bash
npx skills add full-aigc-skills/kling-skills
```

Or install specific skills: `npx skills add full-aigc-skills/kling-skills --skill <skill-name>`

## 🎯 Skills (2)

| Skill | Description |
|-------|-------------|
| `kling-prompt` |  "为 Kling AI（可灵）视频生成模型撰写高质量提示词。涵盖文生视频和图生视频的提示词框架，包括戏剧结构、镜头语言、灯光设计、角色一致性、多镜头叙事、Motion Brush 描述、负向提示词等 |
| `kling-video` |  "通过 Kling AI API / SDK 生成视频，涵盖文生视频、图生视频、AI 数字人、运动控制、多镜头叙事。当用户需要调用 Kling（可灵）生成视频时使用此 skill。触发条件：用户提到 |

## 🤖 Supported Agents

Works with [Claude Code](https://code.claude.com), [Codex](https://developers.openai.com/codex), [Cursor](https://cursor.com), [OpenCode](https://opencode.ai), [Gemini CLI](https://geminicli.com), [GitHub Copilot](https://github.com/features/copilot), [Windsurf](https://codeium.com/windsurf), and [70+ others](https://agentskills.io/clients).

### Claude Code Installation

**Option 1: npx skills CLI (Recommended)**

```bash
npx skills add full-aigc-skills/kling-skills
```

**Option 2: Manual Installation**

```bash
git clone https://github.com/full-aigc-skills/kling-skills.git
cp -r kling-skills/skills/* .claude/skills/
```

For more details, see the [Claude Code Skills Guide](https://code.claude.com/docs/en/skills) and [Agent Skills Spec](https://agentskills.io/).

## 🌐 Ecosystem

| Resource | Link |
|----------|------|
| **Full AIGC Skills** | [github.com/full-aigc-skills](https://github.com/full-aigc-skills) |
| **Agent Skills Spec** | [agentskills.io](https://agentskills.io) |
| **Skills CLI** | [github.com/vercel-labs/skills](https://github.com/vercel-labs/skills) |

## 📄 License

Apache 2.0 — see [LICENSE](LICENSE).
