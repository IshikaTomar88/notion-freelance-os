<div align="center">

# 🤖 Enterprise System Prompt & Custom GPT Architecture Vault

**A production-ready collection of optimized system prompts, guardrails, and structured output schemas for LLM deployments.**

[![Prompt Standard](https://img.shields.io/badge/Prompt-Engineering%202.0-blue?style=for-the-badge)]()
[![License](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](LICENSE)
[![Format](https://img.shields.io/badge/Format-Markdown%20%7C%20JSON-orange?style=for-the-badge)]()

[📋 View Prompts](#-available-system-prompt-templates) · [🛡️ Safety & Guardrails](#%EF%B8%8F-built-in-guardrails) · [💼 Hire on Fiverr](https://fiverr.com)

</div>

---

## 📌 Architectural Blueprint

This repository implements the 5-layer enterprise system prompt design pattern:

```text
┌─────────────────────────────────────────────────────────────────────────────┐
│ 🧠 SYSTEM PROMPT ARCHITECTURE LAYERS                                        │
├─────────────────────────────────────────────────────────────────────────────┤
│ 1. 🎭 IDENTITY & ROLE     ➔ Defines authority level and domain expertise    │
│ 2. 🎯 CONTEXT & GOALS    ➔ Specifies boundary limits and core objective    │
│ 3. 🛡️ GUARDRAILS          ➔ Enforces safety, tone, and hallucination rules  │
│ 4. ⚙️ OUTPUT SCHEMA       ➔ Specifies exact JSON/Markdown structure return  │
│ 5. 🧪 FEW-SHOT EXAMPLES   ➔ Provides sample inputs and target responses     │
└─────────────────────────────────────────────────────────────────────────────┘
