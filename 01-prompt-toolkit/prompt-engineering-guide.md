# 🧠 Prompt Engineering Guide — Write Better Prompts

A practical guide to getting consistently great results from AI tools.
No coding required. Built for business professionals.

---

## The 5-Part Prompt Formula

Every great prompt has some or all of these elements:

```
[ROLE] + [CONTEXT] + [TASK] + [FORMAT] + [CONSTRAINTS]
```

### Example (Weak prompt):
```
Write an email about a delay.
```

### Example (Strong prompt):
```
[ROLE] You are an operations manager at a Hong Kong logistics company.
[CONTEXT] A shipment to a key client has been delayed by 3 days due to a typhoon.
[TASK] Write a professional apology email explaining the delay and proposing a solution.
[FORMAT] Email format with subject line, under 150 words.
[CONSTRAINTS] Tone: apologetic but confident. Do not over-promise on the new date.
```

The difference in output quality is dramatic.

---

## 6 Techniques That Work Every Time

### 1. 🎭 Assign a Role
Tell the AI who it is before asking it to do something.

| Instead of... | Try... |
|---------------|--------|
| "Summarise this report" | "You are a CFO presenting to the board. Summarise this report in 3 bullet points." |
| "Write a caption" | "You are a social media manager for a premium HK restaurant. Write a caption..." |

---

### 2. 📐 Specify Format Exactly
Don't leave format to chance. Tell the AI exactly what you want.

**Good format instructions:**
- "Format as a table with columns: Task, Owner, Deadline"
- "Use bullet points, max 5 points, each under 15 words"
- "Write 3 variations — one formal, one casual, one humorous"
- "Output in Traditional Chinese only"

---

### 3. 🎯 Give an Example (Few-Shot Prompting)
Show the AI what good looks like.

```
Write product descriptions in this style:

Example:
Product: Egg tart
Description: "Golden, flaky pastry cradling a silky-smooth egg custard. A timeless Hong Kong classic, perfected."

Now write descriptions for:
1. [YOUR PRODUCT]
2. [YOUR PRODUCT]
```

---

### 4. 🔄 Use Follow-Up Prompts to Refine
Your first output is a draft. Refine with follow-ups:

- "Make it 30% shorter"
- "Make the tone more formal"
- "Add a sense of urgency"
- "Translate to Traditional Chinese, keep it natural — not a direct translation"
- "Give me 3 more variations"
- "What's missing from this analysis?"

---

### 5. 🧱 Break Complex Tasks into Steps
For complex outputs, prompt step-by-step instead of all at once.

**Instead of:** "Write me a full marketing plan"

**Do this:**
1. "Identify the top 3 target customer segments for [BUSINESS]"
2. "For segment 1, what are their top 3 pain points?"
3. "Write a messaging strategy for segment 1 based on those pain points"
4. "Now create 5 campaign ideas targeting segment 1"

---

### 6. 🚫 Use Negative Constraints
Tell the AI what NOT to do.

- "Do not use jargon"
- "Do not mention competitors by name"
- "Do not make assumptions — if you're unsure, ask me"
- "Do not exceed 100 words"
- "Do not use a formal tone"

---

## Common Mistakes & Fixes

| Mistake | Fix |
|---------|-----|
| Prompt too vague | Add role, context, and format |
| Output too long | Add "Maximum [X] words" |
| Output too generic | Add specific details about your business/audience |
| Wrong tone | Say "Tone: [describe]" or give an example |
| Hallucinated facts | Add "Only use the information I provide. Do not add facts." |
| Bad Chinese translation | Say "Write in natural Hong Kong Cantonese style, not direct translation from English" |

---

## Quick Prompt Templates (Copy & Adapt)

### The Analyser
```
Analyse the following [THING] and provide:
1. Key findings (top 3)
2. Main risks or issues
3. Recommended actions (prioritised)

[PASTE YOUR CONTENT]
```

### The Rewriter
```
Rewrite the following text to be more [ADJECTIVE: clear / persuasive / concise / professional].
Keep the core message. Target audience: [DESCRIBE].
Original: [PASTE TEXT]
```

### The Brainstormer
```
Generate [NUMBER] ideas for [GOAL] targeting [AUDIENCE] in Hong Kong.
Be specific and practical. Rank by ease of implementation.
Context: [BRIEF DESCRIPTION OF YOUR SITUATION]
```

### The Summariser
```
Summarise the following in [NUMBER] bullet points.
Each point should be under [X] words.
Audience: [WHO WILL READ THIS]
[PASTE CONTENT]
```

---

## Tools to Practice With

| Tool | Best For | Free? |
|------|----------|-------|
| [Claude](https://claude.ai) | Long documents, analysis, nuanced writing | ✅ |
| [ChatGPT](https://chat.openai.com) | General tasks, brainstorming | ✅ |
| [Perplexity](https://perplexity.ai) | Research with sources | ✅ |
| [Gemini](https://gemini.google.com) | Google Docs/Sheets integration | ✅ |

---

*Part of the AI Prompt Toolkit — Hong Kong Business Edition*
