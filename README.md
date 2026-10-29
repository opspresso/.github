<div align="center">
  <a href="https://opspresso.com">
    <img src="https://opspresso.com/images/opspresso.png" alt="OpsPresso logo" width="120">
  </a>
  <h1>OpsPresso</h1>
  <p><strong>Platforms and tools for AI agents.</strong></p>
</div>

OpsPresso builds services for operating AI agents and tools for the people building them.

**[Organization profile](profile/README.md)** · **[Website](https://opspresso.com)** · **[Repositories](https://github.com/orgs/opspresso/repositories)**

## What this repository contains

| File | Purpose |
| --- | --- |
| [`profile/README.md`](profile/README.md) | Public introduction and product overview shown on the [OpsPresso organization page](https://github.com/opspresso). |
| [`README.md`](README.md) | Repository purpose and instructions for maintaining that profile. |

The profile groups Studio, Models, Memory, Knowledge, Forge, and Delivery under **Agent Platform**, with `agent-platform` and `agent-plugins` as shared foundations. VibeMon, romty, and Toast sit under **Developer Tools**. See the [profile](profile/README.md) for product descriptions and destinations.

## Maintaining the profile

- Check each product's current documentation before changing its description. Keep capabilities and limits accurate.
- Keep service ownership and the plan → develop → provision → deploy workflow consistent with the current implementation. Do not describe the Models HTTP integration as a completed MCP migration.
- Keep names, product groups, and destinations consistent with the [website source](https://github.com/opspresso/opspresso).
- Use public website links. Do not link visitors to repositories that require private access.
- Product marks are served from `https://opspresso.com/images/`. Publish a new mark on the website before referencing it here.
- Check Markdown rendering, image loading, and links before merging. After merging to `main`, verify the public organization profile.

No build or package installation is required. This repository has no configured lint or automated test suite; use `git diff --check` and inspect the rendered Markdown.
