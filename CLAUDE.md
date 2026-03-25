# WPPoets Engineering

Private infrastructure and API services for the WPPoets hosting platform.

## Folder Structure

```
wppoets-engineering/
  CLAUDE.md          # This file - project context for AI agents
  AGENTS.md          # Agent-specific instructions and capabilities
  .gitignore         # Excludes bench/ from anvil tracking
  anvil/             # AI artifacts, research, decisions (tracked by anvil repo)
  bench/             # Source code (separate git repo: wppoets/wppoets-engineering)
```

## Repository Info

- **Anvil repo:** `michaeljstutz/wppoets-engineering-anvil` (private, AI artifacts)
- **Bench repo:** `wppoets/wppoets-engineering` (private, infrastructure code)

## Project Context

- Rust API services (licensing, email relay/billing, update manifest)
- Infrastructure as code (deployment, provisioning)
- Internal tooling and scripts
- Not GPL-bound (not WordPress derivatives)
