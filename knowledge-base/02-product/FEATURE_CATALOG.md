---
document:
  id: DOC-104
  title: FEATURE_CATALOG
  version: 0.1.0
  status: Draft
  category: Product
  type: Product Catalog
  owner: RAE Platform Architecture
  release: v0.3.0 Product
  domain: Product
  ddl: DDL-1
---

# Feature Catalog

> Official catalog of user-facing features available in RAE Platform.

---

# Executive Summary

A Feature is a user-visible functionality that enables interaction with one or more business capabilities.

Features are built on top of capabilities and exposed through web, mobile or API interfaces.

Every feature must belong to a single capability, while a capability may support multiple features.

---

# Feature Hierarchy

Platform

↓

Domain

↓

Module

↓

Capability

↓

Feature

↓

Component

↓

Screen

---

# Feature Principles

Every feature:

- Has one primary purpose.
- Belongs to one capability.
- Can be versioned.
- Can be enabled or disabled.
- Supports permissions.
- Generates audit events.
- Produces telemetry.
- Can be documented independently.

---

# DOM-001 Core Platform

## FEAT-001 Login

Users authenticate using supported identity providers.

---

## FEAT-002 User Profile

View and update personal information.

---

## FEAT-003 Organization Switcher

Switch between organizations or tenants.

---

## FEAT-004 User Management

Create, edit, suspend and delete users.

---

## FEAT-005 Role Assignment

Assign roles and permissions.

---

## FEAT-006 Audit Viewer

Browse audit events and security logs.

---

# DOM-002 Audio Management

## FEAT-101 Playlist Editor

Create and manage playlists.

---

## FEAT-102 Smart Scheduler

Schedule playlists using calendars and rules.

---

## FEAT-103 Audio Library Browser

Browse and organize audio assets.

---

## FEAT-104 Zone Manager

Assign playlists to locations and zones.

---

## FEAT-105 Device Dashboard

Monitor and manage playback devices.

---

## FEAT-106 Live Playback Monitor

View real-time playback status.

---

# DOM-003 Retail Media

## FEAT-201 Campaign Builder

Create advertising campaigns.

---

## FEAT-202 Campaign Calendar

Visualize campaign schedules.

---

## FEAT-203 Media Inventory Manager

Manage advertising inventory.

---

## FEAT-204 Audience Dashboard

View audience estimations and analytics.

---

## FEAT-205 Billing Center

Manage advertising billing and invoices.

---

## FEAT-206 Campaign Performance Dashboard

Analyze campaign effectiveness.

---

# DOM-004 Artificial Intelligence

## FEAT-301 AI Campaign Generator

Generate campaigns with AI assistance.

---

## FEAT-302 AI Copy Assistant

Create promotional copy.

---

## FEAT-303 AI Music Composer

Generate music using supported providers.

---

## FEAT-304 AI Voice Studio

Generate voice announcements.

---

## FEAT-305 AI Recommendation Center

Receive operational recommendations.

---

## FEAT-306 AI Knowledge Assistant

Ask questions about the platform and documentation.

---

# DOM-005 Analytics

## FEAT-401 Executive Dashboard

Executive KPIs and business overview.

---

## FEAT-402 Operational Dashboard

Operational metrics and system health.

---

## FEAT-403 Predictive Analytics Dashboard

Forecast trends and recommendations.

---

## FEAT-404 Custom Report Builder

Build custom reports.

---

## FEAT-405 Real-Time Monitoring Dashboard

Monitor live events and alerts.

---

# DOM-006 Integration

## FEAT-501 API Explorer

Browse available APIs.

---

## FEAT-502 Webhook Manager

Configure webhook subscriptions.

---

## FEAT-503 Integration Center

Manage third-party integrations.

---

# DOM-007 Marketplace

## FEAT-601 Plugin Store

Browse and install plugins.

---

## FEAT-602 AI Agent Store

Install and configure AI agents.

---

## FEAT-603 Template Library

Browse templates for campaigns, playlists and workflows.

---

# Feature Metadata

Each feature should eventually include:

- Feature ID
- Name
- Description
- Domain
- Module
- Capability
- User Roles
- Required Permissions
- Related Screens
- APIs
- Events
- AI Support
- Dependencies
- Status
- Release Version

---

# Feature Lifecycle

Draft

↓

Review

↓

Development

↓

Testing

↓

Released

↓

Deprecated

↓

Archived

---

# Success Criteria

The catalog is successful when:

- Every user-facing functionality is documented.
- Features are traceable to capabilities.
- Features support governance and lifecycle management.
- Duplicate functionality is avoided.
- AI agents can identify and consume features consistently.

---

# Related Documents

DOC-102 MODULE_CATALOG

DOC-103 CAPABILITY_CATALOG

DOC-105 USER_ROLES

DOC-106 PERMISSION_MODEL

DOC-117 DASHBOARD_CATALOG

---

# Approval

Status:

Draft (v0.1)

Pending Product Review. Lo que acabamos de consolidar

Con este documento, la estructura oficial de RAE Platform queda definida de forma completa: Platform
│
├── Domain (DOM)
│
├── Module (MOD)
│
├── Capability (CAP)
│
├── Feature (FEAT)
│
├── Component (CMP)
│
└── Screen (SCR)
