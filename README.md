# Sofía B2B Prospector Agent

Demo built as part of my application for the **PM, Growth Systems** role at [Sofía](https://sofiasalud.com).

## What it does

A browser-based prospecting agent that simulates the full B2B acquisition pipeline:

1. **Apollo prospecting** — filter by ICP (industry, role, headcount, location)
2. **SofíaBusiness fit scoring** — 4 signals: headcount, industry, location, current benefits → score 0–100
3. **AI-generated emails** — personalized per prospect via Claude API (or demo mode, no key needed)
4. **SDR assignment + 5-step flow** — each SDR has a defined skill profile (cold caller, email writer, LinkedIn hunter, adaptive) and gets a customized cadence per lead

## Built with

- Vanilla HTML/CSS/JS — no framework, no backend
- Claude (Anthropic) — real-time email generation via API
- Claude as co-builder — all code written in conversation with Claude

## Who built what

| David Flores | Claude (Anthropic) |
|---|---|
| Product architecture & business logic | All HTML, CSS, JavaScript |
| SofíaBusiness match engine (4 signals) | Real-time email generation via API |
| SDR profiles, skills & cadence logic | Iterative debugging & refinement |
| Prompt design & flow decisions | This README |

## How to run

Open `index.html` in any browser. No install, no server needed.

To enable real-time AI emails: add your Anthropic API key in Step 3.

## Context

Sofía has a B2B sales engine that works but is limited by human capacity. This prototype shows what the agent layer on top of that engine could look like — automated prospecting, fit scoring, personalized outreach, and SDR-adapted cadences.

---

Built by **David Flores** · Founder, [Key-Netic](https://key-netic.com) · León, Guanajuato, México
