---
document_id: PH-901
title: AI Instructions
version: 1.0.0
status: Approved
project: Project Harvest
product: CAP Market
company: Carrier's Abundant Produce
author: Bryce Carrier
created: 2026-07-10
last_updated: 2026-07-10
category: Repository
tags:
  - ai
  - instructions
  - governance
related_documents:
  - PH-900
  - PH-000
---

# AI Instructions

## Project

Project Harvest

---

## Product

CAP Market

---

## Company

Carrier's Abundant Produce (CAP)

---

# Purpose

You are contributing to the development of **CAP Market**, a digital platform that makes healthy food simple to buy, simple to sell, and simple to manage.

Your responsibility is not simply to generate code.

Your responsibility is to faithfully implement the product specification while maintaining simplicity, consistency, and long-term maintainability.

---

# Source of Truth

The `/specifications` directory is the authoritative source for all product requirements.

Never invent functionality that conflicts with the documentation.

If documentation appears incomplete or ambiguous, ask for clarification before implementing.

---

# Development Philosophy

Follow this order:

1. Understand the specification.
2. Understand the business need.
3. Design carefully.
4. Write clean code.
5. Write tests.
6. Update documentation if implementation changes approved behavior.

Never reverse this order.

---

# Product Principles

Every implementation should support one or more of these principles.

1. Feed Families First
2. Simplicity Wins
3. Speed Matters
4. Truth Above All
5. Every Action Is Recorded
6. Design for Tomorrow
7. Human Before Technology
8. Delight Through Simplicity
9. Stewardship
10. Excellence Honors God

---

# Design Philosophy

The interface should feel:

- Clean
- Friendly
- Calm
- Fast
- Honest
- Professional

Avoid unnecessary complexity.

Every screen should have one primary purpose.

---

# Business Philosophy

Technology exists to support the business.

The business does not exist to support the technology.

Whenever a technical decision conflicts with usability, prefer the solution that is easiest for the user to understand.

---

# Documentation First

Before implementing a feature:

Read the relevant specification.

Examples:

Customer login
→ **PH-003 Customer Experience Specification.md**

Inventory
→ **PH-004 Operations Specification.md**

Business logic
→ **PH-006 Business Rules Specification.md**

Database
→ **PH-005 Data Specification.md**

Never assume.

Always verify.

---

# Simplicity

When choosing between two solutions:

Choose the simpler one.

If both satisfy the requirements equally well:

Choose the one that will be easier to maintain five years from now.

---

# Architecture

Build modular software.

Prefer small, focused components.

Avoid unnecessary dependencies.

Write reusable code.

Avoid duplication.

---

# User Experience

The user should rarely need instructions.

Interfaces should feel obvious.

Every additional tap should have a clear purpose.

---

# Performance

Optimize for responsiveness.

Avoid unnecessary loading.

Design for slow mobile networks.

Design for lower-end Android devices.

Minimize bandwidth usage.

---

# Accessibility

Use readable typography.

Provide sufficient color contrast.

Support screen readers where possible.

Ensure touch targets are large enough.

Never rely on color alone to communicate important information.

---

# Security

Validate all input.

Never expose sensitive information.

Follow the principle of least privilege.

Protect customer data.

Protect employee data.

Protect financial data.

---

# Data Integrity

Data accuracy is more important than convenience.

Inventory should never become inconsistent.

Financial records should be traceable.

Every inventory change should be recorded as an event.

Never silently modify historical data.

---

# Error Handling

Provide helpful error messages.

Never expose technical stack traces to users.

Log errors appropriately.

Recover gracefully whenever possible.

---

# AI Behavior

When requirements are unclear:

Ask questions.

Do not invent business rules.

Do not make assumptions.

Do not create features outside the documented scope.

---

# Coding Standards

Write readable code.

Prefer clarity over cleverness.

Use descriptive names.

Keep functions small.

Document complex logic.

Remove unused code.

---

# Documentation

If implementation changes an approved specification:

Update the documentation.

Documentation and implementation must remain synchronized.

---

# Long-Term Vision

This project is intended to become the operating platform for Carrier's Abundant Produce.

Design every feature with future growth in mind while keeping Version 1 intentionally simple.

---

# Guiding Principle

Build software that people enjoy using.

The greatest compliment is not that the software is powerful.

The greatest compliment is:
> "That was easy."

---

# Revision History

| Version | Date | Summary |
|---------|------|---------|
| 1.0.0 | 2026-07-10 | Added YAML front matter and corrected specification path references to match PH-900 File Naming standard. |
