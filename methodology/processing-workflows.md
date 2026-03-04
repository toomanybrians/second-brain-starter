# Processing workflows

A second brain isn't just a knowledge store. It's a system that processes inputs into connected knowledge. These workflows tell the AI how to handle different types of material.

## Core principle: integrate, don't file

When something new arrives, the AI shouldn't just put it in a folder. It should:
1. Extract the key insights
2. Ask: what does this connect to?
3. Update any active thinking or projects it affects
4. Create new idea files for novel concepts
5. Add tasks if action is needed

Filing without integration is organized forgetting.

## Inbox processing

When items arrive in `inbox/`:
1. Determine type (transcript, article, idea, note, etc.)
2. Extract: ideas go to `ideas/`, tasks go to `tasks/`, strategic insights go to relevant `work/` files
3. Wire extracted knowledge into active thinking files
4. Move processed item to `archive/inbox/` with date prefix

## Meeting transcripts

1. Identify speakers and context
2. Create structured meeting notes in `meetings/`
3. Extract: decisions made, action items, key insights, open questions
4. Route action items to `tasks/`
5. Update any affected project or work files
6. Wire strategic insights into `me/thinking.md` if relevant

## Articles and research

1. Read and extract key arguments
2. Create an idea file if the article introduces novel concepts
3. Cross-reference with existing ideas and positions
4. Update relevant work files or thinking if it shifts your perspective
5. File the source in `reference/` or `research/`

## Idea capture

Ideas can arrive anytime (conversations, shower thoughts, walks). The system should:
1. Capture quickly in `ideas/` with a descriptive filename
2. Tag with status: seed / developing / ready / incorporated / stale
3. Note what it connects to (which arguments, projects, or questions)
4. During weekly reviews, prune stale ideas and promote developing ones

## Weekly review

A periodic consolidation (weekly or biweekly):
1. Review all new ideas and connections from the past week
2. Check: are any ideas ready to promote to active arguments?
3. Check: are any active projects stale or stuck?
4. Update `me/thinking.md` with current state of your arguments
5. Clean up: archive completed tasks, prune dead ideas
6. Surface: what patterns or connections did you miss?

## The flow

```
Raw input → inbox/ → Extract & categorize
                    → ideas/ (novel concepts)
                    → tasks/ (action items)
                    → work/ (project updates)
                    → me/thinking.md (frontier shifts)
                    → archive/ (processed source)
```

Every arrow represents an integration step, not just a move.
