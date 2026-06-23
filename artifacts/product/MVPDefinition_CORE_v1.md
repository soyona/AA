# MVPDefinition_CORE_v1.md

## Document Information

| Item | Value |
|--------|--------|
| Artifact Type | MVP Definition |
| Project | AA |
| Version | v1.0 |
| Lifecycle Stage | MVP Definition |
| Status | Frozen |
| Based On | artifacts/problem/ProblemDefinition_CORE_v1.md; artifacts/solution/SolutionDefinition_CORE_v1.md; artifacts/dna/DNASelection_CORE_v1.md; artifacts/product/ProductRepresentation_CORE_v1.md; artifacts/product/ProductRequirement_CORE_v1.md; artifacts/product/UXSpecification_CORE_v1.md; artifacts/product/VisualDesignSpecification_CORE_v1.md |
| Producer | ChatGPT |
| Consumer | Task Package |

---

# 1. Purpose

This artifact defines the minimum viable product scope for AA.

The MVP must create a usable end-to-end learning-world loop without expanding into a full platform, full curriculum, full game, or full knowledge graph.

This artifact defines:

- MVP objective
- included capabilities
- excluded capabilities
- minimum user journey
- minimum screens
- minimum content scope
- minimum data persistence
- acceptance criteria

This artifact does not define:

- engineering implementation details
- database schema
- component code
- task breakdown
- QA plan
- release plan

Those belong to downstream stages.

---

# 2. Source Authority

This MVP Definition consumes the following frozen artifacts:

- artifacts/problem/ProblemDefinition_CORE_v1.md
- artifacts/solution/SolutionDefinition_CORE_v1.md
- artifacts/dna/DNASelection_CORE_v1.md
- artifacts/product/ProductRepresentation_CORE_v1.md
- artifacts/product/ProductRequirement_CORE_v1.md
- artifacts/product/UXSpecification_CORE_v1.md
- artifacts/product/VisualDesignSpecification_CORE_v1.md

Selected Visual DNA:

```text
Arc
```

Selected Product DNA:

```text
Minecraft
```

Secondary Visual Reference:

```text
Toca Boca
```

Secondary Product Reference:

```text
Animal Crossing
```

---

# 3. MVP Objective

The MVP must prove that AA can turn one child-facing Chinese character learning session into a personal world-growth experience.

The MVP must validate this loop:

```text
Enter My Character World
↓
Discover one character relationship
↓
Understand the relationship
↓
Build it into the world
↓
See growth
↓
Parent sees a light growth summary
```

The MVP is successful if the product feels like:

```text
I discovered and built something in my character world.
```

not:

```text
I completed a quiz and earned points.
```

---

# 4. MVP Scope Summary

## In Scope

MVP includes:

- one child user flow
- one parent view flow
- one initial world: Character World
- one discovery path based on character structure
- one build action
- one growth reflection surface
- local progress persistence
- child-safe error recovery
- Arc-informed personal spatial visual structure
- Toca Boca-informed child-facing warmth

---

## Out Of Scope

MVP excludes:

- account system
- cloud sync
- multi-child profiles
- full curriculum coverage
- all eight knowledge worlds
- AI-generated open content
- parent configuration system
- leaderboard
- streak system
- points economy
- badges as primary motivation
- social features
- payment
- teacher dashboard
- admin dashboard
- mobile app packaging
- full game mechanics

---

# 5. MVP User Roles

## Child User

Primary MVP user:

```text
Yuanyuan
```

Child MVP needs:

- enter the character world quickly
- discover a relationship
- receive simple guidance
- build the discovery into the world
- see that the world grew
- recover from mistakes without shame

---

## Parent User

Secondary MVP user:

```text
Parent
```

Parent MVP needs:

- see what the child discovered
- see whether the child persisted or recovered
- receive one suggested praise topic
- avoid supervising every step

---

# 6. MVP Core Flow

```text
Start
↓
My Character World
↓
Explore Discovery
↓
Discovery Detail
↓
Build Into World
↓
Growth View
↓
Parent View
```

---

# 7. MVP Screens

## Screen 1: My Character World

Purpose:

Primary child entry screen.

Must show:

- a personal Character World surface
- current world state
- one available discovery path
- recent growth if available
- calm entry to exploration

Must not show:

- streak
- score
- leaderboard
- badge wall
- daily pressure

---

## Screen 2: Explore Discovery

Purpose:

Let the child choose or start one discovery.

MVP discovery path:

```text
木 → 林 → 森
```

Must show:

- the discovery pattern
- a child-readable prompt
- a clear start action
- low-pressure framing

---

## Screen 3: Discovery Detail

Purpose:

Help the child understand the pattern.

Must support:

- one focused question or prompt
- immediate gentle guidance
- hint if wrong
- retry without punishment
- confirmation of understanding

MVP learning target:

