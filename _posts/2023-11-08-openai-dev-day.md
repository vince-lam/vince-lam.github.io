---
title: "Unpacking OpenAI’s Dev Day: A Leap Forward in AI Development"
date: 2023-11-08
permalink: /posts/openai-dev-day/
tags:
  - AI
  - GenAI
---

OpenAI's recent [Dev Day](https://youtu.be/U9mJuUkhUzk) announcements, such as the launch of GPT-4 Turbo, custom GPTs, and the GPT Store, are going to cause a massive disruption to not just the AI landscape of applications and services but also millions of businesses around the world - by making these powerful tools more accessible.

OpenAI keeps raising the bar of LLM/LMM chatbots, with their tightly integrated technologies, making it difficult for their competitors to keep up, let alone the open-source community. Below is a summary and my thoughts.

![Sam Altman presenting at OpenAI Dev Day](/images/blog/2023-11-openai-dev-day.jpeg)
<p style="text-align: center;font-size:12px">Key announcements at OpenAI Dev Day <a href="https://youtu.be/U9mJuUkhUzk">(Source)</a></p>

## GPT-4 Turbo Revealed

### Improved Contextual Understanding

The newly unveiled GPT-4 Turbo has made vast improvements on its context window size to 128K tokens (previously 8K, then increased to 32K tokens), which is roughly 300 book pages worth of tokens. This puts it head-to-head with competitors like Anthropic's [Claude](https://claude.ai/). Supposedly there is improved accuracy over longer contexts too, we will wait and see if that holds true from evaluations on open-source tests.

### Enhanced Developer Control

Developers now have more control over their AI tools:

* **JSON Mode**: Ensures the model always outputs valid JSON, making it seamless for applications to parse responses.
* **Reproducible Outputs**: Introducing a seed parameter allows for consistent outputs, lending a deterministic nature to what is an inherently probabilistic process. This is a game-changer for building trust in AI applications. Will be good to see competitors follow suit. See [here](https://platform.openai.com/docs/guides/text-generation/reproducible-outputs) for more info.
* **Improved Function Calling**: Instead of calling one function at a time to model, you can instead combine all requests into a single prompt

### Enriched World Knowledge and Modalities

* **Better World Knowledge**: GPT-4 and GPT-3.5 now possesses knowledge up to April 2023 (previous cut-off date was September 2021), with a commitment to more frequent updates.
* **Integrated Retrieval**: Models can now leverage external documents or databases, enriching its responses with a broader knowledge base.
* **Vision and Voice Integration**: Following the release of DALL-E 3 for image generation, GPT-4 now accepts visual inputs, such as enhancing a headshot to a professional level, and includes a text-to-speech (TTS) model with six realistic voices. This leap forward will be interesting to compare with HuggingFace's [distil-whisper](https://huggingface.co/distil-whisper) TTS model in terms of transcription speed and accuracy.

### Customization and Legal Assurance

* **Fine-Tuning**: Now extended to GPT-4, developers can refine the model's performance with minimal data, allowing for more personalized and efficient applications.
* **Copyright Shield**: OpenAI has committed to defending its customers against copyright infringement claims, covering legal costs for both ChatGPT Enterprise and API users.

### Accessibility and Affordability

* **Major Price Cut**: Despite all these enhancements, GPT-4 Turbo is more affordable, with token costs significantly reduced, leading to a blended rate that's over 2.75 times cheaper for most users.

Many of these updates have been integrated into ChatGPT. For more details, such as timelines, it's worth checking their [blog post](https://openai.com/blog/new-models-and-developer-products-announced-at-devday).

## Introduction of Assistant APIs, Agents/GPTs and the GPT Store

**Assistant API** allows developers to incorporate specialized assistant functions into their applications, such as a Code Interpreter capable of coding and file generation within a sandbox environment. Check out their [documentation](https://platform.openai.com/docs/assistants/how-it-works) for more info.

### Mainstream Agents

The concept of 'GPTs' as OpenAI terms them, is now here, allowing the creation of agents that can perform real-world actions. This is now integrated within ChatGPT, providing users with the ability to instruct, inform, and actuate GPTs with external knowledge and capabilities.

### Lowering Development Barriers

OpenAI has made it substantially easier for non-coders to build with LLMs, thanks to a low/no-code UI. With natural language processing capabilities, the process of creating a GPT agent has been simplified to the point where it can be done vocally.

> *"The hottest programming language is English"* - Andrej Karpathy

It was already relatively straightforward to build LLM apps with some python knowledge using frameworks such as **LangChain** and **LlamaIndex** but OpenAI have abstracted this even further - removing the need code embeddings or text chunking or via a visual UI such as Flowise.

### The GPT Store: A New Marketplace

The GPT Store could potentially become the "Apple App Store" for AI, allowing developers to either keep their custom GPTs private, share them within an enterprise, or publish them publicly. The revenue-sharing model is still to be disclosed, but it's clear that this platform will impact startups and businesses that have built wrapper services/Chatbots around OpenAI's API.

![GPT Store](/images/blog/2023-11-openai-gpts.jpeg)
<p style="text-align: center;font-size:12px">GPT Store <a href="https://youtu.be/U9mJuUkhUzk">(Source)</a></p>

### Competing with Poe

OpenAI is not the first to release an AI marketplace, [Poe](https://poe.com/login) already allows users to build chatbots with other models, such as Claude, [Llama](https://ai.meta.com/llama/), and [Stable Diffusion](https://stablediffusionweb.com/), but Poe lacks the market share and integrated multimodal input of OpenAI. The GPT Store is poised to dominate the AI marketplace. It will be interesting to see if OpenAI can keep its marketshare when Microsoft and Google will integrate such AI into the products that people use in their day-to-day lives.

> *"We Have No Moat, and Neither Does OpenAI"* - Google employee

### Environmental Considerations

The expansion of AI services raises concerns about energy consumption and environmental impact. While OpenAI operates on net-zero emissions through carbon credits and Microsoft's Azure Infrastructure, the water usage and carbon footprint associated with increased data center activity remain significant challenges.

## Reflections on OpenAI’s Strategy

OpenAI has clearly been attentive to the developer community, addressing their needs and challenges. The innovations and strategic moves suggest a trajectory toward an OpenAI-centric ecosystem in the AI market. The question remains: How will competitors and the open-source community keep pace with such rapid advancements?

The Dev Day has undoubtedly set a new pace for innovation and accessibility in AI. As we embrace these new tools and platforms, it's vital to balance the enthusiasm for progress with a mindful approach to the environmental and competitive implications.

![Could this be the future of the MAD (Machine Learning, Artificial Intelligence) Landscape? - Source unknown](/images/blog/2023-11-2024-MAD-landscape.png)
<p style="text-align: center;font-size:12px">Could this be the future of the MAD (Machine Learning, Artificial Intelligence) Landscape? - Source unknown </p>
