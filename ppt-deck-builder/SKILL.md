---
name: ppt-deck-builder
description: Plan, write, design, build, critique, and verify presentation decks for business reports, pitches, roadshows, product launches, training, academic talks, and executive briefings. Use when the user asks for PPT, PowerPoint, PPTX, slide deck, presentation outline, deck rewrite, roadshow deck, investor deck, speaker notes, visual style, or turning documents into slides.
---

# PPT Deck Builder

## Workflow

1. Identify the deck mode: outline-only, content fill, full PPTX creation, deck critique, redesign guidance, speaker notes, or roadshow/video script.
2. Extract the brief: topic, audience, goal, page count, source material, language, brand/style, deadline, output format, and required depth.
3. Choose a deck type and story structure before writing.
4. Build a page plan with one core message per slide.
5. Write slide content in short, presentation-native phrasing, with supporting detail in notes.
6. Define the visual system: layout rhythm, colors, typography, chart style, image direction, and icon/diagram needs.
7. If generating files, use the available presentation/PPTX tooling and produce editable slides where possible.
8. Verify the deck: narrative flow, text density, layout consistency, visual hierarchy, source fidelity, and file renderability.

## Reference Loading

- Read `references/deck-types.md` when selecting structure, page count, or narrative sequence.
- Read `references/slide-writing.md` when drafting or rewriting slide content.
- Read `references/visual-system.md` when choosing style, layouts, images, charts, or visual prompts.
- Read `references/pptx-build-checklist.md` when generating or reviewing a PPTX file.
- Read `references/roadshow-video.md` when the user asks for roadshow scripts, voiceover, subtitles, or video adaptation.

## Default Deliverable

Unless the user asks only for a file, first produce or internally build:

```text
Deck brief:
- Audience:
- Goal:
- Tone:
- Page count:

Slide plan:
1. [Title] - [One-sentence message] - [Layout]
2. ...

Visual direction:
- Style:
- Color:
- Imagery:
- Chart/diagram approach:

Build/verification:
- Output:
- Checks performed:
```

For full deck creation, include speaker notes when useful. Keep notes separate from visible slide text.

## Content Rules

- One slide, one message. Do not make slides into document pages.
- Keep visible text short: titles should be decisive; bullets should be parallel and scannable.
- Put nuance, caveats, citations, and narration in speaker notes.
- Use data visuals for comparisons, trends, shares, funnels, timelines, and systems instead of dense prose.
- Preserve user-provided facts. Do not invent numbers, clients, credentials, logos, citations, or market claims.
- For investor, medical, legal, financial, or public company decks, mark assumptions clearly and avoid unsupported claims.

## Build Rules

- Prefer editable PPTX output when the user asks for a deck file.
- Use 16:9 widescreen unless the user specifies another aspect ratio.
- Use a consistent layout grid, title position, typography scale, and color system.
- Add diagrams, charts, or images only when they clarify the message.
- Render or inspect generated decks when possible before final delivery.
- If a requested output cannot be generated in the current environment, deliver the structured slide plan and explain what remains.

## Quality Gate

Before finalizing, check:

- The opening establishes why the topic matters.
- The sequence has a clear beginning, middle, and end.
- Each slide has a distinct purpose.
- No slide depends on unexplained jargon.
- Text fits within slide bounds.
- Visual style is consistent across cover, section, content, data, and closing slides.
- The final slide gives a useful takeaway or action, not just `Thank you`.
