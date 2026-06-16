# ProductRequirement_CORE_v1.md
## Document Information
| Item | Value |
|--------|--------|
| Artifact Type | Product Requirement |
| Project | AA |
| Version | CORE_v1 |
| Lifecycle Stage | Product Requirement |
| Status | Proposed |
| Based On | ProblemDefinition_CORE_v1.md; SolutionDefinition_CORE_v1.md; ProductRepresentation_CORE_v1.md |
---
# Purpose
This document defines what capabilities AA must provide.

This document does not define UI, page structure, technical architecture, database design, implementation details, MVP scope, or task breakdown.
---
# Authority
This document uses only frozen conclusions from:

- ProblemDefinition_CORE_v1.md
- SolutionDefinition_CORE_v1.md
- ProductRepresentation_CORE_v1.md

This document also uses the frozen Product Requirement Design decisions:

- PR-D-001 Discovery Selection Rules
- PR-D-002 Knowledge World Structure
- PR-D-003 Observable Growth Signals
- PR-D-004 Story & Human Experience World
- PR-D-005 Counterfactual Reasoning Capability
---
# Product Requirement Scope
AA is designed for:

```text
Primary school children

Approximately 7–12 years old
```

Current target user:

```text
Yuanyuan
```

AA remains a personal Chinese Character World Building Product.

AA is designed to support growth through exploration. Knowledge is the medium, and growth is the final objective.
---
# Product Objective
Chinese character learning is not the final objective.

Growth is the final objective.

Knowledge is a medium.

Growth through exploration is the objective.

AA must therefore provide capabilities that help Yuanyuan discover, understand, connect, build, reason, persist, recover from difficulty, and see growth over time.
---
# Core Requirement Principles
## Principle-1: Growth Before Achievement
AA must treat growth as more important than achievement.

Achievement may appear through literacy progress, but the product requirement focus is the child's growth qualities: emotional regulation, persistence, focus, courage to face difficulty, and growth mindset.
---
## Principle-2: Discovery Before Drill
AA must prioritize meaningful discovery over repetitive drill.

The child should encounter patterns and relationships that invite curiosity, understanding, and reasoning.
---
## Principle-3: Connection Before Isolation
AA must prevent knowledge from remaining isolated.

Knowledge should become connected across structures, categories, hierarchies, time, space, evolution, causality, inference, and transfer.
---
## Principle-4: Mastery Before Memorization
AA must treat mastery as understanding, connection, explanation, classification, and reasoning.

Memorization alone is not mastery.
---
## Principle-5: Parent Insight Before Parent Supervision
AA must help parents observe growth signals without requiring them to become teachers, examiners, or continuous supervisors.
---
# Capability Requirements
## Capability 1: Discovery
AA must support discovery of meaningful patterns.

Discovery candidates must satisfy:

- age appropriate
- connection potential
- reasoning potential
- real-world transfer potential
- growth value

Discovery must support the child's experience of finding something meaningful, rather than merely completing assigned practice.

Discovery must remain aligned with growth through exploration.
---
## Capability 2: Meaningful Connection
AA must support meaningful connections across:

- structure
- classification
- hierarchy
- temporal
- spatial
- evolution
- causal
- inference
- transfer

Knowledge should not remain isolated.

Connections must help Yuanyuan understand relationships between knowledge items, explain why items belong together, and transfer understanding from one context to another.
---
## Capability 3: Knowledge World Construction
AA must support construction of personal cognitive worlds.

Current frozen worlds:

- Character World
- Language World
- Time World
- Number World
- Life World
- Nature World
- Space World
- Story & Human Experience World

Knowledge world construction must help Yuanyuan build a personal sense of ownership over connected knowledge.

The worlds must support discovery, understanding, connection, mastery, and growth. They must not become isolated content categories.
---
## Capability 4: Mastery
AA must support mastery.

Mastery is not memorization.

Mastery means:

- understanding
- connection
- explanation
- classification
- reasoning

AA must support the child's feeling of becoming more capable through understanding and reasoning, not through repetition volume.

Mastery must protect the child's motivation when difficulty appears.
---
## Capability 5: Growth Reflection
AA must support visibility of growth.

Growth should be reflected through:

- attempts
- recovery after difficulty
- exploration
- persistence
- increasing understanding

Growth reflection must make visible that trying again, recovering from frustration, staying focused, and deepening understanding are meaningful progress.

Growth reflection must not reduce progress to the number of completed exercises.
---
## Capability 6: Parent Insight
AA must support observation of growth signals.

Primary signals:

- emotional regulation
- facing difficulty
- persistence
- focus
- active exploration
- inference ability
- growth mindset

Growth is more important than achievement.

Parent insight must help parents understand how Yuanyuan is growing through literacy exploration, without requiring heavy supervision or constant correction.
---
## Capability 7: Story & Human Experience
AA must support meaningful connections through:

- mythology
- history
- legends
- fables
- literature
- historical figures
- hero stories

AA must support:

- character relationships
- event relationships
- value relationships
- growth relationships

Story and human experience must help knowledge feel meaningful, connected, and emotionally understandable.

This capability must remain age appropriate and aligned with growth qualities.
---
## Capability 8: Counterfactual Reasoning
AA must support counterfactual reasoning:

```text
What if the condition changes?
```

Examples:

- no air
- no wind
- changed assumptions
- changed rules

AA must support:

- causal reasoning
- hypothetical reasoning
- mental simulation

Counterfactual reasoning must remain age appropriate.

This capability must help Yuanyuan reason about conditions, causes, changes, and possible outcomes without expanding AA into a general-purpose knowledge platform.
---
# Requirement Boundaries
AA is NOT:

- exam preparation software
- drill-and-practice software
- worksheet replacement
- encyclopedic knowledge platform
- general-purpose education platform

AA must remain focused on growth through exploration using knowledge as the medium.
---
# Non Goals
This artifact does not define:

- UI
- Page structure
- Technical architecture
- Database design
- Implementation details
- MVP scope
- Task breakdown

This artifact does not introduce new capabilities beyond the frozen Product Requirement Design decisions.
---
# Validation
## Consistent With ProductRepresentation_CORE_v1.md
PASS

AA remains a personal Chinese Character World Building Product for Yuanyuan. The visible goal remains literacy growth, and the hidden goal remains growth qualities.
---
## No Contradiction With Frozen Scope
PASS

The requirements preserve the frozen direction: Chinese characters are the training ground, knowledge is a medium, and growth is the ultimate objective.
---
## No UI Definitions
PASS

This document does not define screens, page structure, interaction layout, visual design, or user flows.
---
## No Architecture Definitions
PASS

This document does not define technical architecture, system design, database design, or implementation approach.
---
## No MVP Definitions
PASS

This document does not define MVP scope, release scope, delivery phases, or task breakdown.
---
## No Implementation Details
PASS

This document defines required product capabilities only. It does not define how to build them.
---
# Acceptance Decision
Product Requirement Status:
PASS

Ready For:
MVPDefinition_CORE_v1.md
