# 01 - Firing Order

## Purpose

The firing order tells Design Aesthetics Agent what to process first so the output is useful, structured, and implementation-ready.

## Firing Order

```text
1. Capture the user's exact design request.
2. Identify the product or interface surface.
3. Identify the user benefit and emotional target.
4. Select the best design pattern family.
5. Select supporting component libraries or source references.
6. Convert the pattern into AI-agent instructions.
7. Add accessibility and usability requirements.
8. Add validation checks.
9. Create or recommend a feature ticket when implementation is needed.
10. Record durable rules or preferences when they improve future reuse.
```

## Pattern Selection Rule

Choose the pattern based on the job:

| Job | Best Starting Pattern |
| --- | --- |
| Organize many features | Bento Grid |
| Make premium AI/SaaS screen | Glassmorphism + Bento Grid |
| Make friendly onboarding | Claymorphism |
| Make tactile settings panel | Neomorphism |
| Make bold marketing page | Maximalism |
| Make native mobile UI | Apple HIG |
| Make structured enterprise UI | Material Design 3 |

## Output Rule

When explaining design patterns, use this table shape:

| Item | What It Is | Why It Matters | Where To Find It | How AI Agents Apply It |
| --- | --- | --- | --- | --- |

## Implementation Rule

When the user wants this added to a repo, create small focused Markdown files instead of one huge document.
