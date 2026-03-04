# Knowledge hierarchy

Not all knowledge is equal. Your second brain needs to know what's authoritative, what's developing, and what's raw material. This hierarchy tells the AI how to weight different sources when answering questions, writing for you, or making recommendations.

## The levels

### Level 1: Canonical (highest authority)
Your published positions, your professional profile, established facts about who you are and what you believe. This is the foundation. When lower levels conflict with Level 1, Level 1 wins.

**Lives in:** `me/profile.md`, `me/synthesis.md` (if you write/publish)

### Level 2: Frontier
Where your thinking is right now. Arguments forming, connections emerging, questions you're chewing on. This changes frequently and represents your current intellectual edge.

**Lives in:** `me/thinking.md`

### Level 3: Working context
Active projects, domain intelligence, strategic documents. Factual and current, but specific to your job or situation.

**Lives in:** `work/`

### Level 4: Raw material
Ideas, seeds, drafts, articles you've read, things you've collected. May be incorporated into higher levels or discarded. Not yet authoritative.

**Lives in:** `ideas/`, `drafts/`, `reference/`, `research/`

## How the AI uses this

When you ask a question or request writing:
- The AI checks Level 1 first for your established position
- Then Level 2 for your current thinking
- Then Level 3 for working context
- Level 4 is supporting material, not authoritative

When new information arrives:
- It enters at Level 4 (raw material)
- If it shifts your thinking, it updates Level 2
- If it's significant enough to change your published positions, it updates Level 1
- Ideas flow upward through maturation, never jump straight to the top

## Why this matters

Without a hierarchy, the AI treats a random article you saved three months ago with the same authority as your carefully developed professional position. The hierarchy prevents that.

It also prevents the AI from "updating" your positions based on a single data point. New information goes to the frontier (Level 2) first. Only after it's been tested against your existing thinking does it graduate to canonical status.

## Implementing it

You don't need to label every file with a level. The folder structure encodes the hierarchy:
- `me/` files are Levels 1-2 (canonical and frontier)
- `work/` files are Level 3 (working context)
- Everything else is Level 4 (raw material)

Your CLAUDE.md file should explain this hierarchy so any AI session knows the rules.
