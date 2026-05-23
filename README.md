# The Estée Lauder Companies

The Estée Lauder Companies Inc. (NYSE: **EL**) is one of the world's leading
manufacturers, marketers and sellers of quality prestige skin care, makeup,
fragrance and hair care products. Founded in 1946 by Estée and Joseph Lauder
and headquartered in New York City, ELC operates a portfolio of more than
20 prestige brands sold in approximately **150 countries and territories**,
employs roughly **57,000 people worldwide**, and reported **~$14.32 billion
in fiscal 2025 net sales**.

ELC is family-controlled by the Lauder family. Current leadership includes
CEO **Stéphane de La Faverie**, Board Chair **William P. Lauder**, and CTO
**Brian Franz**.

This repository is an API Evangelist profile of the company. It documents
ELC's brand portfolio, strategic transformation programs, and AI / cloud
technology partnerships. **ELC does not publish any public developer APIs,
SDKs, OpenAPI specs, or a developer portal.** Its [GitHub organization
`EsteeLauder`](https://github.com/EsteeLauder) exists but contains zero
public repositories. The company's technology surface is expressed entirely
through enterprise partnerships with Microsoft, Adobe, Google Cloud, Shopify,
Accenture, and WPP.

## Brand Portfolio (25)

| Brand | Category |
|---|---|
| AERIN Beauty | Multi-Category |
| Aramis | Fragrance |
| Aveda | Hair Care |
| Balmain Beauty | Multi-Category |
| Bobbi Brown Cosmetics | Makeup |
| Bumble and bumble | Hair Care |
| Clinique | Skin Care |
| Darphin Paris | Skin Care |
| DECIEM | Skin Care / House of Brands |
| Dr.Jart+ | Skin Care |
| Editions de Parfums Frédéric Malle | Fragrance |
| Estée Lauder (flagship) | Multi-Category |
| GLAMGLOW | Skin Care / Treatment |
| Jo Malone London | Fragrance |
| KILIAN PARIS | Fragrance |
| La Mer | Skin Care (Luxury) |
| Lab Series | Skin Care (Men) |
| Le Labo | Fragrance |
| M·A·C | Makeup |
| NIOD | Skin Care |
| Origins | Skin Care |
| Smashbox | Makeup |
| The Ordinary | Skin Care |
| TOM FORD | Fragrance / Beauty |
| Too Faced | Makeup |

Source: [elcompanies.com/en/our-brands](https://www.elcompanies.com/en/our-brands).

## Strategic Transformation

- **Beauty Reimagined** — Strategic vision announced February 2025 to
  restore sustainable sales growth and double-digit adjusted operating
  margins via a leaner, faster, more agile operating model and expanded
  consumer coverage.
- **Profit Recovery and Growth Plan (PRGP)** — Restructuring program
  targeting the upper range of **$0.8–$1.0 billion gross benefits**, with
  estimated restructuring charges of **$1.2–$1.6 billion**. Majority of
  full run-rate benefits expected in fiscal 2027; execution substantially
  complete by year-end.
- **One ELC Operating Model** — Three pillars: One Team (July 2025), One
  Culture (February 2026), One Operating Ecosystem (2026). CEO Stéphane de
  La Faverie, April 2026: *"One ELC operating model is now fully
  established. This unified system will enable faster, more agile and
  efficient operations supporting growth."*

## AI and Technology Partnerships

ELC has no in-house AI/ML API surface. Its generative AI footprint is
delivered through these enterprise partnerships:

| Initiative | Partner | Announced | Stack |
|---|---|---|---|
| AI Innovation Lab | Microsoft | 2024-04-26 | Azure OpenAI Service — marketing chatbot, R&D acceleration, Voice-Enabled Makeup Assistant (VMA) accessibility app |
| ConsumerIQ | Microsoft | 2025-04-29 | Copilot Studio + Azure OpenAI — unified consumer/market/industry insight across 25 brands and 150 countries |
| Generative marketing assets | Adobe | 2025-03-12 | Adobe Firefly Services APIs, Generative Expand, Adobe Experience Manager Assets as Cloud Service. M·A·C is the pilot brand |
| Jo Malone London Scent Advisor | Google Cloud | 2025-12-02 | Google Gemini + Vertex AI — conversational fragrance discovery on JoMalone.com (US/UK) |
| Global commerce platform | Shopify | 2025-10-28 | Unified omnichannel direct-to-consumer stack; first phase Q1 2026; ~50% rollout by calendar year-end 2026 |
| Enterprise Business Services | Accenture | 2026-04-01 | Standardized shared services within the One ELC operating ecosystem |
| Global media partnership | WPP | 2026-04-01 | First-ever unified global media partner replacing decentralized regional structure |

ELC was named to Microsoft's inaugural **"Agents of Change"** list in March
2025 for its work on ConsumerIQ.

## API Surface Assessment

| Surface | Status |
|---|---|
| Public developer portal | None |
| Public OpenAPI / AsyncAPI specs | None |
| Public REST / GraphQL APIs | None |
| SDKs / CLIs | None |
| GitHub public repositories | Zero (`github.com/EsteeLauder` is empty) |
| Status page / changelog / release notes | None public |
| Sandbox / Console | None |
| API Evangelist tier | **Tier 3 — no-apis**; technology surface is vendor-mediated |

## Artifacts in this Repository

| Path | Description |
|---|---|
| [`apis.yml`](./apis.yml) | apis.yml 0.19 index — brand portfolio, AI/tech partnerships, strategic programs, common properties |
| [`vocabulary/estee-lauder-companies-vocabulary.yml`](./vocabulary/estee-lauder-companies-vocabulary.yml) | Domain vocabulary covering corporate facts, brands, programs, AI partnerships, scale metrics |
| [`json-ld/estee-lauder-companies-context.jsonld`](./json-ld/estee-lauder-companies-context.jsonld) | JSON-LD context modelling ELC as `schema:Corporation` with brands, programs, and technology initiatives |

No `openapi/`, `asyncapi/`, `capabilities/`, `rules/`, `json-schema/`,
`examples/`, `plans/`, `rate-limits/`, or `finops/` artifacts are produced
for this repository — there is no API surface to back them, and the
pipeline rule is to avoid empty/placeholder specs.

## Key Sources

- Corporate site: <https://www.elcompanies.com>
- Brand portfolio: <https://www.elcompanies.com/en/our-brands>
- Lauder family / governance: <https://www.elcompanies.com/en/who-we-are/the-lauder-family>
- Investor relations: <https://www.elcompanies.com/en/investors>
- Newsroom: <https://www.elcompanies.com/en/news-and-media/newsroom>
- AI Innovation Lab (Microsoft, 2024-04-26): <https://www.elcompanies.com/en/news-and-media/newsroom/press-releases/2024/04-26-2024>
- ConsumerIQ (Microsoft, 2025-04-29): <https://www.elcompanies.com/en/news-and-media/newsroom/company-features/2025/elc-microsoft-consumer-iq>
- Adobe Firefly (2025-03-12): <https://www.elcompanies.com/en/news-and-media/newsroom/press-releases/2025/03-12-2025-02>
- Shopify (2025-10-28): <https://www.elcompanies.com/en/news-and-media/newsroom/press-releases/2025/10-28-2025-212608571>
- Jo Malone Scent Advisor (Google, 2025-12-02): <https://www.elcompanies.com/en/news-and-media/newsroom/press-releases/2025/12-02-2025-121509645>
- One ELC / PRGP milestone (2026-04-01): <https://www.elcompanies.com/en/news-and-media/newsroom/press-releases/2026/04-01-2026-220015297>

## Maintainer

[Kin Lane](mailto:kin@apievangelist.com) — [API Evangelist](https://apievangelist.com).
