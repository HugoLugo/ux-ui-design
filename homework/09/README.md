---
week: 09
neptun: ADFUXK
---

# Homework 09 — Iteration, Components, and Mini Design System

## Project: Exotic Pet Keeper

### Figma Deliverables

- [Homework 9 — Clickable Prototype](https://www.figma.com/proto/LqJRKvQKSnCPGnXdbsarWf/Exotic-Pet-Keeper-%E2%80%94-Homework-6-Wireframes?node-id=54-138&page-id=0%3A1&starting-point-node-id=54%3A138)
- [Mini Design System](https://www.figma.com/design/LqJRKvQKSnCPGnXdbsarWf?node-id=60-145)
- [Decision Log](https://www.figma.com/design/LqJRKvQKSnCPGnXdbsarWf?node-id=62-144)
- [Developer Handoff — Quick Feeding](https://www.figma.com/design/LqJRKvQKSnCPGnXdbsarWf?node-id=54-159)

## Reusable Components

The mini design system contains four component families:

| Component | Variants | Instances |
|---|---|---|
| Button | Primary/Secondary; Default, Focus, Pressed, Disabled, Loading | 11 |
| Input field | Default, Focus, Filled, Error, Disabled | 12 |
| Feeding outcome option | Selected, Unselected | 6 |
| Feeding record card | Default, Focus | 2 |

All 31 instances use shared Figma components. The components reuse semantic color variables, spacing variables, and text styles from Homework 8.

## Essential Iterations

**1. Clearer feeding form**

- Problem: The simulated walkthrough suggested confusion about non-editable fields.
- Change: Reusable input states with persistent labels, visible values, and clearer sample-selection instructions.
- Expected effect: Better understanding of how to complete the feeding task.

**2. Improved validation**

- Problem: The simulated walkthrough suggested hesitation when correcting missing information.
- Change: Field-level error messages and an explicit correction path.
- Expected effect: Easier recovery from incomplete forms.

**3. Consistent feeding history**

- Problem: Retrieving a previously saved feeding must remain straightforward.
- Change: Reusable record cards, consistent button labels, and a prominent View History action.
- Expected effect: Easier recognition and retrieval of saved records.

The complete decision log in Figma includes the evidence, hypotheses, rejected alternatives, expected effects, trade-offs, and open questions.

## Modification Check

The shared `radius/control` variable was changed from 8 px to 10 px.

**Result:** All seven inspected nodes, including the main Button component and six sampled instances, updated automatically.

The main prototype navigation and validation branches were also checked structurally.

**Limitation:** These checks demonstrate component consistency and functioning navigation. They are not measurements of usability with real participants.

## Developer Handoff

The **Homework 9 — Quick Feeding** screen was selected for development handoff and marked Ready for dev.

The screen includes native Figma annotations covering:

- Interaction behavior and navigation.
- Input validation and accessibility.
- Semantic variables and reusable components.

The related selected-example and validation-error screens remain available in the same Figma file.

## Research Limitation

The Homework 8 participant walkthroughs were fictional simulations, clearly identified as such. No empirical usability findings or participant retest results are claimed.

## Proposed Next Step

Test the component-based prototype with three real participants to verify whether the improved form instructions and error messages reduce hesitation, navigation mistakes, and requests for assistance.
