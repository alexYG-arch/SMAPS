# SMAPS

SMAPS stands for **Structured Multi-Agent Prompt System**.

This repository contains a white-paper-style specification for building modular, controllable, reusable, routable, and fault-tolerant prompt systems. The core idea is that prompts in complex AI workflows should be treated as structured engineering artifacts rather than one-off natural-language instructions.

## Repository Contents

- [`SMAPS.md`](./SMAPS.md) - Markdown version of the SMAPS specification.
- [`SMAPS.pdf`](./SMAPS.pdf) - PDF version of the same document.

## What SMAPS Covers

The specification combines five related parts:

1. **SMAPS white paper** - A system architecture for structured prompt engineering.
2. **Prompt Card DSL syntax specification** - A reusable card-style prompt format.
3. **PDS decoupling design guide** - Design rules for reducing semantic coupling and prompt drift.
4. **PDS module library** - Reusable modules for identity, composition, lighting, color, environment, aesthetics, constraints, routing, and fallback behavior.
5. **Semantic encapsulation and anchor framework** - A model for preserving meaning, boundaries, and execution stability across complex prompt flows.

## Core Concepts

SMAPS introduces a prompt architecture based on:

- Prompt Cards
- Prompt Design System (PDS)
- Modular decomposition
- Multi-agent FlowChain orchestration
- Semantic guardrails
- Routing logic
- Stability and drift control
- Fallback mechanisms
- DSL-style prompt representation

## Intended Use

SMAPS is designed for researchers, prompt engineers, AI product builders, and multi-agent workflow designers who need prompt systems that are:

- Easier to reuse
- Easier to route
- Easier to validate
- Less prone to semantic drift
- Better suited for complex image, text, and agentic generation pipelines

## Author

guo xiaopang

## Status

Initial public release.
