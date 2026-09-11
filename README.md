# AI Tools Portfolio

**Full-stack AI applications** built with **Python + JavaScript**, designed to demonstrate production-ready skills for mid-level Full-Stack Developer roles.

These projects showcase:
- End-to-end full-stack architecture (auth, databases, APIs, real-time features)
- Modern AI/LLM integration (RAG, agents, tool use, evaluation)
- Clean code, TypeScript/Python best practices, and deployable structure
- Focus on real user problems rather than toy demos

---

## Projects

| # | Project | Description | Stack | Status |
|---|---------|-------------|-------|--------|
| 1 | [**RAG Knowledge Base**](https://github.com/Invenitur42/rag-knowledge-base) | Upload documents → semantic search + chat with your own knowledge. Hybrid search + citations. | FastAPI · LangChain · Next.js · Postgres/pgvector | Scaffolded |
| 2 | [**AI Writing Copilot**](https://github.com/Invenitur42/ai-writing-copilot) | Real-time writing assistant: tone rewrite, grammar, style suggestions, email drafts. | FastAPI · OpenAI · Next.js · Redis | Scaffolded |
| 3 | [**Smart Document QA**](https://github.com/Invenitur42/smart-document-qa) | Production-style document Q&A with re-ranking, evaluation metrics, admin dashboard. | FastAPI · LangChain · Next.js · Vector DB | Scaffolded |
| 4 | [**AI Job Assistant**](https://github.com/Invenitur42/ai-job-assistant) | Track applications + AI resume/cover letter tailoring + interview prep. | FastAPI · Next.js · Postgres · OpenAI | Scaffolded |
| 5 | [**AI Agent Workspace**](https://github.com/Invenitur42/ai-agent-workspace) | Multi-tool AI agent with memory, tool calling, background tasks, and dashboard. | FastAPI · LangGraph/Agents · Next.js | Scaffolded |

---

## Why these projects?

For a 2-year experience full-stack role, interviewers look for:
- Ability to design and ship complete features (not just frontend or backend)
- Understanding of auth, data modeling, API design, and state management
- Practical AI integration (not just calling an API once)
- Clean documentation and reasoning about trade-offs

Each repo is structured so you can expand it into a strong portfolio piece with screenshots, live demos, and architecture notes.

---

## Recommended Tech Stack (consistent across projects)

**Backend**
- Python 3.11+
- FastAPI
- SQLAlchemy + Alembic (or similar)
- PostgreSQL (+ pgvector for embeddings)
- Redis (caching / queues)
- LangChain / OpenAI SDK / LlamaIndex

**Frontend**
- Next.js 14/15 (App Router) + TypeScript
- Tailwind CSS + shadcn/ui
- React Query / TanStack Query
- Auth (NextAuth.js or custom JWT)

**Infra / Quality**
- Docker + docker-compose
- GitHub Actions (basic CI)
- Environment-based config
- Structured logging & error handling

---

## Getting Started with the Portfolio

1. Clone any individual project repo.
2. Follow the README inside that repo (setup, env vars, running locally).
3. Add your own OpenAI / Anthropic / local LLM keys.
4. Deploy frontend (Vercel) + backend (Railway / Render / Fly.io / AWS).

---

## Next Steps

I will help you flesh out each project one by one with:
- Professional folder structure
- Core API endpoints and database models
- Frontend pages and components
- Auth flow
- AI integration points
- Strong README with architecture notes and interview talking points

**Recommended build order:**  
1. RAG Knowledge Base  
2. AI Job Assistant  
3. AI Writing Copilot  
4. Smart Document QA  
5. AI Agent Workspace

---

*Built for interview readiness • Focused on depth over quantity*