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

Use small teaching examples when they clarify a concrete operation, and map their objects back to the paper. Label them as illustrative. Do not invent a module, result, or exact parameter setting to fill a gap. Distinguish conceptual similarity to a named framework from verified software usage.

## Explain equations

For each equation needed to understand the argument:

1. State the problem it addresses and where it is used.
2. Define the symbols, objects, and relevant dimensions.
3. Explain the computation or objective in plain language.
4. Connect its output to selection, training, inference, or evaluation.
5. State important assumptions, normalization, tradeoffs, and interpretation limits.

Use the depth needed for the current question; these steps are explanation aids, not compulsory reply headings. Preserve the original equation and notation before simplifying it. Distinguish a definition, an optimization objective, a heuristic, and a proved result. Do not turn a mathematical expectation into an unsupported description of the implemented evaluation procedure.

## Read the experiments

Establish the evaluation protocol before reading winners: task, data scale and units, labels, split, validation and selection procedure, repeated runs, metric definitions, and controls across comparisons.

For a composite metric, reconstruct its components, transformations, weights, direction, and runtime convention if specified. Keep it separate from each underlying score. A fitness increase alone does not establish a predictive-performance increase.

Explain what each baseline and ablation changes and what conclusion it can support. Check whether architecture, preprocessing, features, topology, training, hardware, or budget also changes. Treat a missing detail as unreported, with any consequence framed conditionally.

Read exceptions as part of the result. Retain ties, reversals, task dependence, and restrictions on generalization. Do not infer an unreported benchmark number or a statistical conclusion.

Distinguish reproduction, automation, recovery of known findings, and new scientific insight when assessing what the experiments establish. Discuss research value or extensions when the user's question calls for it.

Use case studies to connect the method to a concrete observed change. Explain whether a case supports feasibility, interpretability, transfer, or effectiveness; do not elevate one example into a universal conclusion.

## Deliver the requested reading material

For a broad guide, organize around problem and motivation, necessary background, method and equations, evaluation and results, evidence boundaries, and useful discussion questions. Adjust depth to the paper and the user's confusion instead of enforcing a fixed heading list.

For a Markdown mind map, use meaningful nested headings or lists: problem, prerequisites, method components, optimization/evaluation, evidence, and limitations. Express dependencies and roles rather than copying the paper's contents page. Add source locators where they help later review.

For a targeted question, lead with the relationship or definition that resolves it, then give the necessary mechanism and source evidence. Separate paper-specific terminology from established disciplinary usage. Avoid reopening the entire reading workflow.

