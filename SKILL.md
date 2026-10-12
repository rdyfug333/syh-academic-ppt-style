---
name: syh-academic-ppt-style
description: Apply the user's personal academic presentation style to graduate lab meetings, journal clubs, paper presentations, research presentations, thesis literature reviews, academic slide decks, and technical paper readings when the user wants this style. Preserve technical completeness, source evidence, and paper logic; do not use for commercial, marketing, sales, keynote-style, or visually decorative presentations.
---

# SYH Academic PPT Style

This skill defines the user's personal academic presentation style for graduate lab meetings, journal clubs, paper reading presentations, research reports, thesis discussions, and technical literature reviews.

Its purpose is NOT to create commercial, keynote-style, marketing, sales, or visually decorative presentations.

Primary goals:

1. preserve technical completeness;
2. preserve source evidence;
3. preserve the source paper's original logic;
4. maintain medium-high to high information density;
5. produce clean, restrained academic slides;
6. prioritize readability and evidence over visual decoration.

核心理念：

> 我是在带着实验室成员读论文，而不是在向客户推销论文。

完整、准确、可讨论

>

简洁、留白、视觉冲击力

## Trigger

Use this skill when a task involves a graduate lab meeting, journal club, paper presentation, research presentation, thesis literature review, academic slide deck, or technical paper reading, and the user wants their personal academic PPT style.

Do not route ordinary commercial presentations, sales decks, marketing decks, keynote-style talks, or decorative visual storytelling to this skill.

## Priority order

1. Explicit current user instructions
2. Source material / paper fidelity
3. syh-academic-ppt-style
4. paper2ppt evidence and research logic
5. presentation-skill implementation guidance
6. generic presentation best practices

If generic presentation guidance conflicts with this skill, follow syh-academic-ppt-style. For example, if generic guidance suggests only 3–5 bullets per slide but this skill permits complete technical paragraphs, preserve the complete technical paragraphs.

## Responsibility split

This skill is usually used together with $paper2ppt and $presentation-skill.

- paper2ppt is responsible for paper understanding, evidence, figures, tables, equations, research questions, methods, experiments, and the evidence chain. It decides what to present.
- syh-academic-ppt-style is responsible for the user's writing habits, content density, layout choice, visual system, formula and chart presentation, and academic tone. It decides how to present the material in the user's established style.
- presentation-skill is responsible for producing the actual PPTX, including text boxes, images, tables, coordinates, compatibility, overflow handling, and QA. It decides how to implement the deck as a PPTX.

## Required references

Read the references that match the current work before drafting or generating slides:

- Read [references/visual-system.md](references/visual-system.md) for every deck.
- Read [references/writing-style.md](references/writing-style.md) when drafting or editing slide text.
- Read [references/slide-archetypes.md](references/slide-archetypes.md) when selecting or implementing layouts.
- Read [references/evidence-rules.md](references/evidence-rules.md) whenever source materials, figures, tables, formulas, numerical results, or notes are involved.
- Read [references/anti-patterns.md](references/anti-patterns.md) before visual design decisions.
- Read [references/qa-checklist.md](references/qa-checklist.md) before delivery.
- Read [examples/meaningful-sis-reference.md](examples/meaningful-sis-reference.md) when matching the user's established style or resolving conflicts among reference decks.
- Read [examples/layout-examples.md](examples/layout-examples.md) when a slide's content-region arrangement is unclear.
- Use [assets/academic-template.pptx](assets/academic-template.pptx) as the clean reusable base when creating a new local PPTX, unless the user provides another template or explicitly requests a different base.

## Layout selection

- IF content is primarily continuous academic discussion → Layout B.
- IF content contains 150–300 words + one important figure → Layout C.
- IF formulas / definitions / lemmas dominate → Layout D.
- IF algorithmic steps dominate → Layout E.
- IF one original figure is central to understanding → Layout F.
- IF several related experiment images must be shown together → Layout G.
- IF one claim requires multiple evidence forms → Layout H.
- IF qualitative evidence needs substantial interpretation → Layout I.
- IF efficiency / comparison requires figure + tables → Layout J.
- IF conclusion → Layout K.

Layouts are archetypes, not rigid templates. Content completeness, evidence clarity, and image readability take priority over pixel-level uniformity.

## Speaker notes

Each slide's speaker notes should contain:

- Source: Paper page / section / equation / figure / table
- Evidence: What claims are directly supported
- Presenter note: Additional explanation
- Verification: Any unresolved ambiguity or source conflict

Do not display these records in the main slide body.

## Execution workflow

1. Read user request
2. Read source material
3. Determine slide purpose
4. Identify evidence
5. Select slide archetype
6. Draft academic content
7. Apply personal visual system
8. Insert original figures/tables/formulas
9. Add speaker-note evidence
10. Generate PPTX
11. Run QA checklist
12. Report unresolved issues

Do not use this workflow:

read paper → auto summarize → create visually decorative slides

The required approach is evidence-led, technically complete, faithful to the source paper's sequence, and suitable for discussion with laboratory members.
