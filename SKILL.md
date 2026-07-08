---
name: xhs-prepublish-check
description: "Open Skill for checking Xiaohongshu / RedNote publish readiness before posting: title click reason, cover recognition, first lines or first seconds, keyword placement, audience fit, and truthful content promise. Use when the user asks for Xiaohongshu pre-publish check, RedNote publish readiness, XHS content review, title cover check, 小红书发布前检查, 发前检查, 标题封面检查, 前三行检查. This Skill uses user-provided material and public-safe reasoning only; it does not publish automatically, scrape private data, copy creators, or promise growth."
---

# Xiaohongshu Pre-Publish Check

## Purpose

发布前检查一条小红书 / RedNote 内容的标题、封面、前三行、关键词和内容承诺是否能发。

This is a lightweight standalone open Skill. It turns a repeated creator task
into a clear Agent workflow with inputs, checks, output shape, and boundaries.

## Use This For

- publish readiness score
- top 3 problems
- exact edits
- final title, cover, or opening suggestion
- keyword placement notes
- after-publishing data to watch

## Do Not Use This For

- automatic publishing
- private account login
- private data extraction
- guaranteed traffic, growth, sales, or viral outcomes
- copying another creator's exact wording, identity, images, or claims
- making claims that the user's material does not support

## Inputs

- title
- cover image or cover copy
- first 3 lines or first 3 seconds
- body copy, script, or page text
- keywords if available
- content goal: saves, comments, follows, leads, or sales

If the input is incomplete, proceed with a first-pass version and mark
assumptions. Ask only the smallest necessary follow-up when the missing detail
would materially change the result.

## Workflow

Read `references/workflow-rules.md` when the task needs the full rule set.

- Check whether the title has a concrete click reason.
- Check whether the cover says one clear thing.
- Check whether the first 3 lines or first 3 seconds create context fast.
- Check body specificity and user promise.
- Check natural keyword placement.
- Return exact fixes and the data to watch after publishing.

## Output Contract

```markdown
## 1. Scope And Assumptions

## 2. Input Reading

## 3. Main Judgment

## 4. Working Table Or Checklist

## 5. Recommended Next Action

## 6. Boundaries
```

## Quality Bar

- Be specific and operational.
- Prefer a small usable output over a broad lecture.
- Explain why each recommendation fits the user's material.
- Mark weak evidence instead of pretending certainty.
- Do not promise results.
- Do not copy another creator's protected expression or personal story.

## Tone

Write in the user's language. For Chinese creator tasks, default to clear,
practical Chinese.

## Public Boundary

Keep examples generic. Do not include internal thread IDs, private file paths,
unpublished customer material, private account data, or internal product notes.
