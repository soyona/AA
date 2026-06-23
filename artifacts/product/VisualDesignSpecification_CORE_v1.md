# VisualDesignSpecification_CORE_v1.md

## Document Information

| Item | Value |
|--------|--------|
| Artifact Type | Visual Design Specification |
| Project | AA |
| Version | v1.0 |
| Lifecycle Stage | Visual Design Specification |
| Status | Frozen |
| Based On | artifacts/dna/DNASelection_CORE_v1.md; artifacts/product/UXSpecification_CORE_v1.md |
| Producer | ChatGPT |
| Consumer | MVP Definition |

---

# 1. Purpose

This artifact defines the visual design direction for AA after UX Specification v1.2.

It defines:

- visual personality
- visual hierarchy principles
- spatial layout direction
- surface language
- motion direction
- child-facing visual adaptation
- parent-view visual boundary
- visual anti-patterns

This artifact does not define:

- technical implementation
- CSS tokens
- exact color values
- exact typography values
- component code
- MVP scope
- task breakdown

Those belong to downstream implementation or MVP artifacts.

---

# 2. Source Authority

This Visual Design Specification consumes the following frozen artifacts:

- artifacts/dna/DNASelection_CORE_v1.md
- artifacts/product/ProductRepresentation_CORE_v1.md
- artifacts/product/ProductRequirement_CORE_v1.md
- artifacts/product/UXSpecification_CORE_v1.md

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

# 3. Visual Objective

AA should visually feel like a personal, spatial, calm, child-safe Chinese character world.

The visual system should make the child feel:

```text
This is my character world.
It is calm and safe.
I can explore it.
I can build it.
It grows because I understand more.
```

The visual system should not make the child feel:

```text
This is homework.
This is a quiz.
This is a dashboard.
This is a score machine.
```

---

# 4. Visual DNA Adaptation

## 4.1 Arc Visual DNA Adaptation

Arc contributes:

- personal workspace perception
- spatial organization
- soft chrome
- rounded surfaces
- calm hierarchy
- lightweight focus
- customizable workspace feeling
- quiet modern personality

AA adapts Arc from an adult browser/workspace context into a child-facing learning-world context.

AA must not copy Arc browser mechanics, browser UI, tab structure, or productivity workflow assumptions.

---

## 4.2 Minecraft Product DNA Visual Implication

Minecraft contributes the need for visible world growth and personal construction.

Visual design must support:

- world areas
- discovered items
- connected knowledge nodes
- visible growth through construction
- child-owned space

Visual design must not copy Minecraft block art, pixel art, voxel style, game HUD, survival UI, or combat visuals.

---

## 4.3 Toca Boca Secondary Visual Reference

Toca Boca contributes child-facing warmth and emotional safety.

Allowed influence:

- soft emotional tone
- non-threatening affordances
- playful simplicity
- no-failure feeling
- approachable visual cues

Toca Boca must not replace Arc as the selected canonical Visual DNA.

---

## 4.4 Animal Crossing Secondary Product Reference

Animal Crossing contributes gentle pacing and low-pressure return.

Allowed influence:

- calm return atmosphere
- gentle world continuity
- soft anticipation
- personal space attachment

Animal Crossing must not introduce collection pressure, real-time scarcity pressure, or completion anxiety.

---

# 5. Visual Personality

Primary visual personality:

- personal
- spatial
- calm
- warm
- exploratory
- safe
- lightweight

Secondary visual personality:

- modern
- soft
- friendly
- organized
- quietly playful
- growth-oriented

AA should feel less like a school app and more like a personal knowledge world.

---

# 6. Visual Hierarchy Principles

## Principle 1: World First

The child's personal world should be the primary visual focus.

Screens should visually answer:

```text
Where am I in my world?
What can I discover or build next?
```

not:

```text
What task must I complete today?
```

---

## Principle 2: Discovery Before Completion

Visual hierarchy should emphasize discoveries, relationships, and world growth before completion metrics.

The most prominent visual elements should be:

- world spaces
- discovery prompts
- connected knowledge
- growth changes
- next curiosity

The most prominent visual elements must not be:

- scores
- points
- streaks
- leaderboard ranking
- daily task pressure

---

## Principle 3: Calm Focus

Each screen should provide one primary visual focus.

The child should not need to process dense dashboards, many competing panels, or adult productivity controls.

---

## Principle 4: Spatial Continuity

Visual layout should preserve a sense of place.

Moving between My Character World, Explore, Build, and Growth should feel like moving through related spaces, not jumping between unrelated pages.

---

## Principle 5: Child-Safe Warmth

Visual cues should feel safe, soft, and forgiving.

Difficulty, correction, and retry states must avoid harsh red-alert styling, punishment, or failure imagery.

---

# 7. Spatial Layout Direction

AA visual design should use spatial world organization.

Allowed spatial patterns:

- world map
- soft panels
- rounded surfaces
- connected areas
- discovery paths
- growth zones
- calm side or bottom navigation
- child-readable grouping

Avoid:

- dense dashboard grid
- spreadsheet-like layout
- enterprise sidebar complexity
- exam-paper layout
- quiz-card-only flow
- aggressive gamified HUD

---

# 8. Surface Language

AA surfaces should feel soft, layered, and low-pressure.

