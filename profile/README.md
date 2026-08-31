# BCVaadbot

**BCVaadbot** builds digital infrastructure for residential building management in Israel: mobile applications, administrative dashboards, payment workflows, resident communication, document handling, and operational tooling for building committees and property-management teams.

The organization maintains the codebases behind **VaadBot**, **VaadBit**, and related public information/payment websites.

## Product Areas

### VaadBot

VaadBot is a property-management platform for multi-apartment buildings. It helps building committees, residents, suppliers, accountants, and property managers coordinate everyday operations from one digital environment.

Core capabilities include:

- resident and building management;
- apartment, floor, and profile management;
- payment and invoice workflows;
- monthly reporting and financial visibility;
- documents and forms;
- forums, polls, and resident communication;
- supplier and service-provider coordination;
- administrative workflows for operational teams.

### VaadBit

VaadBit focuses on financial and operational workflows around shared residential buildings, including digital payment flows, administration tools, and supporting mobile/web interfaces.

### BillClick

BillClick is the public business and services layer connected to the broader residential-building management ecosystem.

## Technology Stack

- **Mobile:** Flutter / Dart, with legacy React Native code retained for historical versions.
- **Frontend/Admin:** SvelteKit, TypeScript, Tailwind, Vite.
- **Backend:** TypeScript, Bun, Elysia, Node.js, PostgreSQL, Redis.
- **Infrastructure:** Docker Compose, Nginx, GitHub Actions, DigitalOcean services.
- **Documentation & public sites:** static websites and knowledge-base style documentation.

## Repository Structure

The organization contains repositories for:

- mobile applications;
- admin dashboards;
- backend services;
- deployment and infrastructure projects;
- shared server utilities;
- public marketing and information websites.

Most product repositories are private because they contain active application code and operational logic.

## Security

Security reports can be sent to [security@hellsec.dev](mailto:security@hellsec.dev).

Please include:

- a clear description of the vulnerability;
- affected area or endpoint, if known;
- reproduction steps;
- potential impact;
- suggested remediation, if available.

We aim to acknowledge valid security reports within **48 hours** and provide a status update within **5 business days**.

---

This GitHub organization is maintained for product development, deployment, documentation, and operational support of the VaadBot/VaadBit ecosystem.
