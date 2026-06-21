# Praveen Kumar

**Engineering leader · agentic systems · LLM inference & cost engineering · production AI**

20 years in engineering leadership — the last four-plus building production generative AI at Amazon (Berlin), and a decade before that as a customer-embedded technical lead delivering for UK enterprise clients. I work on the unglamorous parts that decide whether AI products survive contact with production: cost, reliability, evaluation, and safe autonomy.

The repositories below are **reference designs** — distilled from production work and written as the decisions an engineering leader actually owns, not as tutorials. Each one is runnable.

---

## Selected work

**[LLMInferenceRouter](https://github.com/kumarpraveendev/LLMInferenceRouter)** — *cascaded multi-provider routing*
Try the cheapest model first; escalate only when quality demands it. This is where the unit economics of an AI product are won or lost — so it ships with a reproducible cost-vs-quality benchmark rather than an asserted number.

**[AgenticAI-OncallAgent](https://github.com/kumarpraveendev/AgenticAI-OncallAgent)** — *safe autonomy under pressure*
An on-call agent is the highest-stakes place to put autonomy: it acts during incidents, on production, where a wrong move makes a bad night worse. Built around action gating (auto / approval-required / forbidden), RAG over runbooks, and per-action evaluation.

**[CustomerSupportAgent — A Decision Record](https://github.com/kumarpraveendev/CustomerSupportAgent-A-Decision-Record)** — *the decisions, not the diagram*
A production-grade customer-facing support agent written as the architecture and policy decisions a Head of Engineering owns — the tradeoffs and their rationale, not a tour of the boxes.

**[AIAgent-eval-harness](https://github.com/kumarpraveendev/AIAgent-eval-harness)** — *evaluation as a first-class artifact*
A small, runnable test bench for tool-using agents: adversarial scenarios — a hidden instruction in a search result, a refund over the policy limit, an ambiguous request — each with explicit pass/fail invariants.

**[shortlink](https://github.com/kumarpraveendev/shortlink)** — *cloud-native, hands-on*
A compact Node.js + Redis URL shortener deployed to Kubernetes — a small, end-to-end cloud-native deployment.

---

## Focus areas

Agentic systems (LangGraph · MCP · tool-calling · human-in-the-loop) · LLM inference & cost engineering · RAG · evaluation & guardrails · responsible AI & the EU AI Act · AWS · production reliability / SRE

## Background

At Amazon: a cascaded multi-provider inference platform adopted as an org-wide reference standard (~70% serving-cost reduction), a production LangGraph multi-agent system that removed ~50% of manual on-call effort, and a multi-tenant LLM inference platform. Earlier, nearly a decade embedded directly with UK enterprise customers at British Telecom.

## Certifications

Agentic AI — DeepLearning.AI (course). NVIDIA Certified Professional: Agentic AI (NCP-AAI) and Anthropic Claude Certified Associate, Foundations — in progress.

---

**[Website](https://kumarpraveen.dev)** · **[LinkedIn](https://www.linkedin.com/in/kumarpraveendev)** · praveen.git@gmail.com
