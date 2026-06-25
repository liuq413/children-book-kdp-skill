---
name: children-book-kdp
description: Use when creating, improving, auditing, or packaging a children's picture book for Amazon KDP, including idea generation, story structure, manuscript writing, character sheets, illustration prompts, cover prompts, KDP descriptions, series expansion, Canva or Book Brush layout, originality review, keyword/category strategy, print specs, bleed, safe-area validation, and reusable prompt workflows.
metadata:
  short-description: Children's picture book to KDP workflow
---

# Children's Book KDP

Use this skill to turn a children's picture book idea into a commercially usable Amazon KDP production plan. Keep outputs practical, age-appropriate, original, and easy to reuse.

## When To Use

Use this skill when the user asks to:

- Create a children's book, picture book, bedtime story, illustrated storybook, or KDP kids book.
- Build a prompt workflow for Gemini, ChatGPT, Claude, Midjourney, Ideogram, Canva, Book Brush, or similar tools.
- Generate or improve book ideas, story outlines, manuscripts, characters, illustration prompts, cover prompts, Amazon listings, series plans, or print-ready layout checks.
- Review a children's book for originality, commercial appeal, keywords, categories, trim size, bleed, safe margins, or KDP readiness.

Do not use this skill for adult fiction, general publishing advice, or legal advice unless the request also involves a children's picture book workflow.

## Operating Rules

- Ask for missing essentials only when they affect the result: age range, theme, lesson, page count, language, trim size, and art style.
- If the user wants speed, make reasonable defaults explicit and proceed.
- Do not present AI output as legal, copyright, trademark, or publishing compliance advice. Flag risks and recommend human review for final publication.
- Avoid imitating living artists or protected brands. Use broad style language instead.
- Keep the child reader first: simple conflict, clear emotional arc, concrete scenes, and lesson shown through action.
- Keep the parent buyer in view for titles, descriptions, keywords, and cover direction.

## Default Variables

Use these defaults when the user has not specified values:

- Age range: 4-8
- Pages: 24 or 32
- Words per page: 20-60
- Tone: warm, clear, parent-friendly
- Format: square picture book, 8.5 x 8.5 inches
- Output language: match the user's language

## Main Workflow

Run only the steps the user needs. For a full book pipeline, use all 12:

1. Idea generator
2. Story structure
3. Manuscript writer
4. Character sheet
5. Illustration prompt generator
6. Cover prompt
7. Amazon KDP description
8. Series expansion
9. Layout plan
10. Originality and rights risk review
11. KDP keywords and categories
12. Print specs and bleed check

For copy-ready prompt blocks, read `references/prompt-templates.md`.
For KDP production checks, output schemas, and print-readiness guidance, read `references/kdp-production-guide.md`.
For realistic user prompts and example outputs, read `references/usage-examples.md`.
For Chinese users, read `references/zh-cn.md` for Chinese usage notes, example prompts, and localized workflow guidance.

## Output Style

- Prefer numbered sections that match the workflow step.
- Keep prompts copy-ready, with placeholders preserved when the user has not provided details.
- When generating image prompts, include consistency anchors from the character sheet.
- When reviewing publication readiness, separate "must fix" from "nice to improve".
- If the user asks for a reusable template, provide prompt blocks rather than long explanations.
- If the user asks for a complete pipeline, include a compact success checklist at the end.
- Use the user's language unless they ask for another language.

## Quality Checks

Before finishing, verify:

- The age range matches vocabulary, conflict intensity, and lesson complexity.
- The lesson is shown through story action, not only explained.
- Character and art prompts include enough continuity details for consistent illustrations.
- KDP text is parent-benefit focused, not just plot summary.
- Print specs include trim size, bleed, safe area, and PDF readiness.
- The output does not encourage copying protected characters, brands, titles, or living artists' styles.
