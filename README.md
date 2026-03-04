# Second Brain Starter

An open source framework for building a personal AI knowledge system. Connect your AI to the methodology via MCP, or fork this repo and start from the templates.

## What this is

A second brain is a personal knowledge system: a folder of markdown files that your AI reads at the start of every conversation. It compounds over time as you add your knowledge, decisions, thinking, and workflows. The AI becomes a true cognitive partner because it has persistent access to everything you know and care about.

This isn't an app. It's a pattern of usage that works with any AI tool (Claude Code, Claude Desktop, ChatGPT, Gemini, or anything that reads files).

## Three ways to use this

### 1. Connect via MCP (easiest)

Add this to your Claude Desktop config (`~/Library/Application Support/Claude/claude_desktop_config.json` on Mac):

```json
{
  "mcpServers": {
    "second-brain-starter": {
      "url": "https://brianmadden.ai/start"
    }
  }
}
```

Restart Claude Desktop, then say: **"Help me build my second brain."**

The methodology guides you through setup interactively. You learn second brains by talking to one.

### 2. Fork this repo (developers)

```bash
git clone https://github.com/toomanybrians/second-brain-starter.git my-brain
cd my-brain
# Start Claude Code or your preferred AI tool
# Say: "Read CLAUDE.md and help me customize this system for my work"
```

### 3. Read the methodology (manual)

Browse the `methodology/` folder for the full framework, then copy templates from `templates/` to get started.

## What's inside

```
second-brain-starter/
├── methodology/          # The framework: philosophy, principles, workflows
│   ├── overview.md       # What and why (start here)
│   ├── knowledge-hierarchy.md
│   ├── processing-workflows.md
│   └── platforms/        # Setup guides per AI tool
├── templates/            # Starter files to copy and customize
│   ├── CLAUDE.md         # Master AI instruction file
│   ├── index.md          # System manifest
│   ├── me/               # Identity layer
│   ├── work/             # Current work context
│   ├── ideas/            # Idea capture
│   ├── reference/        # Published/external material
│   ├── skills/           # Processing workflows
│   ├── inbox/            # Raw inputs
│   └── tasks/            # To-dos
└── starter-interview.md  # The guided setup conversation
```

## Philosophy

- **Files, not databases.** Markdown files in a git repo. You own them. Any AI can read them. No vendor lock-in.
- **Integration, not filing.** Every piece of knowledge gets wired into your active thinking: what does this change? What does it connect to? Filing without integration is organized forgetting.
- **The AI maintains the system.** Unlike every productivity system you've abandoned, this one maintains itself. The maintenance is the product.
- **Your system is yours.** Everyone's brain works differently. This framework gives you the scaffolding; you customize everything.

## Origin

This framework is derived from [Brian Madden's](https://bmad.com) personal AI knowledge system, which he's been building and writing about since 2025. The public version of his system is available as an MCP server at [brianmadden.ai](https://brianmadden.ai).

## License

MIT
