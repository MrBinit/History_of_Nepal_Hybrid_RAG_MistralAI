# Rewriting Nepal’s Past: My Adventure with RAG, Mistral AI, and Forgotten Chronicles

The journey to understand Nepal’s complex and rich history often presents challenges, especially when relying on existing AI models, which frequently provide incomplete or inaccurate responses. This frustration led me to develop a specialized Language Learning Model (LLM) using advanced Hybrid Retrieval-Augmented Generation (RAG) techniques, combined with Mistral AI’s powerful 8x7b model. The goal was to create a tool that could accurately answer questions about Nepal’s history with depth and precision.

## Project Overview

To build a reliable knowledge base, I utilized authoritative sources on Nepal’s history, including:

- **Massacre at the Palace: The Doomed Royal Dynasty of Nepal** by Jonathan Gregson
- **A History of Nepal** by John Whelpton
- **History of Nepal** by Munsi Shew Shunker Singh and Pandit Shri Gunanand
- **A Case Study on the Nepal Maoist Party** published by the Stabilisation Unit
- **The Rise of the House of Gorkha** by Ludwig F. Stiller

These sources form the backbone of the knowledge base, enabling the model to provide well-rounded and authoritative answers. This project is not just a technical achievement but also a personal endeavor, driven by a passion for understanding my own country’s history.

## Why I Chose Mistral AI 8X7b

I chose Mistral AI 8X7b for my project because it’s an open-source model that delivers superior performance compared to other large language models, including LLaMA 3 70B. Despite its smaller size, Mistral AI 8X7b excels in generating high-quality, accurate results, making it an ideal choice for my project focused on exploring Nepal’s history.

## Why I Chose Hybrid RAG

A hybrid Retrieval-Augmented Generation (RAG) approach offers enhanced flexibility and accuracy by combining different retrieval techniques. Hybrid RAG integrates the strengths of both dense and sparse retrieval methods, allowing the model to capture a broader range of relevant information. This combination improves the quality of the generated content, especially in complex queries.

## Why Groq’s LPU for My Project?

Groq’s Logic Processing Unit (LPU) technology offers groundbreaking AI inference performance, ideal for real-time applications. It delivers up to 18 times faster performance than traditional GPUs, drastically reducing latency and enhancing user engagement. Groq’s architecture is optimized for large context windows and real-time fine-tuning, enabling highly accurate and responsive AI systems.

## Project Execution

For this project, I utilized Google Colab TPUv2, as the computational demands were relatively low. Below is an outline of how the project was executed:

### 1. Install Required Packages

First, install all necessary packages:

```bash
pip install -r requirements.txt
