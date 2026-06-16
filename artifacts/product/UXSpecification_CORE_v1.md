# UXSpecification_CORE_v1.md

## Document Information

| Item | Value |
|--------|--------|
| Artifact Type | UX Specification |
| Project | AA |
| Version | CORE_v1 |
| Lifecycle Stage | UX Specification |
| Status | Frozen |
| Based On | artifacts/problem/ProblemDefinition_CORE_v1.md; artifacts/solution/SolutionDefinition_CORE_v1.md; artifacts/product/ProductRepresentation_CORE_v1.md; artifacts/product/ProductRequirement_CORE_v1.md |

---

# Purpose

This document defines the user experience requirements for AA.

AA must help Yuanyuan discover, understand, connect, build, reason, persist, recover from difficulty, and see growth through a personal knowledge world.

This document does not define visual design, technical architecture, implementation details, MVP scope, or task breakdown.

---

# UX Positioning

AA is experienced as a personal knowledge world for growth through exploration.

The primary child experience is:

```text
I discovered something meaningful.
I understand how things connect.
I can build my own world.
I can keep trying when it is difficult.
```

The product must not feel like:

```text
I completed assigned exercises.
I am being tested.
I must repeat until I satisfy an adult.
```

---

# UX Goals

1. Make discovery the starting point of each learning session.
2. Make knowledge connections visible and understandable before asking for repeated practice.
3. Support personal knowledge world construction across the frozen worlds.
4. Help Yuanyuan feel mastery through understanding, explanation, classification, reasoning, and transfer.
5. Make growth qualities visible, including emotional regulation, persistence, focus, courage to face difficulty, and growth mindset.
6. Reduce parent supervision by giving parents concise insight into growth signals.
7. Keep sessions short, low pressure, and suitable for home after-school use.

---

# User Profiles

## Primary User

Yuanyuan.

User characteristics:

- Primary school child, approximately 7-12 years old.
- Needs age-appropriate discovery and reasoning.
- Benefits from short, clear, emotionally positive activities.
- Responds better to discovery, construction, and mastery than drill volume.
- May experience frustration when facing difficulty.
- Needs immediate feedback that protects willingness to continue.

## Secondary User

Parent.

User characteristics:

- Wants to support literacy and broader growth.
- Does not want to become a full-time teacher, examiner, or continuous supervisor.
- Needs clear signals of growth without reviewing every answer.
- Values lower emotional conflict and sustained engagement.

---

# User Journeys

## Journey 1: Child Discovery Session

1. Yuanyuan enters AA and sees a clear next discovery opportunity.
2. AA presents a meaningful pattern, relationship, story, or question.
3. Yuanyuan explores the relationship through a short interaction.
4. AA gives immediate feedback that explains what was discovered or understood.
5. Yuanyuan connects the discovery to a knowledge world.
6. AA shows how the world grew through the session.
7. Yuanyuan leaves with a clear sense of progress and curiosity for the next return.

## Journey 2: Difficulty and Recovery

1. Yuanyuan encounters a challenge that is not immediately solved.
2. AA lowers pressure and frames the moment as exploration rather than failure.
3. AA offers a hint, comparison, or simpler connection.
4. Yuanyuan tries again or chooses a nearby discovery path.
5. AA recognizes recovery, persistence, focus, or reasoning effort.
6. The session records growth through trying again, not only correct completion.

## Journey 3: Knowledge World Construction

1. Yuanyuan chooses or receives an age-appropriate discovery path.
2. AA helps connect new knowledge to an existing world.
3. Yuanyuan sees how the new item relates through structure, classification, hierarchy, time, space, evolution, causality, inference, or transfer.
4. Yuanyuan adds the discovered relationship into the personal world.
5. AA makes the world feel owned by Yuanyuan rather than assigned by an adult.

## Journey 4: Parent Review

1. Parent opens a concise growth view.
2. Parent sees recent discovery, persistence, focus, recovery, reasoning, and understanding signals.
3. Parent can understand whether Yuanyuan is returning and growing without checking every answer.
4. Parent receives enough context to encourage the child without turning the product into supervision.

---

# User Flows

## Flow 1: Start Session

1. Open AA.
2. Resume the current knowledge world or start the next recommended discovery.
3. Show one clear discovery objective.
4. Start without requiring configuration, scoring setup, or parent involvement.

## Flow 2: Explore Discovery

1. Present a pattern, relationship, story, or counterfactual question.
2. Let Yuanyuan observe, choose, classify, connect, explain, or simulate.
3. Provide feedback after each meaningful action.
4. Offer a hint when confusion or repeated difficulty appears.
5. End the activity with a visible connection to world growth.

## Flow 3: Build Knowledge World

