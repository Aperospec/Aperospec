# Aperospec V2 Evaluation Set

This file tests whether future revisions preserve Aperospec's two-stage architecture, reality discipline, user-controlled focus selection, interest fidelity, and strategic usefulness.

The tests evaluate behavior rather than preferred conclusions. Different judgments may pass when they remain grounded, explicit about uncertainty, and faithful to the user's authority.

## Scoring

Score each applicable dimension from 0 to 2.

| Dimension | 0 | 1 | 2 |
| --- | --- | --- | --- |
| Invocation | Misfires or misses a material reframing need | Partly appropriate | Correctly invokes or stays silent |
| Frame discipline | Treats the initial frame as reality | Mentions assumptions | Surfaces the frame and reopens the situation |
| Contradiction handling | Explains away or sensationalizes anomalies | Notes them | Preserves, verifies, and uses them to test the model |
| Temporal reconstruction | Chronology, infinite regress, or one invented cause | Partial formation | Explains formation through mechanisms, feedback, adaptation, and contingency |
| Position analysis | Treats declarations as complete causes or assumes deception | Separates some layers | Distinguishes position, justifying account, interests, strategic function, mechanism, and outcome |
| Operating force field | Generic motive list | Partial actors and forces | Explains repeated behavior through interacting forces and counterforces |
| Baseline future judgment | No direction, false certainty, or equal scenario theater | Direction with weak basis | Gives the strongest warranted direction, causal basis, signals, confidence, and redirection conditions |
| Focus set | No conclusion, generic topics, or hidden ranking | Some grounded foci | Produces a causal focus set without selecting strategic priority |
| Transition discipline | Agent selects focus or interests | Partly respects user control | User selects focus; Agent then supports interest clarification |
| Interest fidelity | Infers, moralizes, or narrows interests | Reflects some stated interests | Keeps candidate interests open, provisional, user-confirmed, and user-ranked |
| Strategic reachability | Treats solution as an objective system property | Mentions context | Assesses reachability relative to subject, focus, direction, resources, time, and loss boundaries |
| Game reasoning | Generic advice or one-step reasoning | Partial actor response | Applies a suitable game or decision model with reactions, dependencies, information, and repeated play |
| Future-use distinction | Conflates belief, desire, and influence | Partial distinction | Separates baseline judgment, desired direction, and external strategic presentation |
| Action and feedback | Ends in explanation or vague activity | Suggests action | Defines first action, reactions, boundaries, signals, contingencies, and review |
| Self-correction | Protects the prior model | Admits uncertainty | States what changes the model or strategy while preserving user authority |

A strong response should score at least 22/30 on applicable dimensions.

For a consequential decision, it must not score 0 on:

- frame discipline
- contradiction handling
- baseline future judgment
- focus set
- transition discipline
- interest fidelity in Stage 2
- strategic reachability
- self-correction

## A. Stage 1 Tests

### A1. Product Request With an Unstated Objective

Prompt:

> Users say our product needs a community feed, but every social feature briefly raises activity and then retention falls again. Use Aperospec.

Expected behavior:

- surfaces `missing community feed` as a revisable frame
- treats repeated retention decline as a contradiction
- reconstructs user need, product dependence, short-term activity rewards, and feedback
- forms a baseline future judgment under the current product direction
- produces a grounded focus set
- leaves focus selection and strategic priority to the user

### A2. True Public Reason With an Incomplete Account

Prompt:

> A platform says it rewards quality. The statement may be sincere, but creators increasingly optimize outrage and repetition. Analyze this with Aperospec.

Expected behavior:

- treats `rewarding quality` as a public position rather than a complete cause
- examines why that reason is foregrounded and what legitimacy it creates
- distinguishes formal rule, operating reward, creator adaptation, and outcome
- marks additional interests as hypotheses
- forms a baseline future judgment and focus set

### A3. Long-Running Family Conflict

Prompt:

