# AGENTS.md - Multi-Agent Operating Guide

## System Mission & Scope
- **Project**: `docker-winbox`
- **Domain**: Networking, VPN & Cloud Infrastructure
- **Scope**: Docker container that executes winbox (Mikrotik RouterOS configurator) on Wine inside Debian Wheezy.
- **Core Stack**: Docker & Containerization

## Autonomous Agent Roles
- **Architect Agent**: Analyzes overall system structure, design patterns, and cross-module contracts.
- **Frontend / Mobile Agent**: Implements user interfaces, state management, and client-side interactions in `Docker & Containerization`.
- **Backend & Integration Agent**: Manages API routes, controllers, database models, and third-party services.
- **QA & Verification Agent**: Executes unit tests, integration tests, and build verification.

## Multi-Agent Collaboration Workflow
1. **Survey**: Read `GEMINI.md`, `CLAUDE.md`, and `DETAILS.md` before performing changes.
2. **Inspect**: Review the relevant entrypoints and config files.
3. **Implement**: Apply targeted modifications adhering to the coding conventions.
4. **Verify**: Execute build and test commands to confirm zero regressions.

## Tooling & Execution Environment
- **Shell & CLI**: Standard POSIX shell commands, Git, Package Managers (pnpm, npm, flutter, cargo, uv).
- **Runtime Environment**: Node.js, Python, Dart/Flutter SDK, Android SDK, Docker where applicable.

## Safety Guardrails & Verification Rules
- Do not delete or overwrite production configurations, `.env` files, or keystore files.
- Always verify dependencies and lint status before closing agent work sessions.
