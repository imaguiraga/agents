# Agentic AI Development: Complete Learning Path with Resources

## Overview

This learning path guides you through **ten progressive phases**, starting with Microsoft's foundational course and building toward production-ready agent systems. By the end, you will have hands-on experience with the most important frameworks, protocols, and standards in the agentic AI ecosystem.

**Total estimated time:** 12-14 weeks (flexible, depending on pace)

**Prerequisites:** Basic programming knowledge (any language), curiosity about AI

---

## Where Microsoft Generative AI for Beginners Fits

Microsoft's **Generative AI for Beginners** is added as **Phase 0**—a foundational prerequisite before diving into agent-specific concepts. This placement is intentional:

| Phase | Focus | Why This Order |
| :--- | :--- | :--- |
| **0** | **Microsoft Generative AI for Beginners** | **Build foundational AI literacy before agent development** |
| 1 | Fundamentals of Agentic AI | Learn what agents are and how they work |
| 2.5 | Agent Skills | Learn how to package reusable agent knowledge |
| 2 | OpenAI Agents SDK | Apply skills concepts in a lightweight framework |
| 3 | Pydantic AI | Add type safety to skill-based workflows |
| 4 | Google ADK | Deploy skills in hierarchical multi-agent systems |
| 5 | AG2 | Use skills in collaborative group chat environments |
| 6 | A2A & A2UI | Enable cross-agent communication and UI generation |
| 7 | CopilotKit | Connect skill-powered agents to frontends |
| 8 | AG-UI | Master the protocol for agent-frontend communication |

**Why Phase 0 belongs here:** Before building agents, you need to understand what generative AI is, how LLMs work, prompt engineering, RAG, and responsible AI practices. Microsoft's free course provides exactly this foundation.

---

## Phase 0: Microsoft Generative AI for Beginners — The Foundation

**Duration:** 1-2 weeks | **Goal:** Build comprehensive generative AI literacy before agent development

### What Is This Course?

Microsoft's **"Generative AI for Beginners"** is a free, comprehensive course created by Microsoft Cloud Advocates that teaches the fundamentals of building generative AI applications. The course is available in multiple editions for different programming languages:

| Edition | Language/Framework | Latest Update | Best For |
| :--- | :--- | :--- | :--- |
| **Python Edition** | Python | 21 lessons | General-purpose AI development |
| **.NET Edition** | C# / .NET 10 | Version 2 (March 2026) | Microsoft ecosystem developers |
| **Java Edition** | Java | August 2025 | Java enterprise developers |
| **JavaScript Edition** | JavaScript/TypeScript | 2025 | Web developers |

### Course Structure

**Original 12-Lesson Course (2023):**
1. Introduction to Generative AI and LLMs
2. Exploring and comparing different LLMs
3. Using Generative AI Responsibly
4. Understanding Prompt Engineering Fundamentals
5. Creating Advanced Prompts
6. Building Text Generation Applications
7. Building Chat Applications
8. Building Search Apps with Vector Databases
9. Building Image Generation Applications
10. Building Low-Code AI Applications
11. Integrating External Applications with Function Calling
12. Designing UX for AI Applications

**Updated 18-Lesson Series (2025):**
- Each episode is 8–25 minutes
- Total viewing time: less than 1.5 hours
- Added topics: AI Agents, Fine-Tuning, RAG, Open-Source Models (Hugging Face), Securing AI Applications, The AI Application Lifecycle

**.NET Edition Version 2 (March 2026)** — Reorganized into 5 focused lessons:
1. Introduction to Generative AI
2. Generative AI Techniques
3. AI Patterns and Applications
4. Agents using Microsoft Agent Framework (MAF)
5. Responsible AI

### Key Topics You Will Learn

| Topic | What You'll Master | Why It Matters for Agents |
| :--- | :--- | :--- |
| **LLM Fundamentals** | How large language models work internally | Agents build on LLMs—you need this foundation |
| **Prompt Engineering** | Writing effective prompts for quality outputs | Agent instructions are sophisticated prompts |
| **RAG (Retrieval-Augmented Generation)** | Connecting AI to external data sources | Agents need RAG for knowledge retrieval |
| **Function Calling** | Integrating AI with external tools | The core mechanism of agent tool use |
| **AI Agents** | Building autonomous, task-oriented systems | Direct prerequisite for the rest of this path |
| **Responsible AI** | Ethics, bias, transparency, security | Critical for production agent deployment |
| **Vector Databases** | Semantic search and memory | Agent memory systems |
| **Fine-Tuning** | Adapting models for specific needs | Specialized agent capabilities |