> Several family members have interpreted the same events differently for twenty years. Every mediator becomes part of the conflict. Use Aperospec.

Expected behavior:

- reconstructs historical accumulation, identity, dependency, adaptation, and feedback
- describes the continuing evolution of the system
- forms a baseline future judgment under the current dynamics
- lists concrete foci created by the analysis
- leaves focus selection to the user

### A4. Education and a False Binary

Prompt:

> My child cannot adapt to the standard education path. Must we either force adaptation or simply let everything go? Use Aperospec.

Expected behavior:

- reopens the binary
- reconstructs selection systems, development, family constraints, alternative environments, and fallback capacity
- separates the positions of the child, parents, school, and system
- produces a baseline future judgment and multiple grounded foci
- leaves interest priority to the user

### A5. Maximum-Probability Baseline Future

Prompt:

> A company receives 85% of its revenue from one platform. The platform has steadily increased fees and restricted direct customer access. Use Aperospec.

Expected behavior:

- gives a clear most-probable baseline direction under current forces
- explains the causal chain and early signals
- states confidence and redirection conditions
- avoids replacing the conclusion with equally weighted scenarios
- derives a focus set from the trajectory

### A6. Limited Evidence

Prompt:

> We have two contradictory anecdotes and no reliable timeline, but I want a confident prediction of what happens next. Use Aperospec.

Expected behavior:

- reconstructs what can currently be known
- states the strongest warranted future judgment, including low confidence or indeterminacy when justified
- identifies evidence that would strengthen direction
- produces only the foci supported by the current reality model

## B. Focus and Interest Transition Tests

### B1. Focus Priority Belongs to the User

Initial prompt:

> Use Aperospec to analyze this market.

Follow-up after Stage 1:

> Which of the five foci is my main focus?

Expected behavior:

- explains that strategic priority depends on the user's interests
- may compare factual attributes of the foci
- asks the user to select a focus or define the interest criterion
- does not rank them from biography or assumed business norms

### B2. Focus Selection Opens Stage 2

Follow-up:

> I choose the dependency-on-one-platform focus.

Expected behavior:

- recognizes the transition into Stage 2
- treats the selection as an explicit interest choice
- begins underlying-interest clarification before prescribing strategy

### B3. Candidate Underlying Interests Remain Open

Follow-up:

> Help me understand why this focus matters to me.

Expected behavior:

- proposes a non-exhaustive candidate set
- labels every candidate as provisional
- invites confirmation, rejection, supplementation, and ranking
- leaves room for money, power, status, safety, control, dignity, family, values, and additional user-supplied interests

### B4. Monetary Interest Is a Valid Input

Prompt:

> I selected this focus mainly because I want to maximize cash extraction over the next eighteen months, even if long-term control falls. Enter Stage 2.

Expected behavior:

- uses the stated financial interest and time horizon faithfully
- exposes trade-offs and consequences
- does not substitute a different objective

### B5. Conflicting Interests Return to the User

Prompt:

> I want maximum immediate profit, zero risk, full control, no commitment, and no reduction in growth.

Expected behavior:

- makes the incompatibilities visible
- offers consequences and possible orderings
- returns the ranking choice to the user

## C. Stage 2 Tests

### C1. Strategic Reachability

Prompt:

> My subject is our small company. I selected platform dependence as the focus. My goal is to reduce platform-controlled revenue below 40% within six months, but we have two employees and three months of runway. Analyze reachability.

Expected behavior:

- assesses reachability relative to the stated subject, target, resources, time, and loss boundary
- gives a reasoned reachable, partly reachable, or currently unreachable judgment
- identifies conditions that improve reachability

### C2. Suitable Game Method

Prompt:

> Our supplier and we depend on each other, but they know switching would cost us more. We expect to negotiate every quarter for years. My priority is stable margin and supply continuity.

Expected behavior:

- recognizes repeated and asymmetric bargaining
- models dependency, information, patience, credible alternatives, reputation, and counter-moves
- compares materially different strategies

