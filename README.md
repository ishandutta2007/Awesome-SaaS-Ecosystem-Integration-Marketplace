# Awesome-SaaS-Ecosystem-Integration-Marketplace

# Awesome SaaS Ecosystem & Integration Marketplace

> A curated list of top SaaS Ecosystem and Integration Marketplace platforms — both SaaS/Hosted commercial app stores and open-source alternatives for discovering, distributing, and embedding third-party integrations.
> 🌟 Star this repo if you find it useful! 🌟

---

## 📋 Table of Contents

- [SaaS / Hosted Platforms](#-saas--hosted-platforms)
  - [Salesforce AppExchange](#salesforce-appexchange)
  - [Atlassian Marketplace](#atlassian-marketplace)
  - [HubSpot App Marketplace](#hubspot-app-marketplace)
  - [Zendesk Marketplace](#zendesk-marketplace)
  - [Freshworks Marketplace](#freshworks-marketplace)
  - [Slack App Directory](#slack-app-directory)
  - [Google Workspace Marketplace](#google-workspace-marketplace)
  - [Shopify App Store](#shopify-app-store)
  - [AWS Marketplace](#aws-marketplace)
  - [ServiceNow Store](#servicenow-store)
- [Open-Source Software](#-open-source-software)
  - [Panora](#panora)
  - [World Vibe Web (WVW)](#world-vibe-web-wvw)
  - [Integry (Freemium)](#integry-freemium)
- [Comparison at a Glance](#-comparison-at-a-glance)
- [Contributing](#-contributing)

---

## 🟦 SaaS / Hosted Platforms

Commercial, cloud-hosted SaaS Ecosystem and Integration Marketplace platforms. These are not open-source but are included as reference points for feature comparison.

### Salesforce AppExchange
**Type:** Enterprise cloud marketplace with native platform integration
AppExchange is the long-standing enterprise marketplace benchmark, connecting customers with more than **9,000 partner apps** and 9,600 ISV/SI partners since 2005 [citation:1]. It is recognized as a Leader in the IDC MarketScape for Worldwide Application and Platform Marketplaces, with **14 million installs** and **91% of Salesforce customers using at least one AppExchange app** [citation:1]. A key differentiator is **embedded discovery**: customers find and deploy solutions without leaving the Salesforce flow of work, with native platform integration, Data 360-powered search, and personalized recommendations [citation:1]. The newer **AgentExchange** marketplace extends this to agentic AI, with 646+ pre-built agentic assets and A2A/MCP partners [citation:1]. Enterprise trust is enforced through a rigorous review process, algorithmic verification, and a new Trust Center for security and compliance transparency [citation:1].
**Best for:** Salesforce customers wanting a governed, enterprise-grade marketplace with deep native integration and a proven ecosystem track record.

### Atlassian Marketplace
**Type:** App marketplace for Jira, Confluence, and Atlassian tools
Atlassian Marketplace provides a curated assortment of apps for Jira, Confluence, and the broader Atlassian stack, with categories spanning data visualization, AI-powered workflows, Rovo Agents, team communication, and DevOps [citation:3]. The marketplace includes **Forge apps** (running on Atlassian infrastructure with data stored in-platform) and cloud apps with additional security and support tiers [citation:3]. Popular apps include draw.io for diagramming (4.8/5, 1,202 reviews), Adaptavist's ScriptRunner (4.6/5, 822 reviews), and Tempo Timesheets for Jira time tracking [citation:3]. The marketplace surfaces app ratings and review counts prominently, helping buyers assess social proof before installing.
**Best for:** Atlassian users wanting a mature marketplace with strong app ratings, Forge-based security options, and deep integration into Jira/Confluence workflows.

### HubSpot App Marketplace
**Type:** CRM-centric integration marketplace
HubSpot's App Marketplace lists integrations that connect HubSpot with other tools, including integration platforms like Integry that offer a freemium model with 10,000 free runs per month and a visual workflow builder for embedding integrations inside the app [citation:4]. The marketplace is closely tied to HubSpot's CRM ecosystem, making it a natural discovery channel for sales, marketing, and service integrations.
**Best for:** HubSpot users wanting integrations that extend CRM workflows, particularly those exploring embedded integration platforms with freemium entry points.

### Zendesk Marketplace
**Type:** Support-focused app marketplace with custom object support
Zendesk Marketplace provides apps that extend support workflows, with December 2025 support added for **custom objects and object triggers** in Marketplace apps, enabling apps to acquire additional custom data integrated into agent workflows [citation:2]. Apps are tailored to extend the Zendesk interface, with common use cases including time tracking, viewing recent tickets in the sidebar, and visual query builders for complex searches [citation:14]. Apps can be public (listed in the Marketplace) or private (built by the organization and uploaded directly) [citation:14].
**Best for:** Zendesk customers wanting support-focused apps with recent custom object capabilities, accepting a more narrowly scoped ecosystem than enterprise marketplaces.

### Freshworks Marketplace
**Type:** IT and employee service connector marketplace
Freshworks Marketplace hosts **Connector Apps** for Freshservice, offering pre-built integrations with HCM systems (Workday, BambooHR, UKG, ADP, HiBob, Paylocity), ITSM solutions (ServiceNow, ManageEngine), DevOps tools (Azure DevOps, GitHub, Jira), and project management platforms (Smartsheet, Monday.com) [citation:10]. Connector Apps include **Recipes** with pre-built workflows for onboarding, offboarding, and ticket sync, customizable via a visual editor with triggers, conditions, and actions [citation:10]. Connections are established via OAuth2.0, OAuth1.0, or API Key with two-step authentication. **Important:** Connector Apps are billed based on **Task consumption**, with usage visible in the Connector App dashboard [citation:10].
**Best for:** Freshservice users wanting pre-built IT workflow connectors with customizable recipes, accepting task-based billing.

### Slack App Directory
**Type:** Workspace app directory with security review
Slack App Directory lists apps reviewed against Slack's guidelines, with the review process installing each app to test functionality and validate requested scopes [citation:8]. **Important limitation:** Slack does not perform code reviews during submission, though additional penetration testing may be performed at Slack's discretion [citation:8]. Apps must be resubmitted whenever Slack-side configuration changes (new scopes or platform features), and admins can enable app approvals for workspace-level governance [citation:8]. Security and privacy practices are self-certified by developers in the app's compliance tab [citation:8].
**Best for:** Slack workspace admins wanting a curated directory with scope-based review, accepting that security attestation is developer self-certified.

### Google Workspace Marketplace
**Type:** Workspace add-on marketplace
Google Workspace Marketplace provides apps and add-ons that extend Gmail, Docs, Calendar, Sheets, and Meet, with use cases spanning AI-assisted email composition, sales/CRM integration, project updates in Chat, and video conferencing in Calendar [citation:9]. Developers can publish apps publicly or restrict them to their work or school, while administrators can manage Marketplace apps to protect organizational data [citation:9].
**Best for:** Google Workspace organizations wanting add-ons that extend Google apps, with administrative controls for organizational governance.

### Shopify App Store
**Type:** E-commerce app marketplace
Shopify App Store provides apps that extend Shopify storefronts and operations, with listings spanning compliance (e.g., DPDP Compliant for Indian stores), marketing, sales, and operations [citation:7]. App listings include data access requirements (customer data, store data), pricing, and reviews, helping merchants assess fit before installing.
**Best for:** Shopify merchants wanting e-commerce-specific apps with clear data access disclosures, accepting a commerce-focused scope.

### AWS Marketplace
**Type:** Cloud procurement marketplace (guidance for third-party sellers)
AWS provides guidance for retailers building third-party marketplaces on AWS, enabling supplier onboarding and order routing without holding inventory [citation:6]. This is a **reference architecture** for building your own marketplace rather than a consumer-facing app store—it demonstrates how to implement marketplace software that recruits sellers, lists products, and routes orders for fulfillment [citation:6].
**Best for:** Retailers and platforms wanting to build their own third-party marketplace on AWS infrastructure, not as a turnkey integration catalog.

### ServiceNow Store
**Type:** ITSM app and plugin store
ServiceNow Store apps are typically accessible to all instances and can be installed directly within a ServiceNow instance via the "Install plugins" option, rather than requiring a separate store visit and "Get" click . This reflects ServiceNow's platform-native distribution model, where apps integrate directly into the ITSM workflow.
**Best for:** ServiceNow customers wanting platform-native apps that install directly into their instance, accepting the ServiceNow ecosystem scope.

---

## 🟩 Open-Source Software

Self-hosted, community-driven SaaS Ecosystem and Integration Marketplace tools. The open-source ecosystem is **nascent**—available projects focus on embedding integration catalogs into SaaS products or building federated app directories.

### Panora
**Stack:** Node.js / TypeScript / PostgreSQL / Redis / Docker | **License:** AGPL-3.0
Panora is an open-source integration platform positioned as a **Merge.dev alternative**, enabling SaaS companies to add an integration catalog to their product in minutes . Key features include:
- **Pre-built integration catalog** with a unified API layer for multiple third-party services
- **Multi-tenant architecture** with tenant isolation and security
- **White-label customization** with custom branding capabilities
- **Self-service integration setup** for end customers
- **SDK libraries** for multiple languages with comprehensive API documentation
- **Data transformation and mapping** with field mapping, validation, and bidirectional sync
- **Monitoring and observability** with real-time integration monitoring, usage analytics, and error tracking

Deploys via Docker with PostgreSQL and Redis, built on a microservices architecture . It explicitly targets the **integration marketplace use case**, allowing SaaS products to offer their customers a catalog of integrations without building the infrastructure from scratch.
**Best for:** SaaS companies wanting to embed an integration marketplace into their product with multi-tenancy, white-labeling, and a pre-built connector library, accepting AGPL licensing and the operational overhead of a Node.js/PostgreSQL stack.

### World Vibe Web (WVW)
**Stack:** Tauri / Rust / Static Site | **License:** Open Source
World Vibe Web is a **federated app store** for open-source, vibe-coded projects, with a fundamentally different architecture from centralized marketplaces [citation:12]. Key features:
- **Federated model**: each developer maintains their own `apps.json` in their own repo; WVW indexes them without hosting
- **No gatekeeping, no review queue, no 30% cut**: anyone with a GitHub repo can publish
- **Guardrails against manipulation**: declared stars/forks are ignored (WVW fetches live counts), featured arrays are ignored (maintainers curate), categories are validated against a fixed list, and duplicate app IDs are deduplicated [citation:12]
- **AI-powered curation**: featured apps are selected daily by a Copilot-powered agent via GitHub Agentic Workflows [citation:12]
- **Desktop app** built with Tauri + Rust (no Electron) and a PWA for browser installation

**Important caveat:** WVW explicitly states it does **not audit, verify, or guarantee the safety** of any listed app—every listing links to its GitHub repo for source review, and users install at their own risk [citation:12]. It is a directory, not a distributor.
**Best for:** Developers and users wanting a decentralized, open-source app directory for indie/vibe-coded projects with no gatekeeping, accepting that security verification is the user's responsibility.

### Integry (Freemium)
**Stack:** SaaS (with embedded catalog capabilities) | **License:** Freemium (not open-source)
Integry is listed as a **freemium** integration platform on HubSpot's marketplace, offering a visual workflow builder and a **dedicated app directory** that lets SaaS products create a catalog of integrations without building from scratch [citation:4]. The first 10,000 runs per month are free, with paid tiers beyond. While not open-source, it is included as a reference point for the **embedded integration catalog** use case that Panora also targets. Integry positions itself for product managers and designers as well as developers, covering the full integration lifecycle from conception to production [citation:4].
**Best for:** SaaS teams wanting a freemium, no-code approach to embedding an integration catalog, accepting that it is a commercial SaaS product rather than self-hosted open-source.

---

## 📊 Comparison at a Glance

| Software | License | Stack | Marketplace Type | Self-Hosted | Best For |
|----------|---------|-------|------------------|-------------|----------|
| **Salesforce AppExchange** | Proprietary | Cloud | Enterprise app store | ❌ | Governed enterprise marketplace |
| **Atlassian Marketplace** | Proprietary | Cloud | Atlassian app store | ❌ | Jira/Confluence ecosystem |
| **HubSpot App Marketplace** | Proprietary | Cloud | CRM integrations | ❌ | HubSpot CRM workflows |
| **Zendesk Marketplace** | Proprietary | Cloud | Support apps | ❌ | Support workflow extensions |
| **Freshworks Marketplace** | Proprietary | Cloud | Connector apps | ❌ | IT/employee service connectors |
| **Slack App Directory** | Proprietary | Cloud | Workspace apps | ❌ | Slack workspace extensions |
| **Google Workspace Marketplace** | Proprietary | Cloud | Workspace add-ons | ❌ | Google app extensions |
| **Panora** | AGPL-3.0 | Node.js/Postgres | Embedded integration catalog | ✅ | SaaS integration marketplace |
| **World Vibe Web** | Open Source | Tauri/Rust | Federated app directory | ✅ (Static) | Decentralized indie apps |
| **Integry** | Freemium | SaaS | Embedded catalog | ❌ | No-code integration catalog |

---

## 🤝 Contributing

Contributions are welcome! If you know of an open-source SaaS Ecosystem or Integration Marketplace tool that should be listed here, please open a pull request with:

- Project name and URL
- Brief description (1–2 sentences)
- Stack and license
- Why it stands out

Please ensure the project is actively maintained (releases within the last 12 months) and genuinely open-source (or clearly note if it is freemium/source-available but not OSI-approved, as with Integry). Note that the open-source ecosystem for **SaaS integration marketplaces** is **very limited**. **Panora** is the most direct open-source option for SaaS companies wanting to embed an integration catalog into their product, explicitly targeting the Merge.dev alternative use case with multi-tenancy and white-labeling . **World Vibe Web** takes a fundamentally different approach—federated, decentralized, and explicitly without gatekeeping or security verification—making it suitable for indie/vibe-coded projects rather than enterprise procurement [citation:12]. Commercial marketplaces like Salesforce AppExchange and Atlassian Marketplace remain far more capable for governed, enterprise-grade app distribution with rigorous review processes and native platform integration.

---

## 📄 License

This list is released under CC0 1.0 Universal (Public Domain). The software projects listed retain their respective licenses.

---

⭐ **If this list helped you discover a useful tool, please star the repo!** ⭐