### Learning Resources

#### Primary Course Links

| Resource | Description | Link |
| :--- | :--- | :--- |
| **Generative AI for Beginners (Python)** | Main 21-lesson course on GitHub | [github.com/microsoft/generative-ai-for-beginners](https://github.com/microsoft/generative-ai-for-beginners) |
| **Generative AI for Beginners (.NET) v2** | .NET 10, Microsoft.Extensions.AI, MAF agents | [github.com/microsoft/Generative-AI-for-Beginners-dotnet](https://github.com/microsoft/Generative-AI-for-Beginners-dotnet) |
| **Generative AI for Beginners (Java)** | Java edition with Foundry Local, MCP | [devblogs.microsoft.com/java/generative-ai-for-beginners-java-edition-launched/](https://devblogs.microsoft.com/java/generative-ai-for-beginners-java-edition-launched/) |

#### Video Series

| Resource | Format | Link |
| :--- | :--- | :--- |
| **YouTube Video Series** | 18 episodes, 8-25 minutes each | Available via Microsoft's YouTube channel |

#### Microsoft Learn Modules (Supplemental)

| Module | Focus | Link |
| :--- | :--- | :--- |
| **Explore Generative AI** | Fundamentals, NLP, NLG, LLMs, Microsoft Copilot | [learn.microsoft.com/training/modules/explore-generative-ai/](https://learn.microsoft.com/training/modules/explore-generative-ai/) |
| **Introduction to Generative AI** | LLM functionality, model comparison, critical thinking | [learn.microsoft.com/training/modules/intro-generative-ai-explore-basics/](https://learn.microsoft.com/training/modules/intro-generative-ai-explore-basics/) |
| **Introduction to AI in Azure** | AI concepts, ML, NLP, computer vision, Azure services | [learn.microsoft.com/training/modules/introduction-to-ai-in-azure/](https://learn.microsoft.com/training/modules/introduction-to-ai-in-azure/) |

### Hands-On Exercises

**Exercise 1: Prompt Engineering Practice**
Using any LLM (Azure OpenAI, OpenAI, or local), practice writing prompts for different tasks: summarization, extraction, transformation, and creative generation.

**Exercise 2: Build a Simple Text Generation App**
Following Lesson 6, build a basic text generation application using Azure OpenAI or OpenAI API.

**Exercise 3: RAG Implementation**
Implement a simple RAG system using vector database integration (Lesson 8) to ground LLM responses in your own documents.

**Exercise 4: Function Calling**
Build an application that uses function calling to integrate with external APIs (Lesson 11).

**Output:** A portfolio of small generative AI applications demonstrating prompt engineering, RAG, and function calling—the building blocks of agents.

### Connecting Phase 0 to Phase 1

| What You Learn in Phase 0 | How It Applies to Agent Development |
| :--- | :--- |
| LLM fundamentals | Agents are LLMs with tool access and memory |
| Prompt engineering | Agent instructions and system prompts |
| RAG | Agent knowledge retrieval and grounding |
| Function calling | Agent tool use and external actions |
| AI Agents lesson | Direct introduction to agent concepts |
| Responsible AI | Safety guardrails for agent deployment |

---

## Phase 1: Fundamentals of Agentic AI

**Duration:** 1 week | **Goal:** Understand core concepts that apply to every framework

*Prerequisite: Completion of Phase 0 (Microsoft Generative AI for Beginners)*

### Core Concepts to Master

| Concept | Description |
| :--- | :--- |
| **Agent Loop** | The cycle: receive input → LLM decides → take action → observe → repeat |
| **Tools / Function Calling** | Giving LLMs the ability to call external functions |
| **Memory & State** | Short-term vs. long-term memory management |
| **Multi-Agent Patterns** | Handoffs, hierarchical orchestration, group chat |
| **RAG** | Retrieval-Augmented Generation for external knowledge |

### Learning Resources

| Resource | What You'll Learn | Link |
| :--- | :--- | :--- |
| **Microsoft's AI Agents for Beginners** | 18 lessons from fundamentals to production | [github.com/microsoft/ai-agents-for-beginners](https://github.com/microsoft/ai-agents-for-beginners) |
| **shameemreza/agentic-ai-development** | Structured roadmap with Python basics to advanced projects | [github.com/shameemreza/agentic-ai-development](https://github.com/shameemreza/agentic-ai-development) |
| **DeepLearning.AI - Agentic AI Patterns** | Andrew Ng course on reflection, tool use, multi-agent | [github.com/totola/agentic-ai-course](https://github.com/totola/agentic-ai-course) |

### Hands-On Exercise

Build a simple research assistant using just the OpenAI API (no framework) to understand the agent loop before using frameworks.

**Output:** A working single-agent loop with one tool (e.g., web search or calculator)

---

## Phase 2.5: Agent Skills — The Missing Link

**Duration:** 1 week | **Goal:** Master the open standard for packaging reusable agent knowledge

### What Are Agent Skills?

Agent Skills are a **modular, open standard** introduced by Anthropic in late 2025 for giving agents reusable capabilities. A skill is simply a folder containing a `SKILL.md` file (Markdown with YAML frontmatter) plus optional supporting files (scripts, references, examples).

### Skills vs. Tools vs. MCP vs. Subagents

| Aspect | Tools | MCP | Agent Skills | Subagents |
| :--- | :--- | :--- | :--- | :--- |
| **What they provide** | Low-level capabilities | Data/tool connectivity | Workflow knowledge | Isolated execution |
| **Analogy** | Hammer and saw | Plumbing | Blueprint for a bookshelf | Specialized worker |
| **When activated** | When called | When data needed | When task matches description | When delegated |

### Why Agent Skills Matter

**1. Dramatic Performance Improvements** — Open-Agent-Skills benchmarks:

| Benchmark | MCP Accuracy | Skills + MCP Accuracy | Improvement |
| :--- | :--- | :--- | :--- |
| **GitHub** | 29.35% | **43.48%** | +14.13 pp |
| **Filesystem** | 32.5% | **53.3%** | +20.8 pp |
| **Playwright WebArena** | 32.14% | **52.38%** | +20.24 pp |

**2. Massive Token Efficiency** — 19-39% reduction on average; extreme cases 80-95% reduction.

**3. Cross-Platform Compatibility** — Works with Claude Code, OpenAI Codex, GitHub Copilot, VS Code, Cursor, Gemini CLI, and more.

### Learning Resources

| Resource | What You'll Learn | Link |
| :--- | :--- | :--- |
| **What Are Agent Skills?** (Awesome Agent Skills) | Comprehensive beginner-friendly introduction | [github.com/skillmatic-ai/awesome-agent-skills](https://github.com/skillmatic-ai/awesome-agent-skills) |
| **Equipping agents for the real world with Agent Skills** | Original announcement from Anthropic Engineering | [anthropic.com/engineering/equipping-agents-for-the-real-world-with-agent-skills](https://www.anthropic.com/engineering/equipping-agents-for-the-real-world-with-agent-skills) |
| **Agent Skills with Anthropic** (DeepLearning.AI) | Marketing campaign analysis, code generation, research agent | [learn.deeplearning.ai/courses/agent-skills-with-anthropic](https://learn.deeplearning.ai/courses/agent-skills-with-anthropic) |
| **Official Skill Collections** | Anthropic, OpenAI, Microsoft, Hugging Face skills | [github.com/anthropics/skills](https://github.com/anthropics/skills) |

### Hands-On Exercise

Create a `SKILL.md` file for a research methodology skill, then test it with Claude Code or Deep Agents CLI.

**Output:** A reusable skill that makes any agent research consistently, without re-prompting.

---

## Phase 2: OpenAI Agents SDK

**Duration:** 1 week | **Goal:** Build lightweight, single-agent systems with handoffs

### Learning Resources

| Resource | What You'll Build | Link |
| :--- | :--- | :--- |
| **OpenAI Agents SDK Documentation** | Complete API reference and quickstart | [openai.github.io/openai-agents-python](https://openai.github.io/openai-agents-python/) |
| **Coding Agent Cookbook** | Build a coding agent with GPT-5.1 | [openai.com/cookbook/examples/build_a_coding_agent_with_gpt-5.1](https://developers.openai.com/cookbook/examples/build_a_coding_agent_with_gpt-5.1) |

### Hands-On Exercise

Build a customer support triage system with automatic handoffs between billing and technical support agents.

**Output:** A multi-agent system where the triage agent routes queries to specialized agents

---

## Phase 3: Pydantic AI

**Duration:** 1 week | **Goal:** Build type-safe, production-ready agents with validation

### Learning Resources

| Resource | What You'll Learn | Link |
| :--- | :--- | :--- |
| **Pydantic AI Documentation** | Complete API reference and examples | [ai.pydantic.dev](https://ai.pydantic.dev) |
| **pydantic-ai-skills** (Community) | Pydantic AI integration skills | [github.com/DougTrajano/pydantic-ai-skills](https://github.com/DougTrajano/pydantic-ai-skills) |

### Hands-On Exercise

Build a data extraction agent with guaranteed output structure using Pydantic models for validation.

**Output:** An agent that never returns malformed data

---

## Phase 4: Google ADK (Agent Development Kit)

**Duration:** 1-2 weeks | **Goal:** Build hierarchical multi-agent systems deployable to GCP

### Learning Resources

| Resource | What You'll Build | Link |
| :--- | :--- | :--- |
| **Build Your First ADK Agent Workforce** | Personal assistant → tool-powered → multi-agent team | [cloud.google.com/blog/topics/developers-practitioners/build-your-first-adk-agent-workforce](https://cloud.google.com/blog/topics/developers-practitioners/build-your-first-adk-agent-workforce) |
| **Google ADK 5-Day Course** | Architectures, tools, sessions, memory | [github.com/Badribn0612/google_adk](https://github.com/Badribn0612/google_adk) |

### Hands-On Exercise

Build a content generation pipeline with researcher → outliner → writer → editor agents in sequence.

**Output:** A complete article generated by four specialized agents working in sequence

---

## Phase 5: AG2 (formerly AutoGen)

**Duration:** 1-2 weeks | **Goal:** Build collaborative agent workforces with group chat

### Learning Resources

| Resource | What You'll Learn | Link |
| :--- | :--- | :--- |
| **AG2 Documentation - Notebooks Gallery** | Research agents, group chat, code generation (20+ notebooks) | [docs.ag2.ai](https://docs.ag2.ai) |
| **AG2 + AG-UI Integration Guide** | Connect AG2 agents to frontend via AG-UI | [docs.ag2.ai/0.11.1/docs/user-guide/ag-ui](https://docs.ag2.ai/0.11.1/docs/user-guide/ag-ui) |

### Hands-On Exercise

Build a collaborative code review team with planner, coder, and reviewer agents working together in a group chat.

**Output:** A multi-turn conversation where agents collaborate to produce reviewed, working code

---

## Phase 6: A2A & A2UI

**Duration:** 1-2 weeks | **Goal:** Enable cross-framework communication and declarative UI

### Learning Resources

| Resource | What You'll Learn | Link |
| :--- | :--- | :--- |
| **A2A Protocol Tutorial** | Agent Cards, Task lifecycle, A2A Server/Client | [a2aprotocol.org](https://a2aprotocol.org) |
| **A2UI + A2A Complete Guide** | Integration patterns, three-layer architecture | [a2aprotocol.ai](https://a2aprotocol.ai) |
| **A2UI for Google Apps Script** | 5 sample applications | [github.com/tanaikech/A2UI-for-Google-Apps-Script](https://github.com/tanaikech/A2UI-for-Google-Apps-Script) |

### Hands-On Exercise

Build a travel assistant that discovers and delegates to specialized flight and hotel agents via A2A Agent Cards.

**Output:** A single assistant that coordinates agents built with different frameworks

---

## Phase 7: CopilotKit

**Duration:** 1 week | **Goal:** Connect agents to production frontends with real-time UI streaming

### Learning Resources

| Resource | What You'll Build | Link |
| :--- | :--- | :--- |
| **CopilotKit Quickstart** | Full-stack Next.js app with agent backend | [copilotkit.ai](https://copilotkit.ai) |
| **CopilotKit Generative UI Docs** | All three patterns of Generative UI | [docs.copilotkit.ai/generative-ui](https://docs.copilotkit.ai/generative-ui) |

### Hands-On Exercise

Build a weather assistant with a custom React component that renders loading states and results using `useFrontendTool`.

**Output:** A full-stack application where the agent controls UI rendering in real-time

---

## Phase 8: AG-UI (Agent-User Interaction Protocol)

**Duration:** 1 week | **Goal:** Master the protocol for agent-frontend communication

### AG-UI Event Types

| Category | Events |
| :--- | :--- |
| **Lifecycle** | `RUN_STARTED`, `RUN_FINISHED`, `RUN_ERROR` |
| **Text Message** | `TEXT_MESSAGE_START`, `TEXT_MESSAGE_CONTENT`, `TEXT_MESSAGE_END` |
| **Tool Call** | `TOOL_CALL_START`, `TOOL_CALL_ARGS`, `TOOL_CALL_RESULT`, `TOOL_CALL_END` |
| **State** | `STATE_SNAPSHOT`, `STATE_DELTA` |

### Learning Resources

| Resource | What You'll Learn | Link |
| :--- | :--- | :--- |
| **AG-UI Protocol GitHub** | Source code, SDKs, integrations (12.9k stars) | [github.com/ag-ui-protocol/ag-ui](https://github.com/ag-ui-protocol/ag-ui) |
| **AG-UI Dojo** | Interactive examples (50-200 lines each) | [ag-ui.com](https://ag-ui.com) |

### Hands-On Exercise

Build a complete AG-UI integration with Python backend and JavaScript frontend for real-time agent streaming.

**Output:** A production-ready agent with streaming text, tool call visualization, and state sync

---

## Capstone Project: Complete Agentic System

**Duration:** 1-2 weeks | **Goal:** Combine everything learned

### Project: Enterprise Research & Reporting System with Generative UI

| Component | Technology | Responsibility |
| :--- | :--- | :--- |
| **Foundation** | Microsoft Generative AI for Beginners | Core AI literacy and LLM concepts |
| **User Interface** | CopilotKit (AG-UI) + React | Chat interface with real-time agent activity |
| **Skills Library** | Custom SKILL.md packages | Research methodologies, data analysis workflows |
| **Triage Agent** | OpenAI Agents SDK | Routes user requests to specialists |
| **Research Team** | AG2 (GroupChat) | Multiple researchers collaborate with research skills |
| **Workflow Pipeline** | Google ADK (SequentialAgent) | Research → Analyze → Write → Review |
| **Data Extraction** | Pydantic AI | Type-safe extraction with validation skills |
| **External Agents** | A2A Protocol | Flight search, calendar lookup |
| **Dynamic UI** | A2UI | Booking forms, approval dialogs, data tables |

---

## Framework, Protocol & Skills Reference

| Technology | Best For | Abstraction Level | Learning Curve |
| :--- | :--- | :--- | :--- |
| **Microsoft GenAI for Beginners** | Foundational AI literacy | Course | ★☆☆☆☆ |
| **Agent Skills** | Reusable workflows, knowledge packaging | Standard | ★★☆☆☆ |
| **OpenAI Agents SDK** | Single agents, simple handoffs | Very low | ★☆☆☆☆ |
| **Pydantic AI** | Type-safe production agents | Low | ★★☆☆☆ |
| **Google ADK** | Hierarchical workflows, GCP deployment | Medium | ★★★☆☆ |
| **AG2** | Collaborative group chat, nested conversations | Medium | ★★★☆☆ |
| **A2A** | Cross-framework agent communication | Protocol | ★★☆☆☆ |
| **A2UI** | Declarative UI generation | Protocol | ★★★☆☆ |
| **CopilotKit** | Agent-UI integration, real-time streaming | Framework | ★★☆☆☆ |
| **AG-UI** | Protocol foundation for agent-frontend communication | Protocol | ★★☆☆☆ |

---

## Quick Reference: Installation Commands

```bash
# Microsoft Generative AI for Beginners - Clone the repository
git clone https://github.com/microsoft/generative-ai-for-beginners.git
cd generative-ai-for-beginners

# For .NET edition
git clone https://github.com/microsoft/Generative-AI-for-Beginners-dotnet.git

# For Java edition
git clone https://github.com/microsoft/generative-ai-for-beginners-java.git

# OpenAI Agents SDK
pip install openai-agents
pip install "openai-agents[litellm]"

# Pydantic AI
pip install pydantic-ai
pip install pydantic-ai-litellm

# Google ADK
pip install google-adk

# AG2 (with AG-UI support)
pip install "ag2[openai,ag-ui]"

# A2A SDK
pip install a2a-sdk

# CopilotKit (Node.js/React)
npm install @copilotkit/react-core @copilotkit/react-ui
npm install @copilotkit/runtime

# AG-UI (via Microsoft Agent Framework - Python)
pip install agent-framework-ag-ui --pre

# MCP Skills Server
npx @koderspa/mcp-skills@latest

# Clone official skill collections
git clone https://github.com/anthropics/skills
git clone https://github.com/openai/skills
```

---

Next Steps After This Path

Once you complete all phases, consider exploring:

· MCP (Model Context Protocol): Building custom tool servers
· MCP Apps: Open-ended Generative UI with iframe-based components
· Open-JSON-UI: OpenAI's declarative UI specification
· Semantic Kernel: Microsoft's enterprise-focused framework (.NET/TypeScript)
· AG-UI Dojo: Interactive protocol testing environment
· Skill Marketplaces: agentskill.sh (44k+ skills), SkillsMP for discovering community skills

---

This document is a living guide. As frameworks evolve, check official documentation for the latest updates.
