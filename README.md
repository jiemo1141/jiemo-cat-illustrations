# 介墨小黑猫怪诞正文配图

**—— 把中文文章里的判断、流程、状态和隐喻，变成一张张白底、手绘、怪诞但清爽的正文配图。**

16:9 横版 | 小黑猫 IP | 纯白手绘 | 少量红橙蓝中文批注 | Codex / Hermes Skill

---

## 这个仓库是什么

介墨小黑猫怪诞正文配图（jiemo-cat-illustrations）是一个 AI Agent Skill，用来为中文文章、帖子、博客、Notion 文档和方法论内容生成正文配图。

它不是通用插画 prompt，也不是 PPT 信息图模板。它的核心目标是：先理解文章里的认知锚点，再把其中一个判断、流程、结构、状态或隐喻，变成一张有记忆点的 16:9 手绘解释图。

默认视觉 IP 是"小黑猫"：一只黑色圆润团子身体、黄色大眼睛、粉色小鼻子和腮红、表情丰富的小猫。小黑猫不是吉祥物，不是贴纸，也不是蹲在角落里卖萌的装饰品，而是正在认真参与系统运转的荒诞工作者。

**一句话：让 AI 不只是"配一张图"，而是把文章里的一个关键认知动作画出来。**

## 适合谁用

**特别适合：**
- 写中文文章，需要正文配图和文章插图的人
- 做知识型内容、方法论内容、AI 工作流内容的人
- 想把抽象判断画成具体隐喻的人
- 想要一种比 PPT 信息图更轻、更怪、更有个人识别度的配图风格的人
- 用 Codex 或 Hermes 做内容生产，希望稳定复用一套视觉语言的人

**不适合：**
- 想要商业插画、品牌 KV 或精致扁平插画的人
- 想要传统 PPT 信息图、复杂架构图或流程图的人
- 想要儿童卡通、可爱 IP、表情包风格的人
- 想把大量正文、长段解释或完整课程页塞进一张图里的人

## 使用方式

### 在 Codex 中使用

```
Use $jiemo-cat-illustrations 把下面这篇文章生成 4 张小黑猫怪诞正文配图。
要求：16:9 横版、纯白背景、黑色手绘线稿、少量红橙蓝中文手写批注。
每张图只讲一个核心结构，不要做 PPT 信息图，不要可爱卡通。

<粘贴文章>
```

### 在 Hermes 中使用

加载 skill 后，直接说：

> 用 jiemo-cat-illustrations 给这篇文章配图

详细工作流见 `jiemo-cat-illustrations/SKILL.md`。

## 目录结构

```
jiemo-cat-illustrations/
├── README.md
├── NOTICE.md
├── LICENSE
├── assets/
│   └── examples/          # 示例配图
└── jiemo-cat-illustrations/
    ├── SKILL.md            # 核心 skill 指令
    └── references/
        ├── style-dna.md           # 风格 DNA、颜色、禁忌
        ├── cat-ip.md              # 小黑猫 IP 设定
        ├── composition-patterns.md # 构图模式与原创规则
        ├── prompt-template.md     # 生图提示词模板
        └── qa-checklist.md        # 生成后检查清单
```

## 设计理念

纯白、极简、手绘、留白、克制、怪诞、产品草图感、中文手写感、结构清楚但不说明书。

像一个长期做 AI、产品、设计、开发工具的人，在白纸上随手画出来的一张解释草图。

要怪诞、创意、有意思、简洁清爽、天马行空。不要可爱、幼稚、复杂、死板。

## 致谢

本技能基于 [Ian Xiaohei Illustrations](https://github.com/helloianneo/ian-xiaohei-illustrations)（by [helloianneo](https://github.com/helloianneo)）改编，视觉 IP 从"小黑"替换为"小黑猫"。感谢 Ian 贡献了优秀的 skill 框架和风格体系。

## License

MIT
