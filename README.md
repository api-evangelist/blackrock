# BlackRock (blackrock)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

BlackRock is the world's largest asset manager with over $10 trillion in assets under management. Through its Aladdin platform, BlackRock provides institutional investors, wealth managers, and financial services firms with risk analytics, portfolio management, and data capabilities via APIs. The Aladdin platform powers investment operations for many of the world's largest pension funds, insurers, and asset managers.

**URL:** [https://www.blackrock.com](https://www.blackrock.com)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Asset Management, Finance, FinTech, Investment Management, Portfolio Management, Risk Analytics

## Timestamps

- **Created:** 2026-03-21
- **Modified:** 2026-04-21

## APIs

### BlackRock Aladdin API
The Aladdin Developer program provides APIs that enable clients to access BlackRock's Aladdin platform capabilities programmatically. Aladdin APIs support portfolio analytics, risk reporting, data access, order management, and workflow automation for institutional asset managers, wealth managers, and financial services clients.

**Human URL:** [https://www.blackrock.com/aladdin/products/aladdin-developer](https://www.blackrock.com/aladdin/products/aladdin-developer)

#### Tags:

 - Asset Management, Finance, Portfolio Management, Risk Analytics

#### Properties

- [Documentation](https://www.blackrock.com/aladdin/products/aladdin-developer)
- [Python SDK (AladdinSDK)](https://github.com/blackrock/aladdinsdk)
- [JSON Schema - Portfolio](json-schema/blackrock-portfolio-schema.json)
- [JSON Schema - Risk Report](json-schema/blackrock-risk-report-schema.json)
- [JSON-LD Context](json-ld/blackrock-context.jsonld)
- [Example - Portfolio](examples/blackrock-portfolio-example.json)
- [Example - Risk Report](examples/blackrock-risk-report-example.json)

## Common Properties

- [Website](https://www.blackrock.com)
- [Documentation](https://www.blackrock.com/aladdin/products/aladdin-developer)
- [GitHub Organization](https://github.com/blackrock)
- [Terms of Service](https://www.blackrock.com/us/individual/regulatory/privacy-policy)
- [Privacy Policy](https://www.blackrock.com/us/individual/regulatory/privacy-policy)
- [Blog](https://www.blackrock.com/us/individual/insights)
- [Spectral Rules](rules/blackrock-spectral-rules.yml)
- [Naftiko Capability](capabilities/blackrock-aladdin.yaml)
- [Vocabulary](vocabulary/blackrock-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| Aladdin Risk Analytics | Multi-asset risk measurement and attribution capabilities accessible via API, including VaR, factor exposures, stress testing, and scenario analysis. |
| Portfolio Management APIs | APIs for portfolio construction, optimization, rebalancing, and compliance monitoring integrated with the Aladdin operating system. |
| Data Access Layer | Structured access to market data, security reference data, and portfolio data via RESTful APIs with enterprise data governance. |
| Order Management System Integration | APIs for trade order management, execution, and settlement workflows integrating with OMS and EMS systems. |
| AladdinSDK | Open-source Python SDK providing programmatic access to Aladdin APIs with authentication, pagination, and data transformation utilities. |
| Workflow Automation | Event-driven workflow APIs enabling clients to automate investment operations processes and integrate with third-party systems. |

## Use Cases

| Name | Description |
|------|-------------|
| Institutional Risk Reporting | Institutional investors use Aladdin APIs to generate regulatory risk reports, UCITS compliance reports, and investor disclosures. |
| Portfolio Analytics Integration | Wealth managers and RIAs integrate Aladdin risk analytics into their own client-facing and advisor-facing platforms. |
| Fintech Data Integration | FinTech companies access structured investment data through Aladdin APIs to power analytics, research, and advisory products. |
| Automated Rebalancing | Portfolio managers automate rebalancing workflows using Aladdin APIs to trigger trades based on drift thresholds and target allocations. |
| Multi-Manager Aggregation | Family offices and fund-of-funds use Aladdin APIs to aggregate portfolio data across multiple managers into a single risk view. |

## Integrations

| Name | Description |
|------|-------------|
| Charles River Development | Aladdin integrates with Charles River IMS for order management and compliance workflow automation. |
| SimCorp Dimension | Integration between Aladdin risk analytics and SimCorp's portfolio management and accounting systems. |
| Bloomberg | Market data and analytics integrations with Bloomberg Data License and Bloomberg PORT for risk and performance. |
| Refinitiv | Security master data and market data integrations with Refinitiv Datascope and Eikon platforms. |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
