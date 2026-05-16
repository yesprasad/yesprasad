# Hi, I'm Eshwar Prasad Yaddanapudi 👋



[![GitHub](https://img.shields.io/badge/GitHub-yesprasad-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/yesprasad)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-yesprasad-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/eshwarprasadyaddanapudi)
[![npm](https://img.shields.io/badge/npm-fluent--graph-CB3837?style=for-the-badge&logo=npm&logoColor=white)](https://www.npmjs.com/package/@yesprasad/fluent-graph)
[![npm](https://img.shields.io/badge/npm-fluent--graph--mcp-CB3837?style=for-the-badge&logo=npm&logoColor=white)](https://www.npmjs.com/package/@yesprasad/fluent-graph-mcp)



I build the infrastructure layer beneath AI coding agents — the part that gives them architectural awareness, dependency intelligence, and runtime guardrails so they can operate safely in complex enterprise systems.


---

## The Problem I'm Solving

<div align="center">

### *"AI agents should understand consequence before execution."*

</div>

Today's AI coding tools are powerful but architecturally blind. They generate code without understanding what breaks downstream. In enterprise systems — where workflows, automations, approvals, and integrations are deeply interconnected — a single unsafe change can cascade across production.

I'm building open-source infrastructure that closes this gap: giving AI agents real project context, blast radius awareness, and consequence analysis before they write a single line of code.

---

## 🔥 fluent-graph

**Open-source graph engine and CLI that maps dependency lineage and blast radius inside large ServiceNow codebases.**

Enterprise platforms like ServiceNow are notoriously opaque — thousands of interconnected scripts, workflows, and business rules with no clear visibility into what depends on what. fluent-graph turns that into a queryable directed graph.

**What it does in practice:**

- Parses and maps dependency chains across entire ServiceNow instances
- Calculates blast radius for any proposed change — showing every downstream workflow, automation, and integration that could break
- Exposes hidden dependencies that aren't documented anywhere
- Gives engineering teams a "before you deploy" safety check that didn't exist before

**Built with:** Node.js, TypeScript, directed graph modeling, CLI architecture

[![npm](https://img.shields.io/badge/npm-fluent--graph-CB3837?style=for-the-badge&logo=npm&logoColor=white)](https://www.npmjs.com/package/@yesprasad/fluent-graph)


![npm downloads](https://img.shields.io/npm/dm/@yesprasad/fluent-graph?style=flat-square&color=CB3837)

---

## 🤖 fluent-graph-mcp

**MCP server that connects AI coding agents to fluent-graph — giving Claude, Cursor, and any MCP-compatible tool architectural awareness before generating or modifying code.**

This is the bridge between AI coding tools and real system architecture. One configuration connects an agent to the full dependency graph of a project.

**What changes for the AI agent:**

- Before modifying a script, the agent queries blast radius and sees every downstream dependency that could break
- Instead of hallucinating assumptions about system structure, the agent reasons over real graph data
- Unsafe modifications get flagged before they're generated, not after they hit production

**Why this matters:** Most AI coding failures in enterprise aren't syntax errors — they're context failures. The agent didn't know that changing one business rule would break an approval chain three layers deep. fluent-graph-mcp solves that at the infrastructure level.

**Built with:** Node.js, TypeScript, Model Context Protocol (MCP), graph query interface

[![npm](https://img.shields.io/badge/npm-fluent--graph--mcp-CB3837?style=for-the-badge&logo=npm&logoColor=white)](https://www.npmjs.com/package/@yesprasad/fluent-graph-mcp)

![npm downloads](https://img.shields.io/npm/dm/@yesprasad/fluent-graph?style=flat-square&color=CB3837)

---


## What I Think About

I'm less interested in what model you use and more interested in the infrastructure around it:

- **Dependency intelligence** — Can an AI agent understand what depends on what before it acts?
- **Runtime consequence analysis** — Can we calculate blast radius in real time, before deployment?
- **Execution safety** — What guardrails make autonomous engineering systems trustworthy enough for production?
- **Context engineering** — How do we feed AI agents the right project context at the right time?
- **Graph-aware reasoning** — How do directed graphs change the way AI agents plan and execute?

The long-term vision: foundational infrastructure for autonomous engineering systems that are safe enough to trust with real production systems.

---

## Let's Talk

If you're building in the AI infrastructure, agentic systems, or developer tooling space — I'd like to hear what you're working on.

- **GitHub:** [github.com/yesprasad](https://github.com/yesprasad)
- **LinkedIn:** [linkedin.com/in/eshwarprasadyaddanapudi](https://www.linkedin.com/in/eshwarprasadyaddanapudi)
