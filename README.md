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
  - [Skill Collections](#skill-collections)
  - [Backend](#backend)
  - [Storefront](#storefront)
  - [Admin Dashboard](#admin-dashboard)
  - [Integrations](#integrations)
  - [Deployment and Operations](#deployment-and-operations)
  - [Other](#other)
- [Installing a Skill](#installing-a-skill)
- [Submit a Skill](#submit-a-skill)

## Official Skills

Skills maintained by the Medusa team are available in the [medusajs/medusa-agent-skills](https://github.com/medusajs/medusa-agent-skills) repository. Learn more in the [Agent Skills documentation](https://docs.medusajs.com/learn/introduction/build-with-llms-ai/agentic-skills).

## Community Skills

### Skill Collections

Repositories with multiple Medusa skills that span several categories.

_Have one to add? [Submit a skill](#submit-a-skill)._

<!-- Add entries in alphabetical order -->

- [codee-skills](https://github.com/codee-sh/codee-skills/tree/main/frameworks/medusa) - Covers Medusa backend conventions, admin dashboard forms, storefront SDK and UX, testing, scripts, plugin delivery, and spec reviews across nine skills. By [@codee-sh](https://github.com/codee-sh).
- [medusa-commerce](https://github.com/OrcaQubits/agentic-commerce-skills-plugins/tree/main/medusa-commerce) - Covers Medusa v2 setup, modules, workflows, API routes, catalog, cart and checkout, payments, fulfillment, storefronts, testing, and deployment across 21 skills. By [@OrcaQubits](https://github.com/OrcaQubits).

### Backend

Custom modules, data models, workflows, API routes, subscribers, and other Medusa backend customizations.

_Have one to add? [Submit a skill](#submit-a-skill)._

<!-- Add entries in alphabetical order -->

- [medusa](https://github.com/alinaqi/maggy/tree/main/skills/medusa) - Guides agents through Medusa modules, workflows, API routes, and admin UI customizations. By [@alinaqi](https://github.com/alinaqi).
- [medusa](https://github.com/oimiragieo/agent-studio/tree/main/.claude/skills/medusa) - Applies Medusa v2 rules for modules, the Workflow SDK, data models, services, and admin customizations. By [@oimiragieo](https://github.com/oimiragieo).
- [medusa-development](https://github.com/finsilabs/awesome-ecommerce-skills/tree/main/skills/headless-modern/medusa-development) - Extends Medusa with custom modules, event subscribers, and API routes for custom business requirements. By [@finsilabs](https://github.com/finsilabs).
- [medusa-development](https://github.com/Mindrally/skills/tree/main/medusa-development) - Applies best practices for Medusa v2 data models, workflows, API routes, subscribers, module services, and admin customizations. By [@Mindrally](https://github.com/Mindrally).
- [medusajs-developer](https://github.com/greedychipmunk/agent-skills/tree/main/medusajs-developer) - Builds Medusa v2.15+ custom modules, API routes, data models, workflows, scheduled jobs, and third-party integrations. By [@greedychipmunk](https://github.com/greedychipmunk).

### Storefront

Storefronts built with Medusa, using any frontend framework.

_Have one to add? [Submit a skill](#submit-a-skill)._

<!-- Add entries in alphabetical order -->

### Admin Dashboard

Admin widgets, UI routes, and other Medusa Admin customizations.

_Have one to add? [Submit a skill](#submit-a-skill)._

<!-- Add entries in alphabetical order -->

### Integrations

Integrating Medusa with third-party services, such as payment, fulfillment, CMS, search, or analytics providers.

_Have one to add? [Submit a skill](#submit-a-skill)._

<!-- Add entries in alphabetical order -->

- [medusa-commerce](https://github.com/membranedev/application-skills/tree/main/skills/medusa-commerce) - Manages Medusa store data and automates workflows through the Membrane platform, which requires a Membrane account. By [@membranedev](https://github.com/membranedev).

### Deployment and Operations

Deploying, hosting, monitoring, migrating, and upgrading Medusa applications.

_Have one to add? [Submit a skill](#submit-a-skill)._

<!-- Add entries in alphabetical order -->

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
