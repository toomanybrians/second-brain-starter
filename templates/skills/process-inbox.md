# Skill: Process Inbox

## Triggers
"process inbox", "what's in inbox"

## Procedure

When items arrive in `inbox/`:

1. **Identify type**: transcript, article, idea, note, image, URL
2. **Extract value**:
   - Ideas → `ideas/` with descriptive filename
   - Tasks → `tasks/tasks.md` under appropriate priority
   - Strategic insights → relevant `work/` file
   - Meeting content → `meetings/` (use process-meeting skill)
3. **Integrate**: For every piece of extracted knowledge, ask:
   - What does this connect to?
   - Does this change anything in `me/thinking.md`?
   - Does this affect any active project in `work/`?
   - Update those files.
4. **Archive**: Move processed item to `archive/inbox/` with date prefix (YYYY-MM-DD-)
5. **Report**: Summarize what was processed, what was extracted, what was updated

## Key principle

Filing without integration is organized forgetting. Every item should leave a trace in the active system, not just sit in a folder.
