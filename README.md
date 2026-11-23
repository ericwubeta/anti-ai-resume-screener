# 反AI简历筛查助手Pro (Anti-AI Resume Screener Pro)

> Claude Code 技能 — 帮助求职者优化简历以通过 ATS 系统和 AI 筛选

## 功能

- **简历诊断** — 100分制 ATS 友好度检测，格式/关键词/量化/STAR 多维度评分
- **关键词优化** — 根据 JD 提取关键词，生成匹配度报告
- **内容改写** — STAR 法则 + 弱词替换 + 量化描述
- **求职文案** — 60秒电梯演讲 + 求职信生成
- **面试准备** — 5类高频面试题预测 + 回答框架

## 安装

将此文件夹放入 Claude Code 的 skills 目录：

```
.claude/skills/anti-ai-resume-screener-1.0.0/
├── SKILL.md
├── _meta.json
├── references/
│   ├── ats-optimization-guide.md
│   ├── resume-frameworks.md
│   └── star-examples.md
└── templates/
    └── resume-template.md
```

## 使用

在 Claude Code 中触发：

- 提供简历 → 自动进入诊断流程
- "帮我优化简历" / "ATS 检测" / "简历被刷了"
- "根据这个 JD 优化简历"
- "帮我写自我介绍" / "面试准备"

## 许可

本仓库当前修订中由 **ericwubeta** 创作并有权授权的 Skill 指令、指南、示例和模板采用 [CC BY-SA 4.0](LICENSE)。分享原文或改编时请保留署名和许可链接。分享改编时须标明修改并采用 CC BY-SA 4.0 或其允许的兼容许可。第三方内容按各自条款处理，[旧修订](https://github.com/ericwubeta/anti-ai-resume-screener/blob/4bb7fb123d0beff2479d673dd03007d2d6e016e4/README.md#许可)沿用当时的许可声明。
