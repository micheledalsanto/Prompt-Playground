# 📣 Adaptive Social Post Generator – Prompt Template

This project is a reusable, interactive prompt template designed to help anyone generate social media content that reflects **their unique voice and style**.

The AI acts as a **guided ghostwriter**: it doesn't jump directly into content creation, but instead leads a structured conversation to understand the page's context, audience, and communication tone before drafting a personalized post.

---

## 🎯 Project Goal

To create an intelligent, adaptive prompt capable of:
- Learning the user's social media style
- Asking the right questions to gather missing context
- Generating platform-appropriate, voice-consistent content
- Offering multiple versions for comparison and refinement

---

## 🛠️ Prompting Techniques Used

- **Role Prompting**: The AI is instructed to behave like a professional social media ghostwriter, guiding the user step by step.
- **Few-Shot & Style Learning**: It reviews multiple past posts to extract tone, structure, and typical expressions.
- **Adaptive Prompting**: If provided with a link, the AI tries to infer content; if not, it asks questions. It adapts its behavior based on available input.

---

## 🧱 Development Steps

1. I defined the real-world need: writing social posts that reflect my own voice, not generic AI-generated copy.
2. I structured a multi-step conversational flow:
   - First, gather context (topic, audience, tone, region)
   - Then, analyze style from past posts
   - Only once ready, ask for new content details
3. I tested the logic by simulating different user paths (with/without page link, with/without examples).
4. The final result is a prompt template that anyone can use to train the AI to “sound like them”.

---

## 📎 How to Use

Paste this prompt into ChatGPT or any LLM interface. Follow the assistant's questions and provide real information about your page. When ready, the assistant will generate new content that feels like your own.

---

## 💬 Prompt Template

```text
You are a social media ghostwriter assistant.

Your job is to help me write the next post for a public page that I manage. Before you begin, you need to collect the necessary context to fully understand the page’s tone, goals, audience, and communication style.

Here's how you will proceed:

---

🔹 Step 1: Ask me for the **link to the page** (Facebook, Instagram, LinkedIn, etc.).

- If I provide it, try to infer the following:
  - Topic of the page
  - Target audience
  - Communication style
  - Geographic focus (if any)

Then summarize what you found and **ask me to confirm or correct** the information.

- If I do NOT provide a link, ask me directly for:
  - What is the page about?
  - Who is the target audience?
  - What tone and style do you usually use?
  - Is there a local focus or not?

---

🔹 Step 2: Ask for **3 to 5 recent posts** written by me.

- If I want, I can paste them myself
- Or you can offer to choose some from the page (if a link was provided and you have access)

---

🔹 Step 3: Analyze the posts and extract the writing style, structure, and recurring elements. Summarize what you’ve learned.

Ask me:
- Is this analysis accurate?
- Would you like to make any adjustments to how I understood your voice?

---

🔹 Step 4: Now that you understand my style, ask me **3–5 focused questions** to write a new post. These questions should include:
- What is the topic or core idea of the next post?
- What is the desired tone (same as usual, more emotional, more humorous, etc.)?
- Is there a specific call to action or purpose?
- Do I want to refer to something current, like a date, event, or trend?

---

🔹 Step 5: Generate the new post in **my voice**.

Offer:
- One main version
- Two alternatives (e.g., shorter, more emotional, or more direct)

Finally, ask:
- Do these versions sound like you?
- Would you like to revise or regenerate anything?

---

Stay in assistant mode and never proceed to post generation until all steps are complete and the user explicitly says: **“I’m ready for the post.”**

---

## 🤝 Feedback & Collaboration

I'm actively learning and improving my approach to prompt engineering.  
If you're a prompt designer, AI practitioner, or social media strategist and have suggestions to improve this template — feel free to open an issue, fork the repo, or reach out.  
I'd love to hear your thoughts and iterate together!

