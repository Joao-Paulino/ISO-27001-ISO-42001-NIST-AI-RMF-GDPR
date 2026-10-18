# 🛡️ ISO 27001 Prompts & Automation

> **Stop writing ISMS documentation from scratch.**
> A curated arsenal of prompts, MCP servers, and templates that turn AI into your ISO/IEC 27001:2022 compliance co-pilot — for gap assessments, Statement of Applicability, risk treatment, policy drafting, and internal audits.

---

## ⚡ Why this repository exists

ISO 27001 is not a document you write once. It's a **living system** — 93 controls in Annex A, 7 mandatory clauses, continuous risk treatment, internal audits, management reviews. Most teams drown in templates and consultants.

AI changes the economics — **if you prompt it right**.

This repository curates the best open-source resources for **AI-assisted ISO 27001 compliance**, focused on:

- **Prompts that produce audit-ready output** — not vague summaries
- **Automation via MCP** — natural-language ISMS workflows inside Claude
- **Reusable templates** — risk registers, SoA mappings, Annex A control matrices
- **Data safety** — anonymize before you paste; the operator owns the risk

> ⚠️ **Reality check:** AI output is a **draft for human review**. The certification body audits *your* evidence, not your prompt. Accountability never transfers to the model.

---

## 🎯 Featured repositories

### 1. 📚 [GRC-Prompts-Library](https://github.com/KunalCyber/GRC-Prompts-Library)

**The prompt library that actually covers ISO 27001.**

45 professional GRC prompts spanning **ISO 27001**, ISO 42001, NIST AI RMF, GDPR, and more. Structured across three tiers — **Essential, Practitioner, Advanced** — and compatible with Claude, GPT-4o, and Gemini.

> **Best for:** GRC analysts and consultants who need ready-to-use prompts for governance, risk, and compliance deliverables.

---

### 2. 🤖 [MCP-Server-for-ISO27001](https://github.com/Sushegaad/MCP-Server-for-ISO27001)

**ISO 27001 as a natural-language workflow.**

An MCP (Model Context Protocol) server purpose-built for ISO 27001. Run complete ISMS workflows inside Claude using plain language:

- Gap assessment
- Statement of Applicability (SoA) generation
- Policy creation
- Risk register management
- Internal audit execution

The README ships with **concrete prompt examples** you can run immediately.

> **Best for:** teams that want AI to *execute* ISO 27001 processes, not just draft text.

---

### 3. 🧱 [cataam-security/cataam](https://github.com/cataam-security/cataam)

**ISO 27001:2022 templates, MIT-licensed.**

Ready-to-use templates including **risk assessment** and **Annex A control mapping**. Not prompts — but the structural scaffolding your prompts need to produce real documents.

> **Best for:** anyone building the document backbone of their ISMS.

---

## 🧭 How to use this repository

| Goal | Start with |
|---|---|
| Ready-to-use ISO 27001 prompts | **GRC-Prompts-Library** |
| Automate ISMS workflows in Claude | **MCP-Server-for-ISO27001** |
| Risk assessment & Annex A templates | **cataam-security/cataam** |
| Gap assessment from scratch | MCP server → gap assessment prompt |
| Draft your Statement of Applicability | MCP server → SoA prompt + cataam template |

---

## 🧩 Prompt patterns that work for ISO 27001

### 1. Gap Assessment
