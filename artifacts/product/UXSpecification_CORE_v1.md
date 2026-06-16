# UXSpecification_CORE_v1

## Document Information

Version: CORE_v1

Status: Frozen

Stage: UX Specification

Owner: ChatGPT

---

# 1. Objective

Define the complete user experience structure for AA.

This artifact defines:

* User roles
* User journeys
* Page structure
* Core interaction flows
* Motivation mechanisms
* Progress systems
* Parent participation mechanisms

This artifact does not define:

* Visual style
* Color system
* UI components
* Animations
* Technical implementation

These are defined in VisualDesignSpecification.

---

# 2. Product Goal

Enable children to participate in learning voluntarily through challenge-driven growth mechanisms.

The system should promote:

* Learning completion
* Learning continuity
* Growth awareness
* Parent-child positive feedback

---

# 3. User Roles

## Primary User

Child

Age Range:

6–8 years old

Goals:

* Complete challenges
* Gain rewards
* Unlock achievements
* Experience progress

---

## Secondary User

Parent

Goals:

* Understand learning progress
* Encourage positive behavior
* Configure growth goals
* Track long-term development

---

# 4. Core User Journey

```text
Open App
↓
View Today's Challenge
↓
Select Challenge
↓
Complete Practice
↓
Receive Feedback
↓
Receive Rewards
↓
View Growth Progress
↓
Unlock New Goals
↓
Exit
```

---

# 5. Page Structure

## P1 Home

Purpose:

Guide the child directly into action.

Displays:

* Today's Challenge
* Start Button
* Current Streak
* Current Level
* Recent Badge

Design Principle:

Home page answers one question:

"What should I do today?"

---

## P2 Challenge Center

Displays:

* Learning Challenges
* Exploration Challenges
* Growth Challenges

Purpose:

Provide clear challenge selection.

---

## P3 Practice Page

Displays:

* Question
* Answer Area
* Progress Indicator
* Immediate Feedback

Purpose:

Support focused learning.

---

## P4 Result Page

Displays:

* Completion Result
* Accuracy
* Growth Points Earned
* Stars Earned
* New Badge Unlocks

Purpose:

Provide accomplishment feedback.

---

## P5 Growth Center

Displays:

* Current Level
* Growth Points
* Learning Streak
* Achievement History
* Badge Collection

Purpose:

Make growth visible.

---

## P6 Parent Center

Displays:

* Daily Completion
* Weekly Progress
* Growth Trends
* Badge History
* Suggested Praise Topics

Purpose:

Support parent participation.

---

# 6. Learning Flow

```text
Start Challenge
↓
Show Question
↓
Answer
↓
Immediate Feedback
↓
Next Question
↓
Challenge Complete
↓
Result Summary
↓
Reward Distribution
```

---

# 7. Motivation Loop

Core Mechanism:

```text
Goal
↓
Challenge
↓
Reward
↓
Growth
↓
New Goal
```

Home page must display:

* Current Goal
* Reward Preview
* Next Goal

Example:

```text
Learn 5 Characters

Reward:
20 Growth Points
1 Star
```

---

# 8. Daily Challenge System

Challenge Categories:

## Learning Challenge

Examples:

* Learn 5 characters
* Complete a review exercise

## Exploration Challenge

Examples:

* Discover a new radical
* Learn a new word family

## Growth Challenge

Examples:

* Organize school bag
* Read for 10 minutes

Completion grants Growth Points.

---

# 9. Reward System

Reward Layers:

## Immediate Reward

* Stars
* Encouragement Feedback

## Mid-Term Reward

* Badges

## Long-Term Reward

* Exploration Rewards
* Special Unlocks

Reward Flow:

```text
Challenge Complete
↓
Growth Points
↓
Level Progress
↓
Badge Unlock
↓
Exploration Reward
```

---

# 10. Progress System

Visible Metrics:

* Current Level
* Growth Points
* Current Streak
* Weekly Completion Rate
* Progress To Next Level

Purpose:

Maintain visible growth momentum.

---

# 11. Parent Feedback Loop

```text
Child Completes Challenge
↓
Growth Record Generated
↓
Parent Reviews Progress
↓
Parent Provides Praise
↓
Child Receives Recognition
```

Parent Center must support:

* Daily Review
* Weekly Review
* Badge Review
* Suggested Praise Topics

---

# 12. Failure Recovery Flow

Error Flow:

```text
Wrong Answer
↓
Hint
↓
Retry
↓
Success
```

Repeated Failure:

```text
Multiple Errors
↓
Simplified Question
↓
Encouragement
↓
Retry
```

The system must avoid direct failure states.

---

# 13. Child Agency Flow

Children may choose:

* Challenge Order
* Reward Direction
* Badge Route

The system must not fully control all decisions.

Purpose:

Increase autonomy and intrinsic motivation.

---

# 14. Exception Flow

## Exit Mid-Session

Automatically save progress.

---

## No Existing Record

Show onboarding challenge.

---

## Offline State

Provide limited offline mode.

---

# 15. Exit Criteria

This UX Specification is complete when:

* User roles are defined
* User journeys are defined
* Page structure is defined
* Learning flow is defined
* Motivation loop is defined
* Reward system is defined
* Progress system is defined
* Parent feedback loop is defined
* Failure recovery is defined
* Child agency is defined

Result:

UX Specification Complete
