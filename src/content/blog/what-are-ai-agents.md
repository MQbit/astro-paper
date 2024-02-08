---
author: Q Bit
pubDatetime: 2024-01-08T18:16:00.000Z
modDatetime:
title: What are AI Agents?
featured: false
draft: false
tags:
  - AI Agents definition
description: A deep dive into the AI interface of the future
---

# What are AI Agents?

AI Agents are autonomous programs designed to perform tasks that would require human intelligence. They're a subset of artificial intelligence that interact with the world around them, make decisions, and learn from outcomes to improve their performance over time.

## Definition

> Agent = a large language model setup to run iteratively with some goals / tasks defined.
> This is different than how large language models (LLM’s) are “normally” used in tools like ChatGPT where you ask a question and get a single response as the answer.
> Agents have complex workflows where the model essentially talks to itself without a human forcing every part of the interaction.

An AI agent, in the realm of computer science and artificial intelligence, is an entity that perceives its environment through sensors and acts upon that environment through actuators. They're programmed to fulfill a specific purpose, such as providing customer service, managing a smart home, or even playing a game.

## Types of AI Agents

There are several types of AI agents, each with different capabilities:

- **Simple Reflex Agents**: They act only on the current percept, ignoring the rest of the percept history.
- **Model-Based Reflex Agents**: These agents maintain an internal state based on the percept history to help in decision-making.
- **Goal-Based Agents**: These agents act to achieve their goals and can adapt their actions accordingly.
- **Utility-Based Agents**: They not only pursue goals but also do it in a way that maximizes a utility function.
- **Learning Agents**: These agents have the ability to learn from their experiences and improve over time.

## Applications

AI agents are employed in a variety of settings:

- **Virtual Personal Assistants**: Like Siri or Alexa, these agents help with tasks such as setting reminders or answering questions.
- **Chatbots and Customer Service**: AI agents can handle customer queries, bookings, and provide information services.
- **Healthcare**: From diagnostics to personalized treatment plans, AI agents are revolutionizing the medical field.
- **Finance**: AI agents are used in trading, fraud detection, and personalized banking services.

## The future of AI Agents

The idea of AI Agents is not going anywhere, these are the first entities powered by general purpose AI that can solve tasks. Over time, they will get more and more sophisticated powered by more powerful models and tools. For example, you can imagine a simple customer service agent which can take someones problem and iteratively break it down, solve it, and validate the aswer. A few things are required to get there:

- **Much more powerful models**, GPT-4 works great but the use cases are still limited today
- **Better tooling**, the space we looked at is a great example of something super simple and useful, but lacking for true production use cases
- **Different architecture**, as the models evolve, breaking the goal into sub-tasks may no longer be the right design decision, there are many approaches like starting from the end state and working your way backwards which would be potentially just as effective.

## reference

- [What are GPT Agents? A deep dive into the AI interface of the future](https://logankilpatrick.medium.com/what-are-gpt-agents-a-deep-dive-into-the-ai-interface-of-the-future-3c376dcb0824)
