# docker-winbox - Gemini AI Development Guide

## Project Overview
- **Name**: `docker-winbox`
- **Domain**: Networking, VPN & Cloud Infrastructure
- **Summary**: Docker container that executes winbox (Mikrotik RouterOS configurator) on Wine inside Debian Wheezy.
- **Tech Stack**: Docker & Containerization
- **Primary Languages**: Bash Shell (1 files)

## Architectural Structure
Modular architectural structure designed for networking, vpn & cloud infrastructure operations, separating business logic, user interface components, and external communication interfaces.

## Key Directory Structure & Entrypoints
- Standalone files and scripts directory

**Key Entrypoints**:
- Root directory manifests and operational scripts

## Development & Build Commands
```bash
# General Execution
ls -la
./deploy.sh     # if deployment script exists
```

## Environment Variables & Configuration
```bash
# Environment Configuration Template
PORT=3000
NODE_ENV=development
API_BASE_URL=http://localhost:8000
DATABASE_URL=postgresql://user:pass@localhost:5432/dbname
```

## AI Assistant Guidelines & Best Practices
1. **Code Integrity**: Preserve all existing architecture patterns and business rules in `docker-winbox`.
2. **Type Safety & Validation**: Maintain strict typing and runtime payload validation on all external API boundaries.
3. **Security First**: Never hardcode API keys, secrets, or database credentials directly into client-side code.
4. **Testing & Verification**: Run linters, unit tests, and build checks prior to committing changes.
