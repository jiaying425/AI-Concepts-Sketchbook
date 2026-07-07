# AI Concepts Sketchbook

A visual sketchbook for understanding AI systems: from classic deep learning models to transformers, RAG, agents, memory, tools, evaluation, and deployment thinking.

This repository is a public portfolio of AI concept diagrams and engineering sketches. The goal is to make complex AI ideas easier to reason about visually, while keeping the work-in-progress quality of a real learning notebook.

## How This Repo Is Organized

The repo separates **concepts** from **engineering** because they answer different questions.

- [`concepts`](concepts/) explains how AI ideas work: model foundations, RAG, and agents.
- [`engineering`](engineering/) shows how AI systems are built, evaluated, operated, and improved: harnesses, memory, tools, observability, evals, gates, and iteration loops.

In short: `concepts/` is the "how it works" layer, and `engineering/` is the "how to make it useful and reliable" layer.

## Learning Path

1. **AI Model Foundations**  
   Visual notes on classic deep learning models and transformer architecture, from CNNs, RNNs, GANs, and reinforcement learning to tokenization, embeddings, attention, feedforward layers, and parameter intuition.

2. **Retrieval-Augmented Generation**
   A concept map for chunks, embeddings, vectors, vector databases, semantic search, retrieval logic, and top-k relevance tradeoffs.

3. **AI Agents**
   System-level sketches of LLM agents, prompts, memory, tools, APIs, planning, and reasoning loops.

4. **Agent Engineering**
   Architecture sketches for harnesses, memory systems, guardrails, tool calls, evals, traces, observability, gates, and release workflows.

5. **LLM Evals and Observability**
   Operational sketches for tracing, judge-based scoring, release gates, and iteration from feedback.

## Repository Map

| Section | Description |
| --- | --- |
| [`concepts/model-foundations`](concepts/model-foundations/) | Classic deep learning models and transformer foundations |
| [`concepts/rag`](concepts/rag/) | Retrieval-augmented generation concept sketch |
| [`concepts/ai-agents`](concepts/ai-agents/) | AI agent architecture and tool-use sketch |
| [`engineering/agent-harness`](engineering/agent-harness/) | Agent harness, memory, evaluation, and release engineering |
| [`engineering/evals-and-observability`](engineering/evals-and-observability/) | LLM evals, tracing, observability, release gates, and feedback loops |
| [`exports`](exports/) | Future PNG and PDF exports for easier previewing |

## Featured Sketches

- **Agent Harness and Engineering**: an advanced system sketch connecting prompts, memory, RAG, tool calls, guardrails, evals, observability, and release gates.
- **LLM Evals and Observability**: a feedback loop for traces, judge-based scoring, metrics, gates, release, and iteration.
- **Transformer Workflow**: a visual walk-through of transformer internals and GPT-style parameter calculations.
- **RAG**: a compact view of retrieval pipelines and the relevance questions behind top-k search.
- **What Is an AI Agent**: a high-level map of agents, tools, workflows, databases, APIs, and generation capabilities.

## File Formats

Most sketches are stored as `.drawio` or `.excalidraw` files so they can be opened and edited in visual diagramming tools.

Planned exports:

- `.png` for GitHub preview
- `.pdf` for portfolio sharing

## Status

This is an evolving public sketchbook. Diagrams may be refined over time for clarity, spelling, structure, and visual consistency.
