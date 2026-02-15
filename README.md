# Agents

Common configuration and documentation for AI tools.

## Setup

Clone this repo:

```bash
git clone https://github.com/alistairdavies/agents ~/.agents
```

If the tool that you are using does not support ~/.agents out of the box then create symlinks to wherever the configuration is expected.

### Claude Code

```bash
ln -s ~/.agents/skills ~/.claude/skills
ln -s ~/.agents/AGENTS.md ~/.claude/CLAUDE.md
```

### Factory

Factory automatically picks up skills from ~/.agents, but not AGENTS.md it seems:

```bash
ln -s ~/.agents/AGENTS.md ~/.factory/AGENTS.md
```


## Resources
- [skills.sh](https://skills.sh/)
- [agents.md](https://agents.md)
