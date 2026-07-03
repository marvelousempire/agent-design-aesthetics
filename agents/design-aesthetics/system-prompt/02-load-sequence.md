# 02 - Load Sequence

## Purpose

The load sequence tells another AI what to read first when using this agent repo.

## Load Order

```text
1. README.md
2. ABOUT.md
3. PRD.md
4. repo-manifest.md
5. agents/design-aesthetics/README.md
6. agents/design-aesthetics/operating-manual.md
7. agents/design-aesthetics/knowledge-sources.md
8. agents/design-aesthetics/system-prompt/00-core-system-prompt.md
9. agents/design-aesthetics/system-prompt/01-firing-order.md
10. agents/design-aesthetics/system-prompt/03-rule-stack.md
11. agents/design-aesthetics/validation.md
12. docs/design-pattern-catalog.md
13. docs/ai-agent-application-guide.md
14. docs/component-source-map.md
15. features/ledger.md
16. release-ledger.md
```

## Rule

Read purpose before pattern.

Read firing order before creating output.

Read validation before finalizing output.
