# Pattern Blending Guide

## Purpose

This guide teaches the agent how to combine visual patterns without making the interface messy, trendy, or unreadable.

## Safe Pattern Blends

| Blend | Best Use | Rule |
| --- | --- | --- |
| Bento Grid + Glassmorphism | AI dashboards and SaaS homepages | Use glass lightly; keep card readability strong. |
| Bento Grid + Material Design 3 | Admin dashboards and consoles | Use Bento for grouping, Material for structure. |
| Aurora UI + Maximalism | Landing pages and product launches | Use gradients as atmosphere, not as text backgrounds. |
| Claymorphism + Apple HIG | Mobile onboarding | Keep native controls and safe tap targets. |
| Neomorphism + Minimalism | Settings and control panels | Keep contrast high enough for accessibility. |
| Brutalism + Editorial Typography | Opinionated brand pages | Keep layout intentional, not broken by accident. |

## Risky Blends

| Blend | Risk |
| --- | --- |
| Neomorphism + low contrast | Accessibility failure |
| Glassmorphism + busy backgrounds | Poor readability |
| Maximalism + dense dashboards | Cognitive overload |
| Brutalism + enterprise forms | Can feel careless or unsafe |
| Too many animation libraries | Performance and distraction risk |

## Agent Prompt Rule

When blending patterns, name the primary pattern and the supporting pattern.

Good:

```text
Use Bento Grid as the primary layout pattern and Glassmorphism only as a supporting depth effect.
```

Bad:

```text
Use bento, glass, clay, brutalism, aurora, and maximalism all together.
```

## Validation

- [ ] One primary pattern is clearly dominant.
- [ ] Supporting pattern improves the interface.
- [ ] Readability stays strong.
- [ ] Accessibility is preserved.
- [ ] Motion and effects are restrained.
