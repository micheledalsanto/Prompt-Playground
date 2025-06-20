# 📊 Reasoning Prompting – Model Comparison Overview

This document compares how three language models — **ChatGPT-4o**, **Gemini**, and **Claude** — handled multi-step reasoning tasks. The prompts required clarity, logical breakdown, and accurate conclusions across three types of reasoning:

1. Time Calculation (basic logic)
2. Marketing Decision-Making (strategic reasoning)
3. Ethical Trade-offs (moral reasoning)

---

## 1️⃣ Task: Train Time Calculation

**Prompt:**  
"A train leaves at 3:15 PM and arrives at 4:45 PM. How long is the trip? Show your steps."

| Criteria                 | ChatGPT-4o             | Gemini                | Claude                          |
|--------------------------|------------------------|------------------------|----------------------------------|
| Logical Clarity          | ✅ Clear breakdown     | ✅ Minimal but clear   | ⚠️ Over-explained 2-part split   |
| Completeness of Steps    | ✅                     | ✅                     | ✅                               |
| Final Answer Accuracy    | ✅                     | ✅                     | ✅                               |
| Output Format            | ✅ Markdown-friendly   | ✅ Clear and short     | ⚠️ Slightly verbose              |
| Most Thoughtful Output   | ✅                     | ✅                     | ❌ Unnecessary repetition         |

---

## 2️⃣ Task: Budget Marketing Strategies

**Prompt:**  
"A client has a small budget and wants to increase brand awareness. List 3 strategies and explain pros and cons step by step."

| Criteria                 | ChatGPT-4o                | Gemini                      | Claude                                |
|--------------------------|---------------------------|-----------------------------|----------------------------------------|
| Strategic Variety        | ✅ Clear and client-focused| ✅ Diverse, creative         | ✅ Traditional, practical               |
| Pros/Cons Clarity        | ✅ Well-structured         | ✅ Concise and balanced      | ⚠️ Slightly less formatted              |
| Budget-Sensitive         | ✅                         | ✅                           | ✅                                      |
| Tone & Framing           | ✅ Consultant-style        | ✅ Startup-style             | ⚠️ Mixed tone                          |
| Most Usable Response     | ✅                         | ✅                           | ⚠️ Needs polishing                     |

---

## 3️⃣ Task: Ethical Disclosure of a Security Flaw

**Prompt:**  
"A company discovers a security flaw. Should they disclose it immediately or patch it first? Explain the ethical implications."

| Criteria                   | ChatGPT-4o            | Gemini                 | Claude                           |
|----------------------------|------------------------|------------------------|-----------------------------------|
| Ethical Nuance             | ✅ Balanced, 3 options | ⚠️ Binary framing       | ✅ Nuanced and context-aware       |
| Risk/Consequence Analysis  | ✅ Step-by-step        | ✅ Compact              | ✅ Clear and scenario-driven       |
| Structural Clarity         | ✅ Bulleted            | ⚠️ Basic list           | ✅ Full sentence framing           |
| Usefulness for Real-World  | ✅ Strong summary      | ❌ Lacks depth          | ✅ Well-suited to stakeholder view |

---

## ✅ General Observations

- **ChatGPT-4o**  
  Performs consistently well across reasoning types, especially when structure and clarity are important. Strong format control.

- **Gemini**  
  Efficient and concise, but occasionally underdevelops reasoning, especially on moral/ethical tasks. Best for quick insight.

- **Claude**  
  Strong in depth and nuance, particularly in ethically sensitive scenarios. Sometimes overly verbose or loosely formatted.

---

## 💡 Prompting Tips (Based on These Results)

- Always **ask for step-by-step reasoning** and **explicit structure** (e.g., bulleted list, pros/cons).
- If clarity is key, request markdown or numbered outputs.
- For ethical questions, encourage framing from **multiple stakeholder perspectives**.
- Use follow-up prompts to refine overly long or vague outputs.

---

## 🛠 Suggestions For Improvement

- **ChatGPT-4o:** Sometimes assumes structure is obvious; could benefit from more specific formatting constraints.
- **Gemini:** May need reinforcement to expand on moral/strategic reasoning.
- **Claude:** Excellent insights but should be prompted for conciseness and formatting clarity.

