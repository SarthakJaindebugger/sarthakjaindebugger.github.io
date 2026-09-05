---
layout: page
title: Espoo AI Service Assistant
description: Privacy-aware multilingual RAG for public services
importance: 1
category: ai systems
---

An end-to-end public-service assistant built for the City of Espoo's immigration department during the Aalto Science Institute International Summer Research Programme.

**Stack:** Python, FastAPI, Flask, Vue.js, TypeScript, Qdrant, embeddings, hybrid semantic/BM25 retrieval, REST, WebSockets, SQL, Docker.

The system supports multilingual, multi-turn conversations with structured user, dialogue, temporal, and event memory. Its privacy-by-design architecture resolves sensitive information locally and sends only scrubbed context to external LLM APIs.
