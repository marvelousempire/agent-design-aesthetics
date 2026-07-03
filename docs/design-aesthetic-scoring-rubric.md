# Design Aesthetic Scoring Rubric

## Purpose

This rubric helps the agent score whether a design direction is strong enough for implementation.

## Score Table

| Category | 1 | 3 | 5 |
| --- | --- | --- | --- |
| Intent Fit | Style feels random | Style partly supports intent | Style clearly serves the product purpose |
| Visual Hierarchy | Hard to scan | Mostly clear | Immediately understandable |
| Accessibility | Weak or ignored | Basic coverage | Strong contrast, labels, focus, keyboard flow |
| Component Practicality | Hard to build | Buildable with effort | Clear libraries and implementation path |
| Responsiveness | Not considered | Basic responsive note | Clear desktop, tablet, and mobile behavior |
| Motion | Distracting or missing | Some useful motion | Motion supports understanding and state |
| Source Hygiene | No sources | Some sources | Official or stable sources included with freshness note |
| Prompt Readiness | Vague | Usable | Copy-ready for a coding agent |

## Rating Guide

```text
36-40 = Excellent / build-ready
30-35 = Strong / minor tuning
24-29 = Usable / needs refinement
16-23 = Weak / needs rewrite
Below 16 = Not ready
```

## Rule

A design direction should not be treated as ready until it scores at least 30.
