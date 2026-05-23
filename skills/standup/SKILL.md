---
name: standup
description: Create a crisp status update for a team or personal check-in using current commitments, calendar, and tasks.
---

# /standup

User asks for a status update, team standup, or progress note. You return a short, organized summary with what was done, what is next, and what is blocked.

## Recipe

1. **Read memory/commitments.md** for ongoing commitments and PENDING items.
2. **Read memory/life.md** for weekly/monthly priorities and tracked projects.
3. **Read Google Calendar** for today/this week events relevant to the update.
4. **Read Google Tasks** or the user's primary task list for in-progress and due items.

## Structure the output

Use one of these two formats depending on user intent:

### Team-style standup
```
**Yesterday / since last update**
- <accomplished item>
- <accomplished item>

**Today / next**
- <planned item>
- <planned item>

**Blockers / needs**
- <issue that needs attention>
- <decision or resource needed>
```

### Personal weekly check-in
```
**Current focus**
- <top priority>

**Progress this period**
- <what moved forward>
- <what completed>

**Next 24-48h**
- <what you should work on first>

**Risks / blockers**
- <what could stop this>
```

## Output rules

- Keep it short. 5–8 bullet lines total unless the user asks for more detail.
- Use the user's tone: direct, no fluff, no need for apologetic language.
- Highlight only items that are genuinely active or blocking.
- If nothing has moved, say: "No progress yet — still waiting on <person/decision>".

## Why this skill is valuable

- It saves time when the user needs to update a team or prep for a sync.
- It turns scattered notes into a clear narrative.
- It is useful for remote work, founder updates, and weekly reflection.

## When not to use this

- When the user only needs a single sentence status. In that case, use /draft or /reply.
- When the user wants a full project plan rather than a short update.
