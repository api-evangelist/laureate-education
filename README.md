# laureate-education

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
