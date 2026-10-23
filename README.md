### Hi, I'm Yoka 👋

I build LLM features with Claude — agents that act on real systems, RAG assistants, MCP servers —
and I **measure** whether they work: golden sets, deterministic CI gates, DeepEval + RAGAS with a calibrated judge.

**Selected work**

| Project | What it shows |
|---|---|
| [rag-eval-kit](https://github.com/yokadeeds-dev/rag-eval-kit) | Evaluate a RAG system through its real code path. Found that standard tooling breaks on current Claude models and how judge variance distorts scores. |
| [claude-closing-agent](https://github.com/yokadeeds-dev/claude-closing-agent) | Sales agent from "verbal yes" to signed contract: prices never computed by the LLM, guardrails in code, 16-case eval across Opus / Sonnet / Haiku with cost per turn. |
| [EVL](https://github.com/yokadeeds-dev/EVL) | RAG content assistant with tenant isolation (Chinese walls): FastAPI, Postgres/pgvector, Redis, React/TS, CI/CD. Evaluation lifted faithfulness from 0.34 to 0.61. |
| [yoka-cubase-mcp](https://github.com/yokadeeds-dev/yoka-cubase-mcp) | MCP server that lets an AI control Cubase with verified closed-loop state. |

**Stack** · Python · FastAPI · Anthropic API (tool use, structured outputs, prompt caching) · MCP · Postgres/pgvector · Redis · React/TypeScript · Docker · GitHub Actions

**How I work** · Tests and evaluation before claims · decisions written down as ADRs · honest about limits
