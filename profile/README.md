# BootstrapLaboratory

**BootstrapLaboratory** builds production-grade reference systems, reusable libraries, and deep technical tutorials for modern software teams.

Our projects are not toy demos. They are designed around real application constraints: monorepo workflows, CI/CD, package releases, full-stack GraphQL apps, authentication, realtime features, cloud deployment, documentation versioning, and repeatable developer experience.

## What We Build

BootstrapLaboratory focuses on complete, practical foundations for serious software projects:

- **Reference Implementations**  
  Full working applications that show how modern systems fit together in practice.

- **Reusable Infrastructure**  
  Libraries and automation that extract repeatable patterns from real projects.

- **Production Workflows**  
  CI/CD, validation, package release, deployment, and documentation flows built for long-term maintenance.

- **Step-by-Step Documentation**  
  Tutorials and guides that explain not only what to run, but why the system is shaped that way.

## Featured Projects

### Rush Delivery
[Rush Delivery](https://bootstraplaboratory.github.io/rush-delivery/) is a Dagger-powered GitHub Action and CI release engine for Rush monorepos.

It provides a repeatable workflow for:

- pull request validation;
- affected target detection;
- build, lint, test, and verify stages;
- package artifact creation;
- npm package releases through Rush change files;
- deployment orchestration from repository metadata;
- local debugging of the same CI workflow.

Rush Delivery is built for teams that want their release pipeline to be portable, inspectable, and consistent across local development and CI.

### Labkit

[Labkit](https://bootstraplaboratory.github.io/labkit/) is a set of small TypeScript packages for building high-end GraphQL server/client applications.

It provides reusable runtime building blocks for:

- NestJS GraphQL servers;
- React, Vite, and Relay webapps;
- auth contracts, access tokens, refresh sessions, and HttpOnly cookie flows;
- realtime GraphQL websocket reconnect behavior;
- TypeORM database manifests and migration safety;
- browser auth state, Relay environments, route preloading, and theme helpers.

Labkit keeps reusable application infrastructure in packages while leaving product-specific schema, resolvers, UI, deployment, and business behavior in the consuming app.

### Production Reference App

[Anonymous Chat](https://github.com/BootstrapLaboratory/typescript_monorepo_nestjs_relay_trunk) is a complete full-stack reference implementation that shows Rush Delivery and Labkit concepts working together in a real application.

The app includes:

- a NestJS GraphQL backend;
- a React/Vite/Relay frontend;
- websocket subscriptions for realtime chat;
- authentication with refresh sessions;
- PostgreSQL and TypeORM;
- Redis pub/sub;
- Rush monorepo structure;
- Dev Container local development;
- Cloud Run, Neon, Upstash, and Cloudflare Pages deployment.

Live example: [bootlab-example-rush-delivery.pages.dev](https://bootlab-example-rush-delivery.pages.dev/)

### AWS Lambda With Rust

[AWS Lambda With Rust](https://bootstraplaboratory.github.io/aws_lambda_rust_runtime/) is a course-style tutorial for building and deploying AWS Lambda functions with Rust.

It reflects the same BootstrapLaboratory approach: practical setup, clear architecture, and production-aware explanation.

## Why BootstrapLaboratory?

### Real Systems, Not Snippets

Our projects are built from complete workflows and real constraints. The goal is to show how the pieces behave together when a project grows beyond a quick demo.

### Reusable Patterns From Production Work

Libraries like Labkit are extracted from actual application architecture. Tools like Rush Delivery automate workflows that real monorepos need: validation, release, packaging, deployment, and documentation lifecycle.

### Strong Developer Experience

We care about repeatable local development, predictable CI, clear package boundaries, and documentation that helps future maintainers understand the system.

### Learn By Building The Whole Thing

BootstrapLaboratory projects are designed to teach architecture through implementation. You can study the reference app, use the libraries, adopt the workflows, or follow the tutorials step by step.

## Explore

- [Rush Delivery](https://github.com/BootstrapLaboratory/rush-delivery)
- [Labkit](https://github.com/BootstrapLaboratory/labkit)
- [Anonymous Chat Reference App](https://github.com/BootstrapLaboratory/typescript_monorepo_nestjs_relay_trunk)
- [AWS Lambda With Rust](https://bootstraplaboratory.github.io/aws_lambda_rust_runtime/)

BootstrapLaboratory exists for developers who want strong foundations, clear architecture, and production-ready examples they can actually learn from and build on.
