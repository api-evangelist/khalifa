# Khalifa University

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

Khalifa University of Science and Technology is a research-intensive public university in Abu Dhabi, United Arab Emirates (ROR 05hffr360), formed from the 2017 merger of KUSTAR, the Masdar Institute and the Petroleum Institute. Its programmable footprint is small, real, and almost entirely indirect. Two surfaces are genuinely institution-operated: an OAI-PMH 2.0 endpoint for the Khazna research portal at khazna.ku.ac.ae/ws/oai, live and anonymous with an institution admin contact, and the university's own Microsoft Entra ID tenant for the ku.ac.ae namespace, which issues OpenID Connect and SAML 2.0 for institution systems. A third, partial surface is the WordPress REST API on www.ku.ac.ae, whose discovery root and a handful of routes answer publicly while the core collections are closed with HTTP 401. Everything else a search turns up is a vendor contract running under the university's name: Khazna itself is an Elsevier Pure tenant (khazna.ku.ac.ae CNAMEs to khalifauniversity.elsevierpure.com) and Elsevier's own Pure API spec is served from that host; the LMS is a Blackboard Learn tenant behind elearn.ku.ac.ae; discovery is Ex Libris Primo VE; the library web presence, calendar and ask-a-librarian service are Springshare; off-campus access is OCLC EZproxy. Those relationships are recorded here as tenancies. None of their contracts are catalogued as Khalifa's. There is no central developer portal, no published API program, no open-data portal, and no institution-operated API reference.

**Areas:** University · Higher Education · Education · Research · Research Data · Research Repository · Identity Federation · OAI-PMH · Robotics · United Arab Emirates · Abu Dhabi

## Khalifa University on APIs.io

Everything profiled for Khalifa University is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/khalifa/](https://apis.io/providers/khalifa/)** — or go straight to one of the APIs or properties below.

### APIs (10)

- [Khalifa University Identity Federation (Microsoft Entra ID)](https://apis.io/apis/khalifa/entra-identity-federation/) — Khalifa University operates its own Microsoft Entra ID tenant for the ku.ac.ae namespace — tenant id 08fe1c0a-19f5-4f24-a662-fdd5dd460025, getuserrealm.srf…
- [Khalifa University Website (WordPress REST)](https://apis.io/apis/khalifa/ku-ac-ae-website-wordpress-rest/) — The public WordPress REST API (wp-json) of the Khalifa University website at www.ku.ac.ae: the route index of the site's content management system,…
- [Khazna Research Portal (Elsevier Pure tenant)](https://apis.io/apis/khalifa/khazna-pure/) — Khalifa University's CRIS and research portal, Khazna, is an Elsevier Pure tenancy: khazna.ku.ac.ae is a CNAME to khalifauniversity.elsevierpure.com, which…
- [Blackboard Learn (khalifauni tenant)](https://apis.io/apis/khalifa/blackboard-learn/) — Khalifa University's learning management system is an Anthology Blackboard Learn SaaS tenancy named "khalifauni". elearn.ku.ac.ae is a CNAME to…
- [Library Discovery (Ex Libris Primo VE tenant)](https://apis.io/apis/khalifa/primo-discovery/) — Library discovery runs on an Ex Libris Primo VE tenancy at khalifa.primo.exlibrisgroup.com with view id 971KUOSTAR_INST:KU — the institution code still…
- [Library Web, Calendar and Reference (Springshare tenant)](https://apis.io/apis/khalifa/springshare/) — Three Springshare tenancies serve the Khalifa University library. library.ku.ac.ae is a CNAME to region-us.libguides.com (LibGuides; page title "Library…
- [Off-Campus Access (OCLC EZproxy tenant)](https://apis.io/apis/khalifa/ezproxy/) — Off-campus access to licensed library resources runs on an OCLC EZproxy tenancy under the named account khalifa.idm.oclc.org (HTTP 200 on /login, probed…
- [ROR Registration](https://apis.io/apis/khalifa/ror/) — Khalifa University of Science and Technology is registered in the Research Organization Registry as https://ror.org/05hffr360, with the alternate names…
- [KUCARS Open-Source Robotics Research (GitHub)](https://apis.io/apis/khalifa/kucars/) — Public open-source repositories from the Khalifa University Center for Autonomous Robotic Systems (KUCARS) — 71 public repos covering coverage path…
- [Khalifa University Oai Pmh API](https://apis.io/apis/khalifa/khalifa-oai-pmh-api/) — OAI-PMH 2.0 verbs supported by the Khazna repository.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Khalifa Context](https://apis.io/jsonld/khalifa/khalifa-context/)

#### Examples (1)

Example requests and responses.

- [Khalifa Entra Openid Configuration](https://apis.io/examples/khalifa/khalifa-entra-openid-configuration/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Khalifa Authentication](https://apis.io/security/khalifa/khalifa-authentication/)
- [Khalifa Domain Security](https://apis.io/security/khalifa/khalifa-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Khalifa Plans Pricing](https://apis.io/plans/khalifa/khalifa-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Khalifa Rate Limits](https://apis.io/rate-limits/khalifa/khalifa-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Khalifa Finops](https://apis.io/finops/khalifa/khalifa-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.ku.ac.ae)
- [Support](https://www.ku.ac.ae/contact-us)
- [Blog](https://www.ku.ac.ae/news)
- [Terms of service](https://www.ku.ac.ae/disclaimer)
- [Privacy policy](https://www.ku.ac.ae/privacy-policy)
- [GitHub](https://github.com/kucars)

## API Evangelist rating

**Kin Score 25.0** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 48.2 |
| Contract quality | 22.0 |
| Contract governance | 0.0 |
| Operational transparency | 10.5 |
| Developer ergonomics | 35.7 |
| Access clarity | 26.3 |

**Agent readiness 20.1** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | na |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | na |
| Error Semantics | — |
| OpenAPI Examples | documented (partial credit) |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | na |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 24.5** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/khalifa/](https://apis.io/providers/khalifa/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Khalifa University: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/khalifa/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
