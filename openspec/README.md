# OpenSpec for DIC3 Project Refactor

This directory contains a **prepared OpenSpec scaffold**. It has not been generated or verified by executing the OpenSpec CLI.

## Complete installation

OpenSpec upstream: https://github.com/Fission-AI/OpenSpec

Requires Node.js 22.12.0+ for npm installation. In a local shell:

```bash
git clone https://github.com/huanchen1107/2026-11-11-DIC3-ProjectRefactor.git
cd 2026-11-11-DIC3-ProjectRefactor
npm install -g @fission-ai/openspec@latest
openspec init
openspec --version
```

When using this setup branch before merge, check it out first:

```bash
git fetch origin
git checkout chore/openspec-setup
```

Follow the CLI's prompts to select your coding assistant. Initialization may create agent-specific commands or skills and adjust files. Review and commit those generated changes separately.

## Planned workflow

1. Explore: `/opsx:explore`
2. Propose a change: `/opsx:propose <change-name>`
3. Review `proposal.md`, `design.md`, `specs/`, and `tasks.md`
4. Apply only after approval: `/opsx:apply`
5. Verify, then archive: `/opsx:archive`

Commands vary by coding-agent platform; the CLI prints the applicable form.

## Repository policy

- Keep existing `myplan/` records unchanged.
- Treat DietSense C1–C4 as proposed capabilities, not proven benefits.
- Avoid publishing user-specific health logs or secrets in a public repository.
- Require evidence for accuracy, safety, and effectiveness claims.
- This branch is a starter scaffold, not a successful CLI installation.
