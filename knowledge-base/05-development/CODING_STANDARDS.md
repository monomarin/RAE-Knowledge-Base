---
document:
  id: DOC-135
  title: CODING_STANDARDS
  version: 1.0.0
  status: Draft
  category: Development
  type: Development Standard
  owner: RAE Platform Architecture
  release: v0.6.0 Development Standards
  domain: Engineering
  ddl: DDL-1
---

# Coding Standards

> Official coding standards for RAE Platform.

---

# Executive Summary

This document defines the mandatory coding standards for all software written within RAE Platform.

Its purpose is to ensure that every codebase maintained by humans or AI agents has a uniform style, is maintainable, secure, easy to review and designed to evolve over many years.

---

# Vision

Write code that any developer or AI agent can read, understand and modify safely on their first day.

---

# Guiding Principles

All code must be:

- Readable
- Consistent
- Minimal
- Secure
- Testable
- Documented
- Reviewable
- AI Compatible

---

# General Rules

- Write code for humans first.
- Optimize only when necessary and measured.
- Prefer explicit over implicit.
- Prefer simple over clever.
- Every function does one thing.
- Every module has one responsibility.
- Avoid side effects unless explicit.
- Fail fast and fail clearly.

---

# Naming Conventions

## Variables

Use descriptive names.

Avoid abbreviations unless universally understood.

Prefer:

- `userPlaylistCount`
- `campaignStartDate`
- `isTrackAvailable`

Avoid:

- `x`
- `tmp`
- `data2`

## Functions

Name functions with a verb describing their action.

Examples:

- `getPlaylist`
- `createCampaign`
- `validateTrackMetadata`
- `publishEvent`

## Classes and Interfaces

Use nouns that describe the entity.

Examples:

- `PlaylistEngine`
- `CampaignRepository`
- `TrackMetadataService`
- `UserPreferenceAdapter`

## Constants

Use SCREAMING_SNAKE_CASE for constants.

Examples:

- `MAX_PLAYLIST_SIZE`
- `DEFAULT_TIMEOUT_MS`
- `SUPPORTED_AUDIO_FORMATS`

## Files

Use SCREAMING_SNAKE_CASE for documentation files.

Use kebab-case or snake_case for source code files according to language conventions.

---

# Functions

Every function must:

- Have a single clear purpose.
- Accept minimal parameters.
- Return a predictable output.
- Be independently testable.
- Be documented when public.

Maximum recommended function length: 30 lines.

If a function exceeds this, consider splitting it.

---

# Classes and Modules

Every class or module must:

- Represent a single concept.
- Have explicit dependencies.
- Expose minimal public surface.
- Be independently testable.

Avoid God Classes.

Avoid circular dependencies.

---

# Error Handling

- Never swallow errors silently.
- Always log errors with context.
- Return meaningful error types.
- Distinguish business errors from technical errors.
- Never expose internal stack traces to end users.

---

# Comments and Documentation

Inline comments:

- Explain why, not what.
- Keep them current or remove them.
- Avoid commented-out code in production.

Public API documentation:

- Every public function, class and module must be documented.
- Include purpose, parameters, return values and examples.

---

# Security in Code

- Never hardcode secrets or credentials.
- Always validate inputs at system boundaries.
- Sanitize outputs when rendering user data.
- Use parameterized queries for database access.
- Avoid dynamic code execution.
- Follow least privilege principles.

---

# Performance

- Do not optimize prematurely.
- Measure before optimizing.
- Document performance decisions.
- Avoid blocking operations in critical paths.
- Use pagination for large data sets.

---

# Testing

- Every public function must have at least one unit test.
- Tests must be independent from each other.
- Tests must not depend on external services.
- Use mocks and stubs to isolate units.
- Test edge cases and failure scenarios.

---

# AI-Generated Code

AI-generated code must:

- Follow all standards defined in this document.
- Be reviewed by a human before merging.
- Include documentation.
- Pass all automated validations.
- Be traceable to a prompt or specification.

---

# Code Review Standards

Every code review must verify:

- Correctness
- Readability
- Security
- Test coverage
- Documentation
- Compliance with these standards

Reviews are not personal. They protect the product.

---

# Linting and Formatting

- All projects must use automated linters.
- All projects must use automated formatters.
- Formatting rules must be enforced in CI.
- No manual formatting debates. The tool decides.

---

# Forbidden Patterns

- Magic numbers without named constants.
- Functions with more than 5 parameters without justification.
- Deeply nested logic beyond 3 levels without extraction.
- Commented-out code committed to production branches.
- Direct access to infrastructure from domain logic.
- Logging sensitive data.

---

# Success Criteria

Coding standards are successful when:

- Any developer can read any file in the project without confusion.
- Code reviews focus on logic, not style.
- AI-generated code passes validation without manual corrections.
- Security incidents caused by coding errors decrease to zero.
- Onboarding time for new developers decreases.

---

# Related Documents

DOC-134 DEVELOPMENT_STANDARDS

DOC-136 GIT_WORKFLOW

DOC-137 TESTING_STRATEGY

DOC-138 CI_CD_PIPELINE

---

# Approval

Status:

Draft (v1.0)

Pending Engineering Review.
