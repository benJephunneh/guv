# Architecture Review Checklist

Before endorsing an architectural or scope-widening change, check whether it:

- adds or changes a source of truth
- adds a new write path
- bypasses an established runtime boundary
- duplicates an existing surface or capability
- changes sync directionality or ownership
- weakens audit history or traceability
- relies on fuzzy matching where exact identity is required
- creates a second way to perform the same operation
- conflicts with a phase gate, ADR, or non-negotiable constraint
- lacks an acceptance test for the claimed benefit

If any answer is yes, surface the conflict before implementation.
