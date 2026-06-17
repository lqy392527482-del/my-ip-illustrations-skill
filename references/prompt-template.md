# 生图提示词模板

Generate each image separately. Replace the variables with article-specific content.

```text
Generate one standalone 16:9 horizontal Chinese article illustration.

Use the provided character reference if available: assets/reference/ip-character.png.

Visual DNA:
Clean white background. Warm hand-drawn pencil/crayon sketch style. Slightly rough black/dark-brown outlines, visible sketch texture, simple shapes, lots of empty white space. Sparse handwritten Chinese labels with restrained red/orange/blue accents. Friendly creator-notebook feeling. No gradients, no shadows, no paper texture, no realistic UI, no glossy anime poster, no commercial vector style, no PPT infographic look, no dense formal flowchart.

Recurring IP character required:
我的IP少年, a hand-drawn chibi young man based on the reference image: fluffy black middle-part hair with messy sketch strands, large round brown-black eyes with white highlights, peach skin, small calm smile, light cheek blush, black short-sleeve T-shirt, dark charcoal cuffed pants, bright blue sneakers with white details. Keep him warm, curious, focused, and useful. He must perform the core conceptual action, not decorate the scene. Do not replace him with a black creature or generic mascot.

Theme:
{正文配图主题}

Structure type:
{结构类型：Workflow / 系统局部 / 前后对比 / 角色状态 / 概念隐喻 / 方法分层 / 地图路线 / 小漫画分镜}

Core idea:
{这张图要表达的核心意思}

Composition:
{具体画面：我的IP少年在哪里、正在做什么、主要物件是什么、信息如何流动}

Suggested elements:
{元素1} / {元素2} / {元素3} / {元素4}

Chinese handwritten labels:
{标注词1} / {标注词2} / {标注词3} / {标注词4} / {可选标注词5}

Color use:
Black and dark brown for line art, hair, shirt, and main objects. Peach for skin and blush. Dark gray for pants. Bright blue for sneakers and occasional small accent. Orange for main flow/path/arrows. Red only for warnings/problems/key reminders. Blue only for secondary notes or feedback/system state.

Constraints:
One image explains only one core structure. Keep the main subject around 40%-60% of the canvas. Preserve at least 30%-35% blank white space. Use at most 5-8 short handwritten Chinese labels. Do not write a title in the top-left corner. Do not write the structure type on the image. Do not make it a formal diagram, course slide, sticker sheet, or dense explainer. Keep the IP boy recognizable from the reference: fluffy black hair, big eyes, blush, black T-shirt, dark pants, blue sneakers. Invent a fresh visual metaphor for this specific article. It should be clear, warm, slightly playful, and useful.
```

## Image Edit Prompts

Remove top-left title:

```text
Edit the provided image. Remove only the handwritten title "{要删除的文字}" and its underline from the top-left corner. Fill that area with the same clean white background. Preserve everything else exactly: character, labels, paths, hand-drawn line style, composition, aspect ratio, and image quality. Do not add any new text or objects.
```

Improve IP consistency:

```text
Regenerate this illustration with the same core meaning and simple layout, but make 我的IP少年 match the reference more clearly: fluffy black middle-part hair, large brown-black eyes with highlights, peach skin, cheek blush, black T-shirt, dark cuffed pants, bright blue sneakers. Keep him doing the core action, not standing beside the scene.
```

Increase character participation:

```text
Regenerate this illustration with the same core meaning, but make 我的IP少年 the person who physically causes the idea to work. He should carry, connect, sort, open, repair, or assemble the key object. Keep the image clean, white, sparse, hand-drawn, and article-friendly.
```
