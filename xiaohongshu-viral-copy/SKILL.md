---
name: xiaohongshu-viral-copy
description: Generate, rewrite, critique, and optimize Xiaohongshu-style Chinese social media notes, viral titles, cover text, image-cover prompts, comments, and hashtags. Use when the user asks for 小红书文案, 爆款笔记, 种草文案, 标题优化, 封面标题, 小红书封面提示词, 口播转笔记, 仿写爆款结构, or content tailored for Xiaohongshu.
---

# Xiaohongshu Viral Copy

## Workflow

1. Identify the task: generate from scratch, rewrite, critique, title-only, cover-only, or template extraction.
2. Extract the post goal: seeding/conversion, experience sharing, review, tutorial, local visit, personal IP, or lead generation.
3. Collect or infer the input brief: product/topic name, price or offer, core selling points, audience profile, user pain, usage scene, proof, tone, forbidden claims, CTA, category, and required visual output.
4. Choose a note type before writing: product review, tutorial, knowledge explainer, pain-point solution, comparison review, collection/list, experience story, local visit, case study, or trend commentary.
5. If key inputs are missing, make reasonable assumptions and state them briefly. Ask only when legal, medical, financial, or brand-risk details are necessary.
6. Draft in platform-native short paragraphs: concrete scene first, useful details second, soft interaction last.
7. Produce multiple title angles, one polished note, cover text, comment prompt, and tags unless the user asks for a narrower output.
8. Run the quality and risk checks before finalizing.

## Reference Loading

- Read `references/title-patterns.md` for title-only work, weak hooks, or requests for more headline options.
- Read `references/copy-structures.md` for full notes, rewrites, and template extraction.
- Read `references/category-styles.md` when the user provides a category such as beauty, education, local shops, fitness, travel, food, AI tools, or career.
- Read `references/cover-prompts.md` when generating cover text, image-generation prompts, or note illustration prompts.
- Read `references/tag-strategy.md` when tags are requested, tags feel generic, or the user wants SEO/discovery optimization.
- Read `references/risk-checks.md` for regulated categories, strong claims, or ad-like copy.

## Default Output

Use this structure unless the user specifies another format:

```text
标题备选：
1.
2.
3.
4.
5.

正文：
...

封面文字：
主标题：
副标题：
角标/贴纸：

评论区引导：
...

话题标签：
#... #... #...

配图提示词：
...
```

## Style Rules

- Write in simplified Chinese unless the user asks otherwise.
- Prefer real-person phrasing, short sentences, concrete details, and specific scenes.
- Use emojis lightly: useful for rhythm and scannability, not as decoration on every sentence.
- Avoid mechanical connectors: `首先`, `其次`, `然而`, `总的来说`, `最后`.
- Avoid empty hype such as `绝绝子`, `闭眼入`, `天花板`, `全网最强` unless the user explicitly requests exaggerated internet slang.
- Prefer soft CTAs: ask for comments, saves, or use-case sharing instead of hard selling.
- Do not fabricate personal experience, test data, expert endorsement, prices, policies, medical effects, or income results.
- Use stronger internet slang only when the requested persona calls for it. Keep the default more credible than shouty.

## Quality Check

Before finalizing, verify:

- The first line gives a reason to continue reading.
- The title set covers different angles instead of repeating one formula.
- Benefits are concrete, not generic adjectives.
- The post sounds like a person with a point of view, not a press release.
- Tags include 3-6 precise SEO-style tags plus broader category tags when useful.
- Claims are compliant and do not imply guaranteed results.
