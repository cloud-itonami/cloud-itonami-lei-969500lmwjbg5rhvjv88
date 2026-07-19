# cloud-itonami-lei-969500lmwjbg5rhvjv88

> **Independent third-party archive/analysis. Not affiliated with, endorsed by, or sponsored by Transdev Group SA.**

This repository archives the publicly published Terms and Conditions of Use of
**Transdev Group SA**, with source-url and retrieval-date provenance, per
[ADR-2607110300](https://github.com/com-junkawasaki/root/blob/main/90-docs/adr/2607110300-cloud-itonami-lei-corporate-tos-catalog.edn)
(`cloud-itonami-lei-corporate-tos-catalog`, `com-junkawasaki/root`). It is a read-only
reference/archive repository — it does not act, propose, or execute anything on the
company's behalf, and is not a governed Advisor/Governor actor.

## Company identity

- **Legal name**: Transdev Group SA
- **LEI (ISO 17442)**: [969500LMWJBG5RHVJV88](https://search.gleif.org/#/record/969500LMWJBG5RHVJV88) (GLEIF-verified, status ACTIVE, registration ISSUED)
- **Jurisdiction**: FR (France)
- **Website**: https://www.transdev.com
- **Ticker**: unlisted (majority owned by Caisse des Dépôts + Rethmann)

## Contents

- `80-data/public/tos.journal.edn` — EDN quad-log of archived Terms and Conditions of Use documents.
- `NOTICE` — copyright/attribution statement for the archived third-party text.
- `blueprint.edn` — machine-readable company identity record.

## Related cloud-itonami blueprint (passenger-road-transport vertical)

Transdev Group operates urban and suburban public-transit contracts (bus, tram,
light rail, paratransit) for municipal transit authorities across many countries.
This vertical's *generic, forkable* Open Business Blueprint counterpart in the
`cloud-itonami` fleet is
[`cloud-itonami-isic-4921`](https://github.com/cloud-itonami/cloud-itonami-isic-4921)
(ISIC 4921/4922 sibling pair — urban/suburban vs. intercity/chartered coach
scheduling-and-dispatch coordination, Advisor⊣Governor actor pattern). This
LEI-catalog entry is a **read-only ToS reference only** — it is not a fork of, and
has no code dependency on, isic-4921; the cross-reference exists so a reader
researching real-world urban-transit operators for market/competitive context can
find both the real company's published terms and the corresponding generic
governed-actor blueprint from one place. isic-4921's own `docs/business-model.md`
cites this catalog entry as a real-company reference point in its urban/suburban
transit landscape notes.

## Design rationale

See ADR-2607110300 in `com-junkawasaki/root` (`90-docs/adr/`).
