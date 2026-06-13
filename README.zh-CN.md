<div align="center">

# kling-skills

**可灵 (Kling) AIGC 技能 — 文生视频与图生视频提示词工程**

[![GitHub](https://img.shields.io/badge/github-full--aigc--skills%2Fkling-skills-green.svg)](https://github.com/full-aigc-skills/kling-skills)
[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](LICENSE)
[![Agent Skills](https://img.shields.io/badge/Agent%20Skills-兼容-purple.svg)](https://agentskills.io)

[English](./README.md) | 简体中文

</div>

---

## 📖 简介

**kling-skills** 是一组 AI 编码智能体技能，属于 [Full AIGC Skills](https://github.com/full-aigc-skills) 生态。包含 **2 个技能**。

## 📦 安装

```bash
npx skills add full-aigc-skills/kling-skills
```

## 🎯 技能列表 (2)

| 技能 | 描述 |
|------|------|
| `kling-prompt` |  "为 Kling AI（可灵）视频生成模型撰写高质量提示词。涵盖文生视频和图生视频的提示词框架，包括戏剧结构、镜头语言、灯光设计、角色一致性、多镜头叙事、Motion Brush 描述、负向提示词等 |
| `kling-video` |  "通过 Kling AI API / SDK 生成视频，涵盖文生视频、图生视频、AI 数字人、运动控制、多镜头叙事。当用户需要调用 Kling（可灵）生成视频时使用此 skill。触发条件：用户提到 |

## 🤖 支持的智能体

适用于 [Claude Code](https://code.claude.com)、[Codex](https://developers.openai.com/codex)、[Cursor](https://cursor.com)、[OpenCode](https://opencode.ai)、[Gemini CLI](https://geminicli.com)、[GitHub Copilot](https://github.com/features/copilot)、[Windsurf](https://codeium.com/windsurf) 及 [70+ 其他](https://agentskills.io/clients)。

### Claude Code 安装

**方式一：npx skills CLI（推荐）**

```bash
npx skills add full-aigc-skills/kling-skills
```

**方式二：手动安装**

```bash
git clone https://github.com/full-aigc-skills/kling-skills.git
cp -r kling-skills/skills/* .claude/skills/
```

## 📄 License

Apache 2.0
