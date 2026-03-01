# 🧠 MBTI × AI 内容创作提示词系统

> 16种人格 × AI深度洞察 = 精准触达百万读者的内容引擎

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

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

## 核心指令

| 指令 | 功能 | 示例 |
|------|------|------|
| `/选题 热点` | 基于 AI 热点生成选题 | 输入热点新闻 |
| `/选题 组合` | AI话题 × MBTI 创意组合 | 随机生成10个选题 |
| `/选题 复刻 [标题]` | 分析爆款并复刻 | `/选题 复刻 当INFJ遇到外星人` |
| `/写文 [选题]` | 生成完整深度文案 | `/写文 INTJ如何借AI改命` |
| `/写文 改命 [人格]` | AI改命系列 | `/写文 改命 INFJ` |
| `/写文 穿越 [人格]` | 穿越古代系列 | `/写文 穿越 INTP` |
| `/写文 进化 [人格]` | 低阶到高阶系列 | `/写文 进化 INFP` |

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

## 联系我

- **微信**：AIPMAndy
- **公众号**：AI酋长Andy
- **课程咨询**：AI + MBTI 人生管理（4-6周系统课）

---

**Created by AI酋长Andy** | 用 AI 放大你的影响力
