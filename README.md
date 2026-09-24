# RCA 根因分析师 - AI 技能

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

对软件问题进行系统化根因分析（5 Whys），生成结构化分析报告。

## 特性

- **IDE 无关** - 自然语言描述操作，不绑定特定工具名
- **结构化输出** - 标准化 Markdown 报告：5 Whys 分析、方案对比、实施路线图
- **沙盒隔离** - 所有产物仅写入 `.rca/` 目录，不污染项目

## 安装

将 `SKILL.md` 和 `WORKFLOW.md` 复制到你的 AI 技能目录中：

```bash
# CodeBuddy
~/.agents/skills/rca-analyst/

# Cursor
项目根目录 .cursor/

# Windsurf
项目根目录 .windsurfrules/
```

## 使用

```
帮我分析一下这个 Issue: https://github.com/xxx/yyy/issues/123
根因分析：用户登录后首页白屏，控制台报 500 错误
RCA 线上支付接口超时问题
```

分析完成后，报告保存到 `.rca/` 目录：

```
.rca/
  ISSUE_123_根因分析报告.md
  2025-05-04_登录白屏问题_根因分析报告.md
```

## 项目结构

```
rca-analyst-skill/
├── SKILL.md       # 技能定义（入口文件）
├── WORKFLOW.md    # 分析工作流指南
├── LICENSE
└── README.md
```

## 许可证

MIT License
