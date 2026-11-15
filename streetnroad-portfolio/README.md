# StreetNRoad
### Discover. Connect. Grow.

**StreetNRoad is a digital business-discovery and business-technology platform designed around the needs of Sierra Leone, with Freetown as an initial market focus.**

This public portfolio presents the product vision, selected capabilities, high-level architecture and development work behind StreetNRoad. It is a project showcase—not the production application source code.

[Project overview](docs/platform-overview.md) · [Capabilities](docs/features.md) · [Architecture](docs/architecture.md) · [Technology](docs/technology-stack.md) · [Security approach](docs/security-and-privacy.md) · [Demo guide](docs/demo-guide.md)

---

## What is StreetNRoad?

StreetNRoad brings business discovery and practical digital tools together in one platform. It is intended to help people discover local businesses, connect with service providers and help businesses improve their digital presence.

The platform is designed around a simple principle:

> **No Gatekeepers. No Algorithm. No FYP.**

The goal is to make business discovery straightforward and give businesses a direct way to present what they offer.

## Product areas

| Product area | What it is designed to do |
|---|---|
| Business discovery | Help people find and explore businesses and services |
| Business profiles | Present business information, images, galleries and contact options |
| Advertising and promotion | Give businesses tools to improve their visibility |
| Events and property listings | Support discovery of local events and real-estate opportunities |
| WhatsApp contact | Make it easier for customers to contact participating businesses |
| Invoice and receipt SaaS | Support business invoice, receipt and memo workflows |
| Receipt verification | Provide a way to verify supported receipt records |
| Delivery and tracking | Support order coordination, driver location and customer tracking |
| Administration | Provide operational tools for platform management |

These are product capabilities and development areas. Availability may vary by module and deployment.

## Selected development work

StreetNRoad brings together work across:

- Web application development and responsive interfaces
- Business and advertiser workflows
- Backend APIs and database-backed services
- WhatsApp Business Platform integration
- Document generation and receipt workflows
- Mapping, geolocation and route-planning integrations
- Real-time updates and tracking concepts
- Deployment, reverse-proxy and server operations

See [Technology stack](docs/technology-stack.md) for the technologies used across the different components.

## High-level architecture

```text
                  Customers and Businesses
                            |
                     Web / PWA Interface
                            |
                    HTTPS / Application API
                            |
        +-------------------+-------------------+
        |                   |                   |
 Business Discovery   Business Services   Admin Workflows
        |                   |                   |
        +-------------------+-------------------+
                            |
                  Application Data Layer
                            |
       +--------------------+--------------------+
       |                    |                    |
  Database Services   Messaging Integration   Mapping Services
                            |
                    WhatsApp Business API
```

This is a conceptual overview, not a deployment diagram. It intentionally excludes internal hostnames, network details, credentials, production paths and infrastructure identifiers.

## Screenshots and demonstrations

Add approved, sanitized screenshots to [`assets/screenshots/`](assets/screenshots/). Do not add screenshots containing customer information, phone numbers, access tokens, session cookies, private dashboards, internal URLs or operational secrets.

Suggested showcase images:

1. Business discovery homepage
2. Business profile and gallery
3. Advertiser dashboard
4. Invoice or receipt workflow using fictional sample data
5. Receipt verification using a fictional sample
6. Delivery tracking demonstration using simulated data

A screenshot placeholder guide is in `assets/screenshots/README.md`.

## Project status

StreetNRoad is an actively developed product ecosystem. This repository is a public-facing portfolio and documentation showcase. It does not contain the production application, production credentials, customer records or private implementation code.

Feature descriptions are a summary of intended and developed capabilities; they should not be interpreted as a guarantee that every feature is currently enabled for public use.

## About the project

**Product:** StreetNRoad  
**Positioning:** Business discovery and digital business services  
**Initial market focus:** Sierra Leone  
**Website:** https://streetnroad.com  
**Tagline:** Discover. Connect. Grow.

## Contact

For project enquiries and demonstrations, use the contact details published on the official StreetNRoad website.

## Repository safety

This repository is intended to remain safe for public viewing. It should contain only approved portfolio material, documentation and sanitized media. Never upload `.env` files, API keys, private keys, database dumps, customer records, session data, production logs, server backups or unreviewed application source code.

See [Security and privacy](docs/security-and-privacy.md).
