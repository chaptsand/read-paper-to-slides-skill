# Evidence and State

## Source inventory

Record the focal title, supplied version or date if known, local filename or source identifier, accessible page range, and supporting materials. Distinguish PDF page numbers from printed page numbers when they differ. Identify duplicate filenames by file identity and content; do not merge distinct deck versions by name alone.

Record missing, truncated, illegible, and uninspected material. A supplied excerpt supports an excerpt-based interpretation. Prior conversation can supply preferences and questions; it cannot establish what an inaccessible source contains.

## Compact record

Keep the following information as reusable working state, with source locations attached to factual entries. Use a compact table or structured notes; no particular file format is mandatory.

| Field | Contents |
|---|---|
| Task | Requested entry point, audience, domain knowledge, language, time budget, output format, source scope |
| Coverage | Paper sections read; important figures, tables, equations, and appendices checked; gaps |
| Glossary | Source term, stable Chinese wording, definition, first introduction |
| Method objects | Input, output, producer, consumer, trainability or mutability, role in optimization or evaluation |
| Equations | Original symbol definitions, purpose, dependencies, units or normalization, source number |
| Protocols | Task, data, supervision, split, search or model selection, final evaluation, metrics, comparison controls |
| Claims | Statement, evidence type, source location, scope, exceptions, verification status |
| Questions | Resolved explanation or explicitly open uncertainty |
| Deck state | Active file/version, actual page map, user-approved structure, corrections, script mapping |

Separate fixed architecture or training protocol from fitted parameter values. Distinguish a retrieved reference method, an extracted rule, a candidate program, and a downstream evaluator whenever the paper contains those objects. Do not assign roles merely from an object's name.

## Evidence types

Use these distinctions in reasoning and express them naturally in the delivered material:

| Type | Appropriate treatment |
|---|---|
| Reported evidence | Attribute to the exact experiment, table, figure, derivation, or documented implementation |
| Author interpretation | Explain how the authors interpret their evidence, keeping their claim scope |
| Explanatory background | Mark as background or a teaching example; cite external sources if used |
| Presenter inference | State the inferential step and supporting observation; do not attribute it to the authors |
| Open question | Explain what would need checking; do not imply that an unreported procedure was omitted |

Do not treat LLM-generated explanations, code comments, rule labels, or causal terminology as experimental proof. Check the study design supporting the claim. Keep mathematical guarantees, empirical support, and heuristic rationale distinct.

## Traceability

Attach a page and section, equation, table, figure, or appendix identifier to important claims. For inspected code, record a file/function and a version or commit when available. Use the environment's actual file citations when supported; never fabricate citation handles.

Verify copied numerical cells together with headers, metric definitions, averaging units, direction of improvement, and footnotes. Record absolute differences separately from relative percentage changes. Do not infer statistical significance from a mean gap, boldface, or overlapping error bars.

For supplied code, reconcile implementation evidence with the paper only within the authorized inspection scope. Report a discrepancy with both locations. Never claim to have run code merely because it was read.

## Stage transitions and revisions

Carry verified definitions and protocols into slides; do not replace them with shorter but inaccurate summaries. Carry actual slide content into the script. Keep source notes available without overloading the presentation body.

When a correction changes a definition or result interpretation, update every affected downstream statement. If the user asks for restrained edits, change only what the correction requires. Track unresolved issues without withholding independent work.

Anchor continuation to the active paper and deck version. Reuse the existing record and completed checks. Do not claim a previous source check remains sufficient after the source or relevant content changes.

## Comprehension-to-presentation trace

Retain only consequential reading questions and the decisions they lead to; do not turn every question into a slide. A compact trace can contain:

| Trigger | Resolved understanding | Evidence status | Likely audience need | Possible presentation move |
|---|---|---|---|---|
| An unfamiliar selection rule | Its intuition, variables, and role in the method | Original algorithm plus general prerequisite | High if listeners cannot follow the next step | Short prerequisite explanation or worked example |
| Ambiguous module boundary | Inputs, outputs, and implementation role | Source figure/description, code only if examined | High if the later ablation targets that module | Revisit the original architecture with focus |
| Research-value doubt | What the evaluation proves and leaves open | Results plus presenter inference | Important for final discussion | Critical conclusion or Q&A, not an invented author claim |

Treat this as a *decision trace*, not a compulsory appendix or an excuse to overproduce. During ongoing conversation, reuse resolved answers and cite the corresponding source without reposting the whole log. The user's specific technical questions can identify useful prerequisites, but may also be personal interests that should remain outside the deck.

## Change propagation

When new reading resolves or corrects a method detail, update its dependent records: notation, component mapping, slide statement, speaker explanation, and audience question. Do not silently carry an earlier unverified paraphrase into the next artifact. Maintain the identity and page count of the latest approved deck and keep tentative drafts separate from that approved version.

After a completed seminar, capture reusable *decisions* if the user wants to refine the workflow: what listeners needed beforehand, why a figure was revisited, how an algorithm was demonstrated, and what experiment actually supported the conclusion. Do not treat slide count, color, text density, or the focal domain as universal preferences.
