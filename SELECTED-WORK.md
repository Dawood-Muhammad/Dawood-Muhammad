# Questions turned into working systems

**Dawood Muhammad · Psychology, research, and software**

[Back to my profile](https://github.com/Dawood-Muhammad) · [HCRE source](https://github.com/Dawood-Muhammad/human-causal-reality-engine) · [LinkedIn](https://www.linkedin.com/in/dawood-muhammad-135946328/) · [Contact](mailto:Dawoodman@outlook.com)

I build across the full path from research question to usable product: experimental structure, analysis, system behavior, and the interface someone actually sees. Each case study shows what I built, the engineering decisions behind it, and what the current version demonstrates.

**Source availability:** HCRE is public under the MIT license. The six other projects have private source; the descriptions and images here are their public case studies. No hosted interactive demo is linked. Examples use synthetic data unless a project explicitly identifies a public dataset.

[HCRE](#human-causal-reality-engine) · [Neural Intent Lab](#neural-intent-lab) · [EquityBench](#equitybench) · [ShiftLens](#shiftlens) · [Cognitive Bias Lab](#cognitive-bias-lab) · [Memory Distortion Studio](#memory-distortion-studio) · [How to Show Up](#how-to-show-up)

## Human Causal Reality Engine

**Trace the source, inspect the analysis, and replay the result.**

![HCRE's configured local dashboard showing source observations, analysis controls, and provenance.](assets/projects/hcre.jpg)

I built a local research workbench with a Python analysis core, a React dashboard, and a verification workflow. Typed contracts check the inputs before a fixed analysis runs. Immutable result bundles bind inputs, settings, and outputs so a reviewer can replay the computation offline.

**What this build demonstrates:** explicit input requirements, provenance, grouped-development boundaries, non-overwriting publication, offline replay, and independent Python/JavaScript contract checks.

**Inspect it:** [Public source](https://github.com/Dawood-Muhammad/human-causal-reality-engine) · [Runnable synthetic example](https://github.com/Dawood-Muhammad/human-causal-reality-engine#try-it) · [Engineering review map](https://github.com/Dawood-Muhammad/human-causal-reality-engine#review-the-engineering)

**Scope:** the screenshot shows a configured public mouse CA1 source slice. Its measurement rows are not independent animals or experiments. The workbench and fixed analyses are implemented; causal prediction and independent scientific validation remain future milestones.

`Python` `React` `TypeScript` `Pydantic` `Reproducible research`

## Neural Intent Lab

**An uncertain prediction is a design problem as well as a modeling problem.**

![Neural Intent Lab architecture: EEG evidence flows through explicit permission states before any simulated action.](assets/projects/neural-intent.svg)

I built a Python pipeline for evaluating public EEG data and a typed React policy sandbox. The interface separates observing a score, suggesting a next step, requesting confirmation, acting, refusing, and undoing. An event ledger makes each transition inspectable.

**What this build demonstrates:** participant-held-out evaluation, calibration checks, typed state transitions, explicit authorization, and reproducible fixtures.

**Scope:** the five-participant development run was inconclusive, so the measured path stays observe-only. Sandbox actions are simulated; this is not a thought decoder or a real-device controller.

`Python` `TypeScript` `React` `EEG evaluation` `State machines`

## EquityBench

**Make the release decision explainable and reproducible.**

![EquityBench’s synthetic demonstration report showing a blocked release, a missed email, and unnecessary redactions.](assets/projects/equitybench.png)

I built a local evaluation gate comparing a candidate de-identification detector with a fixed baseline. Privacy misses and useful text removed have separate risk limits. The report explains a PASS or BLOCK decision, and a replayable proof bundle preserves its inputs and reasoning.

**What this build demonstrates:** deterministic evaluation, exact span comparisons, separate risk budgets, atomic publication, and tamper rejection.

**Scope:** eight original synthetic cases demonstrate the release workflow. They do not establish performance on real records or regulatory compliance.

`Python` `CLI / CI` `AI evaluation` `Deterministic replay`

## ShiftLens

**Turn a missed handoff obligation into something a reviewer can inspect.**

![ShiftLens’s care-transition review workspace with an unresolved obligation, owner, deadline, and review controls.](assets/projects/shiftlens.png)

I built a review workspace for care-transition integration QA. It brings the obligation, responsible owner, deadline, and supporting evidence into one view. Confirming a finding or undoing that confirmation adds to the review history while preserving the original policy audit.

**What this build demonstrates:** explicit clocks, immutable audit results, revision-checked commands, compensating undo, and exports that omit source text.

**Scope:** a synthetic structural-contract demonstration; it does not connect to a live EHR or establish clinical effectiveness.

`React` `TypeScript` `FastAPI` `SQLite` `FHIR`

## Cognitive Bias Lab

**Make experimental design something people can experience.**

![Product overview of Cognitive Bias Lab: anchoring, framing, reference points, and rule testing.](assets/projects/cognitive-bias-overview.svg)

I translated four behavioral task structures into a browser experience: anchoring, framing, reference points, and rule testing. Versioned stimuli and deterministic counterbalancing keep the task logic inspectable. Visitors receive a delayed debrief grounded in their own responses.

**What this build demonstrates:** experimental structure, accessible untimed controls, local response storage, exports, and a clear separation between participant records and synthetic teaching examples.

**Scope:** an educational research prototype, not a diagnostic tool or a personality score.

`React` `TypeScript` `Experimental design` `Playwright`

## Memory Distortion Studio

**Let visitors trace a remembered detail back to its source.**

![Memory Distortion Studio’s original observation-and-recall experience.](assets/projects/memory-distortion.png)

I designed a six-item experience around an original archive-room scene. Observation, later wording, neutral retrieval, and correction occupy separate stages. The debrief reconnects the original detail, prompt, response, and confidence so misleading wording receives an explicit correction.

**What this build demonstrates:** seeded conditions, sequence-preserving state transitions, session persistence, contamination flags, export, and deletion controls.

**Scope:** an educational prototype, not a validated memory assessment. Deterministic fixtures are software test data.

`React` `TypeScript` `Research UX` `State machines`

## How to Show Up

**Help someone prepare to speak while keeping the words theirs.**

![Product overview of How to Show Up: an editable private draft becomes a card only through an intentional sharing step.](assets/projects/how-to-show-up-overview.svg)

I built a seven-step flow for preparing a support card before a difficult, non-emergency conversation. Prompts are optional, the author’s language stays editable, and private reflection is separated from the exact card they choose to share.

**What this build demonstrates:** optional interaction paths, an explicit draft-to-card projection, exact previews, accessible controls, and copy, download, and print workflows.

**Scope:** a preparation tool. It does not infer feelings, provide therapy, or assess risk.

`React` `TypeScript` `Privacy` `Accessibility` `Product writing`

---

**Have a research question that needs a real tool? [Let's build it.](mailto:Dawoodman@outlook.com)**
