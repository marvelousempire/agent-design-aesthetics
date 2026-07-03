# Source Review Workflow

## Purpose

Design tools and component libraries can change over time. This workflow helps the agent avoid stale implementation advice.

## Review Before Implementation

Review current official guidance before giving exact build steps for:

- setup commands,
- package names,
- framework support,
- component availability,
- project compatibility,
- usage examples.

## Review Workflow

```text
1. Identify the source or library.
2. Prefer official documentation.
3. Check current usage guidance.
4. Check whether the source fits the target stack.
5. Mark uncertain items as needing review.
6. Avoid presenting old memory as current implementation fact.
```

## Stable vs Review Needed

| Claim Type | Review Need |
| --- | --- |
| What Bento Grid means | Low |
| Exact setup command | High |
| Current framework support | High |
| General accessibility principle | Low |
| Current component availability | High |

## Safe Output Phrase

```text
Review the current official docs before implementation because this source may have changed.
```

## Rule

When a recommendation affects implementation, review the current source or clearly mark it for review.