```text
木 means tree/wood.
林 combines two 木.
森 combines three 木.
More 木 means a larger group of trees.
```

---

## Screen 4: Build Into World

Purpose:

Turn understanding into world growth.

Must support:

- adding the discovery into Character World
- showing the relationship as a connected structure
- making the child feel ownership

Minimum build result:

```text
The 木 → 林 → 森 discovery becomes part of My Character World.
```

---

## Screen 5: Growth View

Purpose:

Show growth without score pressure.

Must show:

- discovered pattern
- world growth
- effort or retry signal if applicable
- next gentle curiosity

Must not show:

- points
- stars
- streak
- ranking

---

## Screen 6: Parent View

Purpose:

Provide light parent insight.

Must show:

- child discovered 木 → 林 → 森
- child built it into Character World
- child tried again if retry occurred
- suggested praise topic

Example praise topic:

```text
You discovered how characters can grow from one tree to a forest.
```

---

# 8. MVP Capability Coverage

## Required Capability 1: Discovery

Covered by:

```text
木 → 林 → 森 discovery path
```

---

## Required Capability 2: Meaningful Connection

Covered by:

```text
One 木 connects to two 木 and three 木 through structure and meaning.
```

---

## Required Capability 3: Knowledge World Construction

Covered by:

```text
The discovery is added to Character World.
```

---

## Required Capability 4: Resource-to-Capability Progression

Covered by:

```text
Recognizing one structure unlocks a larger character relationship.
```

---

## Required Capability 5: Mastery

Covered by:

```text
The child explains or selects why 林 and 森 relate to 木.
```

---

## Required Capability 6: Growth Reflection

Covered by:

```text
Growth View shows discovery, retry if any, and world growth.
```

---

## Required Capability 7: Parent Insight

Covered by:

```text
Parent View summarizes discovery, build action, and praise topic.
```

---

## Deferred Capabilities

Deferred after MVP:

- full Story & Human Experience World
- counterfactual reasoning flows
- all eight worlds
- multiple discovery categories
- long-term growth analytics
- advanced parent insight

---

# 9. MVP Visual Direction

MVP must apply Visual Design Specification v1.0 at a minimal level.

Required visual qualities:

- personal world surface
- spatial organization
- calm hierarchy
- rounded surfaces
- soft child-safe tone
- low visual noise
- no dashboard-first framing

MVP must avoid:

- quiz-first presentation
- worksheet presentation
- point-first presentation
- leaderboard presentation
- harsh error styling
- Minecraft visual imitation
- Arc browser imitation
- Toca Boca asset imitation

---

# 10. MVP Data Persistence

MVP must persist locally:

- whether the discovery has been completed
- whether the discovery was built into the world
- retry or persistence signal
- latest growth summary

MVP does not require:

- backend database
- login
- cloud sync
- multi-device persistence

---

# 11. MVP Acceptance Criteria

MVP is accepted when all criteria pass:

1. Child can enter My Character World.
2. Child can start 木 → 林 → 森 discovery.
3. Child can receive gentle guidance and retry if needed.
4. Child can build the discovery into Character World.
5. Child can see world growth after building.
6. Parent can see a light summary and suggested praise topic.
7. Progress persists locally after page refresh.
8. No score, streak, leaderboard, or points-first motivation is used.
9. Visual structure follows personal, spatial, calm, child-safe direction.
10. MVP remains limited to the minimum closed loop.

---

# 12. Non Goals

MVP does not include:

- full Chinese character curriculum
- additional character sets beyond the initial discovery path
- AI content generation
- speech recognition
- handwriting recognition
- spaced repetition engine
- adaptive learning engine
- advanced analytics
- parent configuration
- deployment pipeline
- production authentication

---

# 13. Validation

## Consistent With ProductRequirement_CORE_v1.md v1.2

PASS

The MVP covers Discovery, Meaningful Connection, Knowledge World Construction, Resource-to-Capability Progression, Mastery, Growth Reflection, and Parent Insight at minimum viable scope.

---

## Consistent With UXSpecification_CORE_v1.md v1.2

PASS

The MVP implements the minimum loop from My Character World through Explore, Discovery Detail, Build Space, Growth View, and Parent View.

---

## Consistent With VisualDesignSpecification_CORE_v1.md v1.0

PASS

The MVP requires a personal, spatial, calm, child-safe world surface and excludes dashboard-first, score-first, and quiz-first visual framing.

---

## No Technical Design

PASS

This artifact does not define implementation architecture, database schema, component code, or technology stack.

---

## No Task Breakdown

PASS

This artifact does not define build tasks. Task decomposition belongs to Task Package.

---

# 14. Acceptance Decision

MVP Definition Status:

```text
Frozen
```

Frozen Version:

```text
v1.0
```

Frozen At:

```text
2026-06-23
```

Ready For:

```text
TaskPackage_CORE_v1.md
```
