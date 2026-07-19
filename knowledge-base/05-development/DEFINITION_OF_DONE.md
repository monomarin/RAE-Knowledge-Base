---
document:
  id: DOC-142
  title: DEFINITION_OF_DONE
  version: 1.0.0
  status: Draft
  category: Development
  type: Quality Standard
  owner: RAE Platform Architecture
  release: v0.6.0 Development Standards
  domain: Quality Engineering
  ddl: DDL-1
---

# Definition of Done

> Official acceptance criteria for all deliverables in RAE Platform.

---

# Executive Summary

This document defines the mandatory criteria that any deliverable must satisfy before being considered complete within RAE Platform.

It applies equally to code, microservices, APIs, AI agents, infrastructure, documentation, automations, workflows, UI components and data models.

---

# Vision

Ensure that every deliverable shipped within RAE Platform meets the same baseline of quality, security, observability and documentation.

---

# Principles

The Definition of Done must be:

- Objective
- Measurable
- Enforceable
- Consistent
- Automated where possible
- Applied equally to human and AI contributions

---

# Universal Criteria

Every deliverable must satisfy:

- Functional requirements met
- Automated tests written and passing
- Code reviewed and approved
- Security validation passed
- Documentation updated
- No critical defects open
- Architecture compliance verified
- Merged into the correct branch
- CI/CD pipeline passing

---

# Code

Code is done when:

- Implements the specified behavior
- Follows coding standards
- Passes linting
- Passes static analysis
- Has unit tests with minimum coverage
- Has integration tests where applicable
- Is peer reviewed
- Has no security vulnerabilities
- Is documented

---

# Microservices

A microservice is done when:

- All endpoints are implemented and tested
- API contract is documented
- Events are documented
- Health check is implemented
- Observability is configured
- Deployment is automated
- Security policies are applied
- Documentation is updated

---

# APIs

An API is done when:

- All endpoints are implemented
- Request and response schemas are validated
- Authentication is implemented
- Authorization is implemented
- Rate limiting is configured
- Error responses are standardized
- API documentation is published
- Contract tests are passing
- Performance targets are validated

---

# AI Agents

An AI agent is done when:

- Behavior is specified
- Prompt is documented
- Tool calls are validated
- Memory is tested
- Hallucination risk is assessed
- Human review is completed
- Integration tests pass
- Observability is configured
- Documentation is updated

---

# Infrastructure

Infrastructure is done when:

- Provisioned through code
- Version controlled
- Security policies applied
- Network policies configured
- Monitoring configured
- Alerting configured
- Disaster recovery validated
- Documented

---

# Documentation

A document is done when:

- Content is complete
- Metadata is populated
- Cross references are valid
- Reviewed by stakeholder
- Approved
- Published to knowledge base
- Version updated

---

# Automations and Workflows

An automation is done when:

- Behavior is tested end to end
- Error handling is implemented
- Retry logic is configured
- Observability is in place
- Rollback is defined
- Documentation is updated

---

# UI Components

A UI component is done when:

- Implements design specifications
- Is accessible
- Is responsive
- Has unit tests
- Has visual regression tests
- Is documented in the design system
- Is reviewed by design

---

# Data Models

A data model is done when:

- Schema is defined
- Migrations are written and tested
- Indexes are defined
- Constraints are applied
- Privacy requirements are met
- Documentation is updated
- Validated by architecture

---

# Quality Gates Summary

| Deliverable | Tests | Review | Security | Documentation |
|---|---|---|---|---|
| Code | Required | Required | Required | Required |
| Microservice | Required | Required | Required | Required |
| API | Required | Required | Required | Required |
| AI Agent | Required | Required | Required | Required |
| Infrastructure | Required | Required | Required | Required |
| Documentation | N/A | Required | N/A | Required |
| Automation | Required | Required | Required | Required |
| UI Component | Required | Required | N/A | Required |
| Data Model | Required | Required | Required | Required |

---

# Success Criteria

The Definition of Done is successful when:

- Incomplete deliverables never reach production.
- Quality is consistent across all teams.
- AI contributions meet the same standards as human contributions.
- Technical debt is controlled.
- Production incidents caused by incomplete deliverables reach zero.

---

# Related Documents

DOC-134 DEVELOPMENT_STANDARDS

DOC-135 CODING_STANDARDS

DOC-137 TESTING_STRATEGY

DOC-138 CI_CD_PIPELINE

DOC-139 CODE_REVIEW_GUIDE

DOC-141 AI_DEVELOPMENT_GUIDE

---

# Approval

Status:

Draft (v1.0)

Pending Quality Engineering Review.
