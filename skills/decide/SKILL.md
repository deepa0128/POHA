---
name: decide
description: Run a structured decision framework for any choice. Help the user choose with clarity, not just pros and cons.
---

# /decide

User brings a choice and wants a decision. You return a structured recommendation, not a list of equal-weighted pros and cons.

## Recipe

1. **Clarify the decision.** If the user does not name the decision clearly, ask: "What are the options you are choosing between?"

2. **Read memory/life.md** and `memory/insights.md` to understand the user's values, priorities, and current horizon.

3. **Identify the options.** If the user gives 2+ options, list them clearly. If they are fuzzy, ask for exact wording.

4. **Ask for or infer criteria.** Use one of these patterns:
   - explicit criteria the user gives
   - common decision axes: impact, speed, risk, cost, energy, relationships, optionality
   - values from memory (e.g. "focus", "stability", "learning")

   If criteria are missing, infer them and confirm once with the user if the choice is high-stakes.

5. **Score each option.** For each option:
   - rate it on each criterion (high/medium/low)
   - identify the biggest downside
   - identify the biggest upside
   - note any hidden cost or likely bias

6. **Choose a recommendation.** If one option clearly wins across the criteria and the user's priorities, recommend it.
   - If options are genuinely tied, recommend the option that preserves optionality or minimizes downside.
   - If the user's decision is best framed as "kill one choice," say that.

7. **Add a risk check.** For the recommended option:
   - what would make this recommendation wrong?
   - what should the user watch for in the next 24–48h?

8. **Format the output** as:

```
**Decision:** <clear statement of the choice>

**Options:**
- A: <option>
- B: <option>
- C: <option>

**Criteria:** <list of 3–5 criteria used>

**Evaluation:**
- A — <summary sentence>
- B — <summary sentence>
- C — <summary sentence>

**Recommendation:** <choose one option>.
Why: <one strong sentence rooted in the user's priorities>.

**Risk check:** <what would make this wrong>

**Wildcard:** <a contrarian lens or hidden assumption>
```

## What makes /decide high-value

- It turns indecision into a choice.
- It forces the user to name what matters.
- It prevents endless comparison by adding a recommendation and a risk test.

## What /decide does not do

- It does not say "both are fine."
- It does not defer to the user's emotion alone.
- It does not pretend a serious choice is trivial.
