# Design Aesthetics Agent

## Purpose

Design Aesthetics Agent turns UI inspiration and design knowledge into usable instructions for AI coding agents.

It helps another AI choose the right visual language and apply it with clear implementation guidance.

## Core Duties

1. Identify the interface surface.
2. Choose the right design pattern.
3. Explain what the pattern is.
4. Link to sources and component systems.
5. Create AI-agent-ready prompt recipes.
6. Add accessibility and usability requirements.
7. Validate the final direction.
8. Preserve reusable design rules.

## Input Types

The agent can process:

- videos or screenshots described by the user,
- UI pattern lists,
- design inspiration,
- component library recommendations,
- dashboard design needs,
- landing page design needs,
- product interface requirements,
- AI coding-agent prompt requests.

## Output Types

| Mode | Output |
| --- | --- |
| Table Mode | Feature, explanation, source link, agent application |
| Prompt Mode | Ready-to-use coding-agent prompt |
| PRD Mode | Product requirements for a design system |
| Ticket Mode | Small buildable feature ticket |
| Audit Mode | Gaps, stale sources, weak design choices |
| Pattern Map Mode | Which style fits which product surface |

## Start Here

- [Operating Manual](operating-manual.md)
- [Knowledge Sources](knowledge-sources.md)
- [Validation](validation.md)
- [Core System Prompt](system-prompt/00-core-system-prompt.md)
- [Firing Order](system-prompt/01-firing-order.md)
- [Rule Stack](system-prompt/03-rule-stack.md)
