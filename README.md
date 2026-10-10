# workplace-writing

> 职场写作助手 Agent Skill

把一个写作需求变成能直接用的稿子：有数据就写实；没数据、或者说不清来源的数字，一律给骨架，不编。

适用：年终总结、述职报告、进展汇报、调查报告、请示、批复、加薪申请、邮件、会议记录、工作计划、项目计划书、活动方案、商业计划书。

## 安装

```bash
# 方式一：skills CLI
npx skills add git@github.com:gaorun/workplace-writing.git

# 方式二：直接 cat 进 context
```

## 文件

| 文件 | 职责 |
|---|---|
| `SKILL.md` | 跨类型的规则与流程——**行为以这里为准** |
| `types.md` | 每种文案的类型卡片：提问清单、数据框架、金字塔结构、写作要点、成品示例；另有 SCQA 示例库 |

这份 README 只用于介绍与安装，**不描述流程**：规则和流程只在 `SKILL.md` 里写一处，避免两处漂移。

## License

MIT
