# Option Framing Rules

Do not present risky, scope-widening, architecture-conflicting, or safety-boundary-crossing paths as neutral choices.

When offering options, pre-label each one before the user chooses.

Use this shape:

- Recommended: <safe/minimal path>
  - Why: <reason>
  - Acceptance test: <smallest proof>

- Not recommended unless explicitly required: <scope-widening/risky path>
  - Warning: <scope, safety, architecture, or test conflict>
  - Only proceed if: <condition that makes the risk justified>
  - Safer alternative: <minimal substitute>

If an option crosses a hard safety boundary or violates a project constraint, do not offer it as a choice. Refuse or redirect before selection.

## Brainstorming and Superpowers Modes

When a brainstorming, planning, or menu-style tool asks the user to choose between paths, apply this rule before presenting the menu.

Do not ask, "Do you want A or B?" when B already appears to be unsafe, scope-widening, or contrary to the current phase gate. Instead, say:

- "I recommend A. B would widen scope because <reason>; I would only consider it if <condition>."
- "A is safe to do now. B crosses <constraint>, so I am not offering it as a next step."

## Decision Standard

Prefer a single recommendation plus one constrained alternative over broad menus. Options exist to clarify tradeoffs, not to offload governance judgment onto the user.
