# syh-academic-ppt-style

A reusable **Codex Skill** for graduate lab meetings, journal clubs, academic
paper presentations, thesis literature reviews, and technical slide decks.

**核心原则：完整、准确、可讨论；以论文证据和原文逻辑为先，而不是商业化视觉包装。**

## Style principles

- Clean 16:9 PowerPoint slides, white background, black typography.
- Medium-high to high information density; professional technical paragraphs are welcome.
- Follow the source paper's organization and preserve definitions, algorithms, equations, and evidence.
- Prefer original paper figures/tables when legitimately available; do not fabricate experimental data.
- Use speaker notes for evidence provenance and unresolved verification items.
- Run the Skill's QA checklist before delivering a final deck.

## Repository structure

```text
SKILL.md
references/                    # Visual, writing, evidence, layout and QA rules
examples/                      # Layout and style-reference descriptions
assets/academic-template.pptx  # Two-slide reusable PowerPoint starter
LICENSE
README.md
```

The three original development reference presentations are **not included** in
this installable release. The Skill's written rules and template are provided
for reuse without distributing those original decks.

## Installation

**Windows (Codex local skills):**

1. Clone or download this repository.
2. Place the *repository contents* in
   `%USERPROFILE%\.codex\skills\syh-academic-ppt-style\`.
3. Verify that `SKILL.md` is immediately inside that directory, not one level deeper.
4. Restart Codex if the Skill is not recognized.

**Other systems:** Install to the Codex skills directory appropriate for your setup.

This repository is the Skill's source and is not automatically installed on
every machine just because the repository is connected to Codex Cloud.

## How to use

Example instruction:

```text
Use $syh-academic-ppt-style to prepare an 18-slide, 25-minute
graduate journal-club presentation from the attached paper.
Follow its chapter sequence; preserve technical details and
cite figure/table/equation sources in speaker notes.
```

The Skill can be combined with `paper2ppt` for paper evidence planning
and `presentation-skill` for editable PowerPoint generation.
**Those companion Skills are optional and not bundled in this repository.**

## Verification

Refer to `references/qa-checklist.md` and `references/evidence-rules.md`
for slide and source-fidelity checks. The provided PPTX is a generic
template, not a finished presentation containing paper figures.

## License

MIT License, © 2026 rdyfug333. See [LICENSE](LICENSE).

You are responsible for ensuring you have appropriate rights to any
third-party papers, images, charts, or other materials you add when producing
new presentations.