Allowed surface qualities:

- rounded panels
- soft cards
- gentle depth
- quiet separators
- light spatial grouping
- child-friendly touch targets
- low-noise chrome

Avoid:

- hard industrial panels
- sharp technical density
- adult SaaS dashboards
- heavy chrome
- dark operational surfaces
- noisy decorative frames

---

# 9. Color Direction

This artifact does not define exact color values.

Color direction should be:

- calm
- warm
- soft
- low-pressure
- spatially meaningful
- child-safe

Color may help differentiate worlds or discovery areas.

Color must not create:

- urgency pressure
- reward addiction
- failure shame
- exam stress
- leaderboard competition

---

# 10. Typography Direction

This artifact does not define exact typography values.

Typography direction should be:

- clear
- readable for early primary school children
- calm
- friendly
- not childish in a distracting way
- supportive of Chinese character legibility

Chinese characters must remain visually clear and central when used as discovery material.

Typography must not become decorative at the cost of recognition.

---

# 11. Illustration Direction

Illustration may support world feeling and child safety.

Allowed illustration direction:

- soft world objects
- gentle spatial markers
- knowledge-world areas
- friendly hints
- visual metaphors for growth
- simple story-world cues

Avoid:

- IP imitation
- Minecraft block-art imitation
- Toca Boca character imitation
- overloaded cartoon decoration
- reward-first badge decoration
- combat or survival imagery

---

# 12. Motion Direction

Motion should support spatial continuity and understanding.

Allowed motion purposes:

- moving between world areas
- showing a discovery being added
- showing a connection forming
- showing world growth
- gentle feedback after retry
- calm return cues

Motion must not be used for:

- reward overstimulation
- attention hijacking
- streak pressure
- punishment
- urgency loops

---

# 13. Page-Level Visual Direction

## 13.1 My Character World

Visual role:

Primary personal world surface.

Visual requirements:

- show world ownership
- show world growth
- show discovered areas
- show gentle next curiosity
- keep visual noise low

Must not visually center:

- daily streak
- point count
- badge wall
- leaderboard

---

## 13.2 Explore

Visual role:

Curiosity and discovery entry.

Visual requirements:

- discovery prompts should feel inviting
- patterns should be visually clear
- relationships should be visible
- child should see options without overload

---

## 13.3 Discovery Detail

Visual role:

Focused understanding surface.

Visual requirements:

- one primary pattern or relationship at a time
- Chinese characters must be legible
- hint and guidance must be visually gentle
- wrong answers must not create shame

---

## 13.4 Build Space

Visual role:

Convert understanding into owned world growth.

Visual requirements:

- show where the discovery belongs
- show connection formation
- show world change
- make ownership visible

---

## 13.5 Growth View

Visual role:

Show growth without score pressure.

Visual requirements:

- visualize persistence
- visualize recovery
- visualize exploration
- visualize increasing understanding
- visualize world expansion

Avoid score-board framing.

---

## 13.6 Parent View

Visual role:

Light parent insight surface.

Visual requirements:

- calm summary
- clear growth signals
- suggested praise topics
- minimal supervision burden

Avoid teacher dashboard density.

---

# 14. Visual Anti-Patterns

AA must avoid:

- quiz-first visual framing
- worksheet imitation
- exam-paper layouts
- streak-first home screen
- badge-wall motivation
- points economy as primary visual signal
- leaderboard or ranking surfaces
- dense parent analytics dashboard
- adult productivity workspace tone
- technical SaaS visual density
- harsh failure colors
- overstimulating reward animation
- direct imitation of Arc, Minecraft, Toca Boca, or Animal Crossing assets

---

# 15. Visual Acceptance Criteria

The visual design is acceptable if it satisfies all of the following:

1. The child can recognize the experience as a personal character world.
2. Discovery and world growth are visually more important than scores or tasks.
3. The selected Arc Visual DNA is consumed through spatial, calm, soft, personal visual structure.
4. Toca Boca influence remains secondary and limited to warmth and child-facing safety.
5. The product does not visually resemble a quiz app, worksheet, or school dashboard.
6. Parent view supports insight without heavy supervision or analytics density.
7. Visual design remains compatible with Product Requirement v1.2 and UX Specification v1.2.

---

# 16. Validation

## Consistent With UXSpecification_CORE_v1.md v1.2

PASS

The visual direction supports My Character World, Explore, Build, Growth, Parent View, Discovery Flow, Build Flow, Mastery Flow, and Return Flow.

---

## Consumes Selected Visual DNA

PASS

The visual direction consumes Arc as canonical Visual DNA through personal, spatial, calm, soft, and lightweight workspace/world perception.

---

## Preserves Secondary Visual Reference Boundary

PASS

Toca Boca remains only a secondary child-facing warmth and emotional-safety reference.

---

## Avoids Product DNA Visual Imitation

PASS

The visual direction does not copy Minecraft block art, survival HUD, game UI, or assets.

---

## No Technical Definitions

PASS

This artifact does not define implementation technology, CSS tokens, exact component code, or technical architecture.

---

## No MVP Scope

PASS

This artifact does not define MVP scope, release scope, delivery phases, or task breakdown.

---

# 17. Acceptance Decision

Visual Design Specification Status:

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
MVPDefinition_CORE_v1.md
```
