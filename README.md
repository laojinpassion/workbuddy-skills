# 老金 WorkBuddy 技能库

本仓库收录由「老金」出品、用于 WorkBuddy 的实用技能（Skill），均已按 SkillHub / WorkBuddy 规范整理，可直接导入或发布到技能市场。

## 技能清单

| 技能 | 目录 | 功能简介 |
|---|---|---|
| 老金—招商画像分析 | `laojin-zhaoshang-huaxiang-fenxi/` | 根据招商人员对潜在加盟商的自然语言描述，从十个维度提取证据并评分，输出合作意愿、落地准备度、决策可达性、信息完整度四项判断与跟进优先级（A/B/C/D/待补充）、可执行行动计划。 |
| 老金—客户对话拆解 | `laojin-kehu-duihua-chaijie/` | 将已脱敏的客户对话、询盘或会议笔记拆成客户需求、成交阻力、缺失信息、可编辑回复和下一步行动，辅助销售/咨询在回复客户前理清判断。 |

## 安装方式

### 方式一：本地导入 WorkBuddy
将对应技能目录复制到 `~/.workbuddy/skills/`（Windows：`C:\Users\<用户名>\.workbuddy\skills\`），重启 WorkBuddy 即可在技能列表中看到，触发词含「老金」。

### 方式二：从 SkillHub 市场安装
在 SkillHub（`skillhub.cn`）或 WorkBuddy 技能市场搜索「老金」，一键安装。

### 方式三：命令行安装（SkillHub CLI）
```bash
skillhub install laojin-zhaoshang-huaxiang-fenxi
skillhub install laojin-kehu-duihua-chaijie
```

## 目录约定
- 每个子目录即为一个独立技能，含 `SKILL.md`（必需）及可选 `README.md`、`examples/` 等。
- 技能包内**不含** `LICENSE` 文件（SkillHub 市场规范不允许），仓库根目录的 `LICENSE` 仅作用于本 GitHub 仓库。

## 许可证
本仓库代码以 MIT 许可证发布，详见 [LICENSE](LICENSE)。
