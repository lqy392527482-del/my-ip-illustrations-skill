---
name: my-ip-illustrations
description: Generate Chinese article illustrations using the user's hand-drawn boy IP character. Use when Codex is asked to create, plan, revise, or prompt 16:9 Chinese article images, post illustrations, blog visuals, Notion/document illustrations, workflow sketches, concept metaphors, shot lists, or image edits in the user's IP style; default to the boy character reference, clean white hand-drawn visual style, sparse Chinese handwritten labels, and article-friendly composition.
---

# 我的IP少年正文配图

## Core Positioning

Design and generate 16:9 horizontal illustrations for Chinese articles, posts, blogs, Notion pages, product notes, workflow documents, and methodology writing. The goal is not a PPT infographic or generic cartoon poster. Convert one key judgment, flow, structure, state, or metaphor from the text into a clean hand-drawn article illustration with the user's recurring IP character.

Default visual IP is "我的IP少年": a hand-drawn chibi young man with fluffy black middle-part hair, large brown-black eyes with highlights, soft peach skin, small smile, blush marks, black T-shirt, dark cuffed pants, and bright blue sneakers. He must participate in the core conceptual action of the image, not stand as decoration.

## Read References As Needed

- `references/ip-character.md`: character identity, visual traits, personality, action library, and constraints.
- `references/style-dna.md`: visual style, palette, typography, and forbidden looks.
- `references/composition-patterns.md`: structure types, metaphor generation, and anti-copy rules.
- `references/prompt-template.md`: single-image generation prompt template and image edit prompts.
- `references/qa-checklist.md`: post-generation checks and iteration rules.
- `assets/reference/ip-character.png`: primary visual reference for the IP character. Use it for character consistency; do not copy the exact standing pose unless the user asks.

## Workflow

### 1. Digest The Text

Read the user's article, link, Notion page, Markdown file, screenshot, or concept. Extract:

- The core point.
- The cognitive turn or memorable judgment.
- The parts that benefit from a visual metaphor.
- The parts that should stay as text.

Do not illustrate evenly. Prefer cognitive anchors such as a key judgment, before/after contrast, input-output loop, handoff path, failure point, role change, system bottleneck, or a surprising method.

### 2. Provide A Shot List When Planning

If the user asks for analysis, planning, "where should I add images", or "shot list", do not generate images yet. Output 1-8 illustration ideas depending on text length. For each image include:

- Placement after which section or paragraph.
- Theme.
- Core meaning.
- Structure type.
- What the IP boy is doing.
- Suggested elements.
- Suggested Chinese handwritten labels.

### 3. Generate One Image At A Time

If the user asks to generate, output, make, or revise images, use the available image generation tool for each image separately. Do not combine multiple illustrations into one collage.

Each prompt must include:

- 16:9 horizontal Chinese article illustration.
- Clean white background.
- Hand-drawn pencil/crayon line texture.
- The user's IP boy as the core action subject.
- Character consistency with `assets/reference/ip-character.png`.
- Sparse Chinese handwritten labels.
- Enough whitespace.
- Avoid PPT, commercial vector art, realistic UI, dense diagrams, and childish sticker-poster composition.

### 4. Check And Iterate

After generation, check `references/qa-checklist.md`. Regenerate or edit when:

- The IP boy is missing or only decorative.
- Hair, face, clothing, or blue sneakers drift too far from the reference.
- The image becomes a cute mascot poster instead of an article illustration.
- The canvas is too dense or too much like PPT.
- Chinese labels are too long, too many, or unreadable.
- The background is not clean white.

### 5. Save Deliverables

When working inside a workspace, save final images under:

```text
assets/<article-slug>-illustrations/
```

Name images in order:

```text
01-topic-name.png
02-topic-name.png
```

Preserve original generated files. Do not overwrite existing assets unless the user explicitly asks.

## Output Style

Keep pre-generation strategy short and specific. For generated deliverables, state:

- How many images were generated.
- What each image is for.
- Where the files were saved.
- Which images are strongest and which are optional.
