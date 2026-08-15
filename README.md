# Hi, I'm Nadira

I started building AI and workflow systems because I kept running into problems that the tools available at the time did not solve well enough.

I wanted to understand why context disappeared, why AI output could be wrong or incomplete, where a workflow actually failed, and which parts of a system should remain deterministic instead of being delegated to AI. Building my own systems became the way I learned to answer those questions.

I use AI as part of how I build, but not as a substitute for understanding what I ship. I test behaviour, examine assumptions, investigate failures and document where a system stops.

I am currently looking for a junior or junior+ role where AI engineering, workflow automation and software development come together.

## Featured projects

### [Threshia Governance](https://github.com/nadira-busse/threshia-governance)

A Python governance engine that evaluates proposed AI-agent tool calls as `ALLOW`, `BLOCK` or `FLAG` before execution.

The engine separates deterministic policy rules from optional semantic retrieval and LLM reasoning, with explicit fallback behaviour and audit logging.

**Built with:** Python · ChromaDB · Mistral · OpenAI · policy evaluation · retrieval · testing · CI

### [Weft](https://github.com/nadira-busse/weft)

An archive-first, platform-independent reference implementation for preserving AI conversations, decisions and workflow output as structured records that can be retrieved across different AI clients.

I built Weft after repeatedly losing useful project context between sessions and platforms. It lets me archive a conversation once and retrieve that context later from both ChatGPT and Claude through the same underlying system, instead of depending on the memory or history of one interface.

The repository includes the Make workflows, Notion data model, MCP-facing contracts, installer, JSON Schemas, regression evidence and reproducible setup.

**Built with:** Python · Make · Notion · MCP · JSON Schema · platform-independent context retrieval · idempotency · installer testing

### [Kelvior Agent Decision Gate](https://github.com/nadira-busse/kelvior-agent-decision-gate)

A Microsoft Foundry reasoning-agent MVP that evaluates whether another AI agent is ready for deployment.

It retrieves synthetic enterprise evidence, applies blocking rules and score caps, traces findings back to their sources, and preserves human authority over the final deployment decision.

**Built with:** Microsoft Foundry · Foundry IQ · retrieval · synthetic enterprise evidence · governance rules · source traceability

### [Fenéla](https://github.com/nadira-busse/fenela)

An accountability PWA that helps someone turn one personal goal into a small action and return to it without turning the product into an AI planner or productivity suite.

AI is deliberately bounded to optional anchor suggestions. Account-owned state, reminders and reflections use explicit server-side and deterministic boundaries where appropriate.

**Built with:** TypeScript · Next.js · React · Supabase · OpenAI · Web Push · testing · CI

## Technical focus

**Core:** Python · TypeScript · AI systems · workflow automation · retrieval · APIs · testing

**Working with:** Next.js · React · Make · Microsoft Foundry · MCP · JSON Schema · CI

## How I work

The part of engineering I am most interested in is not getting a demo to work once. It is understanding why it works, where it can fail, what should remain deterministic, and how to make the system simpler, clearer and easier to maintain.

I often notice when a workflow is more complicated or manual than it needs to be. I like finding ways to simplify it with clearer steps, better information flow and automation where it actually helps.

Across my projects I have worked with:

* deterministic rules around probabilistic AI behaviour;
* explicit system and ownership boundaries;
* idempotency and failure recovery;
* schemas and payload contracts;
* retrieval and context systems;
* testing and regression evidence;
* security and privacy boundaries;
* reproducible setup and technical documentation.

I have built most of my experience through independent projects, and I am continuing to deepen the software-engineering foundations behind the systems I build through formal study and hands-on work.

My next step is to develop this work inside an organisation: contributing to existing systems, working with other engineers, learning from technical review and production constraints, and helping improve workflows that are unnecessarily complex or manual.

Over time, I want to grow from building individual AI and automation solutions into designing the systems and architecture that connect them.

