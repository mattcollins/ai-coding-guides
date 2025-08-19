# General
* Follow modern software engineering best practices.

# Git Commits
* Follow the Conventional Commits convention for commit messages.

# Development Workflow
* Do test-driven development.
* Run linters and tests before every commit.

# Error-handling
## Internal Invariants
* If an internal precondition is violated, fail loudly. These are our bugs and must surface immediately.

## External Inputs (users, files, 3rd-party APIs)
* Validate at the boundary. On invalid input, reject with a clear, structured error; do not continue with guessed defaults.
* Only coerce/normalise when an explicit rule exists, and record the coercion.
