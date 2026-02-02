# CLAUDE.md - AI Assistant Guide for Product-Loop

This document provides guidance for AI assistants working on the Product-Loop project.

## Project Overview

**Product-Loop** is a continuous improvement workflow framework that implements an iterative product development cycle:

1. **Requirements** → PRD + acceptance criteria
2. **Development** → Code implementation
3. **Validation** → Automated test creation + execution
4. **Analysis** → Metrics aggregation + reporting
5. **Learning** → Insights extraction + next iteration planning

The workflow loops continuously, using insights from each iteration to improve the next.

## Current Project State

This project is in its **initial setup phase**. The repository currently contains:
- `README.md` - Project description
- `CLAUDE.md` - This file

No source code, dependencies, or build configuration have been established yet.

## Repository Structure

```
Product-Loop/
├── README.md           # Project overview
├── CLAUDE.md           # AI assistant guidelines (this file)
├── src/                # Source code (to be created)
├── tests/              # Test files (to be created)
├── docs/               # Documentation (to be created)
└── config/             # Configuration files (to be created)
```

## Development Guidelines

### When Adding New Features

1. **Start with requirements**: Define clear acceptance criteria before writing code
2. **Write tests first**: Follow TDD principles where practical
3. **Keep changes focused**: One feature or fix per commit/PR
4. **Document as you go**: Update relevant documentation with code changes

### Code Style Conventions

Until project-specific tooling is established, follow these general principles:

- **Naming**: Use descriptive, intention-revealing names
- **Functions**: Keep functions small and focused on a single responsibility
- **Comments**: Write code that is self-documenting; add comments only for "why", not "what"
- **Error handling**: Handle errors explicitly, don't swallow exceptions silently

### Git Workflow

- **Branch naming**: Use descriptive branch names (e.g., `feature/user-auth`, `fix/login-bug`)
- **Commit messages**: Write clear, imperative commit messages
  - Good: "Add user authentication endpoint"
  - Bad: "Fixed stuff"
- **Atomic commits**: Each commit should represent a single logical change

### Testing Philosophy

Aligned with the Product-Loop validation phase:

1. **Unit tests**: Test individual functions/components in isolation
2. **Integration tests**: Test interactions between components
3. **End-to-end tests**: Test complete user workflows
4. **Test coverage**: Aim for meaningful coverage, not 100% coverage

## Commands Reference

*Commands will be added as the project's tooling is established.*

### Placeholder Commands (to be configured)
```bash
# Install dependencies
# npm install / pip install -r requirements.txt / etc.

# Run development server
# npm run dev / python manage.py runserver / etc.

# Run tests
# npm test / pytest / etc.

# Build for production
# npm run build / etc.

# Lint code
# npm run lint / etc.
```

## Architecture Decisions

### Design Principles

1. **Modularity**: Keep components loosely coupled
2. **Iterability**: Design for easy modification and improvement
3. **Observability**: Build in metrics and logging from the start
4. **Automation**: Automate repetitive tasks in the loop

### Technology Stack

*To be determined based on project requirements.*

Considerations for technology selection:
- Match team expertise and project requirements
- Prioritize tools with good testing support
- Choose technologies that support the continuous learning loop

## Working with This Codebase

### For AI Assistants

When working on this project:

1. **Read before writing**: Always understand existing code before modifying
2. **Respect the loop**: Changes should support the Requirements → Development → Validation → Analysis → Learning cycle
3. **Test changes**: Verify modifications work as expected
4. **Document decisions**: Explain the "why" behind significant changes
5. **Keep it simple**: Prefer straightforward solutions over clever ones

### Common Tasks

| Task | Approach |
|------|----------|
| Adding a feature | Define requirements first, write tests, implement, document |
| Fixing a bug | Reproduce the issue, write a failing test, fix, verify |
| Refactoring | Ensure tests exist first, make incremental changes |
| Code review | Check for clarity, correctness, and alignment with project goals |

## Contributing

### Before Making Changes

1. Understand the current project state
2. Check if similar work exists or is in progress
3. Ensure changes align with the Product-Loop methodology

### Pull Request Checklist

- [ ] Code follows project conventions
- [ ] Tests added/updated as appropriate
- [ ] Documentation updated if needed
- [ ] Changes are focused and atomic
- [ ] Commit messages are clear and descriptive

## Project Roadmap

### Phase 1: Foundation (Current)
- [ ] Define technology stack
- [ ] Set up project structure
- [ ] Configure development tooling
- [ ] Establish CI/CD pipeline

### Phase 2: Core Implementation
- [ ] Implement requirements management
- [ ] Build development workflow support
- [ ] Create validation framework
- [ ] Develop analysis/metrics system

### Phase 3: Learning Loop
- [ ] Implement insights extraction
- [ ] Create feedback mechanisms
- [ ] Build iteration planning tools

## Notes

- This document should evolve as the project matures
- Update this file when adding new conventions or tooling
- Keep guidance practical and actionable

---

*Last updated: 2026-02-02*
