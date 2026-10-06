# AGENTS.md

## Commit messages

- Write commit subjects in plain English.
- Use the imperative mood and sentence case.
- Do not use Conventional Commits prefixes such as `feat`, `fix`, `docs`, `chore`, or similar labels.
- Start the subject with a capital letter.
- Do not end the subject with a period.
- Keep the subject concise, preferably within 72 characters.
- Describe the specific change or intent represented by the staged diff.
- Avoid vague wording and unnecessary implementation detail.
- Use one commit for one coherent change whenever practical.
- Inspect the staged changes before generating or applying a commit message.

### Commit body

- Use a subject-only commit message by default.
- Add a commit body only when the staged change is objectively complex enough that the subject cannot communicate the important context by itself.
- Consider a body necessary when the change includes multiple meaningful behaviors, non-obvious rationale, notable tradeoffs, compatibility implications, migration requirements, or user-visible side effects.
- Do not add a body merely because several files changed or because additional detail is available.
- Separate the subject from the body with a blank line.
- Use a short bullet list only when two or more distinct points need clarification.
- Keep each bullet concise and focused on rationale, impact, constraints, or notable behavior.
- Do not repeat information that is already clear from the subject or staged diff.

- Do not mention AI, agents, prompts, or automated generation in commit messages.
