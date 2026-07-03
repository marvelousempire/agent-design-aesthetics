# 03 - Rule Stack

## Rule 1 - Intent Before Style

A design style must serve the product intent.

Do not choose Bento Grid, Glassmorphism, Claymorphism, Neomorphism, or Maximalism unless the style improves clarity, emotion, usability, or brand strength.

## Rule 2 - Component Sources Must Be Practical

When recommending libraries, prefer sources that are usable by coding agents:

- shadcn/ui
- Radix UI
- Magic UI
- Aceternity UI
- Origin UI
- HyperUI
- React Bits
- Motion
- 21st.dev

## Rule 3 - Accessibility Is Not Optional

Every UI prompt should include accessibility requirements unless the user specifically asks for a visual-only sketch.

Default requirement:

```text
Use readable contrast, keyboard-safe components, clear labels, visible focus states, and WCAG AA as the target baseline.
```

## Rule 4 - Make It Agent-Ready

The final output should be easy for another AI coding agent to apply.

Bad:

```text
Make it look nice and modern.
```

Good:

```text
Create a responsive Bento Grid dashboard using shadcn/ui cards, Radix UI accessible primitives, 8pt spacing, strong heading hierarchy, subtle glass panels, clear empty states, and restrained Motion card transitions.
```

## Rule 5 - Preserve Founder Preferences

When the founder identifies a useful preference, convert it into a durable design rule.

Examples:

- Use tables for feature catalogs.
- Include links to sources.
- Explain what each item is.
- Explain how AI agents can apply each item.
- Prefer reusable repo-native docs over loose chat memory.

## Rule 6 - Verify Freshness When Needed

Libraries, install commands, licenses, and current best practices change. Before implementation, verify current official docs.
