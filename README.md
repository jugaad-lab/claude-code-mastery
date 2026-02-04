# Claude Code Mastery 🧑‍💻

A comprehensive skill for mastering Claude Code with setup scripts, dev team subagents, and automated maintenance.

## Quick Install

```bash
# Navigate to skill directory
cd ~/clawd/skills/claude-code-mastery/scripts

# Run setup scripts in order
./01-check-dependencies.sh
./02-install-claude-code.sh
./03-first-time-auth.sh
./04-install-subagents.sh
./05-setup-claude-mem.sh  # Optional
```

## What's Included

### 🤖 10 Dev Team Subagents

| Agent | Purpose |
|-------|---------|
| project-manager | Task breakdown, timelines, dependencies |
| product-manager | Requirements, user stories, prioritization |
| senior-dev | Architecture, complex code, code review |
| junior-dev | Quick fixes, simple tasks (fast & cheap) |
| frontend-dev | React, UI, CSS, client-side |
| backend-dev | APIs, databases, server-side |
| data-scientist | SQL, analysis, statistics |
| data-engineer | Pipelines, ETL, data infrastructure |
| ml-engineer | ML models, training, MLOps |
| ai-engineer | LLM apps, RAG, prompts, agents |

### 📜 Scripts

| Script | Purpose |
|--------|---------|
| 01-check-dependencies.sh | Verify system requirements |
| 02-install-claude-code.sh | Install Claude Code CLI |
| 03-first-time-auth.sh | Authenticate (browser or API key) |
| 04-install-subagents.sh | Install all 10 subagents |
| 05-setup-claude-mem.sh | Setup persistent memory (optional) |
| 06-diagnostics.sh | Health check and status report |
| 07-weekly-improvement-cron.sh | Generate improvement report |

### 📚 Documentation

- **docs/best-practices.md** - Context management, verification, CLAUDE.md tips
- **docs/commands.md** - Complete CLI and slash command reference
- **docs/workflows.md** - Real-world workflow examples
- **docs/tips-and-tricks.md** - 30 pro tips from heavy users
- **docs/claude-mem-integration.md** - Persistent memory setup guide

### 📝 Examples

- **examples/CLAUDE-template.md** - Template for project CLAUDE.md files
- **examples/prompts.md** - Example prompts for common tasks

## Usage

After setup, use Claude Code with your dev team:

```bash
# Start Claude Code
claude

# Use subagents
> Use the senior-dev agent to review this code
> Have project-manager create a timeline for this feature
> Ask frontend-dev to build this component
```

## Heartbeat Maintenance

Add to your HEARTBEAT.md for automatic maintenance:

```markdown
## Claude Code Maintenance

### Every Heartbeat (if coding tasks active):
1. Check claude-mem worker status
2. Restart if stopped

### Daily:
1. Run diagnostics: ~/clawd/skills/claude-code-mastery/scripts/06-diagnostics.sh

### Weekly:
1. Run improvement research
2. Propose optimizations (require approval)
```

## License

MIT License - See [LICENSE](LICENSE) file

## Contributing

See [IMPROVEMENTS.md](IMPROVEMENTS.md) for the improvement roadmap.
