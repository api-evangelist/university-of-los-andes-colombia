# University of Los Andes Colombia (university-of-los-andes-colombia)

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

Universidad de los Andes (Uniandes) is a private research university in Bogota, Colombia, founded in 1948 and ranked #179 in the QS World University Rankings 2025. This repository catalogs its publicly observable developer/API footprint as an APIs.json profile. The most significant public machine-readable surface is the DSpace-based institutional repository "Seneca," which exposes OAI-PMH and a DSpace REST API for open-access scholarly content. No dedicated public developer portal was found at review time.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/university-of-los-andes-colombia/refs/heads/main/apis.yml
- Run with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=university-of-los-andes-colombia-api-evangelist&utm_content=repo

## Type

- Index / Consumer / 3rd-Party

## Tags

- Education
- Higher Education
- University
- Colombia
- Latin America
- Open Access
- Institutional Repository
- Research

## APIs

- **Repositorio Institucional Seneca - OAI-PMH** — OAI-PMH metadata harvesting for the DSpace "Seneca" institutional repository. Docs: https://repositorio.uniandes.edu.co/ (base: https://repositorio.uniandes.edu.co/oai/request)
- **Repositorio Institucional Seneca - DSpace REST API** — DSpace REST API surface for communities, collections, and items. Docs: https://repositorio.uniandes.edu.co/ (base: https://repositorio.uniandes.edu.co/server/api)

Both repository endpoints are publicly documented but returned HTTP 403 to automated clients at review time (likely bot mitigation); treat as conditionally available.

## Plans / Rate Limits / FinOps

- Plans: [plans/university-of-los-andes-colombia-plans-pricing.yml](plans/university-of-los-andes-colombia-plans-pricing.yml)
- Rate Limits: [rate-limits/university-of-los-andes-colombia-rate-limits.yml](rate-limits/university-of-los-andes-colombia-rate-limits.yml)
- FinOps: [finops/university-of-los-andes-colombia-finops.yml](finops/university-of-los-andes-colombia-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.uniandes.edu.co/
- LinkedIn: https://co.linkedin.com/school/universidad-de-los-andes/
- Plans: plans/university-of-los-andes-colombia-plans-pricing.yml
- Rate Limits: rate-limits/university-of-los-andes-colombia-rate-limits.yml
- FinOps: finops/university-of-los-andes-colombia-finops.yml
- Review: review.yml

## Notes

- No dedicated public developer portal or documented open API program was found.
- The "Seneca" DSpace repository (OAI-PMH and REST) is documented via the ROAR registry and the university library, but its endpoints returned HTTP 403 to automated agents during review; verify access (browser-like user agent or library coordination) before integration.
- MiBanner (Ellucian Banner SIS) is authentication-gated with no public API documentation.
- The github.com/uniandes organization exists but exposes no public repositories and its official status is unconfirmed, so it was not cataloged as a common GitHub property.
- No endpoints were fabricated; only publicly documented paths are listed.

## Maintainers

- Kin Lane — kin@apievangelist.com
