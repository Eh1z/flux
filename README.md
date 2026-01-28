# Flux

Flux is a full-stack SaaS automation platform designed to demonstrate what it actually takes to build a Zapier-class product from scratch.

Every connection, trigger, and action is implemented manually without relying on third-party automation libraries. The goal is to showcase real engineering depth, scalable architecture, and product-level execution.

---

## What Flux Is

Flux allows users to visually design automation workflows using a node-based builder. Users can connect external services, define triggers, and execute sequences of actions in response to events.

It is built as a B2C SaaS product with authentication, billing, usage-based pricing, and a polished customer-facing experience.

---

## Core Capabilities

- Custom drag-and-drop automation builder
- Visual node-based workflow editor
- Infinite canvas with mini-map for workflow navigation
- Trigger-based automation execution
- Sequenced actions fired after events
- Credit-based usage system
- Subscription billing with Stripe
- Light and dark mode support
- Production-ready marketing landing page

---

## Integrations (Built From Scratch)

All integrations are implemented manually to demonstrate systems-level understanding.

- Google Drive  
  - Secure account connection  
  - File and change detection triggers  

- Slack  
  - Send notifications  
  - Send custom messages  

- Discord  
  - Send notifications  
  - Send custom messages  

- Notion  
  - Create database entries programmatically  

No automation SDKs or abstraction libraries were used.

---

## Authentication and Payments

- Clerk for authentication and session management
- Stripe subscriptions (monthly billing)
- Credit-based billing tied to automation execution
- Payment enforcement at the workflow level

This mirrors real SaaS monetization logic used in production tools.

---

## Tech Stack

### Frontend
- Next.js 16 (App Router)
- Custom node-based UI
- Aceternity UI
- Drag-and-drop interactions
- Infinite canvas and mini-map
- Light and dark themes

### Backend and Infrastructure
- Neon (Postgres)
- Scalable database architecture
- Webhook-based event handling
- Ngrok for secure local webhook development
- Uploadcare for file handling

---

## Architecture Highlights

- All integrations designed as modular services
- Clear separation between triggers, actions, and execution engine
- Database schema optimized for workflow graphs
- Credit usage tracked per automation execution
- Built to scale beyond MVP usage

This is the same architectural thinking required for real automation platforms.

---

## Why This Project Exists

Flux exists to demonstrate:
- How complex SaaS platforms are actually built
- Deep understanding of integrations, auth, billing, and workflows
- Ability to design and ship product-grade systems
- Attention to UX alongside backend scalability

This is representative of how I approach building real businesses, not prototypes.

---

## Ideal For

- Founders building automation or productivity SaaS
- Startups needing complex integrations and billing logic
- Teams replacing or extending Zapier-like workflows
- Businesses looking for custom automation platforms

---

## Status
Actively developed. Built as a foundation that can support additional integrations, team plans, enterprise billing, and execution scaling.

---

## About the Author
Built by a software engineer focused on shipping production-ready SaaS platforms for founders and businesses.

If you are building a serious product and need someone who understands systems, scale, and monetization, this project reflects that level of execution.