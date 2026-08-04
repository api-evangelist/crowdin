# Crowdin (crowdin)

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

Crowdin is a localization management platform for software, mobile, games, and documentation. It offers a REST API v2 covering projects, files, strings, translations, screenshots, glossaries, MT engines, and webhooks, plus a single GraphQL endpoint. Authentication uses Personal Access Tokens or OAuth 2. Official client libraries are published for JavaScript/TypeScript, Python, PHP, .NET, Java, and Ruby. Crowdin Enterprise customers get a per-tenant domain (e.g. https://{domain}.api.crowdin.com).

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/crowdin/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/crowdin/refs/heads/main/apis.yml)

## Tags

- Localization
- Translation
- TMS
- REST
- GraphQL
- Developer Tools
- Enterprise

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

### Crowdin REST API v2

Full-coverage REST API for Crowdin and Crowdin Enterprise. Resources include projects, files, source strings, string translations, string comments, screenshots, glossaries, MT engines, TMs, tasks, workflows, reports, distributions, webhooks, users, groups, and OAuth applications. Authenticate with a Personal Access Token or OAuth 2 bearer token.

- **Human URL:** [https://support.crowdin.com/developer/api/v2/](https://support.crowdin.com/developer/api/v2/)
- **Base URL:** `https://api.crowdin.com/api/v2`

#### Tags

- REST
- Projects
- Files
- Strings
- Translations
- Screenshots
- Glossaries
- Webhooks

#### Properties

- [Documentation](https://support.crowdin.com/developer/api/v2/)
- [Developer Portal](https://support.crowdin.com/developer/)
- [SDK](https://github.com/crowdin/crowdin-api-client-js)
- [SDK](https://pypi.org/project/crowdin-api-client/)
- [SDK](https://packagist.org/packages/crowdin/crowdin-api-client)
- [SDK](https://www.nuget.org/packages/Crowdin.Api/)
- [SDK](https://github.com/crowdin/crowdin-api-client-java)
- [SDK](https://github.com/crowdin/crowdin-api-client-ruby)
- [Postman Collection](collections/crowdin.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/crowdin.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Crowdin GraphQL API

Single-endpoint GraphQL API for Crowdin Enterprise. Authentication via Bearer token using a Personal Access Token or OAuth 2 access token.

- **Human URL:** [https://support.crowdin.com/developer/graphql-api/](https://support.crowdin.com/developer/graphql-api/)
- **Base URL:** `https://api.crowdin.com/api/graphql`

#### Tags

- GraphQL
- Enterprise

#### Properties

- [Documentation](https://support.crowdin.com/developer/graphql-api/)
- [Postman Collection](collections/crowdin.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/crowdin.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://crowdin.com/)
- [Documentation](https://support.crowdin.com/developer/)
- [Git Hub](https://github.com/crowdin)
- [LinkedIn](https://www.linkedin.com/company/crowdin)
- [Plans](plans/crowdin-plans-pricing.yml)
- [Rate Limits](rate-limits/crowdin-rate-limits.yml)
- [Fin Ops](finops/crowdin-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
