# FLOWFORGE

### Build. Connect. Orchestrate. Automate.

<p align="center">
  <img src="resrc/Flowforge AI Workflow Orchestration Banner.png" alt="" width="100%">
</p>

<p align="center">
  <strong>A visual AI workflow and multi-agent orchestration platform.</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/AI-Multi--Agent-purple?style=flat-square">
  <img src="https://img.shields.io/badge/Workflow-Visual%20Builder-blue?style=flat-square">
  <img src="https://img.shields.io/badge/Platform-Open%20Source-green?style=flat-square">
</p>

---

## Overview

**Flowforge** is a visual platform for building, connecting, and orchestrating AI-powered workflows.

It brings large language models (LLMs), specialized AI agents, tools, and external integrations together in a unified workspace.

From conversational AI applications to sophisticated multi-agent systems, Flowforge provides an interactive environment to design workflows, configure AI providers, manage credentials, and execute intelligent tasks.

## Features

### Visual Workflow Builder

- Interactive node-based canvas.
- Drag-and-drop workflow components.
- Connect AI models, agents, and tools.
- Configure component inputs and outputs.
- Design collaborative AI workflows.

### Chatflows

Build single-agent systems, conversational applications, and simple LLM-powered workflows.

### Agentflows

Create intelligent multi-agent systems where specialized workers collaborate through a supervisor.

- Supervisor-based orchestration.
- Specialized AI workers.
- Custom agent instructions and prompts.
- Tool-calling capabilities.
- Collaborative task execution.

### Multi-Agent Collaboration

Configure dedicated AI workers with individual responsibilities.

| Agent | Responsibility |
|---|---|
| Supervisor | Understands tasks and delegates responsibilities |
| Software Developer | Generates application code and solutions |
| Code Reviewer | Reviews code and suggests improvements |
| Document Writer | Creates technical documentation and user guides |

### Marketplace

Explore and use pre-built AI workflow templates.

Available examples:

- Agentic RAG
- Agents Handoff
- Deep Research with Multi-turn Conversations
- Deep Research with Subagents
- Human in the Loop
- Interacting with APIs
- Iterations
- Simple RAG
- SQL Agent

### AI Provider Integrations

Connect different AI providers and services.

- OpenAI
- Anthropic
- Ollama
- E2B
- Replicate

### Credential Management

- Manage API keys, tokens, and secrets.
- Add and update provider credentials.
- Configure third-party integrations.
- Manage multiple AI provider connections.

### Additional Capabilities

- **Executions:** Manage workflow executions.
- **Assistants:** Manage AI assistants.
- **Tools:** Configure tools for AI agents.
- **Variables:** Manage reusable workflow variables.
- **API Keys:** Manage API access.
- **Document Stores:** Organize documents for retrieval-based workflows.

---

## Screenshots

### 1. Chatflows Dashboard

Manage and organize conversational AI workflows from a unified dashboard.

<p align="center">
  <img src="resrc/Screenshot%202026-04-05%20135630.png" alt="Flowforge Chatflows Dashboard" width="100%">
</p>

### 2. Marketplace

Explore community templates and discover pre-built AI workflows for different use cases.

<p align="center">
  <img src="resrc/Screenshot%202026-04-05%20135722.png" alt="Flowforge Marketplace" width="100%">
</p>

### 3. Credential Management

Configure and manage credentials for multiple AI providers and external services.

<p align="center">
  <img src="resrc/Screenshot%202026-04-05%20135737.png" alt="Flowforge Credentials" width="100%">
</p>

### 4. Multi-Agent Workflow Builder

Design collaborative AI systems by connecting language models, supervisors, and specialized workers through a visual canvas.

<p align="center">
  <img src="resrc/Screenshot%202026-04-05%20135817.png" alt="Flowforge Multi-Agent Builder" width="100%">
</p>

### 5. Interactive AI Execution

Interact with your configured multi-agent system and observe how specialized agents collaborate to complete tasks.

<p align="center">
  <img src="resrc/Screenshot%202026-04-05%20135850.png" alt="Flowforge Interactive AI Execution" width="100%">
</p>

---

## Example: AI Software Development Team

Flowforge can be configured to coordinate multiple specialized agents through a supervisor.

```text
                 OpenAI Model
                       |
                       v
                   Supervisor
                       |
          +------------+------------+
          |            |            |
          v            v            v
      Developer   Code Reviewer  Document Writer
          |            |            |
          v            v            v
      Generate      Review Code   Write Docs
          |            |            |
          +------------+------------+
                       |
                       v
                 Final Response
```

**Example task:**

"Develop a simple calculator application."

The supervisor interprets the request and coordinates specialized workers to generate code, review the implementation, and prepare documentation.

---

## Getting Started

### Prerequisites

- Git
- Node.js
- pnpm

### Installation

**1. Clone the repository**

```bash
git clone https://github.com/candyx3/Flowforge.git
```

**2. Navigate to the project**

```bash
cd Flowforge
```

**3. Install dependencies**

```bash
pnpm install
```

**4. Start the development server**

```bash
pnpm dev
```

**5. Open Flowforge**

Visit:

```text
http://localhost:3000
```

Configure the required AI provider credentials before executing workflows that depend on external AI services.

---

## Project Structure

```text
Flowforge/
├── .github/
├── .husky/
├── assets/
├── docker/
├── i18n/
├── images/
├── metrics/
├── packages/
├── resrc/
│   ├── Screenshot 2026-04-05 135630.png
│   ├── Screenshot 2026-04-05 135722.png
│   ├── Screenshot 2026-04-05 135737.png
│   ├── Screenshot 2026-04-05 135817.png
│   └── Screenshot 2026-04-05 135850.png
├── package.json
├── pnpm-lock.yaml
└── turbo.json
```

---

## Contributing

Contributions, suggestions, and improvements are welcome.

1. Fork the repository.
2. Create a feature branch.
3. Make your changes.
4. Commit your changes.
5. Push your branch.
6. Submit a pull request.

---

## License

See the repository's license file for licensing information.

---

## Connect

**Developed by [Chandru KB](https://github.com/candyx3)**

- GitHub: [@candyx3](https://github.com/candyx3)
- Repository: [Flowforge](https://github.com/candyx3/Flowforge)

If you find Flowforge interesting, consider giving the repository a star!

<p align="center">
  <strong>FLOWFORGE</strong>
  <br>
  Build. Connect. Orchestrate. Automate.
</p>
