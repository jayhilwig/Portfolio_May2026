# Portfolio project rules

This is an existing vanilla HTML/CSS/JS portfolio.

Before changing UI:

- Inspect existing files first.
- Reuse existing CSS classes and JS patterns.
- Do not invent new components if similar ones already exist.
- Do not add React, Tailwind, build tools, or new dependencies.
- Preserve existing URLs and case study structure.
- Reuse the existing lightbox implementation.
- Keep changes small and reversible.
- Prefer editing existing files over creating new files.
- Do not add inline styles unless the existing code already uses them for that pattern.
- After changes, explain exactly which files changed and why.

# Agent instructions

Load `system-prompt.md` as your operating instructions for any design task in this directory. It defines your role, workflow, and the skill library in `skills/`.

When a user request matches a skill description in `system-prompt.md` chapter 20, read the corresponding file from `skills/` and follow its phased procedure.

Skills are reference documents. There is no skill-invocation tool in Codex; load them with a file read.

Verification is in-loop: render HTML output yourself when possible and report findings as a short list.
