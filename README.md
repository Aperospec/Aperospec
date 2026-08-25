# Aperospec V2

Aperospec is a two-stage cognitive operating system for maintaining contact with reality and preserving agency under uncertainty.

> **Aperospec 不以建立一套关于世界的准确解释为目的。它把一切解释都视为可被现实修正的临时模型，用于帮助主体在真实世界中保住主体性、选择权与行动能力，并通过判断、行动和反馈持续生存与进化。**

## Two Positions

> **先把自己放得足够高，看清局；再把自己放得足够低，回到自身利益与具体约束中博弈。高位防止利益扭曲认知，低位防止认知取消行动。**

`Low` means returning from the system view to the subject's concrete position inside the game.

## Stage 1 — High-Position Observation

Stage 1 reconstructs the situation and produces:

1. the active frame and its limits
2. material contradictions
3. the temporal formation of the present
4. actors' public positions, justifying accounts, interests, constraints, strategic functions, and repeated behavior
5. the operating force field
6. a baseline future judgment: the most probable direction produced by the current structure and its endogenous adaptations
7. a focus set: the issues pushed into the foreground by the analysis

Each focus is a conclusion grounded in the formation process, operating forces, current evidence, and baseline future judgment.

The Agent may describe factual attributes of each focus. The user decides which focus becomes central, secondary, deferred, or ignored.

## User Transition

Selecting a focus opens Stage 2.

The selected focus is the user's explicit interest choice:

> What do I choose to care about now?

Stage 2 then clarifies the underlying interest drivers:

> Why does this matter to me, and what am I trying to gain, protect, avoid, or preserve?

The Agent may propose a non-exhaustive set of candidate interests for the user to confirm, reject, supplement, and rank. The interest space remains open and may include money, power, safety, time, autonomy, control, dignity, identity, family, relationships, reputation, psychological cost, mobility, values, exit capacity, future option value, and interests introduced by the user.

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

It evaluates strategic reachability and applies suitable established game-theoretic and decision methods to the actual situation.

`有解` and `无解` are subject-relative reachability judgments. They describe whether the subject can currently move a chosen focus toward a desired state under the stated conditions.

## Future Judgment

Future judgment has two strategic uses.

### Internal Direction

The subject evaluates how the baseline trajectory affects its interests and defines the desired direction of play.

### External Position

The subject may present a future judgment to other actors as a position, signal, warning, argument, commitment, or expectation intended to affect their current choices.

The belief about what is most likely and the strategic function of presenting that belief remain distinct.

## Core Flow

```text
STAGE 1 — HIGH-POSITION OBSERVATION
reality encounter
-> active frame surfaced
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
-> suitable game and decision methods applied
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
- `references/operating-patterns.md` — reusable working forms
- `agents/openai.yaml` — Agent display metadata and default invocation prompt
- `evals/evaluation-set.md` — behavioral regression tests

## Use

Invoke `$aperospec` when the visible framing of a consequential situation may be incomplete or misleading and a stronger reality model could change judgment.

Stage 1 produces the reality model, baseline future judgment, and focus set. Stage 2 begins when the user selects a focus.

## Status

The `v2` branch contains the finalized V2 specification for review. The `main` branch remains unchanged until the V2 change is deliberately merged.
