---
title: Prompting
author: Zachary Loeber
date: 2025-3-3
categories:
  - notes
  - AI
  - LLM
tags:
  - notes
---
```prompt
Create a summary markdown table of the LLM prompting techniques covered here https://www.forbes.com/sites/lanceeliot/2024/05/09/the-best-prompt-engineering-techniques-for-getting-the-most-out-of-generative-ai/. Be certain to include in this table an approximate token usage range for each method (with one-shot prompting being very low and chain-of-thought possibly being very high).
```

| **Technique**                         | **Description**                                                                                    | **Approx. Token Usage Range** |
| ------------------------------------- | -------------------------------------------------------------------------------------------------- | ----------------------------- |
| Browbeating Prompts                   | Uses assertive or demanding language to push AI for better responses.                              | Medium (~100-300)             |
| Catalogs/Frameworks Prompting         | Provides a structured list or framework to guide AI’s response.                                    | Medium (~100-300)             |
| Certainty/Uncertainty Prompting       | Specifies confidence level desired in AI’s response (e.g., certain or exploratory).                | Low (~50-100)                 |
| Chain-of-Density (CoD) Prompting      | Iteratively increases detail density in responses for concise yet rich outputs.                    | High (~300-1000)              |
| Chain-of-Feedback (CoF) Prompting     | Incorporates iterative feedback loops to refine AI outputs.                                        | High (~300-1000)              |
| Chain-of-Thought (CoT) Prompting      | Encourages step-by-step reasoning to improve problem-solving accuracy.                             | Very High (~1000+)            |
| CoT Factored Decomposition Prompting  | Breaks down reasoning into sub-steps for complex tasks, building on CoT.                           | Very High (~1000+)            |
| Chain-of-Verification (CoV) Prompting | Prompts AI to verify each step of its reasoning to reduce errors.                                  | High (~300-1000)              |
| Conversational Prompting              | Engages AI in a dialogue-like exchange for natural, iterative responses.                           | Medium (~100-300)             |
| DeepFakes to TrueFakes Prompting      | Guides AI to distinguish or generate realistic vs. deceptive content.                              | Medium (~100-300)             |
| Directional Stimulus Prompting (DSP)  | Provides hints or directional cues to steer AI’s response.                                         | Low (~50-100)                 |
| Disinformation Detection Prompting    | Instructs AI to identify and flag potential misinformation in responses.                           | Medium (~100-300)             |
| Emotionally Expressed Prompting       | Uses emotional tone (e.g., excitement, urgency) to influence AI’s response style.                  | Low (~50-100)                 |
| End-Goal Prompting                    | Specifies the desired outcome upfront to focus AI’s response.                                      | Low (~50-100)                 |
| Essay-Compression Prompting           | Asks AI to summarize or compress lengthy content into concise forms.                               | Medium (~100-300)             |
| Fair-Thinking Prompting               | Encourages balanced, unbiased responses from AI.                                                   | Low (~50-100)                 |
| Flipped Interaction Prompting         | Reverses roles, asking AI to question the user or simulate a scenario.                             | Medium (~100-300)             |
| Generating Prompts via Generative AI  | Uses AI to craft prompts for itself, automating prompt creation.                                   | Medium (~100-300)             |
| Illicit/Disallowed Prompting          | Attempts to bypass AI restrictions (ethically questionable).                                       | Low (~50-100)                 |
| Imperfect Prompting                   | Embraces flawed prompts, refining through iteration rather than striving for perfection initially. | Low (~50-100)                 |
| Importing Text as Prompting           | Feeds external text (e.g., documents) into AI as context for responses.                            | High (~300-1000)              |
| One-Shot Prompting                    | Provides a single example to guide AI’s response (not explicitly listed but implied in context).   | Very Low (~10-50)             |
