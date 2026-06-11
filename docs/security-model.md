# Security Model

Shortcut Launcher is treated as an internal tool because the shortcut catalog can reveal private operational structure, internal services, and workflow patterns.

## Public Repository Safeguards

This public repository is designed to avoid exposing:

- Source code
- Internal URLs
- Private shortcut definitions
- Credentials or tokens
- Environment variables
- Deployment details
- Screenshots containing sensitive destinations

## Private Data Classification

The following are considered private and should remain outside the public repository:

- Any real shortcut target
- Internal tool names that are not already public
- Organization-specific workflows
- User, team, or account identifiers
- Logs, telemetry, and analytics
- Configuration files from the private implementation

## Review Checklist Before Publishing

- Confirm that no source files are present
- Confirm that no package or lock files are present
- Confirm that no `.env` files are present
- Confirm that no generated build output is present
- Confirm that no screenshots expose internal resources
- Confirm that documentation uses generic examples only

## Reporting

If sensitive information is accidentally published, remove it from the public repository and rotate any affected credentials immediately.

