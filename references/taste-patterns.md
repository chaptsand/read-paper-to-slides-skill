# Taste Patterns: Reusable Decisions from a Successful Paper-to-Talk Process

This file captures the **reason for a presentation choice**, never a page template to clone. The focal worked example is the research-group presentation of *AblateCell: A Reproduce-then-Ablate Agent for Virtual Cell Repositories* (2026), in a user-approved 30-page deck. The example demonstrates pedagogical choices only. Recheck all paper-specific facts and result numbers against the active source if used again.

## Pattern A: Establish the manipulated objects

**Observed choice:** Before interpreting AblateCell's component ablations, the talk presented the original architectures of three target cell-model repositories (pages 4 to 6). These figures made the later phrases "gene graph encoder" and "perturbation graph encoder" spatially and functionally meaningful.

**Reusable rule:** When a paper optimizes, edits, ranks, or explains components of another model or program, show just enough of that target object to make the later operation intelligible. A concrete original architecture may be worth more than a generic background taxonomy.

**Do not copy:** Three architecture slides for every paper. If the audience already knows the model, consolidate or omit them.

## Pattern B: One authoritative figure, several distinct readings

**Observed choice:** The complete system Figure 2 appeared first, then recurred with emphasis on the knowledge source, planner, code executor, and hypothesis/bandit subsystem (pages 9 to 13). The audience could locate each new detail inside a familiar overview. A later page returned to graph-based execution and worktree isolation (page 22).

**Reusable rule:** Revisit source visuals rather than repeatedly inventing simplified architecture diagrams. Mark the current region, say what goes in, what comes out, and how it connects to the next region. Reveal meaningful increments.

**Do not copy:** Identical duplicates without new focus, or a visually clever crop that hides an essential dependency.

## Pattern C: Insert prerequisites exactly when needed

**Observed choice:** After defining the Top-k ablation goal, the deck introduced multi-armed bandits (MAB) with a simple machine illustration (page 15), then UCB with an equation and toy numerical comparison (page 16), before returning to the focal paper's reward and Algorithm 1 (pages 17 to 18).

**Reusable rule:** Diagnose which concept will block a listener from understanding the upcoming method. Explain it with a compact intuitive situation, then a formula or mini example, then explicitly map the toy terms onto the paper's real actors. Background from outside the paper must be labeled as such.

**Do not copy:** Insert a full reinforcement-learning tutorial into every paper using UCB. If the audience already knows bandits, one bridging sentence may be enough.

## Pattern D: Algorithm as evolving state, supported by a running example

**Observed choice:** The deck first focused on Algorithm 1's dynamic exploration and arm selection, then on execution/reward update (pages 18 to 19). Subsequent pages followed a GEARS Perturbation GNN arm and a possible concrete configuration such as disabling message passing (pages 20 to 21).

**Reusable rule:** Show what the algorithm remembers, how it chooses, which executable thing is produced, how the environment is run, what signal returns, and which state variable changes. Highlight the corresponding pseudocode steps. Keep the same example across steps.

**Do not copy:** Conflate an arm (a hypothesis family) with a candidate configuration; claim all examples were executed if one is only illustrative; duplicate the entire pseudocode in speaker narration.

## Pattern E: Let results answer the paper's actual questions

**Observed choice:** The experimental section introduced the task data and evaluation metrics, then human and agent baselines, workflow success, hypothesis/identification quality, a case study, and a failure breakdown (pages 23 to 29). It did not replace the original tables with marketing-friendly percentages alone.

**Reusable rule:** Establish the meaning and scope of each metric before quoting improvements. Direct attention to the relevant cells of real tables and keep evaluation outcomes distinct (for example, task execution success versus fidelity of component identification).

**Do not copy:** Assume benchmark agreement proves new scientific discovery, or describe a change in one metric as proof of global component importance.

## Pattern F: Research judgment after technical comprehension

**Observed exchange:** During paper reading, the presenter asked why an autonomous agent should repeat ablation studies if the published work had already conducted them. The most useful discussion distinguished replication, automation, component identification, and new scientific insight.

**Reusable rule:** Carry genuine research doubts forward as questions with evidence boundaries. A seminar can close with what the study established and what an extension would need to demonstrate. A presenter's inference must not silently become an author claim.

**Do not copy:** Add a universal "grand AI for Science contribution" slide or overclaim autonomous discovery from automated validation.

## Compact response examples

**Reader asks about a formula:** Explain its purpose, its chosen set/object, the selection constraint, and the practical difficulty; connect that difficulty to the next algorithm. For a top-k sum of individual ablation impacts, explicitly avoid calling it a joint k-component intervention.

**Reader asks whether DAG execution is LangGraph:** Say the graph-based dependency concept is similar to an agent workflow orchestrator, but a named software dependency requires repository evidence. Do not guess the implementation.

**Reader asks to review finished slides with only minor edits:** Keep existing page order and visuals. Name exact pages and recommend only factual fixes, redundancy removal, and terminology cleanup unless major revision is explicitly invited.

**Reader asks for a page-aligned script:** Inspect the actual final deck and narrate figures as the audience sees them. If pages 20 and 21 are progressive reveal versions of the same algorithm, continue the running example rather than restarting the entire explanation. Make sure every page is covered.

## Anti-patterns that earlier attempts risked

- Delivering a large generic method guide when the user asked one technical question.
- Treating the paper's section headings as a mandatory slide outline.
- Optimizing slide polish at the expense of source terminology and scientific accuracy.
- Recreating original scientific figures or data with unsourced visual embellishment.
- Mandating a slide count, recurring color scheme, a fixed number of bullets, or a one-size-fits-all formula page.
- Forcing formal approval at each phase rather than letting the researcher move naturally between reading and writing.
- Producing a long final script but failing to verify that it includes the entire final deck.

**Success criterion:** A new paper produces a different presentation, but the same audience-aware reasoning is visible: faithful scientific objects, justified prerequisites, traceable equations and algorithms, measured results, and independent but grounded judgment.
