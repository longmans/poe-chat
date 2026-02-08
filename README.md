# Poe Chat Skill

[English](#english) | [中文](#chinese)

---

<a name="english"></a>

## Overview

Poe Chat Skill is a Claude (for OpenClaw) skill that allows you to call various AI models from [Poe](https://poe.com) directly in your chat interface. Simply use trigger words like `@gemini`, `@gpt`, `@claude`, `@kimi`, `@deepseek` to invoke different models.

### Key Features

- **Multi-Model Support**: Access to Gemini, GPT, Claude, Kimi, Deepseek and other Poe models
- **Auto Model Selection**: Automatically selects the most suitable model based on trigger word
- **File Upload**: Support for analyzing files you upload during conversation
- **API Key Management**: Secure API key handling via environment variables

---

## Installation

Install the skill using OpenCode:

```bash
npx clawhub@latest install poe-chat
```

This will automatically install all required dependencies and configure the skill.

---

## Usage

Simply start a conversation and use trigger words like `@gemini`, `@gpt`, `@claude`, `@kimi`, `@deepseek` to call different AI models.

**Example:**
```
@gemini 请解释量子计算的基本原理
```

The skill will automatically select the most appropriate model and respond with:
```
Model used: gemini-3-flash

<响应内容>
```

---

## License

This project is licensed under the MIT License.

---

<a name="chinese"></a>

## 项目简介

Poe Chat Skill 是一个 Claude (适合Openclaw使用) 技能，允许你在聊天界面中直接调用 [Poe](https://poe.com) 上的各种 AI 模型。只需使用 `@gemini`、`@gpt`、`@claude`、`@kimi`、`@deepseek` 等触发词即可激活不同的模型。

### 主要特性

- **多模型支持**: 访问 Gemini、GPT、Claude、Kimi、Deepseek 等 Poe 模型
- **自动模型选择**: 根据触发词自动选择最合适的模型
- **文件上传**: 支持在对话中上传文件供模型分析
- **API Key 管理**: 通过环境变量安全处理 API 密钥

---

## 安装方法

安装该技能：

```bash
npx clawhub@latest install poe-chat
```

这将自动安装所有必需的依赖并配置技能。

---

## 使用方法

直接开始对话，使用 `@gemini`、`@gpt`、`@claude`、`@kimi`、`@deepseek` 等触发词调用不同的 AI 模型。

**示例：**
```
@gemini 请解释量子计算的基本原理
```

系统会自动选择最合适的模型并返回：
```
Model used: gemini-3-flash

<响应内容>
```

---

## 许可证

本项目采用 MIT 许可证。
