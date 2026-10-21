# Cyber Arcana 卡牌动效 Skill

这份 Codex Skill 用于制作 Cyber Arcana 单张网页卡牌动效：固定入场节奏、2:3 分层卡面、鼠标与触控视差、重播、七美德文案和每日幸运星。每张牌的主题事件与色彩可变化，动画结构保持一致。

## 使用

将本仓库放入 Codex 的 Skills 目录，或从仓库安装，然后在任务中说：

> 使用 `$cyber-tarot-card-motion` 为这张卡制作网页动效。

Skill 的完整步骤见 [SKILL.md](SKILL.md)，参数和验收清单见 [references/card-workflow.md](references/card-workflow.md)。

## 素材准备

执行单卡动效前，需提供已确认的红色「崩裂高塔」原版网页和它引用的背景、透明前景素材，以及目标卡的原画。原项目里的基准页面路径为 `outputs/portfolio-demo/public/tower-animation.html`。本仓库只发布 Skill 文档，不包含个人网站源码或卡牌原画；若当前工作区没有基准文件，先提供它们，再实施与原版一致的动效。
