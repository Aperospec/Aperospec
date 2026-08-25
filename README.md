# Aperospec V2

Aperospec is a two-stage cognitive operating system for maintaining contact with reality and preserving agency under uncertainty.

Its canonical purpose is:

> **Aperospec 不以建立一套关于世界的准确解释为目的。它把一切解释都视为可被现实修正的临时模型，用于帮助主体在真实世界中保住主体性、选择权与行动能力，并通过判断、行动和反馈持续生存与进化。**

Explanation is a provisional tool. Reality, choice, action, and feedback remain authoritative.

## Two Positions

> **先把自己放得足够高，看清局；再把自己放得足够低，回到自身利益与具体约束中博弈。高位防止利益扭曲认知，低位防止认知取消行动。**

`Low` means returning from the system view to the subject's concrete position inside the game.

## Stage 1 — High-Position Observation

Stage 1 is the default. It reconstructs the situation without selecting whose interests should prevail.

It produces:

1. the active frame and its limits
2. the contradictions the current model cannot absorb
3. the temporal formation of the present
4. the actors' public positions, justifying accounts, interests, constraints, strategic functions, and repeated behavior
5. the operating force field
6. a baseline future judgment: the most probable direction if current forces and endogenous adaptation continue without a decisive intervention or structural discontinuity
7. a focus set: the issues that the analysis shows have been pushed into the foreground

Each focus is a conclusion grounded in the formation process, operating forces, current evidence, and baseline future judgment.

Stage 1 can describe factual properties of each focus, such as urgency, scope, reversibility, evidence strength, and time sensitivity. The user decides which focus becomes central, secondary, deferred, or ignored.

## Transition — The User Selects a Focus

Selecting a focus opens Stage 2.

The selected focus is the user's explicit interest choice:

> What do I choose to care about now?

Stage 2 then clarifies the underlying interest drivers:

> Why does this matter to me, and what am I trying to gain, protect, avoid, or preserve?

The Agent may propose a non-exhaustive set of candidate interests for the user to confirm, reject, supplement, and rank. The candidate space remains open and may include money, power, safety, time, autonomy, control, dignity, identity, family, relationships, reputation, psychological cost, mobility, values, exit capacity, and future option value.

## Stage 2 — Grounded Strategic Play

Stage 2 combines:

```text
Stage 1 reality model
+
selected focus
+
subject
+
confirmed interest function
+
desired direction
+
resources and capabilities
+
dependencies and constraints
+
time horizon
+
acceptable and unacceptable loss
```

It then applies appropriate game-theoretic and decision methods to the actual situation.

Stage 2 evaluates:

- strategic reachability: whether the subject can currently move the selected focus toward the desired direction
- other actors' interests, resources, information, dependencies, and likely reactions
- one-shot and repeated interaction
- cooperation, conflict, bargaining, signaling, delay, diversification, coalition, rule change, parallel paths, refusal, and exit
- materially different strategies and their reaction chains
- first action, downside boundary, feedback, contingencies, and review point

`有解` and `无解` are subject-relative reachability judgments. They describe whether the subject can currently move a chosen focus toward a desired state under the stated conditions. They are not permanent properties of reality as a whole.

## Future Judgment

Future judgment has two distinct strategic uses.

### Internal direction

The subject evaluates how the baseline trajectory affects its interests and decides what direction of play is desirable.

### External position

The subject may present a future judgment to other actors as a signal, warning, argument, expectation, or commitment intended to affect their current choices.

The belief about what is most likely and the strategic function of presenting that belief are kept distinct.

## Core Flow

```text
STAGE 1 — HIGH-POSITION OBSERVATION
reality encounter
-> frame surfaced
-> contradiction preserved
-> temporal formation reconstructed
-> positions and operating force field mapped
-> baseline future judgment formed
-> focus set produced

USER TRANSITION
focus selected
-> explicit interest choice
-> underlying interest drivers confirmed
-> desired direction and boundaries defined

STAGE 2 — GROUNDED STRATEGIC PLAY
strategic reachability assessed
-> appropriate game and decision methods applied
-> reaction chains projected
-> strategy selected
-> action taken
-> feedback received
-> model and strategy revised
-> renewed observation
```

## Repository Structure

- `SKILL.md` — executable two-stage Agent protocol
- `references/constitution.md` — normative commitments and authority boundaries
- `references/operating-patterns.md` — reusable working forms for both stages
- `agents/openai.yaml` — Agent display metadata and default invocation prompt
- `evals/evaluation-set.md` — behavioral regression tests

## Use

Invoke `$aperospec` when the visible framing of a consequential situation may be incomplete or misleading and a stronger reality model could change judgment.

Stage 1 is the default. Stage 2 begins when the user selects a focus.

## Status

The `v2` branch contains the finalized V2 specification for review. The `main` branch remains unchanged until the V2 change is deliberately merged.
