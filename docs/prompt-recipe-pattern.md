# Prompt Recipe Pattern

## Purpose

Prompt recipes help AI coding agents apply design aesthetics safely and consistently.

## Recipe Template

```yaml
design_intent:
  surface: "dashboard | app | landing-page | console | mobile-flow"
  audience: ""
  emotional_target: "premium | friendly | bold | calm | safe | elite"
  primary_pattern: ""
  secondary_patterns: []
  component_libraries: []
  typography: ""
  spacing_system: "8pt grid"
  motion: "subtle | expressive | minimal"
  accessibility: "WCAG AA"
  output_requirements:
    - responsive layout
    - clear hierarchy
    - visible focus states
    - readable contrast
```

## Copyable Prompt Shell

```text
Build a [surface] for [audience] using [primary_pattern] with [secondary_patterns]. Use [component_libraries] where appropriate. The interface should feel [emotional_target]. Use clear typography, an 8pt spacing system, responsive behavior, visible focus states, readable contrast, and WCAG AA accessibility. Add [motion] motion only where it improves clarity.
```
