---
document_id: PH-000
title: Master Specification
version: 1.0.0
status: Approved
project: Project Harvest
product: CAP Market
company: Carrier's Abundant Produce
author: Bryce Carrier
created: 2026-07-10
last_updated: 2026-07-10
category: Specification
tags:
  - master
  - product
  - specification
  - architecture
related_documents:
  - PH-001
  - PH-002
  - PH-003
  - PH-004
  - PH-005
  - PH-006
  - PH-007
  - PH-008
---

# Master Specification

## Purpose

This document is the authoritative overview of CAP Market.

It establishes the vision, scope, objectives, principles, and organizational structure of the product. It also serves as the entry point to all supporting specifications.

Every contributor—whether human or AI—should begin here before reading more detailed specifications.

---

# Executive Summary

CAP Market is the digital marketplace for Carrier's Abundant Produce (CAP).

Its purpose is to make healthy food affordable, accessible, and convenient while providing the business with efficient tools to manage inventory, packaging, orders, deliveries, and reporting.

CAP Market is designed to support three primary user groups:

- Customers
- Employees
- Owners

The application is intentionally designed to be simple, mobile-first, and optimized for the realities of daily life in Zambia.

---

# Product Overview

CAP Market is a mobile-first commerce platform that connects customers with healthy food while simplifying business operations.

Customers use CAP Market to browse products, place orders, and arrange pickup or delivery.

Employees use CAP Market to manage inventory, package products, fulfill orders, and complete deliveries.

Owners use CAP Market to monitor business performance, manage operations, and make informed decisions using real-time data.

---

# Business Overview

Carrier's Abundant Produce exists to provide healthy food to local communities with integrity, excellence, and care.

CAP Market is the primary digital platform supporting this mission.

The software should faithfully reflect real-world business operations while remaining simple enough for daily use by customers and employees.

------

# Business Model Reality

This section documents the actual current operating economics of Carrier's Abundant Produce as of 2026-07-10. It exists to ground the specification in real numbers rather than assumptions, and will be expanded into a full Data Specification (PH-005) and Business Rules Specification (PH-006) as those documents are written.

## Current Product and Channel

CAP currently sells Nakonde rice in Lusaka West. A 200 kg bulk bag is purchased and repackaged into approximately 41 five kg bags for individual sale.

## Starting Capital

The business began with approximately K8,000 in initial capital.

## Unit Economics

| Metric | Value |
|--------|-------|
| Cost per 5 kg bag | ~K107 |
| Standard selling price range | K150–K165 |
| Bags per 200 kg sack | ~41 |
| Estimated gross profit per sack | K1,760–K2,380 |

Prices vary by customer rather than following a single fixed rate. Every price must have a documented reason.

## Pricing Reasons

Version 1 must support recording *why* a customer received a given price, not just the price itself. Recognized pricing reasons include:

- **Referral** — the customer was introduced to CAP by another individual.
- **Delivery Assistance** — the customer helps deliver product to other customers.
- **Distribution Branch** — the customer acts as a local distribution point, supplying other customers on CAP's behalf.
- **Bulk Purchase** — the customer buys in larger quantities. Bulk pricing currently has multiple tiers; exact tier thresholds and discounts are intentionally not formalized yet, as they remain subjective and evolving.
- **Financial Hardship** — a discretionary discount extended based on the Owner's personal knowledge of a customer's circumstances. This reason is judgment-based and does not follow a fixed formula.

These reasons should be recorded per order or per customer relationship so that pricing decisions remain traceable over time, consistent with the *Truth Above All* and *Every Action Is Recorded* Product Principles.

Formal business rules governing bulk pricing tiers and discount logic will be defined in **PH-006 Business Rules Specification** once those tiers are ready to be standardized.

---

# Target Users

Version 1 supports three user roles.

## Customer

Purchases products.

Tracks orders.

Views order history.

Receives notifications.

---

## Employee

Packages inventory.

Processes customer orders.

Prepares deliveries.

Records inventory events.

---

## Owner

Manages products.

Monitors inventory.

Views reports.

Manages employees.

Oversees business operations.

---

# Product Objectives

Version 1 has the following objectives.

- Make purchasing healthy food simple.
- Reduce manual business processes.
- Maintain accurate inventory.
- Provide reliable order management.
- Improve delivery coordination.
- Produce trustworthy business reports.
- Create an enjoyable customer experience.

---

# Core Features

Version 1 includes:

- Phone number login using One-Time Password (OTP)
- Customer profiles
- Product catalog
- Product search
- Shopping cart
- Checkout
- Order management
- Pickup scheduling
- Delivery scheduling
- Inventory management
- Packaging management
- Product availability
- Notifications
- Business dashboard
- Reporting

---

# Product Principles

CAP Market is guided by the Product Principles defined in:

**PH-008 Product Principles Specification**

These principles govern every design and implementation decision.

---

# Design Constraints

Version 1 is intentionally constrained.

The product must be:

- Mobile-first
- Android-first
- Optimized for slower mobile networks
- Responsive on lower-end smartphones
- Easy for first-time smartphone users
- English-first
- Expandable for future languages
- Cloud-based
- Simple rather than feature-rich
- Fast to learn

Every feature should respect these constraints.

---

# High-Level System Architecture

The platform consists of several integrated components.

- Customer Experience
- Product Catalog
- Inventory Management
- Packaging Management
- Order Management
- Delivery Management
- Reporting & Analytics
- Administration

Each component is specified in greater detail within the supporting documentation.

---

# Documentation Structure

The complete specification consists of the following documents.

| Document | Title |
|----------|-------|
| PH-000 | Master Specification |
| PH-001 | Vision Specification |
| PH-002 | Brand Specification |
| PH-003 | Customer Experience Specification |
| PH-004 | Operations Specification |
| PH-005 | Data Specification |
| PH-006 | Business Rules Specification |
| PH-007 | Future Roadmap Specification |
| PH-008 | Product Principles Specification |

Together, these documents form the authoritative specification for CAP Market.

---

# Version Scope

Version 1 focuses on delivering a dependable operational platform.

Included:

- Customer ordering
- Inventory tracking
- Packaging workflows
- Deliveries
- Reports
- Employee management

Deferred to future versions:

- Loyalty programs
- Promotions
- Wholesale customers
- Supplier portal
- Farmer portal
- Barcode scanning
- AI forecasting
- Multiple branches
- Driver application

---

# Success Metrics

Success will be measured using metrics such as:

- Customer growth
- Repeat purchase rate
- Inventory accuracy
- Order fulfillment time
- Delivery completion rate
- Packaging efficiency
- Revenue growth
- Customer satisfaction

---

# Glossary

**Inventory Lot**

A quantity of bulk inventory received from a supplier.

**Packaging Batch**

A production event in which bulk inventory is converted into retail products.

**Order**

A customer request to purchase one or more products.

**Delivery**

The transportation of an order to the customer.

**Dashboard**

The primary operational overview presented to employees and owners.

---

# References

Related specifications:

- PH-001 Vision Specification
- PH-002 Brand Specification
- PH-003 Customer Experience Specification
- PH-004 Operations Specification
- PH-005 Data Specification
- PH-006 Business Rules Specification
- PH-007 Future Roadmap Specification
- PH-008 Product Principles Specification

Repository standards:

- PH-900 Documentation Style Guide
- PH-901 AI Instructions

---

# Revision History

| Version | Date | Summary |
|----------|------|---------|
| 1.0.0 | 2026-07-10 | Initial Master Specification. |