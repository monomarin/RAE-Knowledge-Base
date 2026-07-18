---
document:
  id: DOC-108
  title: ORGANIZATION_HIERARCHY
  version: 0.1.0
  status: Draft
  category: Product
  type: Organization Model
  owner: RAE Platform Architecture
  release: v0.3.0 Product
  domain: Core Platform
  ddl: DDL-1
---

# Organization Hierarchy

> Official organizational hierarchy model for RAE Platform.

---

# Executive Summary

The Organization Hierarchy defines how companies structure their operations inside RAE Platform.

The hierarchy provides a common model that supports organizations of every size while remaining flexible enough to represent different industries.

---

# Design Principles

The hierarchy must be:

- Flexible
- Scalable
- Vendor Independent
- Industry Agnostic
- AI Ready
- Multi-Tenant
- Enterprise Ready

---

# Organizational Structure

```text
Platform

↓

Tenant

↓

Organization

↓

Business Unit

↓

Division

↓

Region

↓

Area

↓

Location

↓

Building

↓

Floor

↓

Zone

↓

Device
```

Each level is optional except Tenant and Location.

---

# Hierarchy Levels

## Tenant

Independent customer.

---

## Organization

Legal entity or company.

---

## Business Unit

Independent business operation.

Examples:

Retail

Wholesale

Distribution

E-Commerce

---

## Division

Functional organization.

Examples:

Marketing

Operations

Sales

Technology

Finance

---

## Region

Geographical grouping.

Examples:

North

South

East

West

Country

State

Province

---

## Area

Operational grouping.

Examples:

District

City Cluster

Commercial Zone

---

## Location

Physical establishment.

Examples:

Store

Shopping Mall

Hotel

Restaurant

Hospital

Airport

University

Warehouse

---

## Building

Optional level.

Useful for:

Hospitals

Universities

Corporate campuses

Airports

---

## Floor

Optional level.

Supports multi-floor locations.

---

## Zone

Audio or operational area.

Examples:

Food Court

Entrance

Electronics

Parking

Reception

Lobby

Emergency Area

---

## Device

Playback endpoint.

Examples:

Player

Speaker Controller

Edge Node

Gateway

---

# Organizational Relationships

Every node has:

- Parent
- Children
- Metadata
- Policies
- Permissions
- Analytics
- AI Context

---

# Metadata

Every organizational node includes:

- Identifier
- Name
- Type
- Description
- Status
- Time Zone
- Language
- Currency
- Coordinates
- Tags

---

# Inheritance

Configuration inherits downward by default.

Examples:

Branding

↓

Roles

↓

Permission Profiles

↓

Campaign Policies

↓

Notification Policies

↓

AI Policies

Children may override inherited settings where allowed.

---

# Organizational Scope

Resources may belong to any hierarchy level.

Examples:

Campaign

↓

Region

↓

Playlist

↓

Store

↓

Dashboard

↓

Business Unit

↓

AI Agent

↓

Organization

---

# Search Model

Every hierarchy node is searchable by:

- ID
- Name
- Type
- Parent
- Tags
- Metadata
- Geographic Location

---

# Future Extensions

Possible future levels:

Country Group

Franchise

Campus

Terminal

Department

Section

Warehouse Zone

The hierarchy must remain extensible.

---

# Success Criteria

The hierarchy is successful when:

- Supports organizations of every size.
- Requires no redesign for future industries.
- Integrates naturally with permissions.
- Supports AI context.
- Enables enterprise analytics.

---

# Related Documents

DOC-107 TENANT_MODEL

DOC-109 LOCATION_MODEL

DOC-110 AUDIO_ZONE_MODEL

DOC-106 PERMISSION_MODEL

---

# Approval

Status:

Draft (v0.1)

Pending Product Architecture Review.
