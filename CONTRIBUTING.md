# Contributing

Thank you for sharing your skill with the Medusa community! This guide explains how to add a skill to the list.

## Requirements

A skill must meet the following requirements to be listed:

- It's related to Medusa, such as building, extending, integrating, deploying, or operating a Medusa application.
- It's hosted in a public repository, such as on GitHub, so that anyone can review and install it.
- It follows the [Agent Skills specification](https://agentskills.io), with a `SKILL.md` file that has a `name` and `description` in its frontmatter.
- Its repository has a README that explains what the skill does and how to install it.
- It targets Medusa v2.
- It doesn't contain secrets, obfuscated code, or instructions that perform actions unrelated to the skill's stated purpose, such as sending data to third-party services without the user's knowledge.
- It's not a copy of an [official Medusa skill](https://github.com/medusajs/medusa-agent-skills) without meaningful changes.

## Add a Skill

1. Fork this repository.
2. In [README.md](./README.md), find the category that best fits your skill. If none fits, use the **Other** category. If your repository has multiple Medusa skills that span several categories, use the **Skill Collections** category.
3. Add your skill's entry to the category's list in alphabetical order, using the [entry format](#entry-format).
4. Open a pull request and fill out the pull request template.

Submit one pull request per skill or skill collection. A maintainer will review your pull request and may request changes before merging it.

## Entry Format

Each entry is a single bullet point:

```markdown
- [skill-name](https://github.com/owner/repo/tree/main/path/to/skill) - Short description of what the skill helps agents do. By [@your-github-username](https://github.com/your-github-username).
```

For example:

```markdown
- [medusa-product-reviews](https://github.com/acme/agent-skills/tree/main/medusa-product-reviews) - Builds a product reviews feature with moderation in the Medusa Admin. By [@acme](https://github.com/acme).
```

Keep in mind:

- Use the `name` from the skill's `SKILL.md` frontmatter as the link text. For a collection, use the repository or directory name.
- Link to the skill's directory or repository, not to a specific commit.
- Keep the description to one sentence that starts with a verb and ends with a period.
- Don't include marketing language, such as "the best" or "ultimate".
- If your repository contains multiple Medusa skills, you can add it as a single entry and summarize the skills in the description.

## Update or Remove a Skill

To update your skill's entry, such as its link or description, open a pull request with the change.

Skills may be removed from the list if they're no longer maintained, their link is broken, or they no longer meet the [requirements](#requirements).
