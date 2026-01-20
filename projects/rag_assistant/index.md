---
layout: default
title: Assistant for Statistical Learning
---

# Assistant for Statistical Learning

## Overview
A configuration-driven RAG (Retrieval-Augmented Generation) system built with LangGraph for answering questions about The Elements of Statistical Learning. The project emphasizes reproducibility, agent-based orchestration, and evaluation of hallucination behavior.

## Motivation
Nowadays, many people turn to generative AI for quick answers.  But one major problem is that these models can hallucinate. Combining with my personal experiences, I tried to build a learning assistant which not only can support learning but also increase reliability at once.  It answers questions using "the Elements of Statistical Learning" this textbook as its source, and it shows the exact page numbers where each answer comes from.

# Tech Stack
- LLM: OpenAI GPT-4o
- Framework: LangChain, LangSmith
- Tracing: LangSmith
- UI: Streamlit
- Evaluation: LangSmith (LLM-as-a-judge)

## Code
GitHub Repository  
https://github.com/yyunchieh/Assistant-for-Statistical-Learning


