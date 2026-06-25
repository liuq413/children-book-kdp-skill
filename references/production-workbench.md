# Production Workbench

Use this reference when the user wants to make an actual children's picture book, especially when they have character reference images, a manuscript, or a specific story world. The goal is to organize production, not merely explain the process.

## When To Use Workbench Mode

Use workbench mode for requests like:

- "I have character design images. How do I make the book pages?"
- "Generate all page illustration prompts."
- "Turn this manuscript into a storyboard table."
- "Make this easier to produce in Canva."
- "Check whether these generated images are consistent."
- "Run the whole production workflow."

## Required Mindset

Do not stop at advice. Produce the working tables and prompt assets the user can use immediately.

When information is missing, use clearly labeled defaults and continue unless the missing detail would break production.

## Core Production Outputs

Reference visuals in the repository:

- `assets/production-workbench.png`: end-to-end workbench effect image.
- `assets/sample-spread.png`: sample picture-book spread mockup.
- `assets/character-bible.svg`: character consistency bible diagram.
- `assets/storyboard-layout.svg`: manuscript-to-layout diagram.

### 1. Project Setup Sheet

Use this schema:

| Field | Value |
| --- | --- |
| Book title |  |
| Age range |  |
| Theme |  |
| Core lesson |  |
| Page count |  |
| Words per page |  |
| Trim size |  |
| Art direction |  |
| Main character(s) |  |
| Publishing target |  |

### 2. Character Consistency Bible

If the user provides reference images, extract the visible design features first. If images are not available, create provisional character anchors and mark them as editable.

Use this schema:

| Character | Role | Fixed appearance | Clothing/accessories | Color anchor | Personality | Expression range | Do not change | Reusable prompt anchor |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |

Rules:

- The "Reusable prompt anchor" must be short enough to repeat in every page prompt.
- Include scale and body-shape notes when there are multiple characters.
- Avoid references to protected brands, known characters, or living artists.

### 3. World And Location Bible

Use this schema:

| Location | Visual identity | Color palette | Props | Lighting | Continuity notes |
| --- | --- | --- | --- | --- | --- |

For a town-based book, define recurring places such as central square, main street, character homes, garden, bakery, school, library, stage, or festival area.

### 4. Page-By-Page Storyboard Table

Use this schema:

| Page | Manuscript text | Scene action | Characters | Emotion | Composition | Background/props | Continuity notes |
| --- | --- | --- | --- | --- | --- | --- | --- |

Guidelines:

- Each page should have one clear imageable moment.
- Composition should tell the illustrator or image model what matters.
- Keep emotion explicit and child-readable.
- Track recurring props so they do not disappear.

### 5. Batch Illustration Prompt Table

Use this schema:

| Page | Image prompt | Negative prompt | Aspect/layout | Reference images to use | QA focus |
| --- | --- | --- | --- | --- | --- |

Prompt formula:

```text
Children's picture book illustration, [GLOBAL_ART_STYLE].
Use the character reference/anchor: [CHARACTER_ANCHOR].
Scene: [SCENE_ACTION].
Emotion: [EMOTION].
Composition: [COMPOSITION].
Background and props: [BACKGROUND_PROPS].
Continuity: [CONTINUITY_NOTES].
No text in image, no watermark, no logo, no extra limbs, keep character design consistent.
```

Negative prompt formula:

```text
text, watermark, logo, photorealistic style, scary expression, distorted face, extra fingers, extra limbs, inconsistent outfit, different character design, crowded unreadable composition
```

### 6. Three Test-Shot Prompts

Before generating all pages, create three test-shot prompts:

- Establishing page: usually page 1 or 2, tests world style.
- Emotion page: a middle page with a clear feeling, tests character acting.
- Finale page: last page or climax, tests lighting and group composition.

Output:

| Test shot | Page | Purpose | Prompt | What to inspect |
| --- | --- | --- | --- | --- |

### 7. Image Quality Review Checklist

Use this checklist after the user generates images:

| Check | Pass/Fail | Notes |
| --- | --- | --- |
| Character matches reference |  |  |
| Outfit/accessories consistent |  |  |
| Color palette consistent |  |  |
| Page emotion matches manuscript |  |  |
| Scene includes required props |  |  |
| No unwanted text/logos |  |  |
| Composition leaves room for text |  |  |
| Safe margins likely workable |  |  |
| Style matches previous pages |  |  |

If an image fails, provide a revision prompt rather than only saying what is wrong.

### 8. Canva Or Book Brush Layout Table

Use this schema:

| Page | Layout type | Text placement | Image crop | Safe margin notes | Spread notes |
| --- | --- | --- | --- | --- | --- |

Layout types:

- Full-bleed illustration with text box
- Illustration above, text below
- Text on left, illustration on right
- Full spread image
- Spot illustration with large white space

Rules:

- Do not place text over busy backgrounds.
- Reserve safe margin for all page text.
- Use consistent text placement patterns, but vary enough to keep page rhythm alive.

### 9. KDP Readiness Checklist

Use this concise final checklist:

| Area | Must check |
| --- | --- |
| Interior | Trim size, bleed, safe margins, image resolution |
| Cover | Front, back, spine, title readability, thumbnail readability |
| Text | Proofread, age fit, no text too close to edge |
| Art | Character consistency, no unwanted text, no protected IP imitation |
| Listing | Parent-benefit description, keywords, categories |
| Proof | Order proof copy or inspect exported PDF carefully |

## Chinese Workbench Output Labels

When replying in Chinese, use these labels:

1. 项目设定表
2. 角色一致性圣经
3. 小镇/世界观设定表
4. 逐页分镜表
5. 批量插图 Prompt 表
6. 三张试画 Prompt
7. 出图质量检查表
8. Canva/Book Brush 排版表
9. KDP 上架前检查表

## Compact User Prompt

```text
Use $children-book-kdp in production workbench mode.

Book title:
Age range:
Theme:
Lesson:
Page count:
Manuscript or outline:
Character reference images or descriptions:
Art style:
Trim size:

Output the project setup sheet, character bible, storyboard table, batch illustration prompt table, three test-shot prompts, image QA checklist, Canva layout table, and KDP readiness checklist.
```

## 中文快捷调用

```text
使用 $children-book-kdp 的生产工作台模式。

书名：
年龄段：
主题：
教育点：
页数：
手稿或故事结构：
角色设定图或角色描述：
艺术风格：
尺寸：

请输出：项目设定表、角色一致性圣经、小镇/世界观设定表、逐页分镜表、批量插图 Prompt 表、三张试画 Prompt、出图质量检查表、Canva 排版表、KDP 上架前检查表。
```
