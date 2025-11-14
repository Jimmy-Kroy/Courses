# 🤖 Comprehensive Guide to AI Prompting Best Practices

## 💡 What is Prompting?

Prompting is **the process of providing specific instructions to a generative AI (GenAI) tool to receive new information or to achieve a desired outcome on a task**. Learning how to prompt effectively is crucial because it is considered **the new language by which we converse with computers**. To achieve the best results, users need to be **precise in defining what they need**.

---

## 🎯 The Google T-C-R-E-I Prompting Framework

An effective prompt follows a five-step framework: **T**ask, **C**ontext, **R**eferences, **E**valuate, and **I**terate. This framework provides a dependable formula for writing prompts that applies across various tools and models.

**Remember:** **T**houghtfully **C**reate **R**eally **E**xcellent **I**nputs

---

### 1️⃣ Task (T)

The **Task** is the foundation of any prompt, describing what you want the GenAI tool to help you with. When defining the task, you must be clear and specific, as vague instructions are likely to lead to poor results.

**✨ Key Tips:**
- Include a **persona** (who should the AI act as?)
- Specify a **format preference** (how should the output look?)

---

### 2️⃣ Context (C)

**Context** involves providing the necessary details that help the GenAI tool understand what you need.

**✨ Key Tips:**
- **The more relevant details you include, the better your output will be**
- Include background information, your goals, the reason for the task, or things you've already tried
- Context can be the **longest part of a prompt** — and that's okay!

---

### 3️⃣ References (R)

**References** are examples or additional sources that the GenAI tool can use to inform and steer the output. Giving examples can mean asking the tool to **learn from the tone, style, or length** of a given reference.

**✨ Key Tips:**
- Providing multiple references is known as **few-shot prompting**
- The "sweet spot" is typically **between 2-5 references**
- Too few may not provide enough context; too many could limit creativity
- References can include text, images, or even audio (multimodal prompting)

---

### 4️⃣ Evaluate (E)

**Evaluation** means critically evaluating the AI-generated content before incorporating it into your workflows.

**✨ Key Tips:**
- Check the output for **accuracy, bias, relevance, and consistency**
- GenAI tools **lack critical-thinking skills and human awareness**
- Always check for **hallucinations** — AI outputs that don't match reality or are factually untrue
- Use a **human-in-the-loop** approach: always verify before using
- **Fact-check and cross-reference** important information

⚠️ **Warning:** Mistakes will appear, sometimes in subtle ways. Never blindly trust AI outputs, especially for factual content.

---

### 5️⃣ Iterate (I)

**Iteration** means constantly improving the prompt or interaction. If the output isn't what you need, try again by adding more information or tweaking your prompt. Prompting is an **iterative process** and a **dialogue**, not a "one and done" command.

**✨ Always Be Iterating (ABI)**

**Iteration Methods:**

1. **Revisit the framework** — Add more specificity (persona, format, context, references)
2. **Break into smaller tasks** — Yield more precise results
3. **Tweak phrasing** — Try analogous tasks or different wording
4. **Introduce constraints** — Limit categories, length, or formats to narrow the output

---

## 👤 Prompt Construction: Persona, Format, and Structure

### Why Provide a Persona?

**Persona** refers to the expertise you want the GenAI tool to draw from. Specifying a persona (e.g., "a professional speech writer" or "a marketing executive with 15 years of experience") **instructs the AI tool to draw its expertise from a particular field, filtering out irrelevant information**.

**Example:** "Imagine you're a world-class marketer with a $50,000 budget and a 3-month timeline..."

### Why Specify Output Format?

**Format** refers to **how you want the output to appear**. This could be:
- 📝 Bulleted list
- 📊 Table
- ✍️ Short sentences or paragraphs
- 📈 Chart descriptions

Specifying the format avoids misunderstandings and ensures you get exactly what you need.

### Does Prompt Structure Matter?

**The order of how you construct a prompt is less important than the substance of the prompt itself.** As long as you're thoughtfully creating excellent inputs—including the specific Task, Context, and References—the output should be great.

---

## 📋 Example Prompts Illustrating Principles

### Example 1: Task + Persona + Format + Context

**Prompt:**
> "You're a movie critic who specializes in Italian film. Create a table that contains the greatest Italian films of the 1970s, and separate them into genres like thrillers, dramas, and comedies. Provide a 100-word summary of each movie as well as details about the production including director and release year."

**Components:**
- **Persona:** Movie critic specializing in Italian film
- **Task/Format:** Create a table with 100-word summaries
- **Context:** Italian films, 1970s, separated by genre

---

### Example 2: Adding Context

❌ **Weak Prompt:**
> "Give me some ideas for a birthday present under $30."

✅ **Strong Prompt:**
> "Give me five ideas for a birthday present. My budget is $30. The gift is for a 29-year-old who loves winter sports and has recently switched from snowboarding to skiing."

**Why it's better:** Defines budget, age, interests, and recent changes.

---

### Example 3: Iterating with Persona + Format

❌ **Initial Prompt:**
> "Give me five blog post ideas."

✅ **Revised Prompt:**
> "You are an expert on sports nutrition. Provide five blog post headlines that summarize the biggest trends happening in the industry for an audience of physical therapists working with professional basketball players."

**Why it's better:** Added persona, specific format (headlines), and targeted audience.

---

### Example 4: Introducing Constraints

**Prompt:**
> "Create a bulleted list including the latest developments in the restaurant industry specific to urban areas that could impact the public reception of a dining experience using only ingredients native to the region. This list should only include trends from cities with a population of more than 500,000 people, and should only include trends relevant to vegetarian and vegan restaurants."

**Components:**
- **Constraints:** Population > 500,000, vegetarian/vegan focus, native ingredients
- **Format:** Bulleted list
- **Context:** Urban restaurant industry trends

---

### Example 5: Multimodal Prompting (Image + Text)

**Prompt (with nail art photo):**
> "Write a social media post featuring this image. The post should be fun, short and focus on the fact it's a collection of new designs I am selling."

**Components:**
- **Reference:** The uploaded image
- **Task:** Write a social media post
- **Context:** Fun, short, selling new designs

---

### Example 6: Multimodal Prompting (Image + Format)

**Prompt (with conference schedule photo):**
> "Extract the times of the keynote speaker and two panel discussions from this schedule into a table."

**Components:**
- **Reference:** Schedule image
- **Task/Format:** Extract times into a table

---

### Example 7: Iterating Image Generation

**Initial Prompt:**
> "Create an image of an electric guitar."

**Follow-up Prompt:**
> "Now, make the sky stormy with lightning hitting the guitar."

**Components:**
- **Task:** Refine previous output
- **Constraint:** Add specific elements (storm, lightning)

---

## 🎓 Key Takeaways

1. ✅ Be **specific and clear** with your task
2. ✅ Provide **rich context** to guide the AI
3. ✅ Use **references and examples** (2-5 is ideal)
4. ✅ Always **evaluate and fact-check** outputs
5. ✅ **Iterate continuously** — prompting is a dialogue

Remember: **T**houghtfully **C**reate **R**eally **E**xcellent **I**nputs!

---

*Master these principles and you'll unlock the full potential of AI tools in your workflows.* 🚀