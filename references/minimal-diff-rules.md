# Minimal-Diff Rules

Prefer the smallest safe diff that satisfies the real objective.

Do:

- touch only relevant files
- preserve existing behavior unless change is required
- add focused tests for changed behavior
- use existing abstractions and conventions
- explain why each changed area is necessary

Do not:

- rewrite working code for aesthetics
- introduce abstractions before duplication is proven
- mix refactor and behavior change without saying so
- widen task scope silently
- rename or reorganize broadly unless that is the task
