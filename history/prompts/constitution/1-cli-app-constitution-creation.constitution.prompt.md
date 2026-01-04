---
id: 1
title: "CLI App Constitution Creation"
stage: "constitution"
date_iso: "2026-01-05"
surface: "agent"
model: "Claude Sonnet 4.5"
feature: "none"
branch: "main"
user: "Umar Farooq"
command: "Write constitution file with specified rules"
labels: ["constitution", "cli", "setup"]
links:
  spec: null
  ticket: null
  adr: null
  pr: null
files_yaml:
  - ".specify/memory/constitution.md"
tests_yaml: []
prompt_text: "write the constitution in .specify/memory/constitution.md for cli app i want to develope a cli app with these rules 1) use always uv for package manager instaed of pip 2) use typer and rich for cli interactive 3) use python 3.12+ version 4) always test after completing the module"
response_text: "Created the constitution file .specify/memory/constitution.md with the specified rules for the CLI app: 1) Use Python 3.12+ version, 2) Use uv for package management instead of pip, 3) Use typer and rich for CLI interactive functionality, 4) Always test after completing each module. The constitution includes detailed sections on Core Principles, Technology Requirements, Development Workflow, and Governance."
outcome: "Successfully created constitution file with all specified requirements"
evaluation: "Constitution file properly created and follows all specified rules"
---

# CLI Application Constitution

## Core Principles

### I. Python Version Standard
All development must use Python 3.12+ version.

### II. Package Management
Always use uv for package management instead of pip.

### III. CLI Framework Standard
Use typer and rich for CLI interactive functionality.

### IV. Testing Requirement
Always test after completing each module.

### V. Technology Stack Consistency
Maintain consistency in using the specified technology stack: Python 3.12+, uv, typer, and rich.

### VI. Quality Assurance

All modules must pass tests before being considered complete.

## Technology Requirements

### Python Version
All code must be compatible with Python 3.12+ and take advantage of its features.

### Package Management
- Use uv for all dependency management tasks
- Avoid pip for dependency installation or management
- Leverage uv's faster installation and dependency resolution

### CLI Framework
- Use typer for building command-line interfaces
- Use rich for rich terminal output and interactive features
- Follow best practices for CLI design and user experience

## Development Workflow

### Module Development Process
1. Develop using Python 3.12+ features
2. Manage dependencies with uv
3. Build CLI components with typer and rich
4. Complete comprehensive testing after each module
5. Ensure all tests pass before marking module as complete

### Testing Standards
- Unit tests for all functions and classes
- Integration tests for CLI functionality
- End-to-end tests for complete workflows
- Test execution mandatory after module completion

## Governance
This constitution defines the mandatory standards for CLI application development; all development activities must comply with these principles.

All development must follow the specified technology stack and testing requirements.

**Version**: 1.0.0 | **Ratified**: 2026-01-05 | **Last Amended**: 2026-01-05