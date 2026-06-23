# UXSpecification_CORE_v1.md

## Document Information

| Item | Value |
|--------|--------|
| Artifact Type | UX Specification |
| Project | AA |
| Version | v1.2 |
| Lifecycle Stage | UX Specification |
| Status | Frozen |
| Based On | artifacts/problem/ProblemDefinition_CORE_v1.md; artifacts/solution/SolutionDefinition_CORE_v1.md; artifacts/dna/DNASelection_CORE_v1.md; artifacts/product/ProductRepresentation_CORE_v1.md; artifacts/product/ProductRequirement_CORE_v1.md |
| Producer | ChatGPT |
| Consumer | Visual Design Specification |

---

# 1. Purpose

This artifact defines the user experience structure for AA after DNA Selection and Product Requirement v1.2.

It defines:

- user roles
- experience model
- navigation model
- page-level structure
- core interaction flows
- learning-world flow
- parent insight flow
- error recovery flow
- agency and return model

This artifact does not define:

- visual style
- color system
- typography
- final UI components
- animation specification
- technical architecture
- database design
- implementation tasks
- MVP scope

Those belong to downstream SAPDP stages.

---

# 2. Source Authority

This UX Specification consumes the following frozen artifacts:

- artifacts/problem/ProblemDefinition_CORE_v1.md
- artifacts/solution/SolutionDefinition_CORE_v1.md
- artifacts/dna/DNASelection_CORE_v1.md
- artifacts/product/ProductRepresentation_CORE_v1.md
- artifacts/product/ProductRequirement_CORE_v1.md

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

# 3. UX Objective

AA must make Chinese character learning feel like entering and growing a personal character world.

The UX should support the child in moving through:

```text
Discover
↓
Understand
↓
Build
↓
Grow
↓
Discover Again
```

The core UX goal is not to drive challenge completion.

The core UX goal is to help the child return to a growing world where character patterns, relationships, and knowledge connections can be discovered and built.

---

# 4. User Roles

## 4.1 Child User

Primary User:

```text
Yuanyuan
```

UX needs:

- enter quickly
- feel safe to explore
- choose where to go
- discover patterns
- understand relationships
- build a personal world
- receive immediate guidance
- recover from mistakes without shame
- see growth without pressure

---

## 4.2 Parent User

Secondary User:

```text
Parent
```

UX needs:

- see what the child explored
- see growth signals
- understand difficulty and recovery
- provide positive recognition
- avoid becoming teacher, examiner, or continuous supervisor

---

# 5. Experience Model

AA UX is organized as a personal spatial learning world.

The experience should feel like:

```text
I enter my character world.
I discover something.
I understand why it connects.
I add it to my world.
My world grows.
I want to return.
```

The experience should not feel like:

```text
I open a homework app.
I complete today's task.
I receive points.
I maintain a streak.
```

---

# 6. Navigation Model

AA uses a world-first navigation model.

Primary navigation areas:

- My Character World
- Explore
- Build
- Growth
- Parent View

Navigation intent:

```text
World → Discovery → Construction → Growth → Return
```

---

## 6.1 My Character World

Purpose:

The home space where the child sees the personal world that has grown through discovery and construction.

Must support:

- visible world growth
- unlocked or discovered areas
- recent discoveries
- unfinished curiosities
- gentle next exploration prompt

Must not center on:

- streaks
- points
- leaderboard
- daily task pressure

---

## 6.2 Explore

Purpose:

The place where the child encounters character patterns, relationships, and knowledge-world prompts.

Must support:

- discovery candidates
- age-appropriate curiosity prompts
- structure, sound, meaning, radical, word, story, time, nature, and space connections
- entry through curiosity rather than assignment

---

## 6.3 Build

Purpose:

The place where discovered understanding becomes part of the child's personal world.

Must support:

- adding discoveries to a world
- connecting related items
- placing or grouping knowledge
- turning understanding into ownership

---

## 6.4 Growth

Purpose:

The place where growth signals are visible.

Must support:

- attempts
- recovery after difficulty
- focus
- persistence
- increasing understanding
- new connections
- world expansion

Must not reduce growth to score, badges, exercise count, or streaks.

---

## 6.5 Parent View

Purpose:

The place where the parent sees growth and participation without supervising every step.

Must support:

- latest discoveries
- world growth summary
- difficulty and recovery signals
- suggested praise topics
- light review only

---

# 7. Core Child Journey

```text
Open AA
↓
Enter My Character World
↓
See what changed or what can grow
↓
Choose an exploration path
↓
Discover a character pattern or knowledge relationship
↓
Receive explanation / hint / prompt
↓
Build the discovery into the world
↓
See growth signal
↓
Leave with unfinished curiosity or next possible discovery
```

---

# 8. Core Interaction Flow

## 8.1 Discovery Flow

```text
Enter Explore
↓
Choose or receive a discovery prompt
↓
Observe pattern / relationship
↓
Make a guess or explanation
↓
Receive immediate guidance
↓
Confirm understanding
↓
Move to Build
```

Example anchor:

```text
木 → 林 → 森
```

UX intent:

```text
I discovered a pattern.
```

not:

```text
I answered a quiz question.
```

---

## 8.2 Build Flow

```text
Discovery confirmed
↓
Add discovery to a world space
↓
Connect it with related items
↓
World visibly changes
↓
Growth signal appears
↓
New curiosity appears
```

UX intent:

```text
My world grew because I understood something.
```

---

## 8.3 Mastery Flow

```text
Encounter difficulty
↓
Receive hint or simplification
↓
Try again
↓
Understand one part
↓
Connect it to prior discovery
↓
Record recovery and growth
```

