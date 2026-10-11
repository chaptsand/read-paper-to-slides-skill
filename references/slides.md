# Slides

## Build the narrative

Use the verified understanding record. Apply known audience, duration, and format requirements. If the duration is unknown, provide a provisional structure without claiming a precise speaking time or treating any slide count as a default requirement.

Organize by knowledge dependencies and argument: why the task matters, what prevents existing approaches from solving it adequately, what the paper changes, how the method works, how it is evaluated, and what the evidence establishes. Reorder or combine sections as needed; do not mechanically assign a page to each paper subsection.

Define unfamiliar objects and terms before relying on them. Introduce the system overview before detailed components. Establish evaluation metrics before showing performance tables. Choose detail according to relevance and audience readiness.

Assign each slide a single clear communicative purpose. Use concrete topic titles or evidence-supported statements. Avoid promotional claims, questions used as titles, slogans, and paper-style transition sentences.

## Draft slide content

When the user requests slide text, provide complete page content that can be transferred into a deck. Separate presentation body text from speaker explanation and production instructions.

Use this planning record where useful; do not fill absent sources with invented locators:

| Item | Required content |
|---|---|
| Page and title | Intended page order and a concise title |
| Purpose | What the audience should understand after the page |
| Body | Concise Chinese content with stable English technical terms |
| Visual | Relevant original figure, table, equation, or a clearly identified conceptual schematic |
| Source | Verified paper location or an explicit unresolved source gap |
| Notes | Necessary explanation or transition, outside the slide body |

Keep the body readable at presentation size. Move derivations, extensive qualifications, and supporting explanation into notes or backup pages where appropriate. Split an overloaded page when its concepts require separate explanation. Avoid rigid bullet or word quotas.

Preserve core method terminology and original equation symbols. Give an equation a visible purpose and define the few symbols needed on that page. Do not place a formula without explaining what it computes or controls.

Use original figures and tables where they carry the argument. Keep axes, legends, units, captions, and relevant footnotes intact or explain deliberate simplifications. Mark any new schematic as a teaching representation. Do not manufacture data or use generated imagery for exact method or metric diagrams.

For a result page, identify the task and metric, make the intended comparison visible, and state only the supported conclusion. Use selected examples without hiding exceptions that change the conclusion. Keep composite fitness distinct from ACC, ARI, AUC, or other underlying measures. Include the evaluation context needed to interpret efficiency claims.

Present author limitations and presenter discussion as distinct content. Keep critical questions concrete and proportionate. Do not replace the paper's reported conclusion with unsupported praise or speculation.

## Review an existing deck

Identify the active file by content and actual page count. Follow existing page numbers. If versions are ambiguous, use available metadata and content to resolve them, or ask for the active version while doing independent source checks.

Check semantic accuracy against the paper, then narrative and terminology, then presentation clarity and layout. Prioritize errors that change understanding: object roles, objectives, metric semantics, evaluation scope, claimed causality, and numerical comparisons.

For a light-polish request, preserve correct content, order, titles, and visuals. Remove repetition, shorten dense language, standardize terminology, and improve transitions with small changes. Rewrite a page or reorder the deck only when needed to resolve a specific problem or explicitly requested.

Provide corrections at actual page numbers with the affected wording, replacement wording, and a brief reason. Distinguish required factual corrections from optional presentation improvements. Do not claim visual checks from extracted text alone.

For a requested editable artifact, use the presentation capability and its rendering/inspection workflow. Inspect all final pages for overflow, legibility, figure fidelity, equation rendering, and consistency. Respect requested privacy edits without assuming every academic presentation must be anonymized.

## Freeze the handoff

Record the active deck version, actual order, final terminology, equations, and result interpretation. Resolve important factual errors before using the deck as a script source. If the deck changes later, update the affected script pages without silently retaining old numbering.

Keep source notes and resolved questions available for Q&A. Do not require another confirmation when the user has already authorized the next stage.

## Design from comprehension bottlenecks

Before committing to an outline, identify the two or three places where listeners are most likely to lose the argument. Ask what prerequisite object, original diagram, simple example, or execution trace would remove each barrier. Devote space according to technical difficulty and scientific centrality rather than paper section length.

A good sequence may show the target models before discussing their components, the full method overview before its sub-agents, and an unfamiliar decision problem before its optimization rule. Insert an external prerequisite only when the later paper-specific step benefits. Cite or label prerequisite content as general background, never as a paper contribution.

## Revisit the same figure progressively

Prefer a faithful, recognizable original figure to a freshly synthesized replacement when the original is sufficient. Consider a reveal sequence:

1. Show the full system to establish spatial context.
2. Focus on the region being discussed by framing, cropping, highlighting, or enlarging it.
3. Return to the overview or the next region without redefining previous modules.

Use the same treatment for pseudo-code: expose the algorithm once, then focus on selection logic, execution/reward update, and one concrete candidate as needed. Each repeated slide must have a **new explanatory purpose**, not simply restate the same content. Keep original labels and symbol identities readable. Never imply a proposed teaching schematic or highlight came from the authors unless it actually did.

## Turn an algorithm into an observable process

Identify the algorithm's control state (e.g., per-arm statistics), the choice step (e.g., select hypothesis family), the refinement (generate a concrete experiment), the actual evaluation (code run/model retraining), and the update that changes the next choice. Put these in a coherent order and test whether the audience can explain the loop without reading the pseudo-code aloud.

When useful, revisit an architecture slide and point to the **same named component** used in the algorithm's running example. Distinguish the selected family of hypotheses from the single executable candidate and from the performance metric that evaluates it. Mark an illustrative example clearly when it is not reported in the source.

## Content density and evidence

Slides can be restrained and spacious or use dense original evidence. Choose deliberately:

- Prefer a complete original figure when simplifying it would break an important dependency.
- Prefer a compact equation with a short explanatory anchor when an objective or decision rule is central.
- Prefer original experimental tables with selected cells emphasized to ungrounded performance claims or decorative infographics.
- Put extensive explanation in the oral script when the visual already conveys the object; avoid gratuitous paragraph blocks.

Do not reproduce a particular successful deck's 30 pages, colors, typography, or section proportions. Do not add stock images, novelty figures, extra Q&A slides, or lecture-style tutorials unless they serve a concrete listener need.

## Scientific meaning of results

For each major result, align: research question, evaluated unit and task, protocol, metric direction, compared systems, and justified inference. Make constraints and exceptions visible when they change interpretation. Distinguish automation success from scientific novelty or causal proof. If the user challenges a paper's motivation or importance, consider how to reflect a grounded discussion in the final narrative, but do not attribute it to the original authors.
