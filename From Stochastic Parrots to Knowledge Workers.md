Hook
====
Gen AI is so powerful (Firefox bug fixes) but fails on simple things

Basics of LLM
=============
1. Decoder Architecture
2. Pre-training - Chinchilla Scaling (paper), Task Generalization (T5 paper)
3. RLHF - Instruction Following
4. Problem - Le Cun's error accumulation


Making LLMs Useful
==================
Pre-training and RLHF Done

|Use Case Example | Problem | Solution| 
|-----------------|---------| --------|
| Talk to your documents |Frozen Knowledge, Limited Context Window | RAG|
| Data Extraction | Ambiguity in instructions, Fine Grained Control over output | Few Shot Prompting, ICL paper  |
| Search over diverse knowledge sources | Multi hop tasks - Theoretical Limit on Bounded Depth Transformer (paper) | Prompt Chaining & Workflows, Million Step, Test Time Scaling|
|Customer Service |Prompt Injection, Take Action | Instruction Heirarchy, Agents, React, Structured Generation |

