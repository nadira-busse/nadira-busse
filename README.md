# Hi, I'm Nadira

I started building AI and workflow systems because I kept running into problems that the tools I was using did not solve well enough.

I wanted to understand why context disappeared, why AI output could be wrong or incomplete, where a workflow actually failed, and which parts of a system should remain deterministic instead of being delegated to AI. Building my own systems became the way I learned to answer those questions.

I use AI as part of how I build, but not as a substitute for understanding what I ship. I test behaviour, examine assumptions, investigate failures and document where a system stops.

My current focus is on software development, AI systems, workflow automation, context and retrieval, and governance.

## Featured projects

### [Weft](https://github.com/nadira-busse/weft)

An archive-first reference implementation for preserving AI conversations, decisions and workflow output as structured records that can be retrieved across different AI clients.

I built Weft after repeatedly losing useful project context between sessions and platforms. It lets me archive context outside the AI client itself and retrieve it later from different AI environments through the same underlying system, instead of depending on the memory or history of one interface.

Make handles orchestration, Notion acts as the human-readable source of record and MCP exposes archive, search and context retrieval to different AI clients. The repository also includes public contracts, JSON Schemas, idempotent archive flows, a Python installer, regression evidence and reproducible setup.

**Built with:** Python · Make · Notion · MCP · JSON Schema · context retrieval · idempotency · installer testing

### [Fenéla](https://github.com/nadira-busse/fenela)

An accountability PWA that turns one personal goal into small, concrete actions and keeps one step at a time in focus.

AI has one deliberately bounded role: it can suggest anchors when the user asks for help, but the user decides what is kept. Account-owned state, reminders and reflections remain outside the generative AI layer.

The application uses Supabase Auth and PostgreSQL for authenticated user-owned persistence, Web Push for optional reminders, deterministic reflections from recorded activity, and validation, repair and fallback boundaries around AI-generated suggestions.

**Built with:** TypeScript · Next.js · React · Supabase · PostgreSQL · OpenAI · Web Push · testing · CI

## How I work

I start by defining what a system needs to do, which responsibilities should stay separate, and where the boundaries belong. From there, I design the workflow, information flow and automation around those decisions.

I make important system behaviour explicit through clear logic, ownership and interfaces, so the system remains understandable and easier to test and maintain.

Most of my technical experience has been built through independent projects. I am continuing to strengthen the software-engineering foundations behind that work through hands-on development and formal study in Applied Computer Science.
