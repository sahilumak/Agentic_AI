# Agentic AI Learning Journey 🚀

This repository documents my hands-on journey learning **Agentic AI**, one concept at a time.

## Learning Progress

### LangChain fundamentals
- Configuring chat models and model providers.
- Integrating Google Gemini with LangChain.
- Exploring streaming responses.
- Exploring batching for processing multiple inputs.

These topics reflect my learning notes and experiments so far. I will add topics here as I implement and verify them in this repository.

## Current Focus

- Continue practicing LangChain fundamentals with small examples.
- Build on model invocation patterns and understand how tools fit into agent workflows.
- Record examples, explanations, and outcomes as the code is added.

## Learning Log

| Area | Progress |
|---|---|
| Model/provider setup | Studied |
| Gemini integration | Studied |
| Streaming | Studied |
| Batching | Studied |
| Tool calling | Basic tool binding and tool-call inspection practiced; execution loop needs debugging |
| Structured output (Pydantic / TypedDict) | Pydantic concepts documented; implementation pending |
| Middleware | To explore |

> Progress labels are intentionally conservative: a topic is not marked complete until there is a concrete example or implementation to support it.

## Repository Structure

The notebooks below contain the current examples and notes:

- [Model integration with Google Gemini](UpdatedLangchain/1-Model-Integration.ipynb)
- [Streaming and batching](UpdatedLangchain/2-Streaming-Batch.ipynb)
- [Tool creation and tool-call inspection](UpdatedLangchain/3-Tools-Creation.ipynb) — the manual execution loop still needs debugging.
- [Tool demo with a price lookup](UpdatedLangchain/4-Demo-Tool.ipynb) — includes a tool-call example; a later notebook cell records a kernel crash.
- [Structured output and Pydantic notes](UpdatedLangchain/5-Structured-Output(Pydantic).ipynb) — explanatory notes are present, but the code cell is still empty.

## Goal

Learn Agentic AI through practical implementation, clear notes, and incremental projects using tools and frameworks such as LangChain and LangGraph.
