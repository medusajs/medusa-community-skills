<p align="center">
  <a href="https://www.medusajs.com">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/59018053/229103275-b5e482bb-4601-46e6-8142-244f531cebdb.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://user-images.githubusercontent.com/59018053/229103726-e5b529a3-9b3f-4970-8a1f-c6af37f087bf.svg">
    <img alt="Medusa logo" src="https://user-images.githubusercontent.com/59018053/229103726-e5b529a3-9b3f-4970-8a1f-c6af37f087bf.svg">
    </picture>
  </a>
</p>
<h1 align="center">
  Medusa Community Skills
</h1>

<h4 align="center">
  <a href="https://docs.medusajs.com">Documentation</a> |
  <a href="https://www.medusajs.com">Website</a>
</h4>

<p align="center">
  Building blocks for digital commerce
</p>
<p align="center">
  <a href="./LICENSE">
    <img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="Released under the MIT license." />
  </a>
  <a href="./CONTRIBUTING.md">
    <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat" alt="PRs welcome!" />
  </a>
  <a href="https://discord.gg/xpCwq3Kfn8">
    <img src="https://img.shields.io/badge/chat-on%20discord-7289DA.svg" alt="Discord Chat" />
  </a>
  <a href="https://twitter.com/intent/follow?screen_name=medusajs">
    <img src="https://img.shields.io/twitter/follow/medusajs.svg?label=Follow%20@medusajs" alt="Follow @medusajs" />
  </a>
</p>

