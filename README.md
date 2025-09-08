# GenAI

Practical Optimizations
========================

In use data should be analyzed to determine the architecture of prompt workflow: https://blog.promptlayer.com/prompt-routers-and-modular-prompt-architecture-8691d7a57aee/

Prompt Improver: https://docs.anthropic.com/en/docs/build-with-claude/prompt-engineering/prompt-improver

Reflexion: https://www.promptingguide.ai/techniques/reflexion

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

Test Time Scaling
=================
Long COT survey: https://arxiv.org/pdf/2503.09567

LLMs exhibit an internal chain of thought: https://arxiv.org/abs/2505.14530

COT as solution to impossibility of bounded depth Transformers solving math problems: https://proceedings.neurips.cc/paper_files/paper/2023/hash/dfc310e81992d2e4cedc09ac47eff13e-Abstract-Conference.html

Faithful COT for interpretability: https://par.nsf.gov/biblio/10463284

Soft COT: https://arxiv.org/abs/2502.12134

Chain of X: https://arxiv.org/abs/2404.15676

Reasoning for translation: https://arxiv.org/abs/2502.11544

LRM as Judge: https://arxiv.org/abs/2504.00050

Electronic Circuit Model to understand ICL and COT: https://arxiv.org/abs/2502.03325

Anthropic - deceptive reasoning: https://assets.anthropic.com/m/71876fabef0f0ed4/original/reasoning_models_paper.pdf

Dynamic Depth Scaling Transformer: https://arxiv.org/abs/2502.13842

Mechanistic Understanding COT: https://arxiv.org/abs/2402.18312

Implicit Reasoning https://arxiv.org/abs/2509.02350
