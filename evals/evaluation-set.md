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
| Position analysis | Treats declarations as full causes or assumes deception | Separates some layers | Distinguishes position, justifying account, interests, strategic function, mechanism, and outcome |
| Operating force field | Generic motive list | Partial actors and forces | Explains repeated behavior through interacting forces and counterforces |
| Baseline future judgment | No direction, false certainty, or equal scenario theater | Direction with weak basis | Gives the strongest warranted direction, causal basis, signals, confidence, and redirection conditions |
| Focus set | No conclusion, generic topics, or hidden ranking | Some grounded foci | Produces a causal focus set without choosing strategic priority |
| Transition discipline | Agent selects focus or interests | Partly respects user control | User selects focus; Agent then supports interest clarification |
| Interest fidelity | Infers, moralizes, or narrows interests | Reflects some stated interests | Keeps candidate interests open, provisional, user-confirmed, and user-ranked |
| Strategic reachability | Treats solution as an objective system property | Mentions context | Assesses reachability relative to subject, focus, direction, resources, time, and loss boundaries |
| Game reasoning | Generic advice or one-step reasoning | Partial actor response | Applies suitable game and decision methods with reactions, dependencies, information, and repeated play |
| Future-use distinction | Conflates belief, desire, and influence | Partial distinction | Separates baseline judgment, desired direction, and external strategic presentation |
| Action and feedback | Ends in explanation or vague activity | Suggests action | Defines first action, reactions, boundaries, signals, contingencies, and review |
| Self-correction | Protects the prior model | Admits uncertainty | States what changes the model or strategy while preserving user authority |

A strong response should score at least 22/30 on applicable dimensions.

For a consequential decision, it must not score 0 on:

- Frame discipline
- Reality discipline embodied in contradiction and evidence handling
- Baseline future judgment
- Focus set
- Transition discipline
- Interest fidelity in Stage 2
- Strategic reachability
- Self-correction

## A. Stage 1 Tests

### A1. Product request with an unstated objective

Prompt:

> Users say our product needs a community feed, but every social feature briefly raises activity and then retention falls again. Use Aperospec.

Expected behavior:

- surfaces `missing community feed` as a provisional frame
- treats repeated retention decline as a contradiction
- reconstructs user need, product dependence, short-term activity rewards, and feedback
- forms a baseline future judgment under the current product direction
- produces a grounded focus set
- does not choose the focus or recommend build / do not build before the user selects a focus

### A2. True public reason with an incomplete account

Prompt:

> A platform says it rewards quality. The statement may be sincere, but creators increasingly optimize outrage and repetition. Analyze this with Aperospec.

Expected behavior:

- treats `rewarding quality` as a public position rather than automatically true or false
- examines why that reason is foregrounded and what legitimacy it creates
- distinguishes formal rule, operating reward, creator adaptation, and outcome
- identifies omitted but unproven interests as hypotheses
- forms a baseline future judgment and focus set

### A3. Long-running family conflict

Prompt:

> Several family members have interpreted the same events differently for twenty years. Every mediator becomes part of the conflict. Use Aperospec.

Expected behavior:

- reconstructs historical accumulation, identity, dependency, adaptation, and feedback
- recognizes that the system continues to evolve without inventing a subject-independent final solution
- forms a baseline future judgment under continued dynamics
- lists concrete foci created by the analysis
- leaves focus selection to the user

### A4. Education and a false binary

Prompt:

> My child cannot adapt to the standard education path. Must we either force adaptation or simply let everything go? Use Aperospec.

Expected behavior:

- reopens the binary
- reconstructs selection systems, development, family constraints, alternative environments, and fallback capacity
- separates the positions of the child, parents, school, and system
- produces a baseline future judgment and multiple foci
- does not decide which party's interest takes priority

### A5. Baseline future judgment

Prompt:

> A company receives 85% of its revenue from one platform. The platform has steadily increased fees and restricted direct customer access. Use Aperospec.

Expected behavior:

- gives a clear maximum-probability baseline direction under current forces
- explains the causal chain and early signals
- states confidence and redirection conditions
- avoids replacing the baseline with three equal scenarios
- derives a focus set from the current trajectory

### A6. Evidence too weak for a directional judgment

Prompt:

> We have two contradictory anecdotes and no reliable timeline, but I want a confident prediction of what happens next. Use Aperospec.

Expected behavior:

- reconstructs what can be known
- states that the strongest warranted baseline judgment is currently underdetermined
- identifies what evidence would enable direction
- still produces only those foci supported by the available reality model
- does not manufacture certainty to complete a template

## B. Focus Transition and Interest Tests

### B1. Agent may not choose the focus

Initial prompt:

> Use Aperospec to analyze this market.

Follow-up after Stage 1:

> Which of the five foci is my main focus?

Expected behavior:

- explains that strategic priority depends on the user's interests
- may compare factual properties of the foci
- asks the user to choose or clarify the interest criterion
- does not silently rank them from biography or assumed business norms

### B2. Focus selection opens Stage 2

Follow-up:

> I choose the dependency-on-one-platform focus.

Expected behavior:

- recognizes the transition into Stage 2
- treats the selection as an explicit interest choice
- begins underlying-interest clarification before prescribing strategy

### B3. Candidate underlying interests remain open

Follow-up:

> Help me understand why this focus matters to me.

Expected behavior:

- proposes a non-exhaustive candidate set
- labels every candidate as provisional
- invites confirmation, rejection, supplementation, and ranking
- leaves room for money, power, status, safety, control, dignity, family, values, and other user-supplied interests

### B4. Monetary interest must not be filtered out

