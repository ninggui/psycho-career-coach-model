# 心理咨询师与职业发展规划师评估模型

![GitHub stars](https://img.shields.io/github/stars/ninggui/psycho-career-coach-model)
![License](https://img.shields.io/github/license/ninggui/psycho-career-coach-model)
[![SkillHub](https://img.shields.io/badge/SkillHub-在线安装-blue)](https://skillhub.cn/skills/psycho-career-coach-model)

把与 AI 的语音/聊天记录导出文字，用双角色提示词做全量心理+职业评估。

## 这是什么

一个可复用的 AI Agent 技能（Skill），来自真实业务场景沉淀，含完整执行流程、避坑清单与验证步骤。

## 快速使用

将本仓库放入 Agent 技能目录后，用对应触发词调用（见 SKILL.md），Agent 会自动加载并执行完整流程。

## 核心能力

| 能力 | 说明 |
|------|------|
| 语音记录导出与清洗 |
| 双角色评估提示词（咨询师+规划师） |
| 10 段结构化报告框架 |
| 成果链深化（人格/盲点/职业/简历/面试） |

## 使用方式（安装）

- **Hermes**: 放入 `skills/` 目录
- **Claude**: 放入 `~/.claude/skills/`
- **其他 Agent**: 按对应 SKILL.md 格式放入技能目录
- **SkillHub 一键安装**: https://skillhub.cn/skills/psycho-career-coach-model

## 优势

- 全量记录→结构化自我认知资产
- 提示词模板开箱即用
- 从心理评估到求职落地的完整链路

## 内容结构

- `SKILL.md` — 核心技能定义（触发条件、执行流程、避坑清单）
- `references/` — 可选参考文件

## 许可

MIT
