# Ampersand (ampersand)
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
