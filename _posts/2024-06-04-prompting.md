---
title: "Prompting Tips for Better LLM Outputs"
date: 2024-06-04
permalink: /posts/prompting/
tags:
  - LLMs
---

Large Language Models (LLMs) are complex probabilistic machines that predict the next word. Prompt engineering is about conditioning them for desired outputs. Each instruction steers the model's generation. Here are tips to prompting LLMs to generate useful outputs to your problems.

**1. Start with roles.** Who is your AI pretending to be? A writing coach? A data analyst? By assigning a persona and responsibilities, you steer content, tone, and style.

**2. Set clear goals.** What do you want to achieve? Be specific on the LLM's task. The more descriptive and detailed the prompt, the better the results. Avoid imprecise descriptions.

**3. Use positive language.** LLMs prefer "do this" over "don't do that." It's more specific, easier to grasp. So, frame your requests positively.

**4. Break tasks down.** Treat your AI like a human intern. Complex task? Break it into simpler prompts. They're easier to understand and complete.

**5. Structure with delimiters.** Use tags like <example> {your example} </example> or ###Instruction### to separate parts. This helps the LLM parse your input effectively.

**6. Specify output format.** Want Markdown? Lists? JSON? Ask for it. The more detail you provide about context, length, format, and style, the better. This prevents misinterpretation and ensures usable output.

**7. Example-driven prompting** (aka few-shot prompting or N-shot prompting). This technique enables in-context learning where specific format examples are provided in the prompt to steer the LLM to better performance.

**8. Use Chain-of-Thought (CoT).** Give your AI "space to think" with phrases like "think step by step" or “provide your thought process to explain how you reasoned this response”. This intermediate reasoning yields better results for complex tasks.

For the power users out there:

- **Use the System Prompt Directly.** Use the system prompt to change settings directly instead of the user prompt for more control over the model's behavior.

- **Adjust Temperature and Top P for more (or less) creativity.** Lower values yield more deterministic outputs, while higher values increase variability.