1. Identify what was discovered.
2. Show what it connects to.
3. Let Yuanyuan place, link, or confirm the relationship.
4. Record the world growth.
5. Preview a nearby future discovery.

## Flow 4: Recover From Difficulty

1. Detect incorrect answer, hesitation, repeated attempt, or abandoned action.
2. Respond with a low-pressure explanation or hint.
3. Offer a simpler related step.
4. Recognize trying again and reasoning effort.
5. Return to the discovery path without punishment.

## Flow 5: Parent Insight

1. Parent opens the review area.
2. AA summarizes engagement and growth signals.
3. AA highlights discovery, persistence, recovery, focus, inference, and understanding.
4. Parent can close the review without needing to correct or teach.

---

# Interaction Principles

## Discovery Before Completion

Interactions must make the child feel that something meaningful was found, not merely that a task was finished.

## Connection Before Isolation

Every experience should help knowledge become connected to other knowledge, a world, or a reasoning pattern.

## Mastery Before Memorization

Interactions must privilege understanding, explanation, classification, reasoning, and transfer over repetition volume.

## Growth Before Achievement

The product should recognize growth qualities, including recovery after difficulty, sustained focus, and willingness to try again.

## Low Pressure Before Performance

The experience must avoid shame, countdown pressure, public ranking, punishment, or adult-like testing tone.

## Parent Insight Before Parent Supervision

Parent-facing interactions must summarize growth without requiring constant monitoring or correction.

---

# Navigation Rules

1. The child path must always expose one clear next action.
2. Navigation must keep the child inside discovery, world construction, growth reflection, or session closure.
3. Parent review must be separate from the child discovery path.
4. The child must be able to exit a difficult path and continue through a nearby discovery path.
5. The product must avoid deep menus, complex settings, and adult-oriented configuration during child sessions.
6. Session continuation must be easier than starting from scratch.

---

# Feedback Rules

## Correct or Successful Action

Feedback must explain what was discovered, connected, understood, or built.

## Incorrect or Partial Action

Feedback must avoid failure labeling and should offer a clue, comparison, simpler relation, or second attempt.

## Repeated Difficulty

Feedback must reduce pressure and support recovery. AA may suggest a nearby easier discovery path.

## Growth Signal

Feedback must recognize persistence, focus, trying again, reasoning, emotional recovery, and meaningful exploration.

## Parent Feedback

Parent-facing feedback must summarize growth signals and sustained engagement. It must not require parents to audit every response.

---

# Error Handling Principles

1. Treat wrong answers as discovery opportunities.
2. Avoid negative labels, harsh correction, and score-first messaging.
3. Offer hints before repetition becomes frustration.
4. Let the child continue through an adjacent easier path when blocked.
5. Preserve progress even when a challenge is not fully solved.
6. Make recovery visible as growth.

---

# Accessibility Requirements

1. Use age-appropriate language.
2. Keep instructions short and concrete.
3. Avoid requiring long reading before action.
4. Support short attention spans through small interaction units.
5. Keep parent-facing summaries concise and readable.
6. Do not depend on competitive ranking, time pressure, or dense text to motivate use.

---

# UX Constraints

1. AA must remain a personal knowledge world product, not a quiz system, workbook replacement, exam preparation tool, or general-purpose education platform.
2. UX must support the frozen knowledge worlds: Character World, Language World, Time World, Number World, Life World, Nature World, Space World, and Story & Human Experience World.
3. UX must support counterfactual reasoning in an age-appropriate way.
4. UX must support parent insight without turning parents into teachers, examiners, or continuous supervisors.
5. UX must optimize sustained return and growth through exploration, not session duration or exercise count.
6. UX must not define visual style, screen composition, technical architecture, MVP scope, or implementation tasks.

---

# Visual Design Decision

Visual Design Specification:

```text
Required
```

Decision Source:

AA is an experience product for a child-facing personal knowledge world. Visual quality, world clarity, emotional tone, and age-appropriate presentation are release-critical.

Next required artifact:

```text
VisualDesignSpecification_CORE_v1.md
```

---

# Acceptance Criteria

PASS:

- User journeys are defined.
- User flows are defined.
- Interaction principles are defined.
- Navigation rules are defined.
- Feedback rules are defined.
- Error handling principles are defined.
- Accessibility requirements are defined.
- Visual Design Specification requirement is decided.
- No visual design is defined.
- No technical implementation is defined.
- No MVP scope is defined.

---

# Acceptance Decision

UX Specification Status:
Frozen

Frozen Version:
CORE_v1

Frozen At:
2026-06-16T15:38:38Z

Ready For:
VisualDesignSpecification_CORE_v1.md
