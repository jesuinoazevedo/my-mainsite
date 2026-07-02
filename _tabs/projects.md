---
layout: page
title: Projects
subtitle: Selected Work & Highlights
icon: fas fa-diagram-project
order: 3
---

A mix of hands-on AI builds and enterprise architecture work. I use these projects to stay current, test ideas properly, and apply the same thinking I use in large programmes at a smaller scale.

---

## 🧠 Ask questions from real documents

Ask questions directly against trusted documents. No manual searching.

Use a curated Reserve Bank of New Zealand dataset, or upload your own PDFs. The assistant retrieves relevant content and answers with sources.

<div style="margin: 1.4em 0;">
  <a href="https://ai-rag-document-assistant.streamlit.app/" target="_blank"
     style="background: #1a73e8; color: white; padding: 10px 22px; border-radius: 6px; text-decoration: none; font-weight: bold;">
    🚀 Try the AI RAG Document Assistant
  </a>
</div>

---

## 🤖 AI RAG Document Assistant
**Personal Project · 2025–2026**

Built a Retrieval-Augmented Generation (RAG) application to turn document sets into a usable knowledge interface.

It combines vector search with LLMs to answer questions using real content, not guesses. Supports a shared base dataset and user uploads, with isolation between datasets.

**What it does:**
- Queries a curated Reserve Bank of New Zealand document set  
- Allows users to upload and analyse their own PDFs  
- Uses Qdrant for vector search and retrieval  
- Generates answers grounded in document context  
- Separates datasets by workspace  
- Applies usage limits to control cost during MVP testing  

**Why it matters:**  
This is applied AI engineering. Ingestion, embeddings, retrieval, prompting, and deployment all working together. Not just reading about it.

### Screenshot

<img src="/assets/img/projects/ai-rag-document-assistant.png"
     alt="AI RAG Document Assistant screenshot"
     style="width: 75%; border-radius: 8px; border: 1px solid #ddd; margin: 12px 0;">

**Tech stack:** Python, Streamlit, Qdrant, OpenAI, Anthropic, Docker, Streamlit Cloud

<div style="margin: 1.2em 0;">
  <a href="https://ai-rag-document-assistant.streamlit.app/" target="_blank"
     style="background: #1a73e8; color: white; padding: 9px 20px; border-radius: 6px; text-decoration: none; font-weight: bold;">
    🚀 Live App
  </a>
</div>

---

## 🤖 AI Finance Agent NZ
**Personal Project · 2024–2025**

Built an AI-driven personal finance tool for New Zealand bank data.

It takes raw CSV exports, classifies transactions using an agent, and produces a usable financial summary. Replaces manual spreadsheet work with something far more adaptive.

**What it does:**
- Ingests and normalises CSV exports from NZ banks  
- Uses a CrewAI agent to categorise transactions  
- Visualises income and spending with Plotly  
- Generates a plain-English financial summary  

**Why it matters:**  
End-to-end AI pipeline. Real data, real outputs. Same patterns used in enterprise, just at a different scale.

### Screenshots

<div style="margin: 1.5em 0; display: flex; gap: 16px; flex-wrap: wrap;">
  <figure style="max-width: 420px; margin: 0;">
    <img src="/assets/img/projects/ai-finance-agent-nz-dashboard.png"
         alt="AI Finance Agent NZ dashboard screenshot"
         style="width: 130%; border-radius: 8px; border: 1px solid #ddd;">
    <figcaption style="font-size: 0.9em; margin-top: 6px;">
      Income and spending breakdown.
    </figcaption>
  </figure>

  <figure style="max-width: 420px; margin: 0;">
    <img src="/assets/img/projects/ai-finance-agent-nz-summary.png"
         alt="AI Finance Agent NZ financial summary screenshot"
         style="width: 130%; border-radius: 8px; border: 1px solid #ddd;">
    <figcaption style="font-size: 0.9em; margin-top: 6px;">
      AI-generated summary and insights.
    </figcaption>
  </figure>
</div>

**Tech stack:** Python, CrewAI, Groq LLM, Pandas, Streamlit, Plotly

<div style="margin: 1.5em 0; display: flex; gap: 14px; flex-wrap: wrap;">
  <a href="https://ai-finance-agent-nz.streamlit.app/" target="_blank"
     style="background: #1a73e8; color: white; padding: 9px 20px; border-radius: 6px; text-decoration: none; font-weight: bold;">
    🚀 Live Demo
  </a>
  <a href="https://github.com/jesuinoazevedo/" target="_blank"
     style="background: #333; color: white; padding: 9px 20px; border-radius: 6px; text-decoration: none; font-weight: bold;">
    📁 GitHub
  </a>
</div>

---

## 🛰️ Orbital Flight Dynamics Simulator
**Personal Project · Playground**

Built a browser-based physics simulator modelling rocket ascent.

It runs a deterministic integration loop and visualises telemetry in real time. You can tweak parameters and see the impact immediately.

**What it does:**
- Simulates ascent using a 60Hz Newtonian loop  
- Models fuel burn using specific impulse  
- Calculates drag with atmospheric density decay  
- Validates thrust-to-weight ratio before launch  
- Tracks milestones like Max-Q and the Kármán line  
- Renders telemetry using HTML5 Canvas  

**Why it matters:**  
Shows core engineering fundamentals. Physics, modelling, and performance. Different domain, same discipline.

### Screenshot

<img src="/assets/img/projects/orbital-flight-sim.png"
     alt="Orbital Flight Dynamics Simulator screenshot"
     style="width: 75%; border-radius: 8px; border: 1px solid #ddd; margin: 12px 0;">

**Tech stack:** JavaScript, HTML5 Canvas, physics simulation

<div style="margin: 1.2em 0;">
  <a href="/orbital-flight-sim/" target="_blank"
     style="background: #1a73e8; color: white; padding: 9px 20px; border-radius: 6px; text-decoration: none; font-weight: bold;">
    🚀 Launch Simulation
  </a>
</div>

---

## Professional Projects

## ⚡ Vector – Alphabet X Energy Platform
**Solutions Architecture Lead · 2021–2023**

Led architecture for a digital platform supporting an energy innovation programme with Alphabet X.

- Defined architecture runway and non-functional requirements  
- Designed integration patterns and platform strategy  
- Led architecture governance across delivery streams  
- Worked across business, engineering, and risk  

---

## 🔧 Infrastructure Resilience & Modernisation
**Multiple Programmes · 2015–2020**

Led programmes improving reliability and operational posture across infrastructure.

- Delivered enterprise SAN transformation  
- Led security uplift and UTM refresh  
- Redesigned network to remove legacy dependencies  
- Delivered resilience improvements and cost savings  

---

## 🚀 Delivery Transformation & Ways of Working

Designed and implemented delivery and operating model changes.

- Reduced cost without reducing capability  
- Improved delivery speed and alignment  
- Increased engineering autonomy  

---

## 🧪 Early-Stage Architecture & Startup Advisory
**2023–Present**

Working with small teams on early architecture decisions.

Focus on getting to MVP without creating future problems.

---

*For a full résumé or portfolio reference, [get in touch](mailto:jesuino.azevedo@gmail.com).*
