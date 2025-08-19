# Best Practices for Developing Software With AI Assistants

## Maintain Good Assistant Configuration Files
AI coding assistants allow you to set up configuration files (such as CLAUDE.md
for Claude Code) to provide project-level context to the AI. Use these files
to provide key context:
* System architecture
* Coding style

See [agent-instructions.md](agent-instructions.md) for a starting point.

## Use Automated Tests
* Maintain a good suite of automated tests.

## Use Linters
* Configure linters to run via pre-commit hooks.