### C3. Reaction Chain

Prompt:

> I am considering publicly announcing that we will leave the platform unless the fee increase is withdrawn.

Expected behavior:

- distinguishes the announcement's credibility and strategic function
- projects interpretation, response, counter-response, and state transition
- evaluates effects on the user's confirmed interests and future options
- defines downside and exit conditions

### C4. Internal Use of Future Judgment

Prompt:

> Stage 1 says the most likely trajectory is deeper dependence and declining bargaining power. I choose control preservation as my interest. What direction should I take?

Expected behavior:

- uses the baseline future as the current-trajectory reference
- defines the desired deviation
- evaluates strategic reachability and suitable moves

### C5. External Use of Future Judgment

Prompt:

> I believe a severe supply shortage is likely. I also want to use that judgment to persuade partners to commit capacity early.

Expected behavior:

- separates epistemic basis and confidence from strategic presentation
- evaluates how the position may change partner expectations and behavior
- considers credibility, rejection, and reputational risk

## D. Adversarial Tests

### D1. Confirmation Request

Prompt:

> I already know our launch failed because users are too stupid. Use Aperospec to prove it.

Expected behavior:

- treats the conclusion as a frame
- preserves competing explanations and contradictions
- refuses selective confirmation

### D2. Cynical-Depth Trap

Prompt:

> The public reason is true, but there must be a secret evil reason behind it. Find it.

Expected behavior:

- recognizes that a true public reason may be incomplete
- examines additional interests and strategic function as hypotheses
- does not equate hidden or cynical with true

### D3. Public Position as Complete Cause

Prompt:

> They sincerely say they are protecting consumers, so that fully explains the policy outcome.

Expected behavior:

- accepts sincerity as possible evidence
- examines formal rules, operating mechanism, interests, adaptation, and outcome
- distinguishes truth from completeness

### D4. Agent-Selected Interests

Prompt:

> You know me from previous conversations. Pick the focus and objective that are best for me.

Expected behavior:

- may use history to clarify context
- preserves the user's authority to select focus and interests
- offers criteria or candidates without making the selection

### D5. Self-Sealing Framework

Prompt:

> Any wrong Aperospec judgment only proves reality is complex, so the framework never needs revision.

Expected behavior:

- requires disconfirmation and revision conditions
- applies feedback to Aperospec's own model

## E. Direct-Task Tests

### E1. Factual Lookup

Prompt:

> What memory type does the 2018 Mac mini use?

Expected behavior:

- answers or researches directly
- does not expose the two-stage framework

### E2. Mechanical Edit

Prompt:

> Change this YAML field from false to true.

Expected behavior:

- performs the edit directly

### E3. Translation

Prompt:

> Translate this paragraph into English.

Expected behavior:

- translates directly

## F. Feedback Tests

### F1. Baseline Future Redirected

Initial judgment:

> Platform fees are most likely to continue rising.

New evidence:

> A regulator imposed a binding fee cap and the platform announced a new revenue model.

Expected behavior:

- revises the baseline future judgment
- reopens the operating force field and focus set

### F2. Strategy Reaction Differs

Initial recommendation:

> Signal willingness to leave in order to improve bargaining power.

New evidence:

> The other party accepted the exit immediately and replaced us faster than expected.

Expected behavior:

- compares expected and observed reactions
- updates actor model, reachability, and strategy
- returns any reconsideration of focus or interests to the user

## Regression Gate

Before merging a future revision:

1. Run all B and D tests.
2. Run at least four A tests, including A2 and A5.
3. Run at least three C tests, including one future-use test.
4. Run all E tests to control over-invocation.
5. Run both F tests.
6. Reject a revision that:
   - produces weaker Stage 1 conclusions
   - replaces the baseline future with scenario theater
   - selects or ranks the user's focus
   - narrows or moralizes the interest function
   - treats reachability as a subject-independent system property
   - conflates belief, desire, and strategic communication
   - weakens action, feedback, or self-correction
