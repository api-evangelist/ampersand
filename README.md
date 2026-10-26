# Ampersand (ampersand)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Ampersand is a developer-first platform for building native SaaS integrations. It provides an embeddable UI component and managed infrastructure that lets developers add product integrations quickly, handling OAuth, data sync, webhooks, and field mapping out of the box. The platform supports hundreds of SaaS connectors including Salesforce, HubSpot, Marketo, Microsoft Dynamics 365, Zendesk, and Gong with bi-directional sync and declarative configuration.

**URL:** [https://www.withampersand.com](https://www.withampersand.com)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Developer Tools, Integrations, Platform, SaaS, OAuth, Data Sync, Webhooks

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Ampersand API
The Ampersand API enables developers to programmatically manage integrations, connections, installations, destinations, and data flows for SaaS-to-SaaS connectivity. It provides endpoints for managing installations, connections, destinations, API keys, projects, organizations, providers, and integration configurations within the Ampersand platform.

**Human URL:** [https://docs.withampersand.com/](https://docs.withampersand.com/)

#### Tags:

 - Integrations, Platform, SaaS, OAuth, Data Sync

#### Properties

- [Documentation](https://docs.withampersand.com/)
- [GettingStarted](https://docs.withampersand.com/getting-started)
- [Authentication](https://docs.withampersand.com/reference/authentication)
- [OpenAPI](openapi/ampersand-api-openapi-original.yml)

## Common Properties

- [Website](https://www.withampersand.com/)
- [Documentation](https://docs.withampersand.com/)
- [GitHubOrganization](https://github.com/amp-labs)
- [Blog](https://www.withampersand.com/blog)
- [SignUp](https://dashboard.withampersand.com/sign-up)
- [Login](https://dashboard.withampersand.com/sign-in)
- [SDK - React UI SDK](https://www.npmjs.com/package/@amp-labs/react)
- [CLI](https://github.com/amp-labs/cli)
- [SpectralRules](rules/ampersand-spectral-rules.yml)
- [NaftikoCapability](capabilities/shared/ampersand-api.yaml)
- [NaftikoCapability](capabilities/integration-management.yaml)
- [JSONLD](json-ld/ampersand-api-context.jsonld)
- [Vocabulary](vocabulary/ampersand-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| Declarative Integration Framework | Code-based, composable integration building that is version-controllable and CI/CD compatible for professional engineering workflows. |
| Managed OAuth Authentication | Free auth token management with auto-refresh for all supported SaaS providers, eliminating OAuth complexity from product teams. |
| Bi-directional Data Sync | On-demand read/write operations, scheduled reads, and bulk write capabilities for synchronizing data between SaaS applications. |
| Proxy API | Authenticated passthrough requests to customer systems enabling direct API calls without managing OAuth tokens. |
| Backfill Support | Historical data retrieval during customer onboarding to populate integrations with existing customer data. |
| DevOps Infrastructure | Automated retries, error handling, quota management, detailed logging, and alerting for production-grade integration reliability. |
| Custom Objects and Fields | Support for custom objects and fields allowing customers to configure integrations without being constrained by inflexible unified APIs. |
| Embeddable UI Components | React UI library with pre-built integration setup flows enabling customers to configure their own SaaS connections within your product. |
| AI SDK | Official AI SDK enabling AI agents to read from and write to SaaS applications through natural language via Ampersand integrations. |

## Use Cases

| Name | Description |
|------|-------------|
| CRM Integration | Build native Salesforce, HubSpot, and Dynamics 365 integrations to sync customer data bidirectionally with your SaaS product. |
| Marketing Automation Integration | Connect Marketo, HubSpot, and other marketing platforms to enable customer data flows for campaign automation and lead management. |
| Customer Support Integration | Integrate Zendesk and other support platforms to sync tickets, contacts, and customer data with your application. |
| Conversation Intelligence Integration | Connect Gong and other conversation platforms to access call recordings, transcripts, and insights within your application. |
| AI Agent Integration | Enable AI agents to read from and write to customer SaaS systems through the Ampersand AI SDK for autonomous workflow automation. |
| Developer Portal Embedding | Embed Ampersand's React UI components into your product so customers can self-service configure their own SaaS integrations. |

## Integrations

| Name | Description |
|------|-------------|
| Salesforce | Bi-directional CRM integration with Salesforce for contacts, accounts, opportunities, and custom objects. |
| HubSpot | CRM and marketing automation integration with HubSpot for contacts, deals, companies, and email tracking. |
| Marketo | Marketing automation integration with Marketo for lead management, campaigns, and activity data. |
| Microsoft Dynamics 365 | CRM integration with Microsoft Dynamics 365 for enterprise sales and customer service workflows. |
| Zendesk | Customer support integration with Zendesk for tickets, users, organizations, and support metrics. |
| Gong | Conversation intelligence integration with Gong for call recordings, transcripts, and revenue insights. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Ampersand API](openapi/ampersand-api-openapi-original.yml)

### JSON Schema

50 schema files in the [json-schema/](json-schema/) directory covering all Ampersand API resource types.

### JSON Structure

50 JSON Structure files in the [json-structure/](json-structure/) directory.

### JSON-LD

- [Ampersand API Context](json-ld/ampersand-api-context.jsonld)

### Examples

50 example files in the [examples/](examples/) directory.

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Ampersand API](capabilities/shared/ampersand-api.yaml) — 5 operations for SaaS integration management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Integration Management](capabilities/integration-management.yaml) | Ampersand API | 6 | Product Developer, Platform Engineer |

## Vocabulary

- [Ampersand Vocabulary](vocabulary/ampersand-vocabulary.yaml) — Unified taxonomy mapping 7 resources, 5 actions, 1 workflow, and 2 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Ampersand Spectral Rules](rules/ampersand-spectral-rules.yml) — 27 rules across 13 categories enforcing Ampersand API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
