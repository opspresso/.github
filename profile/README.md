<div align="center">
  <a href="https://opspresso.com">
    <img src="https://opspresso.com/images/opspresso.png" alt="OpsPresso logo" width="120">
  </a>
  <h1>OpsPresso</h1>
  <p><strong>Platforms and tools for AI agents.</strong></p>
  <p>
    <a href="https://opspresso.com">Website</a> ·
    <a href="https://opspresso.com/#platform">Agent Platform</a> ·
    <a href="https://opspresso.com/#tools">Developer Tools</a> ·
    <a href="https://github.com/orgs/opspresso/repositories">Repositories</a>
  </p>
</div>

Build agents and take apps from an idea to deployment. Connect model routing, memory, knowledge, coding workspaces, and app delivery. Keep everyday work moving with monitoring, terminal, and launcher tools.

## Agent Platform

Six independent services own their settings, data, permissions, and consoles. Studio provides identity and orchestration, connecting agents to Memory, Knowledge, Forge, and Runway through MCP. Models provides the central model gateway.

### <img src="https://opspresso.com/images/agent-studio.png" alt="" width="26" height="26" align="top"> [Agent Studio](https://studio.agrt.dev)

**Build agents, run them anywhere, review their work.**

Configure agents with models approved in Agent Models, skills, MCP tools, and sub-agents. Run them from chat, APIs, Slack, Teams, Telegram, webhooks, or schedules. Control access, tool approvals, and spending limits, and review each run's trace.

<sub>MCP tools · Tool approvals · Run traces · Spending limits</sub>

### <img src="https://opspresso.com/images/agent-models.png" alt="" width="26" height="26" align="top"> [Agent Models](https://models.agrt.dev)

**One gateway for every model your agents call.**

Connect OpenAI, Anthropic, Google, xAI, Bedrock, OpenRouter, or self-hosted endpoints with encrypted keys. Approve the models agents may call, route requests in each provider's native format, and track usage and cost by model, user, agent, and service.

<sub>Provider routing · Model approval · Usage &amp; cost ledger · Public catalog</sub>

### <img src="https://opspresso.com/images/agent-memory.png" alt="" width="26" height="26" align="top"> [Agent Memory](https://memory.agrt.dev)

**Carry useful context across agents and sessions.**

Save rules, preferences, decisions, facts, and lessons with their sources. Recall them in Studio, Claude Code, and Codex, and share them by user, team, or organization. Nightly Dreaming merges and promotes memories, and every change keeps a version.

<sub>Durable context · Scoped sharing · Nightly Dreaming · Client handoffs</sub>

### <img src="https://opspresso.com/images/agent-knowledge.png" alt="" width="26" height="26" align="top"> [Agent Knowledge](https://knowledge.agrt.dev)

**Give agents knowledge they can trace to a source.**

Ingest documents and recordings, then produce transcripts and meeting notes. Search text and the knowledge graph with links to source evidence. Track decisions, tasks, and risks as objects, and review AI-extracted knowledge before it is applied.

<sub>Source evidence · Meeting notes · Knowledge graph · Ontology objects</sub>

### <img src="https://opspresso.com/images/agent-forge.png" alt="" width="26" height="26" align="top"> [Agent Forge](https://forge.agrt.dev)

**Give agent work a place to run.**

Run commands and Codex, Claude, or OpenCode sessions in Docker or Kubernetes sandboxes. Keep workspaces and sessions across suspend and resume. Manage profiles, GitHub connections, execution history, and protected Git actions in Forge, with approvals tied to the work being published.

<sub>Persistent workspaces · Coding CLI sessions · Workspace profiles · Git approvals</sub>

### <img src="https://opspresso.com/images/agent-runway.png" alt="" width="26" height="26" align="top"> [Agent Runway](https://runway.agrt.dev)

**Take the apps agents build into production.**

Apply `application.yaml` to provision app resources and deliver secrets to workspaces and deployed apps. Build and test with Argo Workflows, deploy through GitOps, and promote the same release across environments. Review approvals, deployment logs, and rollback targets in Runway. Enter secret values in its console, outside chat.

<sub>App resources · Secret delivery · Build &amp; deploy · Promote &amp; rollback</sub>

### Shared foundations

- **agent-platform** — Shared architecture, service contracts, acceptance scenarios, and reusable CI workflows. It contains no service runtime.
- **[agent-plugins](https://github.com/opspresso/agent-plugins)** — Reusable task skills and MCP declarations for coding, research, design, and operations. Connections and permissions remain with the host and services.

### From request to running app

1. **Plan in Studio.** Use approved models, recall decisions from Memory, and find source material in Knowledge.
2. **Develop in Forge.** Write code and `application.yaml`, run checks, and open a pull request. Review protected Git actions in Forge.
3. **Provision with Runway.** Apply the app declaration and create environment resources. Enter secrets in the Runway console, outside chat.
4. **Deploy and operate with Runway.** Build and test with Argo Workflows, deploy through GitOps, promote the same release with the required approval, and inspect logs or roll back.

Explore the [interactive platform map and workflow](https://opspresso.com/#platform).

## Developer Tools

Monitor your systems, keep coding sessions running, and make everyday actions easier.

### <img src="https://opspresso.com/images/vibemon.png" alt="" width="26" height="26" align="top"> [VibeMon](https://vibemon.io)

**Monitor your agents, accounts, and infrastructure.**

Follow coding-agent activity and plan usage across accounts, with metrics from servers, Kubernetes clusters, DGX Spark hosts, and custom resources. View the same workspace on desktop, web, iPhone, Apple Watch, Android, or an ESP32 display, and pin it to widgets.

<sub>Desktop · Web · iOS · Android · ESP32 · Coding agent activity · Plan usage limits · Resource metrics · Widgets</sub>

### <img src="https://opspresso.com/images/romty.png" alt="" width="26" height="26" align="top"> [romty](https://romty.dev)

**Close the terminal. The shells keep running.**

Keep coding agents running on an always-on machine after you close the terminal or disconnect SSH. Reconnect to the same workspace tabs, search retained output, and see which agents are working, waiting for approval, or done.

<sub>macOS · Linux · Persistent sessions · Agent resume · Searchable scrollback · Agent status</sub>

### <img src="https://opspresso.com/images/toast.png" alt="" width="26" height="26" align="top"> [Toast](https://toastapp.dev)

**A launcher you summon with one shortcut.**

A global hotkey opens your own pages of buttons. Run commands, open files and URLs, run scripts, chain actions, or launch applications. On macOS, snippets expand typed keywords in any app. Optional Cloud Sync keeps pages and snippets in step across devices.

<sub>macOS · Windows · Custom button pages · Script actions · Text expansion · Cloud sync</sub>

## Built on operational experience

Backend development and SRE experience guide how we build, ship, and operate agent systems.

- **Agent platforms** — Orchestration, models, memory, knowledge, workspaces, and app delivery with clear responsibilities.
- **IaC &amp; GitOps** — Infrastructure defined in code, reviewed in Git, and deployed consistently.
- **DevOps &amp; SRE** — A shorter path from a commit to production, with reliability that is measured.

Explore the [website](https://opspresso.com) or browse our [repositories](https://github.com/orgs/opspresso/repositories).
