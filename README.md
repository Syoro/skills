
# Skills

My reusable skills for Codex and other AI coding agents.

[简体中文](#%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87) | [English](#english)
## 简体中文

### [plan-doc-map](./plan-doc-map/SKILL.md)

将开发计划、Spec 和相关设计资料整理为面向开发者的评审指南，说明整体方案、模块关系、关键取舍、待决问题，并保留原文溯源。适用于方案评审、讲解和设计回顾。

#### 安装

克隆仓库后，将 skill 目录复制到 Codex 的个人 skills 目录：

~~~sh
git clone https://github.com/Syoro/skills.git
mkdir -p ~/.codex/skills
cp -R skills/plan-doc-map ~/.codex/skills/
~~~

如果要只在单个项目中使用，将 plan-doc-map 复制到该项目的 .agents/skills/ 目录。

使用此 skill 生成的指南可能会汇总计划、规格、源代码和日志中的信息。分享生成的指南前，请确认源材料允许对外公开，并检查其中的敏感信息。

## English

### [plan-doc-map](./plan-doc-map/SKILL.md)

Turn plans, specs, and related design materials into a developer-facing review guide. It explains the overall approach, module relationships, key tradeoffs, open questions, and links back to the source materials.

#### Installation

Clone this repository and copy the skill directory into your personal Codex skills directory:

~~~sh
git clone https://github.com/Syoro/skills.git
mkdir -p ~/.codex/skills
cp -R skills/plan-doc-map ~/.codex/skills/
~~~

For project-specific use, copy plan-doc-map into the project's .agents/skills/ directory.

Guides created with this skill may summarize information from plans, specifications, source code, and logs. Before sharing a generated guide, confirm that the source materials may be shared and check for sensitive information.
