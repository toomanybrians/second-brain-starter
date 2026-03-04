# Setting up with Claude Code

Claude Code is the most powerful option for a second brain. It reads and writes files directly on your computer, manages git history, and can run automation scripts.

## Initial setup

1. Install Claude Code from claude.ai/download (requires a Claude Pro or Max subscription)

2. Create your brain folder:
   ```bash
   mkdir -p ~/brain
   cd ~/brain
   git init
   ```

3. Copy the template files from this repo's `templates/` folder into your brain folder, or let the starter MCP guide you through creating them.

4. Launch Claude Code:
   ```bash
   cd ~/brain
   claude
   ```

5. Say: "Read CLAUDE.md and let's get started"

## Why git matters

Git gives you:
- **Complete history** of every change to your knowledge
- **Branching** for experimental thinking
- **Backup** via GitHub (private repo)
- **Diffing**: see exactly what changed in your thinking over time

You don't need to know git commands. Claude Code handles commits for you. Just say "commit what we've done" periodically.

## Recommended workflow

### Morning
```
cd ~/brain && claude
```
"What's new? Anything in inbox? What should I focus on today?"

### During the day
Keep Claude Code open. Drop things in as they happen:
- "I just had a call with [person]. Key takeaway: [insight]"
- "Read this article: [paste text]. What does it connect to?"
- "New idea: [thought]. Where does this fit?"

### End of day
"Commit today's changes. Anything I should process before tomorrow?"

### Weekly
"Let's do a weekly review. What patterns are emerging? What ideas are stale?"

## Power features

### Inbox automation
Put a folder action on `inbox/` so that dropping a file there triggers processing. Claude Code can be configured with hooks to auto-process new files.

### Voice capture
Use your phone's voice-to-text to capture ideas, then paste or sync them to `inbox/`. The AI processes raw transcription into structured knowledge.

### Multi-file operations
Claude Code can update multiple files in one session: process a meeting, update tasks, wire insights into your thinking file, and commit everything in one pass.

## Tips

- **CLAUDE.md is your leverage point.** Invest time refining it. The better your instructions, the more autonomous the AI becomes.
- **Don't over-organize early.** Start with a few folders and let the structure emerge from how you actually work.
- **Commit frequently.** Git history is your undo button and your thinking changelog.
- **Read your own thinking.md periodically.** The AI maintains it, but you should review it to make sure it reflects where your head actually is.
