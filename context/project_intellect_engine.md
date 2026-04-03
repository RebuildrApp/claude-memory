---
name: Intellect Engine — second brain IP app
description: App that captures raw thoughts and converts them into structured frameworks, content, courses, and product ideas. Not a notes app — an interpretation + structuring + output engine.
type: project
---

## App: Intellect Engine (working title)

**Concept:** Raw thoughts → structured frameworks → usable assets → products
**User:** Tayla only (single-user, personal IP system)

### Core Pipeline
1. Quick capture (voice, text, photo, video)
2. AI interpretation (transcribe → tag → categorize → connect)
3. Pattern detection (cluster repeated ideas)
4. Framework promotion (formalize recurring patterns)
5. Output generation (reel scripts, carousels, lead magnets, course modules)

### Tech Stack
- Next.js (App Router), PostgreSQL + pgvector, BullMQ + Redis
- DigitalOcean (App Platform, Managed DB, Spaces)
- Claude API (interpretation + generation), Whisper (transcription), OpenAI embeddings

### Status
- Architecture designed (2026-04-02)
- Full spec: `/Documents/Claude-Work/second-brain-product-architecture.md`

**Why:** Tayla's expertise compounds but isn't captured systematically. This app turns her ongoing thinking into structured, reusable IP that feeds content, courses, and Rebuildr.
**How to apply:** Distinct from the Content Intelligence App (competitor analysis + research). This is personal IP capture and structuring. Same infra preferences (DigitalOcean, GitHub: RebuildrApp).
