# CLAUDE.md

This file provides guidance for AI assistants working on the **rianne** repository.

## Repository Overview

- **Repository**: `tszlia111/rianne`
- **Status**: Newly initialized — no application code has been added yet
- **Remote**: GitHub (via `tszlia111/rianne`)

## Project Structure

```
rianne/
├── CLAUDE.md          # AI assistant guidance (this file)
└── .git/              # Git repository
```

> **Note:** This repository is in its initial state. Update this section as the project structure evolves.

## Development Setup

### Prerequisites

_To be defined as the project takes shape. Update this section with:_
- Required language runtimes and versions
- Package managers
- System dependencies
- Environment variables

### Getting Started

```bash
git clone <repository-url>
cd rianne
# Add setup steps here as the project develops
```

## Build & Run Commands

_No build system configured yet. Update this section when tooling is added._

<!-- Example structure to fill in:
| Command          | Description              |
|------------------|--------------------------|
| `npm install`    | Install dependencies     |
| `npm run build`  | Build the project        |
| `npm run dev`    | Start dev server         |
| `npm test`       | Run all tests            |
| `npm run lint`   | Run linter               |
-->

## Architecture

_To be documented as the codebase develops. Include:_
- High-level architecture diagram or description
- Key modules and their responsibilities
- Data flow and control flow
- External service integrations

## Code Conventions

### General Principles

- Keep code simple, readable, and maintainable
- Follow the principle of least surprise
- Prefer explicit over implicit
- Write self-documenting code; add comments only when the "why" isn't obvious

### Git Workflow

- **Branch naming**: Use descriptive branch names (e.g., `feature/add-auth`, `fix/login-bug`)
- **Commit messages**: Write clear, imperative-mood commit messages (e.g., "Add user authentication" not "Added user authentication")
- **Pull requests**: Include a summary of changes and a test plan
- Do not commit secrets, credentials, or `.env` files

### Code Style

_Define language-specific style guides as the project develops. Document:_
- Formatting rules (indentation, line length, etc.)
- Naming conventions (files, variables, functions, classes)
- Import ordering
- Error handling patterns

### Testing

_Define testing conventions as tests are added. Document:_
- Test framework(s) in use
- How to run tests (all, single file, single test)
- Test naming conventions
- Coverage requirements

## AI Assistant Guidelines

When working on this repository:

1. **Read before modifying** — Always read a file before making changes to it
2. **Minimal changes** — Only make changes that are directly requested or clearly necessary; avoid over-engineering
3. **No guessing** — If the intent is ambiguous, ask for clarification rather than assuming
4. **Preserve style** — Match existing code style and conventions in the repository
5. **Test your work** — Run relevant tests after making changes; do not leave the codebase in a broken state
6. **Security first** — Never commit secrets, credentials, or sensitive data; avoid introducing common vulnerabilities (injection, XSS, etc.)
7. **Update this file** — When significant architectural decisions, new tooling, or conventions are established, update this CLAUDE.md to reflect the current state