UX must protect the child's mastery motivation.

Failure must be treated as part of exploration, not as punishment.

---

## 8.4 Return Flow

```text
Return to AA
↓
See world continuity
↓
See recent growth
↓
See a gentle next curiosity
↓
Choose whether to explore, build, or review
```

Return must be driven by curiosity, ownership, and world growth.

Return must not depend on streak pressure.

---

# 9. Page Structure

## P1: My Character World

Purpose:

Primary entry surface for the child.

Displays:

- personal world overview
- discovered worlds or areas
- recent discoveries
- visible world growth
- gentle next curiosity
- entry points to Explore and Build

Primary question answered:

```text
What has my world become, and where can I explore next?
```

---

## P2: Explore

Purpose:

Discovery entry point.

Displays:

- discovery prompts
- pattern cards
- relationship questions
- age-appropriate curiosity choices
- world-based exploration paths

Primary question answered:

```text
What can I discover now?
```

---

## P3: Discovery Detail

Purpose:

Focused understanding surface.

Displays:

- one pattern, relationship, or scenario
- child action area
- explanation prompt
- immediate guidance
- hint path
- move-to-build action

Primary question answered:

```text
What does this mean, and how does it connect?
```

---

## P4: Build Space

Purpose:

Convert understanding into owned world growth.

Displays:

- selected discovery
- connection options
- target world or area
- resulting world change
- growth signal

Primary question answered:

```text
Where does this discovery belong in my world?
```

---

## P5: Growth View

Purpose:

Make growth visible without reducing it to scores.

Displays:

- discoveries made
- connections built
- difficult moments recovered
- focus / persistence / try-again signals
- world growth summary

Primary question answered:

```text
How am I growing?
```

---

## P6: Parent View

Purpose:

Help parent understand and encourage growth.

Displays:

- what the child explored
- what the child understood
- what the child built
- where difficulty appeared
- how the child recovered
- suggested praise topics

Primary question answered:

```text
What growth should I notice and encourage?
```

---

# 10. Required UX Worlds

The UX must support the following world spaces:

- Character World
- Language World
- Time World
- Number World
- Life World
- Nature World
- Space World
- Story & Human Experience World

These are experience spaces, not fixed UI layouts.

Each world must be able to hold discoveries, relationships, and growth signals.

---

# 11. Motivation UX Rules

Primary motivation UX:

```text
Discovery
```

Secondary motivation UX:

```text
Building
```

Third motivation UX:

```text
Mastery
```

Supporting motivation UX:

```text
Low-pressure return
```

The UX must not center motivation on:

- rewards
- badges
- leaderboard
- points
- streaks
- check-in pressure
- exercise volume

Progress may be visible, but progress must represent growth and world expansion.

---

# 12. Parent UX Rules

Parent UX must be light.

Parent View must not require the parent to:

- teach every item
- check every answer
- correct every mistake
- configure complex learning plans
- supervise continuously

Parent View should help the parent say:

```text
I noticed you tried again.
I noticed you discovered a pattern.
I noticed your world grew.
I noticed you stayed focused.
```

---

# 13. Error Recovery UX

## 13.1 Wrong Answer / Misunderstanding

```text
Misunderstanding
↓
Gentle hint
↓
Simpler prompt
↓
Try again
↓
Partial understanding acknowledged
↓
Continue exploration
```

The UX must avoid shame, hard failure, and punitive states.

---

## 13.2 Repeated Difficulty

```text
Repeated difficulty
↓
Reduce complexity
↓
Show related known item
↓
Ask one smaller question
↓
Record persistence
↓
Allow exit without punishment
```

Repeated difficulty should produce a growth signal if the child persists or recovers.

---

# 14. Child Agency UX

The child should be able to choose:

- which world to explore
- which discovery path to enter
- which discovered item to build next
- when to review growth
- when to stop a session

The system may recommend, but must not fully control the child's path.

---

# 15. Visual DNA UX Boundary

Arc Visual DNA affects UX structure only at the level of:

- personal workspace/world perception
- spatial organization
- calm hierarchy
- lightweight navigation
- customizable ownership feeling

Toca Boca affects UX tone only at the level of:

- child-facing warmth
- emotional safety
- playful exploration
- low-pressure affordance

Detailed visual expression belongs to Visual Design Specification.

---

# 16. UX Validation

## Consistent With ProductRequirement_CORE_v1.md v1.2

PASS

The UX supports required capabilities: Discovery, Meaningful Connection, Knowledge World Construction, Resource-to-Capability Progression, Mastery, Growth Reflection, Parent Insight, Story & Human Experience, Counterfactual Reasoning, and Low-Pressure Return.

---

## Consumes Selected DNA

PASS

The UX consumes Minecraft as Product DNA, Arc as Visual DNA, Toca Boca as Secondary Visual Reference, and Animal Crossing as Secondary Product Reference.

---

## Avoids Reward-Centered Drift

PASS

The UX does not center on points, badges, leaderboard, streaks, or check-in pressure.

---

## No Visual Design Definitions

PASS

This artifact does not define colors, typography, final components, illustration style, or animation details.

---

## No Technical Definitions

PASS

This artifact does not define technical implementation, database design, or architecture.

---

## No MVP Scope

PASS

This artifact does not define MVP scope, release scope, delivery phases, or task breakdown.

---

# 17. Acceptance Decision

UX Specification Status:

```text
Frozen
```

Frozen Version:

```text
v1.2
```

Frozen At:

```text
2026-06-23
```

Ready For:

```text
VisualDesignSpecification_CORE_v1.md
```