A curated list of agent skills built by the community for [Medusa](https://medusajs.com). Use these skills with Claude Code, Cursor, Codex, and other AI agents that support skills to build, extend, and operate Medusa applications.

> [!WARNING]
> Community skills are created and maintained by their authors, not by Medusa. Review a skill's contents before installing it, as skills can instruct your agent to run commands and modify files.

## Contents

- [Official Skills](#official-skills)
- [Community Skills](#community-skills)
  - [Backend](#backend)
  - [Storefront](#storefront)
  - [Admin Dashboard](#admin-dashboard)
  - [Integrations](#integrations)
  - [Other](#other)
- [Installing a Skill](#installing-a-skill)
- [Submit a Skill](#submit-a-skill)

## Official Skills

Skills maintained by the Medusa team are available in the [medusajs/medusa-agent-skills](https://github.com/medusajs/medusa-agent-skills) repository. Learn more in the [Agent Skills documentation](https://docs.medusajs.com/learn/introduction/build-with-llms-ai/agentic-skills).

## Community Skills

### Backend

Custom modules, data models, workflows, API routes, subscribers, and other Medusa backend customizations.

_Have one to add? [Submit a skill](#submit-a-skill)._

<!-- Add entries in alphabetical order -->

- [codee-medusa-backend](https://github.com/codee-sh/codee-skills/tree/main/frameworks/medusa/codee-medusa-backend) - Applies architectural patterns and rules for Medusa modules, API routes, workflows, data models, and module links. By [@codee-sh](https://github.com/codee-sh).
- [codee-medusa-backend-conventions](https://github.com/codee-sh/codee-skills/tree/main/frameworks/medusa/codee-medusa-backend-conventions) - Sets file placement, naming, JSDoc, and step shape conventions across workflows, API routes, modules, links, subscribers, and jobs. By [@codee-sh](https://github.com/codee-sh).
- [codee-medusa-scripts](https://github.com/codee-sh/codee-skills/tree/main/frameworks/medusa/codee-medusa-scripts) - Sets conventions for one-off `medusa exec` scripts and migration scripts, including dry runs, arguments, and data access. By [@codee-sh](https://github.com/codee-sh).
- [codee-medusa-testing](https://github.com/codee-sh/codee-skills/tree/main/frameworks/medusa/codee-medusa-testing) - Picks the right test layer for a Medusa backend change and writes it to the repository's conventions. By [@codee-sh](https://github.com/codee-sh).
- [codee-spec-review-medusa](https://github.com/codee-sh/codee-skills/tree/main/frameworks/medusa/codee-spec-review-medusa) - Reviews Medusa specifications for architecture, contracts, queries, caching, tests, and rollout against repository rules and current code. By [@codee-sh](https://github.com/codee-sh).
- [medusa](https://github.com/alinaqi/maggy/tree/main/skills/medusa) - Guides agents through Medusa modules, workflows, API routes, and admin UI customizations. By [@alinaqi](https://github.com/alinaqi).
- [medusa](https://github.com/oimiragieo/agent-studio/tree/main/.claude/skills/medusa) - Applies Medusa v2 rules for modules, the Workflow SDK, data models, services, and admin customizations. By [@oimiragieo](https://github.com/oimiragieo).
- [medusa-api-routes](https://github.com/OrcaQubits/agentic-commerce-skills-plugins/tree/main/medusa-commerce/skills/medusa-api-routes) - Creates custom API routes with file-based routing, middleware, Zod validators, and authentication. By [@OrcaQubits](https://github.com/OrcaQubits).
- [medusa-cart-checkout](https://github.com/OrcaQubits/agentic-commerce-skills-plugins/tree/main/medusa-commerce/skills/medusa-cart-checkout) - Implements cart lifecycle, line items, shipping and payment selection, and checkout completion. By [@OrcaQubits](https://github.com/OrcaQubits).
- [medusa-catalog](https://github.com/OrcaQubits/agentic-commerce-skills-plugins/tree/main/medusa-commerce/skills/medusa-catalog) - Manages products, variants, options, collections, categories, tags, and product metadata. By [@OrcaQubits](https://github.com/OrcaQubits).
- [medusa-customers](https://github.com/OrcaQubits/agentic-commerce-skills-plugins/tree/main/medusa-commerce/skills/medusa-customers) - Manages customer profiles, authentication, customer groups, addresses, and accounts. By [@OrcaQubits](https://github.com/OrcaQubits).
- [medusa-development](https://github.com/finsilabs/awesome-ecommerce-skills/tree/main/skills/headless-modern/medusa-development) - Extends Medusa with custom modules, event subscribers, and API routes for custom business requirements. By [@finsilabs](https://github.com/finsilabs).
- [medusa-development](https://github.com/Mindrally/skills/tree/main/medusa-development) - Applies best practices for Medusa v2 data models, workflows, API routes, subscribers, module services, and admin customizations. By [@Mindrally](https://github.com/Mindrally).
- [medusa-modules](https://github.com/OrcaQubits/agentic-commerce-skills-plugins/tree/main/medusa-commerce/skills/medusa-modules) - Builds custom modules with DML data models, services, loaders, module links, and container registration. By [@OrcaQubits](https://github.com/OrcaQubits).
- [medusa-orders](https://github.com/OrcaQubits/agentic-commerce-skills-plugins/tree/main/medusa-commerce/skills/medusa-orders) - Handles the order lifecycle, returns, exchanges, claims, draft orders, and order edits. By [@OrcaQubits](https://github.com/OrcaQubits).
- [medusa-plugins](https://github.com/OrcaQubits/agentic-commerce-skills-plugins/tree/main/medusa-commerce/skills/medusa-plugins) - Develops and publishes reusable Medusa plugins as npm packages. By [@OrcaQubits](https://github.com/OrcaQubits).
- [medusa-pricing](https://github.com/OrcaQubits/agentic-commerce-skills-plugins/tree/main/medusa-commerce/skills/medusa-pricing) - Configures price lists, currencies, tax calculation, regions, and promotions. By [@OrcaQubits](https://github.com/OrcaQubits).
- [medusa-security](https://github.com/OrcaQubits/agentic-commerce-skills-plugins/tree/main/medusa-commerce/skills/medusa-security) - Secures Medusa applications with auth strategies, API keys, CORS, JWT and cookie secrets, and sessions. By [@OrcaQubits](https://github.com/OrcaQubits).
- [medusa-setup](https://github.com/OrcaQubits/agentic-commerce-skills-plugins/tree/main/medusa-commerce/skills/medusa-setup) - Sets up a Medusa v2 project with its prerequisites, `medusa-config.ts`, directory structure, and environment variables. By [@OrcaQubits](https://github.com/OrcaQubits).
- [medusa-subscribers](https://github.com/OrcaQubits/agentic-commerce-skills-plugins/tree/main/medusa-commerce/skills/medusa-subscribers) - Implements event subscribers, scheduled jobs, and the event module. By [@OrcaQubits](https://github.com/OrcaQubits).
- [medusa-testing](https://github.com/OrcaQubits/agentic-commerce-skills-plugins/tree/main/medusa-commerce/skills/medusa-testing) - Tests Medusa applications with Jest, module unit tests, workflow and API route integration tests, and mocks. By [@OrcaQubits](https://github.com/OrcaQubits).
- [medusa-workflows](https://github.com/OrcaQubits/agentic-commerce-skills-plugins/tree/main/medusa-commerce/skills/medusa-workflows) - Builds workflows with steps, compensation, parallel execution, hooks, and conditions. By [@OrcaQubits](https://github.com/OrcaQubits).
- [medusajs-developer](https://github.com/greedychipmunk/agent-skills/tree/main/medusajs-developer) - Builds Medusa v2.15+ custom modules, API routes, data models, workflows, scheduled jobs, and third-party integrations. By [@greedychipmunk](https://github.com/greedychipmunk).
- [node-backend](https://github.com/OrcaQubits/agentic-commerce-skills-plugins/tree/main/medusa-commerce/skills/node-backend) - Applies Node.js backend patterns for Medusa, including middleware, MikroORM entities, connection pooling, and error handling. By [@OrcaQubits](https://github.com/OrcaQubits).
- [ts-modern](https://github.com/OrcaQubits/agentic-commerce-skills-plugins/tree/main/medusa-commerce/skills/ts-modern) - Writes modern TypeScript for Medusa, including DML type inference, service generics, and container typing. By [@OrcaQubits](https://github.com/OrcaQubits).

### Storefront

Storefronts built with Medusa, using any frontend framework.

_Have one to add? [Submit a skill](#submit-a-skill)._

<!-- Add entries in alphabetical order -->

- [codee-medusa-storefront-sdk](https://github.com/codee-sh/codee-skills/tree/main/frameworks/medusa/codee-medusa-storefront-sdk) - Integrates storefronts with Medusa through the JS SDK, custom API routes, and React Query patterns. By [@codee-sh](https://github.com/codee-sh).
- [codee-medusa-storefront-ux](https://github.com/codee-sh/codee-skills/tree/main/frameworks/medusa/codee-medusa-storefront-ux) - Provides framework-agnostic UX patterns for storefront pages, cart, checkout, and payment flows. By [@codee-sh](https://github.com/codee-sh).
- [medusa-storefront](https://github.com/OrcaQubits/agentic-commerce-skills-plugins/tree/main/medusa-commerce/skills/medusa-storefront) - Builds Next.js 15 storefronts with the JS SDK, TanStack Query, product pages, cart, and checkout. By [@OrcaQubits](https://github.com/OrcaQubits).
- [nextjs-patterns](https://github.com/OrcaQubits/agentic-commerce-skills-plugins/tree/main/medusa-commerce/skills/nextjs-patterns) - Applies Next.js 15 App Router patterns for Medusa storefronts, including data fetching, caching, and server actions. By [@OrcaQubits](https://github.com/OrcaQubits).

### Admin Dashboard

Admin widgets, UI routes, and other Medusa Admin customizations.

_Have one to add? [Submit a skill](#submit-a-skill)._

<!-- Add entries in alphabetical order -->

- [codee-medusa-admin-dashboard](https://github.com/codee-sh/codee-skills/tree/main/frameworks/medusa/codee-medusa-admin-dashboard) - Builds admin widgets, custom pages, forms, and tables with Medusa's design and data loading patterns. By [@codee-sh](https://github.com/codee-sh).
- [medusa-admin](https://github.com/OrcaQubits/agentic-commerce-skills-plugins/tree/main/medusa-commerce/skills/medusa-admin) - Extends the admin dashboard with widgets, UI routes, Medusa UI components, and Admin API calls. By [@OrcaQubits](https://github.com/OrcaQubits).

### Integrations

Integrating Medusa with third-party services, such as payment, fulfillment, CMS, search, or analytics providers.

_Have one to add? [Submit a skill](#submit-a-skill)._

<!-- Add entries in alphabetical order -->

- [medusa-commerce](https://github.com/membranedev/application-skills/tree/main/skills/medusa-commerce) - Manages Medusa store data and automates workflows through the Membrane platform, which requires a Membrane account. By [@membranedev](https://github.com/membranedev).
- [medusa-fulfillment](https://github.com/OrcaQubits/agentic-commerce-skills-plugins/tree/main/medusa-commerce/skills/medusa-fulfillment) - Implements fulfillment providers, shipping options, fulfillment sets, shipping profiles, and multi-warehouse support. By [@OrcaQubits](https://github.com/OrcaQubits).
- [medusa-payments](https://github.com/OrcaQubits/agentic-commerce-skills-plugins/tree/main/medusa-commerce/skills/medusa-payments) - Implements payment providers and the payment session lifecycle, including Stripe and PayPal. By [@OrcaQubits](https://github.com/OrcaQubits).

### Other

Skills that don't fit in the categories above.

_Have one to add? [Submit a skill](#submit-a-skill)._

<!-- Add entries in alphabetical order -->

## Installing a Skill

Each skill's repository explains how to install it. Most skills can be installed with the [`skills` CLI](https://skills.sh), which copies them into your agent of choice:

```bash
npx skills add <owner>/<repo>
```

If a skill is distributed as a Claude Code plugin, add its marketplace and install the plugin:

```bash
/plugin marketplace add <owner>/<repo>
/plugin install <plugin-name>@<marketplace-name>
```

## Submit a Skill

Built a skill for Medusa? Open a pull request that adds it to this list. Refer to the [contributing guide](./CONTRIBUTING.md) for the requirements and entry format.

If you can't open a pull request, [open a skill submission issue](../../issues/new?template=submit-skill.yml) instead.

## Resources

- [Medusa Documentation](https://docs.medusajs.com)
- [Agent Skills for Medusa](https://docs.medusajs.com/learn/introduction/build-with-llms-ai/agentic-skills)
- [Agent Skills Specification](https://agentskills.io)
- [Medusa Discord](https://discord.gg/xpCwq3Kfn8)
