# Starter interview

This is the guided conversation that builds someone's second brain from scratch. When a user connects via MCP and says "help me build my second brain," the AI should follow this flow.

## Principles for the guide

- Be conversational, not robotic. This should feel like a smart colleague helping you set up.
- Ask one thing at a time. Don't overwhelm with options.
- Create files as you go. Don't wait until the end.
- Make it tangible fast. The user should see their first file within five minutes.
- Adapt to the user's technical level. If they say "I don't know what markdown is," adjust.

## The flow

### Step 1: Orient (2 minutes)

Explain what we're building in plain language:

"We're going to build you a personal AI knowledge system. It's a folder of text files that I'll read at the start of every conversation. Over time, it becomes a complete picture of who you are, what you know, what you're working on, and how you think. Every conversation makes it smarter.

Think of it as giving your AI a persistent memory that actually works: not the shallow 'I remember you like coffee' kind, but deep knowledge of your professional world.

We'll build it together right now. I'll ask you some questions, and we'll create the files as we go. By the end of this conversation, you'll have a working system."

### Step 2: Choose the setup (1 minute)

Ask: "How are you using me right now? Are you in Claude Code (terminal), Claude Desktop (the app), or something else?"

Based on their answer, determine:
- **Claude Code**: Full power. Create files directly. Recommend git.
- **Claude Desktop with MCP**: They're connected to the starter server. Guide them to create a local folder and use Claude Code for file creation, or use Projects.
- **Claude Desktop Projects**: Limited but functional. Create content as Project Knowledge entries.

If they're not sure, ask: "Can you see a terminal/command line, or are you in a chat window?" and guide from there.

Help them create the brain folder if needed. On Mac: `~/Documents/brain/` is a safe default.

### Step 3: Build the identity layer (10-15 minutes)

This is the most important part. Interview them to create three files:

#### 3a: Profile (me/profile.md)

Ask these questions (conversationally, not as a checklist):
- What's your name and role?
- What organization do you work for? What does it do?
- What's your professional domain? (What are you an expert in?)
- How long have you been doing this?
- What are 2-3 things you're known for professionally?
- Any key credentials, publications, or achievements worth noting?

Create `me/profile.md` from their answers.

#### 3b: Preferences (me/preferences.md)

Ask:
- How do you like to communicate? (Concise? Detailed? Formal? Casual?)
- Do you prefer outputs as files or conversation?
- Any pet peeves with AI assistants? (Too verbose? Too many caveats? Annoying pleasantries?)
- How do you input things? (Typing? Voice transcription? Paste from other tools?)
- Anything else about how you like to work?

Create `me/preferences.md` from their answers.

#### 3c: Thinking (me/thinking.md)

This is the frontier map. Ask:
- What are the 2-3 biggest things you're working on or thinking about right now?
- What questions are you chewing on? What aren't you sure about?
- Any big decisions coming up?
- What's connecting in your mind lately? Any patterns you're noticing?

Create `me/thinking.md` with sections: "Big projects/priorities," "Open questions," "What's connecting."

### Step 4: Create the system files (5 minutes)

Now create the infrastructure:

1. **CLAUDE.md** — The master instruction file. Customize the template based on everything learned in Step 3. Include:
   - Who they are (reference profile)
   - How to behave (reference preferences)
   - The folder structure
   - The knowledge hierarchy
   - Key workflows

2. **index.md** — The system manifest. List what's where.

3. **Folder structure** — Create the essential folders with README files:
   - `me/` (already populated)
   - `work/` (current projects and context)
   - `ideas/` (idea capture)
   - `reference/` (things they've read or written)
   - `inbox/` (raw inputs to process)
   - `tasks/` (to-dos)
   - `skills/` (processing workflows)

### Step 5: First real workflow (5-10 minutes)

Make it tangible. Ask: "What's something real you want to process right now? A meeting you just had, an article you read, a decision you're mulling over, an idea you had?"

Walk them through processing it using the system:
- If it's a meeting: create meeting notes, extract tasks, update thinking.md
- If it's an article: extract key ideas, create an idea file, connect to their work
- If it's a decision: capture reasoning in work/, update thinking.md
- If it's an idea: create an idea file, note what it connects to

This teaches the integration workflow by doing it for real.

### Step 6: Next steps (2 minutes)

Wrap up with:
- "Your second brain is now live. Every conversation from here builds on what we've created."
- Suggest their next actions:
  - Process another meeting or article
  - Add more detail to their thinking.md
  - Set up a daily workflow (morning check-in, end-of-day commit)
  - Add their writing or published work to reference/
- If they're on Claude Code, suggest git: "Want me to commit everything so we have a snapshot?"
- Mention the weekly review: "Once a week, ask me to do a weekly review. I'll look at everything that changed and surface connections you might have missed."

## Adaptation notes

- **For executives**: Emphasize decisions, meeting processing, and strategic thinking. Skip the technical details.
- **For writers/creators**: Emphasize the writing style capture, idea management, and the "blog for AI" concept.
- **For engineers**: They'll want git, automation, and hooks. Lean into the technical setup.
- **For beginners**: Go slower on steps 1-2, faster on steps 4-6 (let the system emerge rather than explaining it all upfront).
