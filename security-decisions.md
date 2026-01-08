# Security Decisions & Tradeoffs

## Identity Enforcement
Azure Entra ID authentication was enforced to eliminate anonymous access.

## Network Controls
Access Restrictions were used instead of Private Endpoint due to service-tier limitations.

## Transport Security
HTTPS is enforced by default with platform-managed TLS.

## Logging
Log Stream was used for observability due to Free-tier logging limitations.

## Summary
Security decisions balanced effectiveness, platform constraints, and cost.
