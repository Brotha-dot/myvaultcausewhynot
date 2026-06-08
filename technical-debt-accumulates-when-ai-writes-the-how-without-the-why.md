---
type: Evergreen Note
status: Active
related_to: "[[ai-assisted-development]]"
_organized: true
---

# Technical debt accumulates when AI writes the 'How' without the 'Why'

AI can generate the implementation ("how") but rarely captures the rationale ("why") behind a specific choice. Without this context, the code becomes difficult to modify or refactor later, as future developers (including your future self) won't know the constraints that led to that implementation. This results in [[ai-generated-code-often-introduces-subtle-debugging-debt|debugging debt]] that can paralyze a project.