# 🧠 Prompt Engineering Cheatsheet

I put together this cheatsheet to organize what I’ve learned about prompt engineering through courses, hands-on practice, technical blogs, and community resources like OpenAI, DeepLearning.AI, and Google.  
My goal is to make this a practical reference for anyone who wants to explore, learn, and experiment with prompts—whether you're just starting out or already deep into the world of LLMs.

Feel free to use, remix, or improve anything here.  
And if you have suggestions, ideas, or improvements—I'd really appreciate hearing them!

---

## 🔹 1. General Prompt Construction

📌 **Purpose:**  
To create clear and direct prompts for a wide variety of tasks, ensuring high-quality and relevant outputs.

✅ **Ideal Use Cases:**

- Content generation (blog posts, summaries, translations)  
- Structured data extraction (from unstructured text)

🧩 **Template**

### Objective  
[Clearly state the task.]

### Context  
[Provide essential background information.]

### Instructions  
[Define specific steps or expectations.]

### Constraints  
[Include any rules: tone, length, output type.]

### Output Format  
[Specify how the answer should be structured.]

### Example  
[Optional: show an example input/output.]

🧪 **Example**

### Objective  
Summarize the findings of the latest WHO mental health report.

### Context  
The report outlines the global increase in anxiety and depression post-pandemic.

### Instructions  
- Highlight main causes and affected demographics.  
- Include proposed policy recommendations.

### Constraints  
- Max 150 words.  
- Use clear, accessible language.

### Output Format  
- Bullet point summary.

---

## 🔹 2. Few-Shot Prompting

📌 **Purpose:**  
To train the model with 2–5 examples that establish a pattern before giving it a new input.

✅ **Ideal Use Cases:**

- Data labeling (e.g. sentiment classification, translation)  
- Format mimicking (e.g. resume rewriting, headline creation)

🧩 **Template**

### Task  
[Describe the task.]

### Examples  
Input: [Sample input 1]  
Output: [Sample output 1]

Input: [Sample input 2]  
Output: [Sample output 2]

...

### Now, complete the following:  
Input: [New input]  
Output:

🧪 **Example**

### Task  
Classify each sentence as POSITIVE, NEGATIVE, or NEUTRAL sentiment.

Input: I love this product!  
Output: POSITIVE

Input: It’s okay, not great.  
Output: NEUTRAL

Input: Terrible customer service.  
Output: NEGATIVE

### Now, complete the following:  
Input: The movie was better than I expected.  
Output:

---

## 🔹 3. Chain-of-Thought Prompting

📌 **Purpose:**  
To guide the model in producing multi-step reasoning by explicitly showing how to think through the problem.

✅ **Ideal Use Cases:**

- Math word problems  
- Logical decision-making (e.g. legal, business strategy)

🧩 **Template**

### Question  
[Pose a complex or multi-step problem.]

### Instructions  
Explain your reasoning step by step.

### Response  
Let's think step by step.  
1. [...]  
2. [...]  
...  
Final Answer: [...]

🧪 **Example**

### Question  
If eggs cost $2.50 per dozen, how much would 18 eggs cost?

### Instructions  
Explain your reasoning step by step.

### Response  
Let's think step by step.  
1. A dozen eggs = 12 eggs.  
2. $2.50 / 12 = $0.208 per egg.  
3. 18 × $0.208 = $3.75.  
Final Answer: $3.75

---

## 🔹 4. Multimodal Prompting (Text-to-Image)

📌 **Purpose:**  
To generate or manipulate images based on detailed textual instructions.

✅ **Ideal Use Cases:**

- Creative visuals for branding or media  
- UI/UX mockup generation for design teams

🧩 **Template**

### Description  
[What is the scene, object, or idea?]

### Style  
[Artistic direction: photo, sketch, digital art, oil painting, etc.]

### Colors  
[Preferred color palette.]

### Lighting  
[Natural, neon, moody, etc.]

### Composition  
[How elements are arranged.]

### Additional Details  
[Any specific textures, expressions, environments.]

🧪 **Example**

### Description  
A futuristic library floating in space.

### Style  
Digital art with sci-fi influence.

### Colors  
Black, blue, silver with hints of orange glow.

### Lighting  
Soft ambient lighting with glowing book edges.

### Composition  
Wide-angle view with book orbs orbiting a central core.

### Additional Details  
Include a human silhouette reading a holographic book.

---

## 🔹 5. Comparative Prompting (A/B Testing)

📌 **Purpose:**  
To test how slight differences in phrasing, structure, or context affect the model's output.

✅ **Ideal Use Cases:**

- UX writing and conversion testing  
- Evaluating LLM performance (e.g. GPT vs Gemini)

🧩 **Template**

### Task  
[Describe the intended task.]

### Prompt A  
[First variation of prompt.]

### Prompt B  
[Second variation of prompt.]

### Evaluation Criteria  
- Accuracy  
- Creativity  
- Clarity  
- Factual consistency

### Output A:  
[...]

### Output B:  
[...]

🧪 **Example**

### Task  
Write a short bio for a UX designer with 5 years of experience.

### Prompt A  
"Write a professional 2-line LinkedIn bio for a UX designer with 5 years of experience in fintech."

### Prompt B  
"Summarize the professional journey of a fintech UX designer with 5 years of experience in 2 impactful lines."

### Evaluation Criteria  
- Clarity  
- Tone  
- Industry-specific relevance

### Output A:  
"Experienced UX Designer specializing in fintech, with a passion for intuitive product experiences and cross-functional collaboration."

### Output B:  
"Crafting fintech user journeys for 5+ years—designing products that merge usability, trust, and innovation."

---

## 📌 Best Practices for Prompt Engineering

- **Start with clear objectives:** Know exactly what you want the model to do.  
- **Give sufficient context:** More detail usually means more relevant output.  
- **Be explicit about constraints:** Include length, tone, format, style, etc.  
- **Use examples generously:** Especially with few-shot or structured tasks.  
- **Iterate and refine:** Prompting is experimental—test different setups.  
- **Adapt to the model:** Prompt length/style may vary across GPT, Claude, Gemini, etc.

---

## 📚 Resources That Helped Me

- OpenAI Cookbook  
- Google Prompt Engineering Guide  
- DeepLearning.AI & Andrew Ng (Prompt Engineering for Developers)  
- DigitalOcean: Prompt Engineering Best Practices  
- GitHub discussions, technical blogs & community insights (2024–2025)

---

> Built as a reference for myself, but shared in case it’s useful to you too.
>  
> 📬 Got improvements or tips? I’d love to hear them!
