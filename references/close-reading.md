# Close Reading

## Establish the reading path

Confirm the accessible source and user objective. Read the full main text and relevant supplementary material for a full-paper request. Inspect the abstract, introduction, method, results, discussion, and conclusion together; do not build a full guide from the abstract alone. Mark appendix coverage and unavailable material precisely.

First reconstruct the research problem in plain language: objects being studied, available inputs, intended outputs, supervision or feedback, and the scientific or practical use of the result. Explain why the task matters without adopting promotional wording.

Identify only the background prerequisites needed for this paper. For interdisciplinary work, connect application entities and measurements to the computational task. Avoid assuming biological annotation establishes mechanism or experimental validation.

## Reconstruct the method

Map the data path and the optimization or feedback path separately when they differ. For each important component, establish:

- What it receives and returns.
- What it computes, trains, edits, searches, or retrieves.
- Which choices remain fixed and which can vary.
- What objective, signal, or evidence judges its output.
- How it connects to the next component.

Read the formal definitions, algorithm, architectural figure, and implementation descriptions together. Resolve terminology conflicts with explicit source locations. Explain which details are specified and which remain uncertain.

Distinguish the optimized object from the model that evaluates or consumes it. If a downstream model is retrained for each candidate, explain that procedure even when its architecture is fixed. Preserve feature inputs and other dependencies that a simplified graph-only pipeline would hide.

Use small teaching examples only when they clarify a concrete operation. Label them as illustrative. Do not invent a module, result, or exact parameter setting to fill a gap.

## Explain equations

For each equation needed to understand the argument:

1. State the problem it addresses and where it is used.
2. Define the symbols, objects, and relevant dimensions.
3. Explain the computation or objective in plain language.
4. Connect its output to selection, training, inference, or evaluation.
5. State important assumptions, normalization, tradeoffs, and interpretation limits.

Preserve the original equation and notation before simplifying it. Distinguish a definition, an optimization objective, a heuristic, and a proved result. Do not turn a mathematical expectation into an unsupported description of the implemented evaluation procedure.

## Read the experiments

Establish the evaluation protocol before reading winners: task, data scale and units, labels, split, validation and selection procedure, repeated runs, metric definitions, and controls across comparisons.

For a composite metric, reconstruct its components, transformations, weights, direction, and runtime convention if specified. Keep it separate from each underlying score. A fitness increase alone does not establish a predictive-performance increase.

Explain what each baseline and ablation changes and what conclusion it can support. Check whether architecture, preprocessing, features, topology, training, hardware, or budget also changes. Treat a missing detail as unreported, with any consequence framed conditionally.

Read exceptions as part of the result. Retain ties, reversals, task dependence, and restrictions on generalization. Do not infer an unreported benchmark number or a statistical conclusion.

Use case studies to connect the method to a concrete observed change. Explain whether a case supports feasibility, interpretability, transfer, or effectiveness; do not elevate one example into a universal conclusion.

## Deliver the requested reading material

For a broad guide, organize around problem and motivation, necessary background, method and equations, evaluation and results, evidence boundaries, and useful discussion questions. Adjust depth to the paper and the user's confusion instead of enforcing a fixed heading list.

For a Markdown mind map, use meaningful nested headings or lists: problem, prerequisites, method components, optimization/evaluation, evidence, and limitations. Express dependencies and roles rather than copying the paper's contents page. Add source locators where they help later review.

For a targeted question, lead with the relationship or definition that resolves it, then give the necessary mechanism and source evidence. Separate paper-specific terminology from established disciplinary usage. Avoid reopening the entire reading workflow.

## Collaborative question-handling patterns

For an incremental query, use this order when appropriate:

1. Give the answer that resolves the precise confusion in the first paragraph.
2. Locate the concept inside the focal paper's task, figure, equation, or experimental protocol.
3. Explain the minimum prerequisite needed to follow the mechanism, using a tiny example if useful.
4. Map the example back to the paper's actual objects and name one important limitation or ambiguity.
5. Stop when the requested depth is satisfied. Do not automatically start presentation production.

Do not force five numbered headings into every reply. A one-paragraph answer may suffice for a local question. For a deep method walkthrough, systematically trace the inputs, decisions, modified objects, execution, feedback, and downstream consequences.

### Prerequisites as bridges

Add background only when it pays off in the paper. For example, when the paper uses a bandit selection rule, explain the exploration-exploitation dilemma before the formula, then show how an abstract arm, pull, observation, and reward map to the paper's real entities. A numerical toy example can clarify why a lower empirical mean might still be selected. Mark toy numbers as invented.

When a user asks whether a described graph execution resembles a named orchestration framework, distinguish conceptual similarity from verified software usage. When they ask what a maximizing-set formula means, distinguish a set-valued argmax from the objective value and from joint removal of the chosen components.

### Read for scientific significance

Track the distinction between recovering findings already reported in a paper, reproducing published evaluations, discovering a new biological or algorithmic mechanism, and demonstrating reliable autonomous scientific workflow execution. Invite independent critique when the user's question calls for it; do not inflate results or issue superficial praise. Compare the measured evidence with the stated research claim before speculating about extensions.

### Evolving reading state

A newly discovered gap may affect an earlier assumption; reopen that assumption. If slide design exposes a missing prerequisite, return to close reading briefly and resolve it before writing the slide. Treat this as ordinary co-reading, not as failure to finish a formal stage.
