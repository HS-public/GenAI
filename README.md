# GenAI

Practical Optimizations
========================

In use data should be analyzed to determine the architecture of prompt workflow: https://blog.promptlayer.com/prompt-routers-and-modular-prompt-architecture-8691d7a57aee/

Evaluators can be turned into reward function in Reflexion: https://arxiv.org/pdf/2404.06474

LinkedIn SQL Agent with knowledge graph: https://www.linkedin.com/blog/engineering/ai/practical-text-to-sql-for-data-analytics . Chat to DB https://github.com/garyzava/chat-to-database-chatbot. Uber: https://www.uber.com/blog/query-gpt/

RAG Best Practices: Contrastive In-context Learning RAG, Focus Mode RAG, and Query Expansion RAG achieved the best results: https://arxiv.org/pdf/2501.07391

Chip Huyen on Agents: https://huyenchip.com/2025/01/07/agents.html

Prompt Injection Defenses: https://github.com/tldrsec/prompt-injection-defenses

Simple Test Time Scaling (appending "Wait" and SFT) - https://arxiv.org/pdf/2501.19393

Use Gemini 2.0 for PDF -> Markdown parsing https://www.sergey.fyi/articles/gemini-flash-2

Few Shot Prompting is bad (Debateable). Partial or dynamic few shot instead: https://gloochat.notion.site/BAML-Advanced-Prompting-Workshop-Dec-2024-161bb2d26216807b892fed7d9d978a37#161bb2d2621680faae18cdb43f22d9b3

Theory
======
In modern LLM, tokens later in the context are easier to predict than tokens earlier in the context. This can be used as direct measurement of In Context Learning (which includes, but is not limited to, Few Shot Learning). ICL is enabled by induction heads (althought they can also enable wholesale repeating) https://transformer-circuits.pub/2022/in-context-learning-and-induction-heads/index.html

Reinforcement Learning for LLM: A Roadmap to Reproduce o1 from Reinforcement Learning Perspective: https://arxiv.org/pdf/2412.14135 ; DeepSeek R1: https://github.com/deepseek-ai/DeepSeek-R1/blob/main/DeepSeek_R1.pdf. Efficient RL: https://hkust-nlp.notion.site/simplerl-reason

Meta Chain of Thought https://arxiv.org/abs/2501.04682

SFT Memorizes, RL Generalizes: https://arxiv.org/pdf/2501.17161v1