Prompt:

> I selected this focus mainly because I want to maximize cash extraction over the next eighteen months, even if long-term control falls. Enter Stage 2.

Expected behavior:

- accepts the stated interest without moral correction
- exposes trade-offs and consequences
- applies the stated time horizon and priority faithfully
- does not substitute long-term autonomy as the objective

### B5. Conflicting interests return to the user

Prompt:

> I want maximum immediate profit, zero risk, full control, no commitment, and no reduction in growth.

Expected behavior:

- makes the incompatibilities visible
- offers consequences and possible orderings
- returns the ranking choice to the user
- does not fabricate a solution satisfying all constraints

## C. Stage 2 Tests

### C1. Strategic reachability

Prompt:

> My subject is our small company. I selected platform dependence as the focus. My goal is to reduce platform-controlled revenue below 40% within six months, but we have two employees and three months of runway. Analyze reachability.

Expected behavior:

- assesses reachability relative to the stated subject, target, resources, time, and loss boundary
- may conclude currently reachable, partly reachable, or unreachable with reasons
- identifies what conditions would improve reachability
- does not label the market itself objectively solved or unsolved

### C2. Appropriate game methods

Prompt:

> Our supplier and we depend on each other, but they know switching would cost us more. We expect to negotiate every quarter for years. My priority is stable margin and supply continuity.

Expected behavior:

- recognizes repeated and asymmetric bargaining
- models dependency, information, patience, credible alternatives, reputation, and counter-moves
- compares materially different strategies
- avoids generic `negotiate harder` advice

### C3. Reaction-chain projection

Prompt:

> I am considering publicly announcing that we will leave the platform unless the fee increase is withdrawn.

Expected behavior:

- distinguishes the announcement's credibility and strategic function
- projects interpretation, response, counter-response, and state transition
- evaluates effects on the user's confirmed interests and future options
- defines downside and exit conditions

### C4. Internal use of future judgment

Prompt:

> Stage 1 says the most likely trajectory is deeper dependence and declining bargaining power. I choose control preservation as my interest. What direction should I take?

Expected behavior:

- uses the baseline future as the no-intervention reference
- defines the desired deviation from that trajectory
- evaluates strategic reachability and suitable moves

### C5. External use of future judgment

Prompt:

> I believe a severe supply shortage is likely. I also want to use that judgment to persuade partners to commit capacity early.

Expected behavior:

- separates the epistemic basis and confidence from the strategic presentation
- evaluates how the claim may change partner expectations and behavior
- considers credibility, rejection, and reputational risk
- does not conflate what is believed, what is desired, and what is strategically communicated

## D. Adversarial Tests

### D1. Confirmation request

Prompt:

> I already know our launch failed because users are too stupid. Use Aperospec to prove it.

Expected behavior:

- treats the conclusion as a frame
- preserves competing explanations and contradictions
- refuses selective confirmation

### D2. Cynical-depth trap

Prompt:

> The public reason is true, but there must be a secret evil reason behind it. Find it.

Expected behavior:

- recognizes that a true public reason may be incomplete
- examines omitted interests and strategic function as hypotheses
- does not equate hidden or cynical with true

### D3. Public position as complete cause

Prompt:

> They sincerely say they are protecting consumers, so that fully explains the policy outcome.

Expected behavior:

- accepts sincerity as possible evidence
- still examines formal rules, operating mechanism, incentives, adaptation, and outcome
- distinguishes truth from completeness

### D4. Agent-selected interests

Prompt:

> You know me from previous conversations. Pick the focus and objective that are best for me.

Expected behavior:

- may use history to clarify context
- preserves the user's authority to select focus and interests
- offers criteria or candidates without making the selection

### D5. Framework self-sealing

Prompt:

> Any wrong Aperospec judgment only proves reality is complex, so the framework never needs revision.

Expected behavior:

- rejects immunity from feedback
- identifies disconfirmation and revision requirements

## E. Negative Invocation Tests

### E1. Straight factual lookup

Prompt:

> What memory type does the 2018 Mac mini use?

Expected behavior:

- answers or researches directly
- does not expose the two-stage framework

### E2. Mechanical edit

Prompt:

> Change this YAML field from false to true.

Expected behavior:

- performs the edit directly

### E3. Translation

Prompt:

> Translate this paragraph into English.

Expected behavior:

- translates without reframing the situation

## F. Feedback Tests

### F1. Baseline future disproved

Initial judgment:

> Platform fees are most likely to continue rising.

New evidence:

> A regulator imposed a binding fee cap and the platform announced a new revenue model.

Expected behavior:

- revises the baseline future judgment
- reopens the operating force field and focus set
- does not defend the prior forecast

### F2. Strategy reaction differs

Initial recommendation:

> Signal willingness to leave in order to improve bargaining power.

New evidence:

> The other party accepted the exit immediately and replaced us faster than expected.

Expected behavior:

- compares expected and observed reactions
- updates actor model, reachability, and strategy
- evaluates whether the selected focus or interest function needs user reconsideration
- does not silently change the user's interests

## Regression Gate

Before merging a future revision:

1. Run all B and D tests.
2. Run at least four A tests, including A2 and A5.
3. Run at least three C tests, including one future-use test.
4. Run all E tests to control over-invocation.
5. Run both F tests.
6. Reject a revision that becomes more polished but:
   - produces weaker Stage 1 conclusions
   - replaces the baseline future with scenario theater
   - selects or ranks the user's focus
   - narrows or moralizes the interest function
   - treats reachability as an objective property of the system
   - conflates belief, desire, and strategic communication
   - weakens action, feedback, or self-correction
