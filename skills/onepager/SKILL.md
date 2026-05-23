---
name: onepager
description: Turn notes, conversation threads, or meeting highlights into a polished one-page summary.
---

# /onepager

User wants a concise, readable one-page summary of a conversation, project, meeting, or plan.

## Recipe

1. **Identify the source.** The user may provide raw notes, a message thread, or a set of bullet points.
2. **Read the source content** and distill the key facts.
3. **Determine the audience.** If not stated, assume a smart colleague or stakeholder who needs the gist quickly.
4. **Structure the one-pager** into:
   - **What happened / what this is**
   - **Why it matters**
   - **Key points / decisions**
   - **Risks / open questions**
   - **Next steps**

5. **Format cleanly.** Use short sections and bullets. No more than 1 page / ~400 words.

## Output format

```
**Summary**
<one-line overview>

**Why it matters**
- <bullet>
- <bullet>

**Key points**
- <bullet>
- <bullet>

**Open questions / risks**
- <bullet>
- <bullet>

**Next steps**
- <bullet>
- <bullet>
```

## What makes /onepager high-value

- It turns messy input into a shareable asset.
- It is useful for follow-up notes, investor updates, project handoffs, and meeting recaps.
- It scales the user's ability to communicate without extra effort.

## Guardrails

- Do not invent facts. If a point is uncertain, label it as such.
- Do not over-polish when the source is rough; preserve the original meaning.
- Do not use the user's private carry-on notes unless explicitly requested and authorized.
