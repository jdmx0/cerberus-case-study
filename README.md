# Cerberus — OSINT Intelligence Pipeline
### Case Study

---

## Overview

Cerberus is an AI-assisted open-source intelligence (OSINT) and cyber threat intelligence (CTI) workflow designed to collect, enrich, validate, and structure open-source reporting into analyst-ready intelligence products. The pipeline aggregates information from public news feeds, government statements, aviation and maritime open data, and social-source monitoring into a structured daily intelligence brief covering seven global theaters: APAC, Latin America, the Wider Middle East, Iran, Israel/Palestine, Russia/Ukraine, and the United States.

---

## Problem

Open-source intelligence is high-volume, fragmented, and uneven in reliability. Without a structured pipeline, analysts spend the majority of their time on collection, deduplication, and source validation — reducing the time available for actual analysis. Cerberus addresses this by automating collection, normalization, enrichment, and initial structuring, and by applying a defined analytical framework to every output cycle.

---

## My Role

I designed Cerberus end-to-end: the intelligence collection concept, theater coverage framework, source evaluation approach, analyst output structure, confidence discipline methodology, and cycle-over-cycle forecast review system. I built and tested automation components at a high level, integrating AI-assisted analysis into a structured daily production cycle.

---

## Core Capabilities

- Open-source feed collection and normalization across public news, government statements, social-source monitoring, and open data feeds
- Event enrichment, deduplication, and theater tagging
- Source validation and confidence tracking using a defined source-grade framework (A–E)
- Media analysis — imagery and video content reviewed and annotated before brief compilation
- CTI/OSINT context enrichment for active geopolitical events
- Structured analyst brief generation in CerberusSOP format
- Indicator-Based Warning (IBW) with falsifiable conditions, time windows, and explicit invalidation criteria
- Cycle-over-cycle forecast review: HIT / PARTIAL / NO HIT / STALE / INVALIDATED / OPEN
- Structured outputs: PDF, Notion, and mobile notification summary

---

## High-Level Workflow

```
Sources → Collection → Enrichment → Validation → Analyst Brief → Review
```

| Stage | Description |
|---|---|
| **Sources** | Public news feeds, government statements, aviation/maritime open data, social-source monitoring |
| **Collection** | Automated aggregation into normalized format with theater tagging and source attribution |
| **Enrichment** | Media analysis, embedded URL follow-up, live OSINT augmentation via web search |
| **Validation** | Source-grade assessment (A–E), confidence-tier assignment, deduplication, corroboration check |
| **Analyst Brief** | BLUF, theater sections, cross-theater nexus analysis, IBW, forecast tracking |
| **Review** | Cycle-over-cycle forecast review with formal HIT/PARTIAL/NO HIT/OPEN assessment |

---

## Representative Brief Sample

**Brief Date:** May 4, 2026 | **Collection Window:** 24–48 hours | **Theaters Covered:** All seven

> Source attributions have been generalized to source category. Analytic content is drawn from publicly available open-source reporting.

### BLUF

The dominant strategic development of this cycle was the functional collapse of the US-Iran ceasefire. Iran's IRGC Navy executed a multi-vector attack package against US Navy assets in the Strait of Hormuz and UAE energy infrastructure simultaneously — including anti-ship cruise missiles, rocket fire, drone strikes on the Fujairah Oil Industry Zone, and commercial vessel targeting. US CENTCOM responded by destroying six IRGC fast boats. A senior US admiral declined to formally declare the ceasefire void, assessed as deliberate strategic ambiguity ahead of a scheduled senior defense leadership press conference. A secondary theater of critical concern was Mali, where JNIM and allied forces executed the largest coordinated offensive since 2012 — killing the Defense Minister and blocking multiple supply routes into Bamako.

### Key Judgments

