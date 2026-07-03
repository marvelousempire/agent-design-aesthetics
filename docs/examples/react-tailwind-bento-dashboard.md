# React + Tailwind Bento Dashboard Example

## Surface

AI dashboard

## Intent

Show many features, tools, metrics, or agent states in a layout that is easy to scan.

## Pattern

Bento Grid with light Glassmorphism support.

## Component Sources

- shadcn/ui
- Radix UI
- Tailwind CSS
- Motion

## Agent Prompt

```text
Create a responsive React + Tailwind AI dashboard using a Bento Grid layout. Use shadcn/ui cards and Radix UI accessible primitives. Organize content into mixed-size cards with clear visual hierarchy. Add subtle glass-style panels only where they improve depth. Use an 8pt spacing system, readable typography, clear empty states, visible focus states, and WCAG AA contrast. Add restrained Motion transitions for card entrance and hover states.
```

## Accessibility

- Maintain readable contrast over any translucent panel.
- Use semantic headings.
- Ensure keyboard focus is visible.
- Do not hide important information behind hover-only interactions.

## Validation

- [ ] Cards are grouped by purpose.
- [ ] Important cards are visually larger.
- [ ] Mobile layout stacks safely.
- [ ] Effects do not weaken readability.
