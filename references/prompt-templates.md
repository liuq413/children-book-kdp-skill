# Prompt Templates

Use these templates as copy-ready prompt blocks. Preserve placeholders when the user has not provided details. Translate templates to the user's language when useful.

## 1. Idea Generator

```text
Act as a bestselling children's book author, child psychologist, and publishing expert.

Generate 20 original children's picture book ideas for children aged [AGE_RANGE] about [THEME].

Each idea must include:
- A memorable title
- A main character children can identify with
- The key lesson, value, or skill taught
- A brief plot summary
- A clear explanation of why parents would buy the book

Prioritize ideas that are emotionally appealing, highly marketable, visually strong, and capable of becoming illustrated books or successful series.
```

## 2. Story Structure

```text
Create a complete [PAGE_COUNT]-page children's picture book structure for children aged [AGE_RANGE].

The story should focus on [THEME] and teach [LESSON].
The main character is [CHARACTER_DESCRIPTION].

For each page, provide:
- Page number
- Story beat
- Suggested page text
- Illustration direction
- Emotional purpose of the page

The story should have a clear beginning, middle, and end, with the lesson shown through the character's actions.
```

## 3. Manuscript Writer

```text
Using the approved structure above, write the complete manuscript for a children's picture book for readers aged [AGE_RANGE].

Use approximately [WORDS_PER_PAGE] words per page.
Tone: [TONE].
Language style: simple, warm, concrete, rhythmic, and suitable for read-aloud sessions.

Requirements:
- Keep vocabulary age-appropriate
- Show the lesson through story events rather than explaining it directly
- Give each page a clear visual moment
- Avoid overly abstract language
- Output the manuscript page by page
```

## 4. Character Sheet

```text
Act as a professional children's book illustrator and character designer.

Create a detailed character sheet for [CHARACTER_NAME].

Character details:
- Species/type: [SPECIES_OR_TYPE]
- Age: [AGE]
- Personality traits: [TRAITS]
- Story role: [ROLE]
- Art style: [ART_STYLE]

Include:
- Physical appearance
- Clothing
- Accessories
- Color palette
- Facial expressions
- Body language
- Distinctive features
- Do and don't rules for consistency
- A short consistency anchor that can be reused in every illustration prompt

The design must fit a children's picture book and remain consistent across all illustrations in the book or series.
```

## 5. Illustration Prompt Generator

```text
Create a professional children's book illustration prompt for the following page.

Character sheet:
[CHARACTER_SHEET]

Page scene:
[SCENE_DESCRIPTION]

Page emotion:
[EMOTION]

Illustration style:
[ART_STYLE]

Color palette:
[COLOR_STYLE]

Target age:
[AGE_RANGE]

Requirements:
- Keep the character consistent with the character sheet
- Make the emotion readable at a glance
- Use a clear picture-book composition
- Include background and props that support the story
- Avoid text inside the image unless explicitly requested
- Make the image suitable for a professionally published children's book
```

## 6. Cover Prompt

```text
Design a professional children's picture book cover.

Title: [TITLE]
Subtitle: [SUBTITLE]
Target age: [AGE_RANGE]
Theme: [THEME]
Lesson: [LESSON]
Main character: [MAIN_CHARACTER]
Art style: [ART_STYLE]
Mood: [MOOD]

Requirements:
- Feature the main character prominently
- Make the title area easy to read at thumbnail size
- Communicate the story promise clearly
- Appeal emotionally to parents and children
- Look polished, commercial, and suitable for Amazon KDP
- Leave clean space for title, subtitle, and author name
```

## 7. Amazon KDP Description

```text
Write a high-conversion Amazon KDP description for a children's picture book titled "[TITLE]".

Book details:
- Target age: [AGE_RANGE]
- Theme: [THEME]
- Lesson or skill: [LESSON]
- Main character: [MAIN_CHARACTER]
- Short story summary: [SUMMARY]

Requirements:
- Start with a strong hook
- Highlight emotional and educational benefits
- Speak to what parents care about
- Naturally include relevant keywords
- Keep the tone warm, trustworthy, and benefit-focused
- End with a clear reason to buy
```

## 8. Series Expansion

```text
Based on the children's book titled "[TITLE]", create a series plan with [NUMBER] additional books.

Use the same main character:
[MAIN_CHARACTER]

Series theme:
[GENERAL_THEME]

For each additional book, provide:
- Title
- Core lesson
- Brief story concept
- Emotional promise for parents and children
- How it strengthens the overall series brand

The goal is to create a coherent children's book series that encourages repeat purchases and long-term audience growth.
```

## 9. Layout Plan

```text
Act as a children's book layout designer preparing a book for Amazon KDP.

Book details:
- Trim size: [TRIM_SIZE]
- Page count: [PAGE_COUNT]
- Age range: [AGE_RANGE]
- Interior: [COLOR_OR_BLACK_WHITE]
- Layout tool: [CANVA_BOOK_BRUSH_OR_OTHER]

Create a layout plan that covers:
- How to combine text and illustrations
- Page rhythm and spread consistency
- Font guidance for children's books
- Margins and safe zones
- Cover, back cover, and spine considerations
- PDF export settings
- Common mistakes that make children's books look unprofessional
```

## 10. Originality and Rights Risk Review

```text
Act as a children's publishing editor and originality risk reviewer.

Review the following book concept, title, characters, story, and illustration directions for potential originality, copyright, trademark, or brand-confusion risks.

Material to review:
[BOOK_MATERIAL]

Check for:
- Similarity to well-known children's books, films, games, characters, or brands
- Names, designs, traits, or plots that feel too close to existing IP
- Overly generic or template-like story elements
- Prompts that imitate a specific living artist or protected brand style
- Safer ways to make the book more original

Output:
- Risk level: low, medium, or high
- Specific risk points
- Concrete revision suggestions
- A more original and safer revised direction

This is not legal advice. Flag issues that should be reviewed by a qualified professional before publication.
```

## 11. KDP Keywords and Categories

```text
Act as an Amazon KDP children's book market research expert.

Create a keyword and category strategy for the children's picture book "[TITLE]".

Book details:
- Target age: [AGE_RANGE]
- Theme: [THEME]
- Lesson or skill: [LESSON]
- Main character: [MAIN_CHARACTER]
- Short summary: [SUMMARY]

Output:
- Keywords suitable for title or subtitle
- 7 backend keyword phrases for KDP
- Long-tail keywords to naturally include in the description
- Possible children's book categories
- Search phrases parents might use
- Differentiation angles
- Keywords to avoid because they are too broad, misleading, or irrelevant

Keep keyword advice natural, specific, and aligned with real parent buying intent.
```

## 12. Print Specs and Bleed Check

```text
Act as an Amazon KDP print production specialist.

Check whether my children's picture book is ready for print upload.

Book specs:
- Trim size: [TRIM_SIZE]
- Page count: [PAGE_COUNT]
- Binding: [PAPERBACK_OR_HARDCOVER]
- Interior: [COLOR_OR_BLACK_WHITE]
- Bleed: [BLEED_OR_NO_BLEED]
- Layout tool: [CANVA_BOOK_BRUSH_OR_OTHER]

Review:
- Whether the trim size is suitable for a children's picture book
- Whether bleed is required
- Whether text is too close to the edges
- Whether illustrations extend beyond the safe area
- Cover, back cover, and spine requirements
- PDF export settings
- Issues that may cause KDP review or print failure

Output a pre-publication checklist with must-fix items and nice-to-improve items.
```

