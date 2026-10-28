# Rubén Dorta

**Solution Architect | Applied AI & OSS/BSS**

I build AI agents that respect business rules, the way I built telecom systems for 25 years.

I turned telecom operators' business rules into production systems for 25 years: product catalogs, ordering, charging and billing, integrated end to end. The last ten were at Ericsson, embedded with Claro Colombia. Today I build AI agents, RAG systems and evaluations in Python.

## Projects

### Flow Audit

An audit workbench for BSS order flows: it reads evidence exported from the catalog, OMS, BPM and provisioning, and reports where orders get stuck.

- **Today:** dataset, architecture and rule catalogue in place; the audit engine is next.
- **Key decision:** it observes evidence exports instead of touching the systems it audits, and reconstructs each order's journey into one canonical event stream before any rule fires.
- In build · [Repo](https://github.com/rdorta27/flow-audit) · [Site](https://rdorta27.github.io/flow-audit-site/)

### Sentinel Engine

A customer-service agent for bank transaction disputes, in Spanish and Portuguese: the customer names a charge, and the assistant verifies the facts behind it.

- **Today:** it handles the intake and triage of a dispute, verifies the facts, and hands the decision to an advisor with the full case.
- **Key decision:** the LLM only labels intent; masking, policy, confirmation, case creation and handoff run in code and are verified.
- v1.1.0 · active · [Repo](https://github.com/rdorta27/sentinel-engine) · [Site](https://rdorta27.github.io/sentinel-engine-site/)

### Knowman

RAG over your Markdown notes: ask a question and get the passages and the exact lines behind the answer.

- **Today:** it answers from one notes folder through a CLI, an HTTP API and an MCP server, and scores its retrieval with a labeled dataset on every run.
- **Key decision:** a distance threshold decides what counts as evidence; when nothing qualifies, the model is never called and the result is the explicit negative.
- v0.2.4 · [Repo](https://github.com/rdorta27/knowman) · [Site](https://rdorta27.github.io/knowman-site/)

## How I work

- The LLM handles the language; the rules that matter live in code.
- Nothing ships before it passes an evaluation.
- Local-first, with verifiable evidence.

## Elsewhere

[Website](https://rdorta27.github.io/) · [LinkedIn](https://www.linkedin.com/in/ruben-a-dorta/) · [Credly](https://www.credly.com/users/ruben-dorta/badges)
