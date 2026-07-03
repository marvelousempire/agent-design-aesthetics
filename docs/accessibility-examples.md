# Accessibility Examples

## Purpose

This file gives Design Aesthetics Agent clear accessibility examples to include in design prompts and audits.

## Common Requirements

| Area | Requirement | Prompt Language |
| --- | --- | --- |
| Contrast | Text must remain readable over backgrounds. | Use readable contrast and avoid placing text over busy gradients. |
| Keyboard | Interactive elements should be keyboard-safe. | Include visible focus states and keyboard navigation. |
| Labels | Controls need clear names. | Use clear labels, helper text, and error messages. |
| Motion | Animation should not overwhelm. | Keep motion restrained and respect reduced-motion preferences. |
| Color | Color should not be the only signal. | Pair color states with icons, text, or shape changes. |
| Touch | Mobile controls need safe tap areas. | Use comfortable tap targets and spacing. |

## Bad Prompt

```text
Make the dashboard glassy and animated.
```

## Better Prompt

```text
Create a glass-style dashboard with readable contrast, visible focus states, keyboard-safe controls, clear labels, and restrained animation that does not hide important information.
```

## Rule

A beautiful interface is not finished if it is hard to read, hard to navigate, or unclear to operate.
