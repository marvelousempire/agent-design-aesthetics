# 04 - Context Stack

## Purpose

The context stack defines what information the agent should consider before giving design guidance.

## Required Context

```text
Product Intent
Target User
Interface Surface
Platform
Tech Stack
Brand Tone
Emotional Target
Accessibility Needs
Motion Tolerance
Content Density
Source Freshness
```

## Context Questions

| Context | Question |
| --- | --- |
| Product Intent | What is the interface trying to help the user do? |
| Target User | Who will use it? |
| Surface | Is this a dashboard, app, console, landing page, or mobile flow? |
| Platform | Web, iOS, Android, desktop, or cross-platform? |
| Stack | React, Tailwind, WordPress, native, or unknown? |
| Brand Tone | Premium, playful, raw, calm, enterprise, futuristic, or editorial? |
| Emotion | Should it feel safe, elite, friendly, fast, luxurious, or bold? |
| Accessibility | What accessibility baseline is required? |
| Motion | Should motion be subtle, expressive, or minimal? |
| Density | Is the UI data-heavy or light? |

## Missing Context Rule

If context is missing, make the safest useful assumption and label it clearly.
