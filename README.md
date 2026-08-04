# laureate-education

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

Profile for **Laureate Education, Inc.** in the API Evangelist network.
Fortune F1000 (rank 666).

Laureate is a for-profit higher-education holding company founded in 1989 as
Sylvan Learning Systems and renamed Laureate Education in May 2004. Once the
world's largest international university network — more than 200 campuses
across 28 countries serving over one million students at its 2017 NASDAQ IPO
(ticker `LAUR`) — Laureate executed a multi-year divestiture program between
2018 and 2021, exiting roughly two dozen countries and returning $1.29 billion
in cash to shareholders. In **May 2024 an investor group led by the
International Finance Corporation (IFC) and Sterling Capital acquired Laureate
Education, taking the company private** and delisting it from NASDAQ. The
remaining operating footprint is a pure-play Mexico + Peru network of five
institutions serving approximately 460,000 students from headquarters at
1000 Brickell Ave, Miami.

## Why this profile exists

Laureate Education **publishes no public developer API** — there is no
OpenAPI specification, SDK, CLI, webhook surface, sandbox, status page,
changelog, or GitHub organization. This repository therefore documents the
**corporate surface** of the company (institutional network, leadership,
divestiture history, take-private transaction) so the API Evangelist
network has a complete entry for this Fortune-1000 (rank 666) education
operator even though there is nothing programmable to profile.

The detailed corporate history — including event-level timelines for the
1999–2021 acquisition cycle, the 2018–2021 divestiture cycle, and the
2024 IFC / Sterling take-private — lives inline in `apis.yml` under the
`x-corporate-history` and `x-divestiture-summary` extensions.

## Current operating footprint

| Country | Institution | Notes |
|---|---|---|
| Mexico | Universidad del Valle de México (UVM) | 22+ campuses, 180+ programs, founded 1960 |
| Mexico | Universidad Tecnológica de México (UNITEC) | 13 campuses, QS 5-star (2025), FIMPES Lisa y Llana |
| Peru | Universidad Peruana de Ciencias Aplicadas (UPC) | First Peruvian university with QS 5-star; WSCUC accredited |
| Peru | Universidad Privada del Norte (UPN) | Multi-campus regional network |
| Peru | Cibertec | Technical / professional institute |

Total: **~460,000 students across 50+ campuses** (250,000+ in Mexico
across 30+ campuses; 210,000+ in Peru across 20 campuses).

## Divestiture summary (2016–2021)

Geographies exited during the strategic-review cycle:

- **2016** — Switzerland (Glion, Les Roches → Eurazeo, $384.9M)
- **2018** — Morocco, Italy, Malaysia, China, Cyprus, Kendall College (US)
- **2019** — Turkey (Istanbul Bilgi), Spain (UE Madrid/Valencia/Canarias),
  Portugal (Universidade Europeia, IPAM), University of St Augustine for
  Health Sciences (US), Santa Fe University of Art and Design (US)
- **2020** — Australia + New Zealand → Strategic Education; Chile
  (Universidad Andrés Bello + Chilean assets → Fundación Educación y
  Cultura, 11 Sept 2020); UK wind-down (Liverpool, Roehampton)
- **2021** — Brazil (11 institutions → Ânima Holding, ~$765M, May 2021);
  Walden University → Adtalem ($1.48B, August 2021)
- **October 2021** — $1.29 billion cash distribution to shareholders

## Ownership

- **1989–2007** — Sylvan / Laureate; public
- **2007–2017** — Private (investor group led by Doug Becker)
- **2017–2024** — Public on NASDAQ as `LAUR` (B Corporation)
- **May 2024–present** — Private; owned by investor group led by IFC and
  Sterling Capital

## Leadership (current)

- Eilif Serck-Hanssen — President & CEO
- Marcelo Cardoso — EVP & COO
- Rick Buskirk — SVP & CFO
- Leslie Brush — SVP, Chief Legal Officer & Secretary
- Martin N. Fienkeng — CIO & CISO
- Alejandro Gallo — CEO, Laureate Mexico
- Álvaro Ramos — CEO, Laureate Peru

## Repository contents

| File | Purpose |
|---|---|
| `apis.yml` | API Evangelist index — corporate surface, member institutions, full divestiture timeline, leadership references |
| `README.md` | This file |

No `openapi/`, `asyncapi/`, `json-schema/`, `capabilities/`, `examples/`,
`rules/`, `plans/`, `rate-limits/`, or `finops/` artifacts are present
because Laureate exposes no public API surface that would back them. The
pipeline correctly skipped artifact generation rather than produce empty
placeholders.

## Notable absences

- No public REST / GraphQL / webhook API
- No OpenAPI or AsyncAPI specification
- No SDK, CLI, or sandbox
- No GitHub organization
- No status page, changelog, or release notes
- No public developer pricing (consumer tuition is institution-by-institution)

## Network entry

- **GitHub:** <https://github.com/api-evangelist/laureate-education>
- **x-type:** company
- **Master registry:** `api-evangelist-network/apis.yml` (`x-profiled: 2026-05`)
