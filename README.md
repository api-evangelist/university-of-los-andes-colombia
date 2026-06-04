# University of Los Andes Colombia (university-of-los-andes-colombia)

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
