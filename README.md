<div align="center">

# 🧠 MBTI × AI Content Creation Prompt System

> 16 Personality Types × AI Deep Insights = Content Engine for Millions

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)
[![GitHub Stars](https://img.shields.io/github/stars/AIPMAndy/mbti-ai-prompts?style=social)](https://github.com/AIPMAndy/mbti-ai-prompts)

[English](#english) | [简体中文](#中文)

</div>

---

<a name="english"></a>

## 🚀 What Can This System Do?

| Pain Point | Solution |
|------------|----------|
| MBTI content is homogeneous | Unique "Style DNA" system for maximum differentiation |
| Topic selection relies on luck | 5 proven high-traffic series + topic formulas |
| AI content feels robotic | Few-shot samples + quality checklist for human-like output |
| Don't know where to start | Ready-to-use prompt system, get started in 10 minutes |

## 📁 File Structure

```
mbti-ai-prompts/
├── prompts/
│   ├── 01-system-prompt.md      # Core system prompt (Style DNA)
│   ├── 02-topic-generator.md    # Topic generation prompts
│   └── 03-copywriter.md         # Copywriting prompts
├── samples/
│   └── style-samples.md         # Viral content samples
└── README.md
```

## ⚡ Quick Start

### Option 1: Direct Use (Any LLM)

1. Use `01-system-prompt.md` as System Prompt
2. Choose modules from `02-topic-generator.md` or `03-copywriter.md`
3. Replace `{...}` placeholders
4. Send to GPT-4 / Claude / other LLMs

### Option 2: Integrate with OpenClaw / Feishu Bot

```yaml
name: "Andy Writing Assistant"
system_prompt: |
  # Copy full content from 01-system-prompt.md
  ...

tools:
  - web_search  # Trend tracking

commands:
  - trigger: "/topic"
    prompt: |
      # Select module from 02-topic-generator.md
  - trigger: "/write"
    prompt: |
      # Select module from 03-copywriter.md
```

## 🔥 High-Traffic Topic Formula

```
[Personality Type] + [Emotional State/Struggle] + [Solution/New Perspective]
```

**Proven Series:**
- 🔮 **Time Travel Series**: When [personality] travels to [scenario]
- 🚀 **Life Change Series**: How [personality] changes their fate with AI
- 📈 **Evolution Series**: [personality] from low to high level
- 💪 **Habits Series**: N habits that make [personality] [achieve X]
- ✨ **Encounter Series**: When [personality] meets [something]

## 🤝 Author

**Andy | AI Product Expert**

- 🚀 Ex-Tencent / Ex-Baidu AI Product Lead
- 🦄 LLM Unicorn VP → Startup CEO
- 🎯 AI Business Strategy Consultant

**WeChat:** AIPMAndy | **GitHub:** [@AIPMAndy](https://github.com/AIPMAndy)

---

<a name="中文"></a>

# 🧠 MBTI × AI 内容创作提示词系统

> 16种人格 × AI深度洞察 = 精准触达百万读者的内容引擎

## 关于作者

**AI酋长Andy** | 前腾讯/百度 AI 产品专家

- 🚀 大模型独角兽 VP → 创业 CEO
- 🎯 AI 商业战略顾问，服务高净值创始人与 QS100 留学生
- 📚 「AI + MBTI 人生管理」课程创始人
- 💡 专注用 AI 放大个人 IP 与商业影响力

**微信**：AIPMAndy ｜ **公众号**：AI酋长Andy

---

## 这套系统能帮你做什么？

| 痛点 | 解决方案 |
|------|----------|
| MBTI 内容同质化严重，写不出差异化 | 独创「风格DNA」系统，确保每篇文章辨识度拉满 |
| 选题靠灵感，爆款全凭运气 | 5大已验证高流量系列 + 选题公式，批量产出爆款 |
| AI 生成内容太机械，没有人味 | Few-shot 样本库 + 质量检查清单，输出像朋友聊天 |
| 想做 MBTI 账号但不知从何下手 | 开箱即用的提示词系统，10分钟上手 |

---

## 文件结构

```
mbti-ai-prompts/
├── prompts/
│   ├── 01-system-prompt.md      # 核心系统提示词（风格DNA）
│   ├── 02-topic-generator.md    # 选题生成提示词
│   └── 03-copywriter.md         # 文案生产提示词
├── samples/
│   └── style-samples.md         # 爆文样本库
└── README.md
```

## 快速开始

### 方式一：直接使用（任意 LLM）

1. 将 `01-system-prompt.md` 作为 System Prompt
2. 选择 `02-topic-generator.md` 或 `03-copywriter.md` 中的模块
3. 替换 `{...}` 占位符
4. 发送给 GPT-4 / Claude / 其他大模型

### 方式二：集成到 OpenClaw / 飞书机器人

```yaml
name: "Andy写作助手"
system_prompt: |
  # 从 01-system-prompt.md 复制完整内容
  ...

tools:
  - web_search  # 热点追踪

commands:
  - trigger: "/选题"
    prompt: |
      # 从 02-topic-generator.md 选择模块
  - trigger: "/写文"
    prompt: |
      # 从 03-copywriter.md 选择模块
```

## 高流量选题公式

```
[人格类型] + [情绪状态/困境] + [解决方案/新视角]
```

**已验证系列**：
- 🔮 **穿越系列**：当[人格]穿越到[场景]
- 🚀 **改命系列**：[人格]如何借AI改命
- 📈 **进化系列**：[人格]从低阶到高阶
- 💪 **习惯系列**：这N个习惯让[人格][获得某种状态]
- ✨ **相遇系列**：当[人格]遇到[某事物]

## 风格DNA

**必须遵守**
- 开篇：「我是 Andy。」
- 结尾：「我是 Andy。愿你...」
- 称呼：「亲爱的 XXXX」
- 段落：自然过渡，无序号

**绝对禁止**
- ❌ 序号（第一、第二、首先、其次）
- ❌ 加粗符号
- ❌ Emoji 滥用
- ❌ 感叹号滥用
- ❌ 「让我们」「接下来」

## 质量检查清单

- [ ] 开篇是否为「我是 Andy。」
- [ ] 是否存在序号标记
- [ ] 是否存在加粗符号
- [ ] 结尾是否规范
- [ ] 字数是否达标（1200-2000）
- [ ] 是否有具体场景支撑
- [ ] 是否像朋友聊天

---

## 为什么开源？

MBTI 内容赛道正在爆发，但大多数创作者还在用最原始的方式写内容。

我把自己验证过的方法论开源出来，希望能帮到更多想做 MBTI 内容的朋友。

如果这套系统对你有帮助，欢迎：
- ⭐ Star 这个项目
- 🔀 Fork 并改造成你自己的风格
- 💬 提 Issue 交流想法

---

## 📄 许可证 / License

Apache License 2.0 + Additional Terms

**✅ Allowed / 允许**
- Personal learning / 个人学习
- Internal enterprise use / 企业内部使用
- Open source citation (keep author info) / 开源引用（保留作者信息）

**❌ Prohibited (without authorization) / 禁止（未授权）**
- De-branding / 去品牌化
- Commercial SaaS / 商业 SaaS
- Resale / 转售倒卖

**Commercial licensing / 商业授权联系**：WeChat AIPMAndy

---

<p align="center">
  ⭐ If this helps, please give it a star! / 觉得有用请点个 Star！
</p>

**Copyright © 2026 AI酋长Andy. All rights reserved.**
