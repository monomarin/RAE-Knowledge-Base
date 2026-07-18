---
document:
  id: DOC-007
  title: DOCUMENT_ID_STANDARD
  version: 0.1.0
  status: Draft
  category: Foundation
  type: Standard
  owner: RAE Platform Architecture
  release: v0.1.0 Foundation
  domain: Foundation
  ddl: DDL-0
---

# Document ID Standard

> Official identification standard for every artifact within the RAE Platform ecosystem.

---

# Executive Summary

Every reusable artifact in RAE Platform shall have a permanent identifier.

Identifiers are immutable.

Names may evolve.

Architectures may evolve.

Technologies may evolve.

Identifiers never change.

This guarantees complete traceability across documentation, software, infrastructure and Artificial Intelligence.

---

# Objectives

The ID Standard exists to:

- Guarantee uniqueness.
- Simplify navigation.
- Enable semantic documentation.
- Improve AI reasoning.
- Create end-to-end traceability.
- Eliminate ambiguity.

---

# Identifier Format

Every identifier follows the same structure.

```

PREFIX-NNNN

```

Examples

```

DOC-0007

MOD-0012

CAP-0025

API-0008

AI-0004

TEN-0102

```

Identifiers are always uppercase.

Numbers are always zero padded.

---

# Foundation Prefixes

| Prefix | Meaning |
|----------|------------------------------|
| DOC | Documentation |
| STD | Standard |
| TPL | Template |
| ADR | Architecture Decision Record |
| DEC | Business Decision |
| RFC | Request For Comments |
| MAN | Manifesto |

---

# Business Prefixes

| Prefix | Meaning |
|----------|------------------------------|
| CAP | Business Capability |
| CMP | Campaign |
| PRM | Promotion |
| PLN | Playlist |
| SCH | Schedule |
| TEN | Tenant |
| STO | Store |
| ZON | Audio Zone |

---

# Product Prefixes

| Prefix | Meaning |
|----------|------------------------------|
| MOD | Functional Module |
| SVC | Service |
| JOB | Background Job |
| FLOW | Workflow |
| CFG | Configuration |

---

# Artificial Intelligence Prefixes

| Prefix | Meaning |
|----------|------------------------------|
| AI | AI Agent |
| MCP | MCP Server |
| TOOL | AI Tool |
| PROMPT | Prompt |
| MEM | AI Memory |
| KB | Knowledge Base |

---

# Integration Prefixes

| Prefix | Meaning |
|----------|------------------------------|
| API | API |
| EVT | Event |
| WEBHOOK | Webhook |
| MSG | Message |

---

# Data Prefixes

| Prefix | Meaning |
|----------|------------------------------|
| DB | Database |
| TAB | Table |
| COL | Column |
| IDX | Index |
| VIEW | View |

---

# UX Prefixes

| Prefix | Meaning |
|----------|------------------------------|
| UX | UX Flow |
| UI | UI Component |
| SCR | Screen |
| DASH | Dashboard |
| WID | Widget |
| NAV | Navigation |

---

# Infrastructure Prefixes

| Prefix | Meaning |
|----------|------------------------------|
| ENV | Environment |
| DEP | Deployment |
| EDGE | Edge Node |
| DEV | Device |
| NET | Network |
| SEC | Security Component |

---

# Analytics Prefixes

| Prefix | Meaning |
|----------|------------------------------|
| KPI | KPI |
| MET | Metric |
| REP | Report |
| ALERT | Alert |
| DIM | Dimension |
| FACT | Fact |

---

# Media Prefixes

| Prefix | Meaning |
|----------|------------------------------|
| AUDIO | Audio Asset |
| VOICE | Voice Asset |
| MUSIC | Music Track |
| IMG | Image |
| VIDEO | Video |
| BRAND | Brand Asset |

---

# Prefix Governance

New prefixes require:

- Architectural Review.
- Approval.
- Registration.
- Documentation Update.

No duplicate meanings are allowed.

---

# Reserved Prefixes

The following prefixes are reserved for future expansion.

```

BOT

RULE

MODEL

VECTOR

EMBED

OCR

VISION

IOT

BLE

POS

ERP

CRM

CMS

```

Reserved prefixes shall not be used until officially approved.

---

# Naming Rules

Identifiers must never include:

- Vendor names.
- Programming languages.
- Cloud providers.
- Temporary names.
- Versions.

Correct

```

MOD-0031

```

Incorrect

```

MOD-MUREKA

API-GPT4

DB-SUPABASE

```

---

# Traceability

Every identifier should be traceable across:

- Documentation
- GitHub
- Source Code
- Database
- APIs
- Dashboards
- Analytics
- AI Context
- Release Notes

---

# Compliance

All future documentation and implementation artifacts must comply with this standard.

Non-compliant identifiers should be rejected during review.

---

# Approval

Status:

Draft (v0.1)

Pending architectural approval.
