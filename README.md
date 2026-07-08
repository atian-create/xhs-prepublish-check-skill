# 小红书发布前检查 Skill

这是一个给小红书 / RedNote 创作者用的开源轻量 Skill：当你已经写好标题、封面、前三行、正文或口播稿，准备发布前，它帮你做最后一遍“能不能发”的检查。

很多内容不是完全不能发，而是发布前有几个关键点没对齐：

- 标题有关键词，但没有点击理由。
- 封面好看，但用户第一眼不知道解决什么问题。
- 前三行铺垫太长，没有进入痛点或结果。
- 正文有价值，但太散，看不出收藏点。
- 关键词填了，但没有自然出现在标题、封面和正文开头。

这个 Skill 就像一个发布前质检员：它不只是说“优化一下”，而是指出哪里漏用户、哪里不清楚、发布前应该改哪一句。

## 你下载后可以用它做什么

- 检查小红书标题有没有明确点击理由。
- 检查封面文案是不是一眼能懂。
- 检查前三行或前三秒是否快速进入用户问题。
- 检查正文是否具体、是否能承接标题承诺。
- 检查关键词是否自然埋入。
- 给出发布准备度评分。
- 输出可以直接替换的标题、封面或开头修改建议。
- 提醒发布后应该看什么数据。

## 适合谁

- 内容已经快写完，但发之前总觉得不踏实的人。
- 经常标题、封面、正文各写各的创作者。
- 想提高小红书图文发布稳定性的运营者。
- 给客户做发布审核，需要一套固定检查表的人。
- 想让 Agent 做发布前最后一轮检查的人。

## 为什么这个 Skill 值得单独装

普通润色会把句子变顺，但不一定能发现发布风险。

这个 Skill 会按发布链路检查：

1. 用户为什么点。
2. 第一眼看到了什么。
3. 前三行有没有留住人。
4. 正文有没有兑现承诺。
5. 关键词有没有自然出现。
6. 发布后应该观察哪一个指标。

它的目标不是让文案更华丽，而是让内容更清楚、更能被理解、更适合发布。

## 3 分钟上手

把这个仓库里的 `SKILL.md` 放到你的 Agent Skill 目录，然后这样问：

```text
用 xhs-prepublish-check 帮我做发布前检查。
标题：你缺的不是 AI 工具
封面：AI 内容流程
前三行：我最近发现很多人收藏了很多工具，但还是发不出来。
正文概要：讲从选题、写稿到复盘的三步流程。
目标：收藏和关注
关键词：AI 工具、内容流程、小红书运营
```

## 你会拿到什么结果

默认输出会包括：

- 发布准备度评分。
- 最重要的 3 个问题。
- 可以直接修改的标题/封面/前三行建议。
- 关键词埋入提醒。
- 这条内容发布后最应该看的数据。
- 下一条内容的一个小实验方向。

## 公开版边界

这个开源版只基于你提供的草稿、截图或文本做判断。它不登录平台，不自动发布，不保证流量结果，也不替代平台规则审核。它的作用是帮你在按下发布前少漏关键问题。

## Search Keywords

English keywords:

`Xiaohongshu pre-publish check`, `RedNote publish readiness`, `XHS content review`, `title cover check`, `social media publishing checklist`, `keyword placement check`, `creator workflow`, `AI skill for creators`.

中文关键词：

`小红书发布前检查`, `发前检查`, `标题封面检查`, `前三行检查`, `关键词检查`, `内容能不能发`, `小红书发布清单`, `创作者工具`.

## Why This Exists


Many posts are almost ready, but one weak link makes them hard to click, understand, save, or trust.
This Skill gives a publish-readiness check before posting, with exact edits rather than broad advice.

## What It Can Do

- publish readiness score
- top 3 problems
- exact edits
- final title, cover, or opening suggestion
- keyword placement notes
- after-publishing data to watch

## Best Inputs

- title
- cover image or cover copy
- first 3 lines or first 3 seconds
- body copy, script, or page text
- keywords if available
- content goal: saves, comments, follows, leads, or sales

## Workflow

- Check whether the title has a concrete click reason.
- Check whether the cover says one clear thing.
- Check whether the first 3 lines or first 3 seconds create context fast.
- Check body specificity and user promise.
- Check natural keyword placement.
- Return exact fixes and the data to watch after publishing.

## Output Contract

Default output:

1. Scope and assumptions
2. Input reading
3. Main judgment
4. Structured table or checklist
5. Recommended next action
6. Boundary notes

For detailed rules, see `references/workflow-rules.md`.

## Example Prompt

```text
Use $xhs-prepublish-check for this task:
Title: 你缺的不是 AI 工具
Cover: AI 内容流程
First 3 lines: 我最近发现很多人收藏工具但还是发不出来...
Goal: saves and follows
```

## Example Output Shape

See `examples/sample-output.md` for a short sample.

## Open-Source Boundary

This standalone open version includes:

- reusable creator workflow instructions
- input and output contracts
- workflow rules
- example output
- Agent metadata
- MIT license

This standalone open version does not include:

- private platform credentials
- automatic publishing
- private analytics connectors
- scraping or monitoring
- guaranteed traffic, growth, sales, or viral outcomes
- copying another creator's content
- internal operating notes or private project context

## Repository Map

- `SKILL.md`: Agent entrypoint and workflow rules
- `agents/openai.yaml`: Agent display metadata
- `references/workflow-rules.md`: detailed workflow and quality rules
- `examples/sample-output.md`: sample input and output shape
- `LICENSE`: MIT license

## Recommended GitHub Description

> Open Skill for checking Xiaohongshu / RedNote publish readiness before posting: title click reason, cover recognition, first lines or first seconds, keyword placement, audience fit, and truthful content promise.

## Suggested GitHub Topics

`prepublish-check`, `xiaohongshu`, `rednote`, `creator-tools`, `content-workflow`, `social-media`, `publishing-checklist`, `ai-skill`, `open-source`

## License

MIT
