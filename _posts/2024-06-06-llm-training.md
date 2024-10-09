---
title: "How AI Assistants Learn: The Training Process of Large Language Models"
date: 2024-06-06
permalink: /posts/llm-training/
tags:
  - LLMs
---

Understanding the training process of AI assistants reveals how they evolve from simple language models to sophisticated, useful tools. Here's a breakdown of the stages involved.

## Step 1: Pre-training on Massive Text Data

The initial stage is about compressing knowledge to obtain a base model. Terabytes of unlabelled internet data and months of GPU compute are required to create a base model that fulfils a simple objective: to predict a missing or next word in a sentence.

This simple yet powerful objective forces the neural network to internalise a wealth of knowledge about the world. The model undergoes self-supervised learning to identify patterns in how words relate to each other, essentially compressing this vast knowledge into gigabytes of parameters.

However, these base models have limitations. Although they can predict the next word, the output is not usable. It is simply a probability distribution learned from internet data.

## Step 2: Instruction Fine-tuning for an Assistant Model

To transform the base model into a useful assistant, it undergoes further training on high-quality, human-generated question-answering datasets instead of broad internet documents. This fine-tuning stage aligns the model's capabilities with the desired task of answering questions, enabling it to provide more relevant and coherent responses.

While the model can learn new information during fine-tuning, this learning is less comprehensive compared to full training. The model's knowledge is primarily based on data from the initial pre-training stage, known as the knowledge cut-off date.

## Step 3: Enhancing Performance with Feedback (Optional)

Usually there is a final stage involving reinforcement learning. The model generates multiple responses, which are judged by humans or more advanced models. This feedback is then used to fine-tune the model further, improving its performance and accuracy.

Through these stages, AI assistants become more than just language predictors. They evolve into powerful tools capable of understanding and responding to human queries effectively.
