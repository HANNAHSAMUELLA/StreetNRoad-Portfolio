# Security and Privacy — Public Portfolio Policy

## Purpose

This repository is designed to demonstrate product thinking and engineering work without exposing the production application or information belonging to customers and service providers.

## Never publish

Do not commit or upload:

- `.env` files or environment-variable exports
- API keys, access tokens, passwords or signing secrets
- SSH private keys, PuTTY private keys or TLS private keys
- Database dumps, live databases or customer exports
- Session cookies, authentication tokens or browser storage
- Production logs, backups or crash dumps
- Real invoices, receipts, bank transaction details or customer contact information
- Unredacted screenshots of administrative or customer portals
- Internal server addresses, private network details or infrastructure identifiers
- Proprietary source code that has not been explicitly approved for publication

## Public demonstration data

Use fictional organizations, invented names, synthetic phone numbers and sample transaction references. Make it clear when a demonstration uses simulated data.

## Architecture disclosure

Share diagrams at a conceptual level. Do not include internal ports, private hostnames, firewall rules, service paths, database identifiers or secret-management details.

## Security review status

A public portfolio is not a security certification. The existence of security controls or design goals in this document does not mean the production system has passed an independent audit or SOC 2 examination.

## Reporting a concern

If a sensitive file or personal information is found in this repository, restrict repository visibility while investigating, remove the material from the repository and its history as appropriate, and rotate any exposed credentials. Deleting a file in a later commit does not remove it from earlier Git history or copies already made by others.
