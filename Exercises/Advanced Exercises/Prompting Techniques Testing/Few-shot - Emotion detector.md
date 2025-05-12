## 🧵 Few-shot Prompting Exercise – “Emotion Classification with Explanation”

**Chain-of-Thought Prompt Instruction:**

"Im so excited to do this" – Happy  
"I don't wanna do this at all" – Not Happy  
"I'm looking forward to doing this." – ?

---

**Response:**

Both "excited" and "looking forward to" express positive feelings toward a future event — they just vary slightly in tone. "Excited" is more energetic; "looking forward to" is more calm or formal, but still happy.

---

**Annotation**

- **Logical Clarity:** The model clearly compared the emotional tone of "excited" and "looking forward to" and explained the relationship. The contrast in tone (energetic vs. calm) adds nuance.

- **Correctness:** The classification is correct — "looking forward to" expresses a positive emotion. The reasoning supports the answer well.

- **Depth of Reasoning:** The explanation goes beyond a basic synonym match by analyzing tone and style. It could be stronger with a more explicit conclusion or emotion label at the end.

- **Improvement Suggestions:**
  - Add a **final explicit answer**, e.g.:  
    _"So, the correct label is: Happy."_
  - Make the prompt instruction more specific:  
    _"Classify each sentence as 'Happy' or 'Not Happy'. Explain your reasoning step by step."_
  - Add a third negative example to strengthen the few-shot pattern:  
    _"This is the worst thing ever." – Not Happy_

