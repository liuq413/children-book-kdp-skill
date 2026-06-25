# Usage Examples

Use these examples when the user wants help understanding how to run the skill, or when you need a realistic starting point.

## Example 1: Full KDP Pipeline

User prompt:

```text
Use $children-book-kdp to create a complete KDP workflow for a children's picture book.

Age range: 4-8
Theme: sharing
Lesson: sharing can make play more fun
Main character: a fox cub who wants to keep every toy
Page count: 32
Words per page: 20-40
Art style: cheerful watercolor, bright forest colors
Trim size: 8.5 x 8.5 inches
```

Expected response shape:

```text
1. Assumptions
2. Book Concept
3. Story Structure
4. Manuscript
5. Character Sheet
6. Illustration Prompt Set
7. Cover Prompt
8. Amazon Listing
9. Series Plan
10. Layout Plan
11. Originality Risk Review
12. KDP Readiness Checklist
```

## Example 2: Idea Generation Only

User prompt:

```text
Use $children-book-kdp to generate 20 children's book ideas for ages 3-5 about bedtime routines.
```

Expected response:

- 20 ideas
- Each with title, character, lesson, plot summary, and parent-buying reason
- Ideas should be visually strong and emotionally clear

## Example 3: Manuscript From Existing Outline

User prompt:

```text
Use $children-book-kdp to write the manuscript from this outline.

Age range: 4-8
Tone: gentle and funny
Words per page: 25-45

[paste outline]
```

Expected response:

- Page-by-page manuscript
- Age-appropriate vocabulary
- Read-aloud rhythm
- Clear visual moment per page
- No extra analysis unless requested

## Example 4: Character Sheet For Illustration Consistency

User prompt:

```text
Use $children-book-kdp to create a character sheet.

Character: Nori
Type: small moon rabbit
Age: childlike, around 6
Traits: shy, curious, careful, kind
Art style: soft watercolor picture book
Series role: main character for bedtime stories
```

Expected response:

- Physical appearance
- Clothing and accessories
- Color palette
- Facial expressions
- Body language
- Distinctive features
- Do and don't consistency rules
- Reusable consistency anchor

## Example 5: Illustration Prompt Set

User prompt:

```text
Use $children-book-kdp to create illustration prompts for all pages.

Character sheet:
[paste character sheet]

Page outline:
[paste page-by-page outline]

Style: warm watercolor, soft paper texture, cozy lighting
```

Expected response:

- One prompt per page
- Repeated consistency anchor
- Clear scene composition
- Mood and expression for each page
- No text in images unless requested

## Example 6: KDP Listing

User prompt:

```text
Use $children-book-kdp to write an Amazon KDP description and keyword strategy.

Title: The Dragon Who Named the Dark
Age range: 4-8
Theme: bedtime anxiety
Lesson: naming feelings makes them less scary
Main character: a tiny dragon afraid of bedtime shadows
```

Expected response:

- Strong hook
- Parent-benefit description
- Natural keywords
- 7 backend keyword phrases
- Category ideas
- Keywords to avoid

## Example 7: Pre-Publication Audit

User prompt:

```text
Use $children-book-kdp to audit this children's book before KDP upload.

Trim size: 8.5 x 8.5 inches
Page count: 32
Interior: premium color
Bleed: yes

[paste manuscript, cover concept, and sample illustration prompts]
```

Expected response:

```text
1. Overall Readiness
2. Must Fix
3. Nice To Improve
4. Originality and Rights Risks
5. Age Fit
6. Visual Consistency
7. KDP Listing Quality
8. Print and Layout Issues
9. Next Actions
```

