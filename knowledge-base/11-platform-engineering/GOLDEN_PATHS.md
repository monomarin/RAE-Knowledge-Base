---
document:
  id: DOC-204
  title: GOLDEN_PATHS
  version: 2.0.0
  status: Draft
  category: Platform Engineering
  type: Developer Experience Standard
  owner: Platform Engineering Team
  release: v1.1.0 Platform Engineering & Developer Experience
  domain: Developer Experience
  ddl: DDL-1
---

# Enterprise Golden Paths

> Official Golden Paths for RAE Platform.

---

# Executive Summary

Golden Paths are standardized engineering workflows that define the recommended way to build software within RAE Platform.

Instead of starting from scratch, developers begin from pre-approved templates, automated pipelines and architectural guardrails.

Golden Paths encode enterprise knowledge into repeatable engineering workflows.

---

# Vision

Allow every engineer to build production-ready software using secure, scalable and fully governed workflows from day one.

---

# Strategic Objectives

- Standardize Development
- Accelerate Delivery
- Reduce Cognitive Load
- Improve Developer Experience
- Enforce Architecture
- Increase Automation
- Improve Security
- Enable AI-Assisted Development

---

# Golden Path Principles

Every Golden Path shall be:

- Opinionated
- Automated
- Secure by Default
- Observable
- Documented
- Repeatable
- Self-Service
- Continuously Improved

---

# Supported Golden Paths

The platform officially supports:

- Microservices
- REST APIs
- gRPC Services
- AI Agents
- Event Producers
- Event Consumers
- Background Workers
- Scheduled Jobs
- Frontend Applications
- Infrastructure Modules
- Kubernetes Services
- Terraform Projects
- GitHub Actions
- Shared Libraries

---

# Microservice Golden Path

Includes:

- Repository Creation
- Template Generation
- CI/CD Pipeline
- Dockerfile
- Kubernetes Manifests
- Health Checks
- Metrics
- Logging
- Tracing
- Security Policies
- Documentation
- ADR Template

Deployment should require minimal manual configuration.

---

# API Golden Path

Every API includes:

- OpenAPI Specification
- Authentication
- Authorization
- Rate Limiting
- Versioning
- Error Standards
- SDK Generation
- Documentation
- Monitoring

---

# AI Agent Golden Path

Every AI Agent includes:

- Prompt Registry
- Model Abstraction
- Evaluation Pipeline
- Guardrails
- RAG Integration
- Knowledge Sources
- AI Memory
- Human Approval Rules
- Monitoring
- Cost Tracking

---

# Event-Driven Golden Path

Provides:

- Event Schema
- Publisher Template
- Consumer Template
- Retry Policies
- Dead Letter Queue
- Idempotency
- Event Documentation
- Observability

---

# Frontend Golden Path

Includes:

- Next.js Template
- Design System
- Authentication
- API SDK
- Accessibility
- Responsive Layout
- Performance Budget
- Testing
- Monitoring

---

# Infrastructure Golden Path

Infrastructure templates include:

- Terraform
- Kubernetes
- Secrets
- Networking
- IAM
- Monitoring
- Alerts
- Backup
- Disaster Recovery

Infrastructure follows Infrastructure as Code principles.

---

# CI/CD Golden Path

Pipeline stages:

Source

↓

Static Analysis

↓

Unit Tests

↓

Security Scan

↓

Build

↓

Integration Tests

↓

Container Scan

↓

Deployment

↓

Smoke Tests

↓

Production Approval

↓

Release

---

# Observability Golden Path

Every workload includes:

- Metrics
- Logs
- Traces
- Dashboards
- Alerts
- SLOs
- Health Checks

No production deployment is allowed without observability.

---

# Documentation Golden Path

Every project generates:

- README
- ADR
- Runbook
- API Documentation
- Architecture Diagram
- Deployment Guide
- Troubleshooting Guide

Documentation is generated automatically whenever possible.

---

# AI-Assisted Development

AI supports:

- Project Scaffolding
- Code Generation
- Documentation
- Test Generation
- Architecture Validation
- Security Review
- Dependency Analysis

Generated artifacts require human review.

---

# Governance

Platform Engineering owns:

- Templates
- Automation
- Standards
- Documentation
- Versioning
- Developer Feedback

---

# Continuous Improvement

Golden Paths evolve through:

Developer Feedback

↓

Metrics

↓

Platform Analytics

↓

Architecture Review

↓

Template Updates

↓

Release

---

# Operational Metrics (KPIs)

Monitor:

- Golden Path Adoption
- Deployment Success Rate
- Developer Onboarding Time
- Lead Time for Changes
- Platform Satisfaction
- Automation Coverage
- Security Compliance
- Documentation Completeness

---

# Risks

- Template Drift
- Outdated Standards
- Low Adoption
- Excessive Customization
- Automation Failures

---

# Dependencies

- DOC-201 INTERNAL_DEVELOPER_PLATFORM
- DOC-202 DEVELOPER_PORTAL
- DOC-203 SERVICE_CATALOG
- DOC-205 ENGINEERING_SCORECARDS

---

# Compliance Alignment

Supports:

- CNCF Platform Engineering
- Backstage
- DevOps
- GitOps
- Twelve-Factor App
- OpenTelemetry

---

# Success Criteria

Golden Paths are successful when:

- Most projects begin from an official template.
- Engineers rarely build infrastructure manually.
- Platform standards are automatically enforced.
- AI accelerates project creation.
- Developer productivity continuously improves.

---

# Related Documents

DOC-201 INTERNAL_DEVELOPER_PLATFORM

DOC-202 DEVELOPER_PORTAL

DOC-203 SERVICE_CATALOG

DOC-205 ENGINEERING_SCORECARDS

---

# Approval

Status:

Draft

Pending Platform Engineering Approval.
