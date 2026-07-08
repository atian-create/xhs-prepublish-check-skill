# XHS Pre-Publish Check Skill

Open Skill for checking Xiaohongshu / RedNote publish readiness before posting: title click reason, cover recognition, first lines or first seconds, keyword placement, audience fit, and truthful content promise.

中文一句话：发布前检查一条小红书 / RedNote 内容的标题、封面、前三行、关键词和内容承诺是否能发。

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
