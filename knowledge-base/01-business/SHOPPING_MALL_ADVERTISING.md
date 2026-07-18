---
document:
  id: DOC-019
  title: SHOPPING_MALL_ADVERTISING
  version: 0.1.0
  status: Draft
  category: Business
  type: Business Model
  owner: RAE Platform Architecture
  release: v0.2.0 Business
  domain: Retail Media
  ddl: DDL-1
---

# Shopping Mall Advertising

> Retail Media model for shopping centers and multi-tenant commercial complexes.

---

# Executive Summary

Shopping malls are one of the most strategic customer segments for RAE Platform.

Instead of only playing background music, shopping centers can monetize their internal communication infrastructure by offering advertising services to tenants.

RAE Platform provides the technology to manage, schedule, measure and optimize these campaigns.

---

# Vision

Every shopping mall becomes its own Retail Media Network.

Every tenant can purchase advertising.

Every campaign can be measured.

Every announcement becomes valuable business intelligence.

---

# Business Model

Participants

• Shopping Mall Operator

↓

• Tenant

↓

• Advertising Campaign

↓

• Audience

↓

• Analytics

↓

• Billing

---

# Main Actors

## Shopping Mall Administrator

Responsibilities

- Manage tenants
- Define advertising policies
- Approve campaigns
- Monitor performance
- Generate reports

---

## Tenant

Responsibilities

- Create campaigns
- Purchase advertising
- Select locations
- Define schedules
- Monitor results

---

## Marketing Agency

Optional participant.

Can manage campaigns for one or multiple tenants.

---

## System AI

Responsible for:

- Campaign recommendations
- Schedule optimization
- Audience estimation
- Performance analysis
- Content suggestions

---

# Campaign Workflow

```mermaid
flowchart LR

A[Campaign Request]

-->

B[Review]

-->

C[Approval]

-->

D[Scheduling]

-->

E[Broadcast]

-->

F[Analytics]

-->

G[ROI Report]
```

---

# Advertising Inventory

Inventory may include:

- Common areas
- Corridors
- Food courts
- Parking
- Entrances
- Escalators
- Elevators
- Children's areas
- Event spaces

Each inventory item is linked to one or more Audio Zones.

---

# Campaign Configuration

Each campaign defines:

- Tenant
- Budget
- Start date
- End date
- Schedule
- Audio assets
- Target locations
- Priority
- Frequency
- Objectives

---

# Audience Targeting

Campaigns may target:

Entire mall

↓

Specific floor

↓

Specific zone

↓

Nearby stores

↓

Custom areas

The architecture must support geographic segmentation.

---

# Estimated Audience

The platform estimates:

- Daily listeners
- Weekly listeners
- Monthly listeners
- Campaign reach
- Repetition frequency
- Estimated impressions

Values may come from:

- Computer Vision
- Occupancy sensors
- Historical traffic
- Manual estimates
- AI prediction models

---

# Revenue Models

Examples

Flat campaign fee

↓

Subscription

↓

Pay per announcement

↓

Pay per estimated audience

↓

Premium placement

↓

Seasonal packages

↓

Sponsored events

The platform should support multiple billing models simultaneously.

---

# Billing Support

The platform stores:

- Campaign cost
- Campaign duration
- Estimated audience
- Billing status
- Invoice reference
- Payment status

Financial integrations remain optional.

---

# Dashboards

Shopping Mall Executive Dashboard

Displays:

- Active campaigns
- Revenue
- Occupancy
- Campaign calendar
- Estimated audience
- Campaign performance
- Top tenants

---

Tenant Dashboard

Displays:

- Campaign status
- Estimated audience
- Budget consumption
- ROI indicators
- Upcoming campaigns

---

# Artificial Intelligence

AI assists by:

- Suggesting schedules
- Predicting campaign performance
- Improving advertising copy
- Generating promotional music
- Recommending campaign duration
- Detecting low-performing campaigns

---

# Future Integrations

Possible future integrations:

- Digital Signage
- Mobile Apps
- Loyalty Programs
- Parking Systems
- POS Systems
- CRM
- Marketing Automation
- Computer Vision

The platform remains technology-independent.

---

# Success Metrics

Examples

Advertising Revenue

↓

Campaign Delivery

↓

Estimated Audience

↓

Campaign Completion

↓

Tenant Satisfaction

↓

Revenue per Campaign

↓

Revenue per Square Meter

↓

Campaign ROI

---

# Strategic Objective

Enable shopping centers to create and operate their own Retail Media Network without requiring multiple disconnected systems.

---

# Related Documents

- DOC-018 RETAIL_MEDIA
- DOC-020 AUDIO_ADVERTISING_METRICS
- DOC-021 ROI_MODEL

---

# Approval

Status:

Draft (v0.1)

Pending Business Review.
