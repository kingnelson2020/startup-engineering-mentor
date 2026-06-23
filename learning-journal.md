# Learning Journal

## Current Phase

Phase: Phase 1 — JavaScript & TypeScript Foundations

Current Topic: Control Flow (completed) → Loops (next)

Date Started: 2026-06-23

---

## Concepts Learned

* Concept: if / else
* Key Takeaway: Only the first matching condition in a chain runs — the engine stops checking once it finds a true condition, even if later conditions are also true. Condition order matters; broad/loose conditions placed before strict ones cause silent logic bugs (e.g. a discount-tier bug where a big spender gets the worst tier because a loose `> 100` check fired before a stricter `> 1000` check).
* Confidence (1-10): 9

* Concept: switch
* Key Takeaway: switch compares one value against exact matches using strict equality. Once a case matches, execution falls through to subsequent cases unless a `break` stops it — fall-through runs the next case's code unconditionally, regardless of whether that case's value actually matches.
* Confidence (1-10): 9

* Concept: Ternary operator
* Key Takeaway: A ternary (`condition ? a : b`) is an expression — it evaluates to a value, so it can be used anywhere a value is expected (return statements, function arguments, template literals). if/else is a statement that controls flow and cannot be used the same way (e.g. cannot be passed directly into `return` or `console.log`).
* Confidence (1-10): 9

---

## Exercises Completed

| Date | Exercise | Result |
| ---- | -------- | ------ |
| 2026-06-23 | Trace buggy if/else discount-tier chain (totalSpent = 1500) | Correct — identified that loosest condition fires first |
| 2026-06-23 | Trace switch fall-through (role = "admin", missing break) | Correct — identified fall-through into "editor" case |
| 2026-06-23 | Trace switch with break (role = "viewer") | Correct — identified clean stop, no fall-through |
| 2026-06-23 | Convert if/else (shipping cost) into ternary | Correct — working code, verified with console.log |
| 2026-06-23 | Explain why ternary works in `return` but if/else statement would not | Correct — tied reasoning to return needing a value |

---

## Mistakes Made

* Mistake: First explanation of switch's "Full access" print described the case match as the condition being "True," conflating switch's strict-equality matching with if's boolean evaluation.
* Lesson: switch doesn't evaluate truthiness per case — it checks `value === case` until a match, then runs code line-by-line until a break. Fall-through code runs unconditionally, not because the next case's condition was checked and passed.

---

## Questions To Revisit

* Question: (none flagged yet — revisit if redundant boolean-ternary pattern, e.g. `cond ? true : false`, comes up again in real code)

---

## Weekly Reflection

### What I Learned

Completed Control Flow: if/else, switch, and the ternary operator. Understood not just the syntax but the failure modes — condition-ordering bugs in if/else chains, and fall-through bugs in switch statements from missing break.

### What Was Difficult

Initial explanation of switch's matching mechanism blurred the line between boolean condition evaluation (if/else) and strict-equality case matching (switch). Corrected after mentor clarification.

### What Improved

Reasoning became more precise across the session — by the ternary section, explanations correctly tied claims to underlying mechanics (e.g. "return needs a value" → expression vs statement) rather than just restating definitions.

### What I Will Focus On Next Week

Loops: for, while, for...of, for...in, break/continue. This is a broad-coverage topic per the curriculum — expect multiple variations and real-world use cases for each loop type.