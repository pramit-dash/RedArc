# ADR-001: Project Structure

## Context

RedArc is a PoC project to track cricket ball trajectories. We need a clear, modular structure to allow easy development, testing, and future scaling.

## Decision

1. **Use Poetry** for package management, as it simplifies dependency handling and virtual environments.
2. **Organize core code in `src/redarc/`**, following the common pattern of separating source code and tests.
3. **Document** key design aspects in `docs/`, including a development plan, architecture decisions, and design overview.
4. **Containerize with Docker** to facilitate consistent local and cloud deployment.

## Status

Accepted

## Consequences

The modular project structure will make it easier to test, deploy, and manage dependencies, though it requires more initial setup.

