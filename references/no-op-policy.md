# No-Op Policy

A correct no-op is better than an unnecessary diff.

Recommend no change when code is already correct, readable, tested, convention-aligned, and proportionate to the problem.

Require a diff only when it improves at least one of:

- correctness
- security
- performance
- type safety
- maintainability
- test coverage
- observability
- domain clarity
- removal of proven duplication

Reject changes justified only by preference, novelty, style, or speculative future needs.
