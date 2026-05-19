# AIZEN — Multi-Agent Workflow Skills

AIZEN is an open-source AI Agent Skills Library for building multi-agent workflow systems.

This repository contains reusable `SKILL.md` files that can be copied, customized, or loaded into AI agents.

Each skill is designed to help AI agents do more than chat. The goal is to create agents that can research, analyze, execute, automate, notify, and report.

## What Is AIZEN?

AIZEN is a multi-agent workflow skill pack.

It provides structured AI agent skills for:

- Multi-agent routing
- Market intelligence
- Content creation
- Lead generation
- Customer support
- Document processing
- Workflow automation
- Telegram bot automation
- Tool and API integration
- Reporting and execution

## Why This Exists

Most AI agents fail because they only respond.

AIZEN is designed to help agents work in structured workflows.

Instead of one generic chatbot, AIZEN uses specialist skills that can be combined into a multi-agent system.

```txt
User Request
   ↓
Aizen Router Agent
   ↓
Specialist Agent
   ↓
Execution Workflow
   ↓
Telegram / Dashboard / Report / Output
   ↓
Final Result
```

## Repository Structure

```txt
Multi-Agent-Workflow/
│
├── README.md
├── index.html
├── Aizen.jpg
│
└── skills/
    ├── aizen/
    │   └── SKILL.md
    │
    ├── crypto-market-agent/
    │   └── SKILL.md
    │
    ├── content-agent/
    │   └── SKILL.md
    │
    ├── lead-generation-agent/
    │   └── SKILL.md
    │
    ├── customer-support-agent/
    │   └── SKILL.md
    │
    ├── document-agent/
    │   └── SKILL.md
    │
    ├── workflow-automation-agent/
    │   └── SKILL.md
    │
    └── telegram-bot-agent/
        └── SKILL.md
```

## Available Skills

| Skill | Description |
|---|---|
| Aizen Router | Master router that selects the right specialist agent |
| Crypto Market Agent | Analyze crypto markets, sentiment, news, risk, and opportunities |
| Content Agent | Create threads, scripts, captions, newsletters, and content plans |
| Lead Generation Agent | Find prospects, score leads, and create outreach messages |
| Customer Support Agent | Handle FAQs, support tickets, WhatsApp flows, and replies |
| Document Agent | Summarize PDFs, extract key points, and generate reports |
| Workflow Automation Agent | Connect agents, tools, APIs, Telegram, dashboards, alerts, and workflows |
| Telegram Bot Agent | Build Telegram bot workflows for commands, alerts, reports, and AI agent notifications |

## How To Use

1. Open the `skills` folder.
2. Choose the skill you want.
3. Open the `SKILL.md` file.
4. Copy the instruction.
5. Paste it into your AI agent system.
6. Customize the inputs, tools, and output format.
7. Run the agent.

## Compatible With

These skills can be adapted for:

- OpenClaw
- Hermes
- Custom GPTs
- Claude Projects
- Cursor Agent
- n8n AI Agent
- Flowise
- LangChain
- CrewAI
- AutoGen
- Telegram Bot API
- Zapier
- Make
- Pipedream
- Activepieces
- Any custom multi-agent framework

## Example Multi-Agent Workflow

```txt
User:
"I want an AI workflow that monitors crypto markets and sends daily reports to Telegram."

Aizen Router Agent:
Selects Crypto Market Agent + Workflow Automation Agent + Telegram Bot Agent.

Crypto Market Agent:
Analyzes market condition, sentiment, risks, and opportunities.

Workflow Automation Agent:
Designs scheduled automation and data flow.

Telegram Bot Agent:
Sends reports, alerts, and updates to Telegram.

Report Agent:
Formats the final result into a clear daily report.
```

## Example Use Cases

### Crypto Market Monitoring

```txt
Crypto Market Agent
   ↓
Workflow Automation Agent
   ↓
Telegram Bot Agent
   ↓
Daily Telegram Market Report
```

Use for:

- Daily crypto reports
- Token watchlists
- Market sentiment
- Risk notes
- Telegram alerts

### Content Creation Workflow

```txt
Content Agent
   ↓
Research Agent
   ↓
Report Agent
   ↓
Twitter/X Thread or Script
```

Use for:

- Twitter/X threads
- Hooks
- Captions
- Newsletters
- Content calendars
- Short-form video scripts

### Lead Generation Workflow

```txt
Lead Generation Agent
   ↓
Workflow Automation Agent
   ↓
CRM / Google Sheets / Telegram Alert
```

Use for:

- Prospect research
- Lead scoring
- Cold outreach
- CRM-ready data
- Follow-up workflow

### Customer Support Workflow

```txt
Customer Support Agent
   ↓
Workflow Automation Agent
   ↓
Telegram Bot Agent
   ↓
Human Review or Auto Reply
```

Use for:

- FAQ automation
- WhatsApp support
- Ticket classification
- Complaint summary
- Support alerts

### Document Processing Workflow

```txt
Document Agent
   ↓
Report Agent
   ↓
Knowledge Base / Summary / Table
```

Use for:

- PDF summary
- Key point extraction
- Meeting notes
- Report generation
- Document-based FAQ

## Skill Format

Each skill uses a structured `SKILL.md` format:

```txt
---
name:
title:
description:
category:
version:
---

# Skill Name

## Role
Defines what the agent is.

## Objective
Defines what the agent should accomplish.

## When To Use This Skill
Defines when the skill should be activated.

## Required Input
Defines what information the agent needs.

## Workflow
Defines the step-by-step process.

## Output Format
Defines the final response structure.

## Example Use Case
Shows how the skill works.

## Multi-Agent Collaboration
Shows how the skill works with other agents.

## Behavior Rules
Defines how the agent should behave.

## Prompt
The reusable instruction that can be copied into an AI agent.
```

## Agent Ecosystem

AIZEN skills are designed to be copied, customized, and loaded into multi-agent systems such as:

```txt
OpenClaw
Hermes
n8n
CrewAI
AutoGen
LangChain
Flowise
Telegram Bot API
Custom GPT
Claude Projects
Cursor Agent
Custom AI Agent Frameworks
```

## Important Notes

AIZEN is not a one-click SaaS product.

AIZEN is a reusable AI agent skills library.

The skills are designed to help builders, creators, founders, traders, operators, and developers create structured AI agent workflows.

You can use these skills as:

- System prompts
- Agent instructions
- Custom GPT instructions
- Claude project instructions
- n8n AI agent prompts
- OpenClaw skill references
- Hermes workflow references
- CrewAI role definitions
- AutoGen agent specs
- LangChain agent instructions
- Custom multi-agent workflow templates

## Recommended Workflow

```txt
1. Choose a skill from the skills folder.
2. Copy the SKILL.md instruction.
3. Paste it into your AI agent system.
4. Add tools, APIs, memory, or automation logic.
5. Test with real input.
6. Customize the output format.
7. Connect it into a larger workflow.
```

## Built By

Built by Ghost of Sol.

AIZEN is for builders who want AI agents that can actually execute workflows, not just chat.