---
document:
  id: DOC-105
  title: USER_ROLES
  version: 0.1.0
  status: Draft
  category: Product
  type: Security Model
  owner: RAE Platform Architecture
  release: v0.3.0 Product
  domain: Product
  ddl: DDL-1
---

# User Roles

> Official catalog of user roles within RAE Platform.

---

# Executive Summary

User Roles define the responsibilities, privileges and scope of every actor interacting with RAE Platform.

Roles are independent of permissions.

Permissions are assigned through the Permission Model.

Roles represent business responsibilities.

---

# Design Principles

Roles define responsibilities.

Permissions define actions.

Policies define constraints.

Capabilities define business functions.

---

# Role Hierarchy

Platform

↓

System Roles

↓

Organization Roles

↓

Operational Roles

↓

External Roles

↓

AI Roles

---

# System Roles

## ROLE-001 Platform Owner

Full platform ownership.

Responsibilities

- Platform governance
- Global configuration
- Licensing
- Product configuration

Scope

Global.

---

## ROLE-002 Platform Administrator

Responsible for operating the SaaS platform.

Responsibilities

- Tenant management
- Platform monitoring
- Global maintenance
- Incident management

---

## ROLE-003 Platform Support

Provides technical support.

Responsibilities

- Diagnostics
- User assistance
- Incident analysis

---

# Organization Roles

## ROLE-101 Organization Owner

Highest authority within an organization.

Responsibilities

- Organization settings
- Billing
- Global administration
- Business configuration

---

## ROLE-102 Organization Administrator

Daily administration.

Responsibilities

- Users
- Stores
- Campaigns
- Devices

---

## ROLE-103 Business Manager

Business oversight.

Responsibilities

- KPIs
- Dashboards
- Reports
- Retail Media

---

# Marketing Roles

## ROLE-201 Marketing Manager

Advertising strategy.

Campaign approval.

Content planning.

---

## ROLE-202 Campaign Manager

Campaign execution.

Scheduling.

Performance monitoring.

---

## ROLE-203 Content Manager

Media assets.

Playlists.

Voice assets.

Promotional content.

---

# Operational Roles

## ROLE-301 Operations Manager

Daily operation.

Device monitoring.

Scheduling.

Incident response.

---

## ROLE-302 Store Manager

Store-level administration.

Campaign execution.

Local monitoring.

---

## ROLE-303 Regional Manager

Multiple stores.

Regional KPIs.

Regional campaigns.

---

# Technical Roles

## ROLE-401 Device Technician

Install devices.

Replace equipment.

Maintenance.

Diagnostics.

---

## ROLE-402 Integration Administrator

ERP.

CRM.

POS.

API.

Webhooks.

---

# Analytics Roles

## ROLE-501 Business Analyst

Business Intelligence.

KPIs.

Dashboards.

Reports.

---

## ROLE-502 Data Analyst

Data exploration.

Forecasting.

Predictive analytics.

---

# Retail Media Roles

## ROLE-601 Media Sales Manager

Advertising sales.

Tenant relationships.

Campaign proposals.

---

## ROLE-602 Tenant Advertiser

Creates campaigns for a tenant.

Views campaign performance.

---

## ROLE-603 Agency Operator

Manages campaigns on behalf of clients.

Supports multiple organizations.

---

# External Roles

## ROLE-701 Auditor

Read-only access.

Compliance.

Audit logs.

Reports.

---

## ROLE-702 Guest

Restricted temporary access.

---

# Artificial Intelligence Roles

## ROLE-801 AI Assistant

Provides recommendations.

Answers questions.

Guides users.

---

## ROLE-802 AI Operator

Executes approved automations.

Generates content.

Optimizes campaigns.

Always operates under human governance.

---

## ROLE-803 AI Supervisor

Coordinates AI Agents.

Assigns tasks.

Validates AI workflows.

---

# Future Roles

The architecture allows unlimited future roles.

Role identifiers remain stable.

---

# Role Metadata

Each role should eventually include:

- Role ID
- Name
- Description
- Scope
- Responsibilities
- Related Permissions
- Related Capabilities
- Related Features
- Security Level
- Default Policies
- Delegation Rules

---

# Success Criteria

The role model is successful when:

- Every user belongs to at least one role.
- Roles remain business-oriented.
- Permissions remain independent.
- Roles support enterprise governance.
- AI agents integrate naturally.

---

# Related Documents

DOC-106 PERMISSION_MODEL

DOC-107 TENANT_MODEL

DOC-103 CAPABILITY_CATALOG

DOC-104 FEATURE_CATALOG

---

# Approval

Status:

Draft (v0.1)

Pending Security Review.
