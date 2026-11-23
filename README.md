# AROSA

**Written for AROS**

*Independent prerelease project for AROS.*

See [branding and release-line policy](BRANDING.md).

**AROSA** (Application Runtime Operating Services Abstraction) is an **independent application platform being developed for AROS** by **DaniloS**.

AROSA brings reusable services, capability discovery and selection, providers, adapters, authorization, state, lifecycle and composition into a coherent application environment. Applications are intended to both request and contribute capabilities, so features can be shared across file management, browsing, content, graphics, documents, tools and workspace experiences.

> **Status: early development vision preview.** AROSA has active implementation work and compiled components, but many capabilities remain incomplete, experimental or at design stage. Production readiness and current AROS x86_64/SMP stability are under investigation. No finished release or release date is announced here.

## Public project site

This repository contains the **public project overview and community issue templates only**. It does **not** contain the AROSA development source, private architectural records, artifacts, internal traces or a license to use unpublished software.

After GitHub Pages is enabled, see the project site for:

- [Architecture](docs/architecture.html) — services, providers, consumers, adapters and capability composition
- [Roadmap](docs/roadmap.html) — parallel development workstreams and honest status
- [FAQ](docs/faq.html) — how AROSA relates to AROS and existing technologies
- [Community](docs/community.html) — technical feedback and public issue reports

## Why AROSA?

AROSA aims to make an Amiga-derived platform useful for modern everyday computing: documents, content, web, multimedia, developer tools, administration and multiple user environments, without requiring each application to independently recreate the same cross-cutting functionality.

Its architectural approach has parallels with service-oriented and event-driven systems, but does not imply every distributed-system feature is implemented. It is an application platform, **not merely a GUI theme**, and it does not replace AROS, Intuition, Exec, Zune/MUI or existing native applications.

## Participation

Use public Issues for specific, shareable bug reports, documentation improvements and feature suggestions. Engineering source and detailed internal diagnostics are tracked privately. Please do not post security-sensitive information or unpublished source in public reports.

## Independence and attribution

AROSA is an independent project by **DaniloS**. It is **not an official AROS distribution or an endorsed AROS component**. Existing AROS/Amiga technologies, code and artwork remain the property of their respective authors and are subject to their own licenses.

This documentation-only repository does **not** grant a license to unpublished AROSA implementation code. A public-source license will be announced separately if and when publication occurs.
