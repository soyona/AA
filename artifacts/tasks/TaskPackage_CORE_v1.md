# TaskPackage_CORE_v1.md

## Document Information

| Item | Value |
|---|---|
| Artifact Type | Task Package |
| Project | AA |
| Version | v1.0 |
| Lifecycle Stage | Task Package |
| Status | Frozen |
| Based On | artifacts/product/MVPDefinition_CORE_v1.md |
| Producer | ChatGPT |
| Consumer | Codex Build |

---

# 1. Purpose

This artifact defines the executable implementation package for the AA MVP.

It converts the frozen MVP scope into Codex build tasks.

This artifact does not execute implementation and does not modify business code.

---

# 2. Source Authority

Codex must consume:

- artifacts/problem/ProblemDefinition_CORE_v1.md
- artifacts/solution/SolutionDefinition_CORE_v1.md
- artifacts/dna/DNASelection_CORE_v1.md
- artifacts/product/ProductRepresentation_CORE_v1.md
- artifacts/product/ProductRequirement_CORE_v1.md
- artifacts/product/UXSpecification_CORE_v1.md
- artifacts/product/VisualDesignSpecification_CORE_v1.md
- artifacts/product/MVPDefinition_CORE_v1.md

MVP Scope:

```text
My Character World + 木→林→森 discovery + Build Into World + Growth View + Parent View
```

---

# 3. Build Objective

Build a working AA MVP that supports one complete child-facing character-world loop:

```text
Start → My Character World → Explore Discovery → Discovery Detail → Build Into World → Growth View → Parent View
```

The experience must feel like world growth through discovery, not quiz completion.

---

# 4. Implementation Scope

## In Scope

- child-facing web MVP
- My Character World screen
- Explore Discovery screen
- Discovery Detail screen
- Build Into World screen
- Growth View screen
- Parent View screen
- fixed 木→林→森 discovery path
- local progress persistence
- gentle retry handling
- minimal responsive browser layout

## Out Of Scope

- login
- backend
- cloud sync
- account system
- multi-child profiles
- full curriculum
- AI content generation
- handwriting recognition
- speech recognition
- leaderboard
- streak system
- points economy
- payment
- teacher dashboard
- admin dashboard
- mobile app packaging

---

# 5. Required Product Behavior

## My Character World

Must show:

- personal Character World surface
- current world state
- one available discovery path
- recent growth if available
- calm entry to exploration

Must not center on score, streak, leaderboard, or points.

## Discovery Path

Fixed MVP discovery:

```text
木 → 林 → 森
```

Learning meaning:

```text
木 means tree or wood.
林 combines two 木.
森 combines three 木.
More 木 means a larger group of trees.
```

## Discovery Detail

Must support:

- one focused prompt
- child-readable explanation
- immediate gentle feedback
- hint and retry
- confirmation of understanding

## Build Into World

Must support:

- add the discovery to Character World
- show relationship as connected structure
- show ownership and world growth

## Growth View

Must show:

- completed discovery
- world growth
- retry or persistence signal if applicable
- next gentle curiosity placeholder

Must not show score, points, streak, rank, or badge-first motivation.

## Parent View

Must show:

- what the child discovered
- what the child built
- retry or persistence note
- one suggested praise topic

Example praise:

```text
You discovered how characters can grow from one tree to a forest.
```

---

# 6. Suggested Technical Boundary

Recommended baseline if repository has no better existing stack:

- React
- TypeScript
- Vite
- localStorage persistence
- simple component structure
- deterministic fixed content
- no backend

If the repository already contains a frontend stack, Codex must adapt to the existing stack instead of replacing it unnecessarily.

---

# 7. Task Breakdown

## Task 1: Repository Inspection

Inspect current repository structure and determine the existing frontend stack.

Acceptance:

- Build plan matches repository structure.
- No unnecessary framework replacement.

## Task 2: App Shell

Create or repair the app shell.

Acceptance:

- App launches locally.
- My Character World is the entry screen.
- Navigation to required screens exists.

## Task 3: Fixed Discovery Content

Implement fixed 木→林→森 discovery content.

Acceptance:

- Content is deterministic.
- No AI generation is used.
- Child-readable explanation exists.

## Task 4: Discovery Flow

Implement Explore Discovery and Discovery Detail.

Acceptance:

- User can start discovery.
- User can interact with one focused prompt.
- User receives gentle feedback.
- Hint and retry are available.

## Task 5: Build Flow

Implement Build Into World.

Acceptance:

- User can add discovery to Character World.
- World state changes visibly.
- Build result communicates ownership.

## Task 6: Growth View

Implement Growth View.

Acceptance:

- Shows discovery completion.
- Shows world growth.
- Shows retry or persistence signal if applicable.
- Does not show score, streak, leaderboard, or points-first motivation.

## Task 7: Parent View

Implement Parent View.

Acceptance:

- Shows discovery summary.
- Shows build result.
- Shows retry or persistence note.
- Shows one suggested praise topic.
- Avoids dense analytics dashboard framing.

## Task 8: Local Persistence

Persist MVP progress locally.

Acceptance:

- Refresh preserves discovery/build completion.
- Refresh preserves retry or persistence signal.
- User can continue from saved state.

## Task 9: Visual Direction

Apply minimal visual direction from VisualDesignSpecification_CORE_v1.md.

Acceptance:

- Personal spatial world feeling.
- Calm hierarchy.
- Rounded or soft surfaces.
- Child-safe tone.
- No score-first or quiz-first visual framing.

## Task 10: Build Verification

Run available verification.

Acceptance:

- Install succeeds.
- Build succeeds.
- Tests pass if tests exist.
- Manual smoke check confirms complete MVP flow.

---

# 8. Codex Return Requirements

Codex must return:

```text
Commit URL
Files Changed
Implementation Summary
Test / Build Results
Manual Smoke Check Result
Known Limitations
```

---

# 9. Build Acceptance Criteria

Build is accepted when:

1. The app runs locally.
2. My Character World is visible as the entry screen.
3. User can complete 木→林→森 discovery.
4. User can receive hint and retry.
5. User can build discovery into Character World.
6. Growth View shows world growth and persistence signal.
7. Parent View shows light summary and praise topic.
8. Progress persists after refresh.
9. No points, streak, leaderboard, or score-first motivation is primary.
10. Visual direction feels personal, spatial, calm, and child-safe.
11. Build/test command succeeds or any failure is clearly explained.

---

# 10. Non Goals

Do not implement:

- additional discovery paths
- additional knowledge worlds
- user account system
- backend services
- AI generation
- analytics dashboard
- curriculum management
- deployment automation
- release packaging

---

# 11. Acceptance Decision

Task Package Status:

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
Build
```
