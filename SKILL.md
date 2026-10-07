---
name: read-paper-to-slides
description: "Guide close reading of one research paper and carry the understanding into a lab-meeting presentation. Use for paper reading guides, prerequisite explanations, Markdown mind maps, method and equation interpretation, experimental analysis, slide drafting or restrained review, and slide-aligned scripts and Q&A. Trigger on 论文精读, 文献导读, 组会汇报, Slides制作或审阅, and 逐字稿. Preserve source terminology, evaluation protocols, evidence boundaries, and the final deck."
---

# Read a Paper to Slides

## Scope and defaults

- Work on one focal paper. Accept its supplementary material, an explicitly requested repository, existing slides, advisor requirements, and relevant discussion as supporting inputs.
- Support four entry points: close reading; slide drafting; slide review; final-deck script and Q&A. Enter at the requested stage and complete that deliverable. Do not generate every artifact after a narrow request.
- Default to a graduate student in computer science preparing a research-group presentation, with limited familiarity with the application domain. Explain prerequisites where they affect understanding. Adapt to the user's actual knowledge and audience.
- Use Chinese explanatory prose and slide body text by default. Retain established English method names, module names, core technical terms, and mathematical notation. Follow a requested language change.
- Do not add multi-paper synthesis or weekly-report production to this workflow.
- Keep workflow instructions independent of any particular paper, repository, organism, dataset, method, slide count, or presentation duration.

## Source policy

Use supplied attachments as the primary factual source. Do not require a connector or a web search to begin. Open external papers, background resources, citations, or repositories only when explicitly requested, already authorized in the conversation, or required by higher-priority verification instructions. A later request can expand the source scope without restarting the workflow.

Record the paper version before using external material. Keep external background and implementation evidence separate from claims about the focal paper. Do not silently substitute a newer version, a repository README, a review, or an earlier assistant summary for the supplied paper.

If a file is unavailable or only an excerpt is accessible, name the gap and request the missing material. Continue independent work. State the available coverage and never claim to have read inaccessible pages. Treat prior drafts and conversation history as workflow context until their factual claims are checked against a source.

## Shared working record

Read [Evidence and state](references/evidence-and-state.md) for all entry points. Maintain a compact record of sources, reading coverage, terminology, method objects, equations, experimental protocols, claims, unresolved questions, and the active slide version. Reuse it across stages; correct it when new evidence arrives.

Keep this record proportional to the task. Use conversation state for a short explanation. Preserve a checkpoint with substantial artifacts when continuing work would otherwise lose important decisions. Do not expose a large audit table unless it is useful or requested.

## Route the request

| Request | Read next | Deliver |
|---|---|---|
| Explain or closely read a paper | [Close reading](references/close-reading.md) | A reading guide, targeted explanation, or Markdown mind map matching the request |
| Prepare a research-group presentation | [Close reading](references/close-reading.md) as needed, then [Slides](references/slides.md) | A coherent plan and complete slide body text, or the requested deck artifact |
| Review or lightly polish an existing deck | [Slides](references/slides.md) | Source-checked corrections with restrained edits at actual slide numbers |
| Prepare a script or audience questions | [Script and Q&A](references/script-and-qa.md) | A script aligned to the active deck and answers with clear evidence boundaries |

Reuse available understanding without repeating completed reading. For a conceptual follow-up, answer the specific confusion directly. For a new paper, reset the paper-specific record while retaining workflow preferences.

Ask only for missing information that materially changes the result. Use established audience, timing, format, and language preferences. If an optional preference is absent, proceed with a stated, reasonable assumption; do not invent a mandatory approval gate between stages.

## Carry understanding into the presentation

1. Establish source coverage and the task definition, then explain the prerequisites needed to understand the paper.
2. Reconstruct the method through its inputs, outputs, component roles, optimization targets, and feedback loops. Explain important equations in that context.
3. Establish the evaluation protocol before interpreting results. Verify tables, figures, metrics, exceptions, and conclusion boundaries.
4. Organize slides around the audience's knowledge dependencies and the paper's argument. Give each page one clear communicative purpose.
5. Review the draft against the paper and the shared record. Preserve user-approved structure during minor revision requests.
6. Use the actual final deck as the script's sequence and content reference. Propagate later corrections into the record, relevant slides, and corresponding script passages.

Execute only the stages necessary for the current request. A script request with a verified deck can begin at the last stage.

## Writing and notation

- Write in plain, measured language. Use direct affirmative sentences. Avoid contrastive denial-and-replacement formulations, promotional titles, rhetorical questions, em dashes, decorative quotation marks, and metaphors.
- Explain an unfamiliar term at its first meaningful use. Use a stable Chinese rendering with the English term once, then apply the glossary consistently.
- Preserve the paper's terminology and symbols. Flag overloaded or inconsistent notation before adding any explanatory notation.
- Use `$...$` for inline mathematics and `$$...$$` for display mathematics in both Markdown replies and files, so copied content works in Typora. Do not use `\(...\)` or `\[...\]` delimiters. Put display formulas on their own lines. Avoid `\tag` unless the requested renderer supports it; cite equation numbers in prose.
- Express Chinese page or section ranges with 至 rather than dash punctuation. Apply the prose and notation rules to source notes, revision explanations, and scripts as well as slide body text.
- Use compact headings or lists where they aid reading; avoid forcing a template onto every conversational explanation or every slide.

## Files and capabilities

Use the relevant PDF, presentation, or document workflow when reading or producing those file formats. Extract text for coverage, and visually inspect important equations, tables, plots, and existing slide layouts when extraction is insufficient. For a requested editable deck, produce the actual editable artifact and perform its required rendering checks. For a slide-body request, provide text without silently creating a deck.

Follow the environment's artifact-saving rules. Save deliverables to the established destination and report them accurately. Do not create extra exports, packages, or reports unless they serve the request.

## Completion checks

- Check every substantive paper claim and reported number against an accessible source location.
- Resolve component-role confusion and metric-definition confusion before relying on them in slides or a script.
- Distinguish reported evidence, author interpretation, explanatory background, presenter inference, and open questions.
- Preserve material exceptions and limitations; keep discussion proportional to the paper's evidence.
- Verify that concepts appear before their use, equations have a stated purpose, and experiments have an intelligible protocol.
- Confirm review scope, actual slide order, script coverage, and timing constraints where applicable.
- Scan the full response for dash punctuation, unsupported mathematical delimiters, and unnecessary quotation marks before delivery.
- Report remaining source gaps or unverified items without presenting them as facts. Do not claim source verification or visual verification that was not performed.
