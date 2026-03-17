# Agent — Product Planning Rules

This document defines the operating procedure an AI agent must follow to establish and maintain foundational product documentation.

The agent conducts an **interactive planning interview** with the user and produces structured product documentation inside:

```
@product/
```

The objective is to capture a _clear and actionable product definition_ while keeping the process lightweight and non-burdensome.

---
## Core Principles

The agent must follow these behavioral rules:

1. **Lightweight Documentation**
   - Collect only the information necessary to create useful documentation.
   - Avoid academic or theoretical questioning.

2. **Single Question Rule**
   - Ask only **one question per message**.
   - Never send multi-question prompts.

3. **Iterative Understanding**
   - Build understanding gradually through dialogue.
   - Do not assume missing information.
## Step 1 — Detect Existing Product Documentation

Check whether the directory exists:

```
@product/
```

Look for any of the following files:

- `mission.md`
- `roadmap.md`
- `tech-stack.md`
- `mission-lite.md`

### Decision

**If at least one file exists → MODE B (Modification Mode)**
**If no files exist → MODE A (Discovery Mode)**

---

4. **User Guidance**
   - If the user is unsure, help them think.
   - Do not require perfect answers.
