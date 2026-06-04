# University of Birmingham (university-of-birmingham)

The University of Birmingham is a public research university in Birmingham, United Kingdom, and a founding member of the Russell Group, ranked #94 in the QS World University Rankings 2025. This repository catalogs the institution's confirmed public developer/API footprint as an [APIs.json](https://apisjson.org) profile. The footprint is limited and decentralized — there is no central developer portal — and is concentrated in library/research-repository OAI-PMH endpoints plus a small open research API.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/university-of-birmingham/refs/heads/main/apis.yml
- Run it with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=university-of-birmingham-api-evangelist&utm_content=repo

## Type

Index / Consumer / 3rd-Party

## Tags

Education, Higher Education, University, United Kingdom, Research, Open Data, Library, OAI-PMH

## APIs

- **UBIRA eData OAI-PMH** — research data repository metadata harvesting. Docs: https://edata.bham.ac.uk/policies.html (base: https://edata.bham.ac.uk/cgi/oai2)
- **UBIRA eTheses OAI-PMH** — electronic theses metadata. Docs: https://etheses.bham.ac.uk/ (base: https://etheses.bham.ac.uk/cgi/oai2)
- **ePapers OAI-PMH** — working papers / grey literature metadata. Docs: https://epapers.bham.ac.uk/ (base: https://epapers.bham.ac.uk/cgi/oai2)
- **English Constructicon API** — open construction grammar research API (JSON). Docs: https://englishconstructicon.bham.ac.uk/database/api/

## Plans / Rate Limits / FinOps

- Plans & Pricing: [plans/university-of-birmingham-plans-pricing.yml](plans/university-of-birmingham-plans-pricing.yml)
- Rate Limits: [rate-limits/university-of-birmingham-rate-limits.yml](rate-limits/university-of-birmingham-rate-limits.yml)
- FinOps: [finops/university-of-birmingham-finops.yml](finops/university-of-birmingham-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://www.birmingham.ac.uk/
- GitHub: https://github.com/University-of-Birmingham (org exists, no public repos)
- LinkedIn: https://www.linkedin.com/school/university-of-birmingham/
- Twitter/X: https://x.com/unibirmingham
- Review: [review.yml](review.yml)

## Notes

All listed endpoints were probed and returned HTTP 200 on 2026-06-03. No endpoints were fabricated. No central developer portal, API key program, or published REST/SIS/course/timetable API was found. Library discovery is powered by Ex Libris Primo (FindIt@Bham) but exposes no documented public API. The OAI-PMH endpoints and the English Constructicon API require no authentication.

## Maintainers

- Kin Lane — kin@apievangelist.com
