# CLAUDE.md

This file provides project-specific guidance for Claude Code when working in `docker-winbox`.

## Overview
- **Project**: `docker-winbox` (Networking, VPN & Cloud Infrastructure)
- **Summary**: Docker container that executes winbox (Mikrotik RouterOS configurator) on Wine inside Debian Wheezy.
- **Tech Stack**: Docker & Containerization

## Quick Commands
```bash
# General Execution
ls -la
./deploy.sh     # if deployment script exists
```

## Architecture & Code Patterns
Modular architectural structure designed for networking, vpn & cloud infrastructure operations, separating business logic, user interface components, and external communication interfaces.

## Critical Knowledge & Gotchas
Ensure all environment variables and external API dependencies are configured before running production builds. Verify network port availability and file permissions.