1. The April 8 ceasefire is assessed as **functionally inoperative**. Iran's simultaneous targeting of US Navy assets and UAE energy infrastructure exceeds the threshold of gray-zone harassment.
2. UAE use of an Israeli-deployed air defense system to intercept Iranian missiles constitutes the **first operationally confirmed Israel-UAE air defense integration in live combat**.
3. UAE threats of independent retaliation represent an **emergent escalation calculus** assessed as the most underappreciated risk factor in the current cycle.
4. JNIM's Mali offensive has materially degraded the junta's security rationale. Government collapse assessed as high-probability if remaining Bamako supply routes closed within 72 hours.
5. US Treasury pressure on Beijing combined with yuan adoption across Iranian and Russian transactions indicates an **accelerating geoeconomic dimension** to the Hormuz crisis.

### Indicators and Watch Items

| Forecast ID | Indicator | Window | Invalidation |
|---|---|---|---|
| IRAN-20260504-01 | Additional Gulf NOTAMs + IRGC vessel surge → follow-on strike preparation | 72 hrs | 72 hrs normal transit, no IRGC activity |
| ISRAEL-20260504-01 | IDF staging in northern Israel + ceasefire cancellation → ground offensive | 7 days | Renewed ceasefire with verified pullback |
| SAHEL-20260504-01 | JNIM second assault on Kati → attempt to seize armed forces command infrastructure | 72 hrs | Confirmed JNIM ceasefire overture |
| UKR-20260504-01 | Modified loitering munition confirmed operational → fielded anti-drone UAS capability | 14 days | No further confirmed employment |
| DOMESTIC-20260504-01 | Formal ceasefire void declaration → resumption of US kinetic operations | 48 hrs | Announced ceasefire extension |

### Confidence Language

Probability tiers used: **Very Low (0–10%) / Low / Plausible / Even Chance / Likely / Very Likely / Near Certain (85%+)**. Tier assignments checked against capability, intent, opportunity, cost tolerance, and availability of lower-cost alternatives before assignment.

### Why It Mattered

The May 4 brief captured a multi-theater escalation event at the moment it was unfolding — before most mainstream analysis had connected the Hormuz kinetic activity, the UAE-Israel air defense convergence, and the Mali offensive into a unified strategic picture. Cross-theater nexus analysis identified that simultaneous US Hormuz focus and European NATO distraction was creating a strategic attention deficit for Sahel counterterrorism — a linkage absent from single-theater reporting. Indicator-based warnings issued in this cycle were structured to be falsifiable and reviewable in subsequent brief cycles.

---

## What This Demonstrates

| Skill | Application |
|---|---|
| OSINT collection design | Multi-source collection architecture across public news, government sources, social monitoring, and open data |
| CTI enrichment | Threat actor tracking, capability assessment, and intent analysis across seven global theaters |
| Source validation | Defined A–E source-grade framework with explicit confidence assignment and single-source flagging |
| Structured analytic writing | BLUF-first, evidence-grounded products in a defined intelligence format |
| Confidence discipline | Probability tier language with explicit pre-assignment checks |
| Indicator-Based Warning | Falsifiable warnings with time windows, primary/secondary indicators, and invalidation criteria |
| Forecast tracking | Cycle-over-cycle review with formal HIT/PARTIAL/NO HIT/OPEN assessment |
| Workflow automation | Consistent collection-to-delivery pipeline across daily production cycles |
| Risk reporting | Cross-theater nexus analysis connecting first-order events to second-order strategic implications |
| AI-assisted analysis governance | Deliberate structure separating AI augmentation from analyst judgment |

---

## Security and Disclosure Note

This public case study is intentionally sanitized to demonstrate workflow design, analytical methodology, and output quality without disclosing the full technical implementation, source registry, infrastructure, credentials, internal prompts, or operational workflows.

---

## Current Status

Active personal intelligence tooling project. Daily briefs produced on a recurring schedule covering all seven monitored theaters.

---

## Future Improvements

- Stronger source reliability scoring with automatic grade adjustment based on historical track record
- Quantified forecast accuracy metrics
- Expanded geospatial output support for location-tagged events
- Dashboard-based analyst review workflow for indicator tracking across cycles
- More robust human-in-the-loop validation checkpoints
