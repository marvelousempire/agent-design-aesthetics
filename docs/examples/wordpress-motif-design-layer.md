# WordPress / Motif Design Layer Example

## Surface

WordPress admin-style product, idea, or feature interface.

## Intent

Give a WooCommerce or Motif-style system a clearer visual lens without changing the underlying engine.

## Pattern

Bento Grid for overview pages, clean cards for object details, and restrained Material-style structure for forms.

## Component Sources

- WordPress admin patterns
- Tailwind or block-based CSS where available
- Material Design 3 as structure reference
- WCAG for accessibility

## Agent Prompt

```text
Create a WordPress/Motif-style interface that changes the visual lens without changing the underlying engine. Use clean card sections, a Bento-style overview for object summaries, structured form groups, clear labels, readable spacing, and accessible contrast. Keep the UI compatible with admin workflows and avoid decorative effects that reduce clarity. Treat each object as intent-driven and show its status, purpose, next action, and validation state.
```

## Accessibility

- Use plain labels and helper text.
- Keep form errors visible and specific.
- Preserve keyboard navigation.
- Avoid low-contrast admin cards.

## Validation

- [ ] Does not break the underlying engine.
- [ ] Improves object readability.
- [ ] Shows intent, status, and next action.
- [ ] Keeps admin workflows clear.
