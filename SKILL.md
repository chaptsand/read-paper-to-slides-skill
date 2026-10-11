---
name: read-paper-to-slides
description: "Help closely read a research paper, explain technical questions, and prepare group-meeting slide content, restrained reviews, page-aligned scripts, or Q&A. Trigger on 论文精读, 文献导读, 组会汇报, Slides制作或审阅, 逐字稿. Preserve source meaning and adapt to the user's audience and approved deck."
---

# Read a Paper to Slides

## Scope and entry point

Work on one focal paper and the deliverable requested now: a reading guide, targeted explanation, mind map, slide plan or content, deck review, script, or Q&A. Enter at the user's current stage and reuse verified understanding. A slide request can begin directly with presentation preparation.

Use natural, precise Chinese by default, retaining established English technical terms and original mathematical notation. Adapt depth to the reader and audience. Follow established preferences for structure, length, sources, and presentation style.

Let reading and presentation work inform each other: resolve technical gaps when they matter, and carry useful explanations into the talk. Ask only for missing information that materially changes the result; an intermediate outline or approval step is optional.

## Source fidelity

Use the supplied paper version as the factual anchor. Check relevant figures, tables, equations, and supplements alongside the text. Keep external background and inspected code distinct from the paper's reported design; consult them within the authorized scope or when required for verification.

Preserve terminology, conditions, metric definitions, units, and exceptions that affect interpretation. Distinguish reported results, author interpretation, explanatory background, teaching examples, and presenter inference. Attach source locations to substantive claims. State unresolved details accurately.

Read [Evidence and state](references/evidence-and-state.md) when source tracking or continuity matters. Keep a proportionate working record of definitions, protocols, consequential questions, presentation preferences, and the active deck. Use conversation state for short exchanges; preserve a checkpoint when substantial work needs it.

## Choose the relevant guidance

| Request | Reference |
|---|---|
| Reading guide, technical question, prerequisites, equations, algorithms, or experimental interpretation | [Close reading](references/close-reading.md) |
| Slide planning, complete slide content, or review of an existing deck | [Slides](references/slides.md) |
| Page-aligned script or audience questions | [Script and Q&A](references/script-and-qa.md) |

Read the references needed for the current task. A new paper resets paper-specific evidence while retaining the user's established communication preferences.

## Carry understanding into a talk

Keep the reading record thorough; select presentation material for the research argument and audience. Prioritize the problem, essential mechanism, and evidence needed to understand the conclusion. Allocate space to important comprehension difficulties within the user's page or time budget.

Use the user's reference deck to calibrate material choices and pacing. For paper-sharing content, preserve useful original passages or faithful translations and let figures, tables, formulas, and pseudocode carry their own explanations. Retain the author's reasoning and scientific voice.

Introduce unfamiliar objects before operating on them. An original architecture figure can establish components; a small teaching example can unlock an unfamiliar rule. Explain algorithms through decisions, execution, feedback, and changing state. Revisit the same source visual with a new focus when it helps listeners follow the process.

Follow the requested paper-sharing structure. Ground conclusions in the evaluation. Include presenter critique, extensions, or discussion questions according to the user's purpose.

## Deliver and continue

For slide-content requests, provide complete transferable page content. Separate visible content from necessary speaker notes, source locators, and production instructions. Create an editable deck when requested.

For an existing deck, preserve accepted content and order within the requested revision scope. Use actual page numbers. The approved final deck determines subsequent script order and visual cues; propagate material corrections to affected explanations.

Use `$...$` for inline math and `$$...$$` for display math in Markdown for Typora compatibility. Preserve original symbols and explain formulas by their role in the method.

Inspect PDF and slide images when visual content or presentation style matters. Do not claim inspection from extracted text alone. Before delivery, check source accuracy, requested coverage, audience dependencies, and alignment with the latest approved deck.

