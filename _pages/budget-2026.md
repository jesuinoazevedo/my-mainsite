---
title: NZ Budget 2026 AI Assistant
icon: fas fa-landmark
order: 5
permalink: /budget-2026/
---

An AI-powered assistant grounded in the official **New Zealand Budget 2026** documents from the NZ Treasury. Ask questions in plain English — answers come only from the source documents, with citations.

<div style="position: relative; width: 100%; height: 900px; margin-top: 2rem; border-radius: 12px; overflow: hidden; box-shadow: 0 4px 16px rgba(0,0,0,0.08);">
  <iframe
    src="https://budget-2026-nz.streamlit.app/?embed=true"
    style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; border: none;"
    title="NZ Budget 2026 AI Assistant"
    allow="clipboard-write"
    loading="lazy">
  </iframe>
</div>

<p style="margin-top: 1rem; font-size: 0.9em; opacity: 0.7;">
  Having trouble with the embedded view? <a href="https://budget-2026-nz.streamlit.app/" target="_blank">Open the assistant in a new tab</a>.
</p>

## About this project

Built on top of a generic RAG (Retrieval-Augmented Generation) document assistant, this version is specialised in the official NZ Budget 2026 document set — including the Budget Speech, Fiscal Strategy Report, BEFU 2026, HYEFU 2025, Child Poverty Report, Tax Expenditure Statement and more.

**Tech stack:** Streamlit · OpenAI embeddings · Qdrant vector store · Anthropic Claude Haiku 4.5

[View source on GitHub](https://github.com/jesuinoazevedo/Budget-2026-AI-Assistant)

> ⚠️ **Disclaimer:** Independent project, not affiliated with the NZ Treasury or Government. Verify against source documents.