# LLM Evaluation with Phoenix

## Overview
This project presents an end-to-end research assistant system that retrieves relevant literature, generates structured summaries, and systematically evaluates LLM agent performance using Phoenix. The evaluation framework focuses on three critical dimensions: tool-calling reliability (router accuracy), hallucination detection, and summary factual accuracy, enabling transparent and traceable assessment of LLM behaviors in research workflows.

## Motivation
In research-oriented applications, accuracy and reliability are more critical than surface-level fluency. While LLMs can produce convincing outputs, unverified or hallucinated information poses significant risks in academic and analytical contexts. This project is motivated by the need for systematic and reproducible evaluation of LLM-based research assistants. By explicitly measuring tool-calling correctness, hallucination rates, and summary accuracy, the system allows users to assess the credibility of generated outputs and better understand the limitations of LLM agents in real research settings.

# Tech Stack
- LLM: OpenAI GPT-4o
- Framework: OpenAI Python SDK, LangChain (ChatOpenAI wrapper)
- Tracing: Phoenix AI (OpenTelemetry)
- Web Search: Tavily API
- UI: Streamlit
- Evaluation: Phoenix Evals (LLM-as-a-judge)

## Demo
▶ **YouTube Demo (5 minutes)**  
[https://www.youtube.com/watch?v=VIDEO_ID](https://youtu.be/UWhUrhJEork)

> This demo shows the end-to-end evaluation workflow and how Phoenix traces are used.

## Code
GitHub Repository  
https://github.com/yyunchieh/LLM-Evaluation-with-Phoenix
