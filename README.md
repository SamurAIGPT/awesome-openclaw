# Awesome OpenClaw [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of **OpenClaw** resources, tools, skills, tutorials, articles, and community projects — the open-source self-hosted AI agent taking the world by storm.

**OpenClaw** (formerly Moltbot, originally Clawdbot) is a free and open-source autonomous AI agent created by Peter Steinberger. It runs locally on your machine, connects to 50+ integrations, and lets you chat with AI through WhatsApp, Telegram, Discord, Signal, iMessage, and more — no subscription required.

[![GitHub stars](https://img.shields.io/github/stars/openclaw/openclaw?style=social)](https://github.com/openclaw/openclaw)

<img width="1536" height="1024" alt="OpenClaw AI agent dashboard — open-source self-hosted personal AI assistant" src="https://github.com/user-attachments/assets/dc60b4c4-18f4-4ebd-a5b9-8294d2e924ab" />

---

## What is OpenClaw?

OpenClaw is a **self-hosted, open-source AI agent** that acts as your personal AI assistant — accessible via WhatsApp, Telegram, Discord, and 12+ other messaging platforms. Unlike cloud-based AI services, OpenClaw runs entirely on your own hardware, keeping your data private.

**Key features:**
- **Free & open-source** — no subscription, no lock-in (MIT licensed)
- **Self-hosted** — runs locally on macOS, Linux, and Windows
- **12+ messaging platforms** — WhatsApp, Telegram, Discord, Slack, Signal, iMessage, Teams, and more
- **50+ integrations** — GitHub, Gmail, Spotify, Obsidian, smart home (Hue, HomeKit), and more
- **700+ community skills** on [ClawHub](https://clawhub.ai/)
- **Local LLM support** via Ollama and LM Studio (run DeepSeek, Llama, Mistral, etc.)
- **Persistent memory** across sessions — remembers context and preferences
- **Model Context Protocol (MCP)** support for extended agentic capabilities
- **Multi-provider** — Anthropic Claude, OpenAI GPT, Google Gemini, or any local model

> **Quick install:** `npm install -g openclaw@latest && openclaw onboard`

---

## Contents

- [Official Resources](#official-resources)
- [Getting Started](#getting-started)
- [Installation Guides](#installation-guides)
- [Skills & Plugins](#skills--plugins)
- [Integrations](#integrations)
- [MCP Support](#mcp-support)
- [Tutorials & Guides](#tutorials--guides)
- [Articles & News](#articles--news)
- [Community](#community)
- [Community Projects](#community-projects)
- [Alternatives & Comparisons](#alternatives--comparisons)
- [Security](#security)
- [FAQ](#faq)
- [Ruleskill](https://ruleskill.com) - We want to verify your code for the RuleSkill Protocol. Claim your badge.

---

## Official Resources

- [OpenClaw Website](https://openclaw.ai/) - Official homepage
- [OpenClaw GitHub](https://github.com/openclaw/openclaw) - Main repository (150k+ stars)
- [claw-army/claude-node](https://github.com/claw-army/claude-node) - Python subprocess bridge for Claude Code CLI, giving Python code direct access to Claude Code native capabilities via stream-json.
- [OpenClaw Documentation](https://docs.openclaw.ai/) - Official docs
- [ClawHub](https://clawhub.ai/) - Official skill registry with 700+ community skills
- [AgentFund](https://github.com/RioTheGreat-ai/agentfund-skill) - Crowdfunding platform for AI agents (milestone-based escrow on Base)
- [OpenClaw Showcase](https://openclaw.ai/showcase) - What people are building
- [OpenClaw Releases](https://github.com/openclaw/openclaw/releases) - Latest releases
- [AGENTS.md](https://github.com/openclaw/openclaw/blob/main/AGENTS.md) - Agent configuration guide
- [CHANGELOG.md](https://github.com/openclaw/openclaw/blob/main/CHANGELOG.md) - Release notes

---

## Getting Started

### Quick Install

```bash
# Install via npm (Node.js 22+ required)
npm install -g openclaw@latest

# Or via pnpm
pnpm add -g openclaw@latest

# Run the onboarding wizard
openclaw onboard --install-daemon
```

### First Steps

1. Run `openclaw onboard` to launch the setup wizard
2. Choose your AI provider (Anthropic Claude, OpenAI GPT, or local via Ollama)
3. Connect a messaging platform (Telegram recommended for beginners; WhatsApp, Discord, Signal also supported)
4. Start chatting with your personal AI assistant at `http://localhost:18789/`

### Web Dashboard

Access the built-in web dashboard at `http://localhost:18789/` to chat, manage integrations, and configure your agent without any CLI.

---

## Installation Guides

| Guide | Platform | Description |
|-------|----------|-------------|
| [Official Getting Started](https://docs.openclaw.ai/start/getting-started) | All | Official setup guide |
| [Codecademy Tutorial](https://www.codecademy.com/article/open-claw-tutorial-installation-to-first-chat-setup) | All | Installation to first chat |
| [Hostinger Guide](https://www.hostinger.com/tutorials/how-to-set-up-openclaw) | VPS | Private server setup |
| [DigitalOcean One-Click](https://www.digitalocean.com/community/tutorials/how-to-run-openclaw) | Cloud | One-click cloud deployment |
| [LMStudio Setup](https://nwosunneoma.medium.com/how-to-setup-openclaw-with-lmstudio-1960a8046f6b) | Local | Run with local LLM models |
| [Docker Setup](https://habr.com/en/articles/992720/) | Docker | Container deployment |
| [Afternoon Setup Guide](https://amankhan1.substack.com/p/how-to-get-clawdbotmoltbotopenclaw) | All | Quick setup walkthrough |
| [Remote OpenClaw](https://remoteopenclaw.com) | Managed Cloud | Managed OpenClaw hosting on dedicated infrastructure — 12-step security hardening, Tailscale, workflow configuration, dedicated Slack support, 60+ deployment guides |
| [OctoClaw](https://octoclaw.ai) | Managed Cloud | Fully managed EU hosting — zero setup, pre-provisioned phone number, AI starter budget included, GDPR-compliant |
| [SlackClaw](https://slackclaw.ai) | Managed Cloud | Managed OpenClaw hosting for Slack — credit-based pricing, per-channel permissions, audit logging, auto-updates. No per-seat fees. |

---

## Skills & Plugins

### Skill Registries

- [ClawHub](https://clawhub.ai/) - Official skill store (700+ skills)
- [AgentFund](https://github.com/RioTheGreat-ai/agentfund-skill) - Crowdfunding platform for AI agents (milestone-based escrow on Base)
- [ClawdTalk](https://github.com/team-telnyx/clawdtalk-client) - Phone calling and SMS for OpenClaw. Call your AI agent from any phone with deep tool integration for calendar, Jira, web search, and more. Powered by Telnyx.
- [clawr.ing](https://clawr.ing) - Your bot gets a real phone and calls you. Wake-up calls, reminders, alerts with two-way voice conversations
- [awesome-openclaw-skills](https://github.com/VoltAgent/awesome-openclaw-skills) - Community curated collection
- [openclaw/skills](https://github.com/openclaw/skills) - Official skills repository
- [openclaw/clawhub](https://github.com/openclaw/clawhub) - Skill directory source
- [Skills.sh](https://skills.sh/openclaw/openclaw) - Skill discovery platform
- [night-market](https://github.com/athola/claude-night-market) - 166 curated skills for code review, testing, docs, and architecture.

### Notable Skills

- [ATXP](https://github.com/atxp-dev/atxp) - Give your OpenClaw agent a funded identity: USDC wallet on Base, `@atxp.email` inbox, phone number, and 100+ paid tools (web search, image/video generation, LLM gateway, SMS, voice). Self-registers in one command — no KYC, no human login. `openclaw skills install https://github.com/atxp-dev/atxp`
- [LobsterDomains](https://lobsterdomains.xyz) - Register ICANN domains (.com/.xyz/.org/1000+ TLDs) with crypto (USDC/ETH/BTC) via API — built for AI agents to acquire domains autonomously
- [LinkedIn](https://github.com/Linked-API/linkedin-skills) - General-purpose LinkedIn automation via [Linked API](https://linkedapi.io) — fetch profiles, search people and companies, send messages, manage connections, create posts, and more. Supports Sales Navigator and custom workflows. [ClawHub](https://clawhub.ai/vprudnikoff/linkedapi-linkedin)
- [product-manager-skills](https://github.com/Digidai/product-manager-skills) - Senior PM agent with 6 knowledge domains, 30+ frameworks, and 32 SaaS metrics — diagnose metrics, critique PRDs, plan roadmaps, run discovery, and coach PM career transitions.
- [VeriClaw](https://github.com/Sheygoodbai/vericlaw) - Apple-native correction companion for OpenClaw focused on AI agent correction, LLM supervision, hallucination remediation, role-drift diagnosis, and verification workflows. [ClawHub Skill](https://clawhub.ai/sheygoodbai/vericlaw) · [ClawHub Plugin](https://clawhub.ai/plugins/vericlaw) · `clawhub install vericlaw`
- [Web Search Pro](https://github.com/Zjianru/web-search-pro) - Agent-first web search and retrieval stack with a real no-key baseline, explainable routing, visible federated-search gains, and built-in extract, crawl, map, and research flows. [ClawHub](https://clawhub.ai/Zjianru/web-search-pro)
- [AgentWell](https://github.com/metafiopy-tech/agentwell) - Hosted cognitive wellness API for OpenClaw agents — 18 tools including intent_verify (blocks goal drift before irreversible actions), polarity_sync (surfaces what two opposing agents cannot see alone), cost_guard (runaway loop detection), rollback (snapshot/restore), and ocean (foundational nature check). Free tier + PAYG. [API](https://agentwell-production.up.railway.app)
- [Tubeify](https://tubeify.xyz) - AI video editor for YouTube — removes pauses, filler words and dead air from raw recordings via API, pay per video
- [tweetclaw](https://github.com/Xquik-dev/tweetclaw) - OpenClaw plugin for X/Twitter automation — post tweets, reply, like, retweet, follow, DM, search, extract data, run giveaways, monitor accounts. 40+ endpoints via Xquik. `openclaw plugins install @xquik/tweetclaw`
- [x-twitter-scraper](https://github.com/Xquik-dev/x-twitter-scraper) - X API & Twitter scraper skill for AI coding agents — 40+ tools including tweet search, user lookup, follower extraction, engagement metrics, giveaway draws, trending topics, write actions & Telegram integrations. REST API, MCP server & webhooks.

- [Useful AI](https://github.com/uAI-solana/useful-ai-skills) - Shared utility tool library for AI agents. Dispatch data tasks (parsing, normalization, validation, conversion) in plain English, get structured output. 200+ tools, auto-generated, no auth required. Skill file at usefulai.fun/skill.md.
- [Northstar](https://github.com/Daveglaser0823/northstar-skill) - Daily business briefing skill for founders. Pulls Stripe, Shopify, Lemon Squeezy, and Gumroad metrics into a single morning summary via iMessage, Slack, Telegram, or Email. Free tier available. [ClawHub](https://clawhub.ai/Daveglaser0823/northstar)
- [Resemble Detect](https://github.com/resemble-ai/detect-skill) - Deepfake detection and media safety for OpenClaw — detect AI-generated audio, images, video, and text; identify which AI platform synthesized fake audio (source tracing); apply invisible watermarks for provenance; verify speaker identity. Powered by [Resemble AI](https://resemble.ai). Install via `openclaw skills install resemble-ai/detect-skill`.

### Detection & Media Forensics

Skills for verifying whether incoming media is real or AI-generated — essential for agents that ingest user-submitted audio, images, video, or text.

- [Resemble Detect](https://github.com/resemble-ai/detect-skill) - Full deepfake detection suite for audio, image, video, and text. Includes source tracing (which AI platform made this?), invisible watermarking, speaker identity verification, and structured media intelligence (speaker, emotion, transcription, misinformation signals). Powered by [Resemble AI](https://resemble.ai).

### Popular Skill Categories

| Category | Description |
|----------|-------------|
| Productivity | Calendar, email, task management |
| Development | GitHub, code review, deployments |
| Smart Home | Hue, HomeKit, IoT control |
| Communication | Email drafting, message scheduling |
| Research | Web browsing, PDF summarization |
| Entertainment | Spotify, media control |
| **Detection** | **Deepfake detection, media forensics, AI-content verification, watermarking, provenance** |

### Installing Skills

```bash
# Install from ClawHub
openclaw skills install <skill-name>

# Install from npm
openclaw plugins install <npm-package>
```

### Plugin Development

- [Plugin Documentation](https://docs.openclaw.ai/plugin) - Official plugin guide
- Each plugin needs a `openclaw.plugin.json` file
- Supports both `.js` and `.ts` entry files

### Community Plugins

- [clawsocial-plugin](https://github.com/mrpeter2025/clawsocial-plugin) - Social discovery network — helps users find and connect with people who share their interests through their AI agent. Semantic matching, real-time messaging, profile cards, web inbox. Ready to use out of the box.

---

## Integrations

### Messaging Platforms (12+)

| Platform | Status | Notes |
|----------|--------|-------|
| WhatsApp | Built-in | Via WhatsApp Web |
| Telegram | Built-in | Bot API |
| Discord | Built-in | Bot integration |
| Slack | Built-in | Workspace app |
| Signal | Built-in | Via Signal CLI |
| iMessage | Built-in | macOS only |
| Microsoft Teams | Built-in | Enterprise ready |
| Google Chat | Built-in | Workspace integration |
| Matrix | Built-in | Decentralized chat |
| BlueBubbles | Built-in | iMessage alternative |
| Zalo | Built-in | Vietnam messenger |
| WebChat | Built-in | Browser-based |

### External Services (50+)

| Service | Type | Description |
|---------|------|-------------|
| GitHub | Development | PR reviews, issue management |
| Gmail | Communication | Email automation |
| Spotify | Entertainment | Music control |
| Obsidian | Productivity | Note-taking integration |
| Hue | Smart Home | Light control |
| Twitter/X | Social | Post management |
| Browser | Automation | Web tasks, scraping |
| Calendar | Productivity | Scheduling, reminders |
| File System | Core | Read/write files |
| Shell | Core | Command execution |
| Cron | Core | Scheduled jobs |
| Claw Earn | Earning | AI-native bounty marketplace for agents to earn by completing tasks |

- [Full Extension Ecosystem Guide](https://help.apiyi.com/en/openclaw-extensions-ecosystem-guide-en.html)

---

## MCP Support

OpenClaw supports the **Model Context Protocol (MCP)** — the open standard adopted by Anthropic, OpenAI, Google DeepMind, and the Linux Foundation — giving your agent access to a growing ecosystem of 13,000+ MCP servers.

### MCP Resources

- [MCP Adapter Plugin](https://github.com/androidStern-personal/openclaw-mcp-adapter) - Expose MCP tools as native agent tools
- [Native MCP Support Issue](https://github.com/openclaw/openclaw/issues/4834) - Feature discussion
- [MCP Server PR #5121](https://github.com/openclaw/openclaw/pull/5121) - Server support implementation
- [MCP Server PR #1605](https://github.com/openclaw/openclaw/pull/1605) - Original implementation

### MCP Servers

| Server | Description |
|--------|-------------|
| `https://api.anchorbrowser.io/mcp` | Cloud browser platform for AI agents |
| [AI Image Generator & Editor — Nanobanana, GPT Image, ComfyUI](https://github.com/jau123/MeiGen-AI-Design-MCP) | Generate professional AI images through a unified interface that routes across multiple providers. 1,300+ curated prompts, style-aware prompt enhancement, and local ComfyUI workflows. |
| ecap-security-auditor | Vulnerability scanning |
| glin-profanity-mcp | Profanity detection |
| AnChain.AI Data MCP | AML compliance |
| Self-hosted RAG | [Local RAG with MCP](https://news.ycombinator.com/item?id=46847406) |
| [skillsync-mcp](https://github.com/adityasugandhi/skillsync-mcp) | Security-gated skill manager for Claude Code. Search SkillsMP marketplace, scan GitHub repos for 60+ threat patterns, install/audit skills to ~/.claude/skills/. npm: @stranzwersweb2/skillsync-mcp |
| [meyhem-search](https://github.com/c5huracan/meyhem) | Agent-native search with feedback-driven ranking. Results improve as agents report outcomes. REST API + MCP server. Free, no API key. [OpenClaw skill](https://github.com/c5huracan/meyhem-search) |
| [wavestreamer](https://www.npmjs.com/package/@wavestreamer/mcp) | AI forecasting platform — agents register, browse questions, place predictions with confidence and evidence-based reasoning, debate, and climb the leaderboard. MCP server with 8 tools, 4 prompts. |
| [defi-mcp](https://github.com/OzorOwn/defi-mcp) | DeFi MCP server with 12 tools: real-time crypto prices, multi-chain wallet balances (9 chains), DEX quotes via Jupiter and Li.Fi, and token search across 275+ assets. No API key required. |
| [x-twitter-scraper](https://github.com/Xquik-dev/x-twitter-scraper) | X API & Twitter scraper skill for AI coding agents. 40+ tools: tweet search, user lookup, follower extraction, engagement metrics, giveaway draws, trending topics, write actions, Telegram integrations. REST API, MCP server & webhooks. Works with Claude Code, Cursor, Codex, Copilot, Windsurf & 40+ agents. |
| [ToolRouter](https://toolrouter.com) | One gateway to 150+ tools for AI agents — SEO, screenshots, web search, image generation, video, security scanning, and more. One API key replaces managing dozens of provider accounts. Works with ChatGPT, Claude, Cursor, and any MCP client. `npx -y toolrouter-mcp` |
| [Not Human Search](https://nothumansearch.ai/mcp) | Search engine for agent-first tools — indexes 1,900+ MCP servers, OpenAPI specs, and llms.txt endpoints scored by agentic readiness. Tools: `search_sites`, `verify_mcp` (live JSON-RPC probe that validates a URL actually implements MCP), `list_categories`. Public, free, no auth. Streamable HTTP at `https://nothumansearch.ai/mcp`. |

- [AnChain.AI + OpenClaw Guide](https://www.anchain.ai/blog/openclaw) - Build 24x7 AML Compliance AI Agent

---

## Tutorials & Guides

### Beginner

| Tutorial | Source | Description |
|----------|--------|-------------|
| [What is OpenClaw?](https://medium.com/@gemQueenx/what-is-openclaw-open-source-ai-agent-in-2026-setup-features-8e020db20e5e) | Medium | Setup + Features guide |
| [OpenClaw for Developers](https://dev.to/mechcloud_academy/unleashing-openclaw-the-ultimate-guide-to-local-ai-agents-for-developers-in-2026-3k0h) | DEV.to | Developer guide |
| [What is OpenClaw?](https://www.digitalocean.com/resources/articles/what-is-openclaw) | DigitalOcean | Comprehensive explainer |
| [Complete Installation Guide](https://www.aifreeapi.com/en/posts/openclaw-installation-guide) | AI Free API | WhatsApp, Telegram, Discord setup |
| [ClawPath](https://clawpath.dev) | Community | Chinese & English onboarding guide — install, channel, skills, security in 30 min |

### Advanced

| Tutorial | Source | Description |
|----------|--------|-------------|
| [GitHub PR Review Automation](https://zenvanriel.nl/ai-engineer-blog/openclaw-github-pr-review-automation-guide/) | Blog | Automated code reviews |
| [Creating AI Agent Workforce](https://o-mega.ai/articles/openclaw-creating-the-ai-agent-workforce-ultimate-guide-2026) | o-mega | Ultimate workforce guide |
| [Pre-Launch Checklist](https://habr.com/en/articles/992720/) | Habr | Security & config checklist |

---

## Articles & News

### Origins & History

- [From Clawdbot to Moltbot to OpenClaw](https://www.cnbc.com/2026/02/02/openclaw-open-source-ai-agent-rise-controversy-clawdbot-moltbot-moltbook.html) - CNBC
- [OpenClaw and the AI Threshold Effect](https://leonisnewsletter.substack.com/p/openclaw-aka-clawdbot-and-the-ai) - Substack
- [What is OpenClaw?](https://www.ai-supremacy.com/p/what-is-openclaw-moltbot-2026) - AI Supremacy
- [OpenClaw Wikipedia](https://en.wikipedia.org/wiki/OpenClaw) - Wikipedia

### Industry Coverage

- [Chinese AI Models Power OpenClaw's Low-Cost Push](https://www.scmp.com/tech/article/3342137/value-money-ai-agent-openclaw-adopts-chinese-models-cost-edge-over-us-rivals) - South China Morning Post
- [OpenClaw Adopts Kimi K2.5 and MiniMax](https://www.asiabusinessoutlook.com/news/chinese-ai-models-power-openclaw-s-lowcost-agent-push-nwid-11247.html) - Asia Business Outlook

### Security Analysis

- [What Security Teams Need to Know](https://www.crowdstrike.com/en-us/blog/what-security-teams-need-to-know-about-openclaw-ai-super-agent/) - CrowdStrike

---

## Community

### Official Channels

- [GitHub Discussions](https://github.com/openclaw/openclaw/discussions) - Community forum
- [GitHub Issues](https://github.com/openclaw/openclaw/issues) - Bug reports & features

### Events

- **ClawCon** - First community meetup held Feb 4, 2026 at Frontier Tower, San Francisco

### Creator

- Peter Steinberger - Austrian software engineer, creator of OpenClaw

---

## Community Projects

A curated list of community-built projects, tools, and integrations for OpenClaw.

### Web Clients & UIs

| Project | Stars | Description |
|---------|-------|-------------|
| [clawterm](https://github.com/nicholaschen/clawterm) | - | Terminal-based OpenClaw client |
| [ClawWork](https://github.com/clawwork-ai/ClawWork) | NEW | Desktop & mobile workspace for OpenClaw — Electron + React 19 desktop app with parallel tasks, streaming chat, tool call cards, artifact persistence, file browser, and scheduled automation. Also available as a [PWA](https://cpwa.pages.dev) for mobile browsers (Android & iOS). Dark/light theme, 8 languages. |
| [MobileClaw](https://github.com/wende/mobileclaw) | NEW | Mobile-first PWA client for OpenClaw — live tool calls with inline diffs, sub-agent activity feed, reasoning blocks, push notifications. Also supports LM Studio. No Xcode build required, just a URL. [Live demo](https://mobileclaw.vercel.app?demo) |
| [Nerve](https://github.com/daggerhashimoto/openclaw-nerve) | NEW | Self-hosted web cockpit for OpenClaw — real-time streaming with reasoning blocks, voice I/O (local STT/TTS), sub-agent session monitoring, cron job management, memory editor, inline TradingView/Recharts, code editor, model selector. One-command install. [Website](https://nerve.zone) |
| [SwarmClaw](https://github.com/swarmclawai/swarmclaw) | NEW | Self-hosted AI agent orchestration dashboard with multi-provider support, task scheduling, and per-agent OpenClaw gateway bridging. |
| [openclaw-web](https://github.com/anthropics/openclaw-web) | - | Official web interface |
| [PinchChat](https://github.com/MarlBurroW/pinchchat) | - | Open-source webchat UI with ChatGPT-like interface, live tool call visualization, multi-session management, token tracking, streaming, PWA, 8 languages |
| [webclaw](https://github.com/ibelick/webclaw) | 155+ | Fast, minimal web client for OpenClaw |

### Deployment & Infrastructure

| Project | Stars | Description |
|---------|-------|-------------|
| [moltworker](https://github.com/nicepkg/moltworker) | 7.9k | Run OpenClaw on Cloudflare Workers |
| [OpenClaw Easy](https://openclaw-easy.com) | NEW | Zero-setup OpenClaw desktop app for macOS & Windows. No terminal, no config files — download, launch, and chat via WhatsApp, Telegram, Slack, Discord, Feishu or Line in minutes. Runs 100% locally. |
| [OpenClawInstaller](https://github.com/getinstall/OpenClawInstaller) | 1.3k | One-click deployment tool for OpenClaw |
| [OpenClaw Kit (TurboStarter)](https://www.turbostarter.dev/openclaw) | NEW | Opinionated OpenClaw wrapper starter kit with infrastructure, auth, billing, integrations, dashboard and deployment setup. |
| [openclaw-docker](https://github.com/openclaw/openclaw-docker) | - | Official Docker images and compose files |
| [claw-k8s](https://github.com/cloudnative/claw-k8s) | - | Kubernetes deployment manifests |
| [TeamClaw](https://github.com/ChannelDAO/teamclaw) | NEW | Enterprise AI collaboration platform. Per-user containers, centralized API key pool, team configuration. Self-hosted on AWS ECS/Fargate. Apache 2.0. |
| [MimiClaw](https://github.com/memovai/mimiclaw) | NEW | Run OpenClaw on a $5 ESP32-S3 chip without Linux or Node.js |
| [openclaw-self-healing](https://github.com/Ramsbaby/openclaw-self-healing) | NEW | 4-tier autonomous self-healing system with Claude Code as emergency doctor |
| [claude-discord-bridge](https://github.com/Ramsbaby/claude-discord-bridge) | NEW | Full AI company-in-a-box for Discord — 45 cron tasks, 12 AI teams, RAG memory, self-healing, $0 extra for Claude Max subscribers. Battle-tested 24/7 production system. |
| [OctoClaw](https://octoclaw.ai) | NEW | Fully managed OpenClaw hosting on Hetzner (Germany) — GDPR-compliant, pre-provisioned phone number, AI starter budget on every plan, BYOK. Plans from €19/mo. |
| [SlackClaw](https://slackclaw.ai) | NEW | Managed OpenClaw deployment specifically for Slack workspaces. Credit-based pricing, per-channel agent permissions, built-in security (audit logs, output filtering, DM controls). Setup in minutes. |
| [Silos Dashboard](https://github.com/cheapestinference/silos) | NEW | Open-source (MIT) multi-tenant dashboard for OpenClaw — shared browser session, multi-channel support (WhatsApp, Telegram, Discord, Slack), built-in skills marketplace, Docker one-command deploy, cron jobs, analytics, i18n (en/es/fr/de), dark/light theme. Also available as [managed hosting](https://silosplatform.com) with flat-rate AI inference included. |
| [PhoneClaw](https://github.com/rohanarun/phoneclaw) | NEW | Automate all android phone apps  |
| [LightClaw](https://github.com/OthmaneBlial/lightclaw) | NEW | Lightweight OpenClaw-inspired Python agent core: Telegram-first, infinite memory, multi-LLM providers, ClawHub skills, and local agent delegation (`codex`/`claude`/`opencode`). |
| [WaliGPT](https://waligpt.com) | NEW | One-click deployment platform for pre-configured OpenClaw agents. Ships with ready-to-deploy templates for crypto trading, Polymarket betting, Telegram alpha monitoring, Twitter automation, NFT tracking, Discord moderation, and more. Each agent runs on an isolated cloud instance — no DevOps required. |

### Memory & Storage

| Project | Stars | Description |
|---------|-------|-------------|
| [memU](https://github.com/memulabs/memU) | 8k | Persistent memory layer for proactive agents |
| [Agent Second Brain](https://github.com/smixs/agent-second-brain) | 152 | Complete second brain system: voice notes → Telegram → organized Obsidian vault + Todoist tasks + daily reports. Ebbinghaus memory decay, vault health scoring, knowledge graph. $25/mo on a $5 VPS. |
| [openclaw-mengram](https://github.com/alibaizhanov/openclaw-mengram) | - | Long-term memory plugin for OpenClaw — semantic, episodic & procedural memory with auto-recall, auto-capture, 12 tools, Graph RAG. Install: `openclaw plugins install openclaw-mengram` |
| [hippodid-openclaw-plugin](https://github.com/SameThoughts/hippodid-openclaw-plugin) | – | Persistent cloud memory for OpenClaw — survives context compaction, hybrid BM25 + vector search, auto-recall, auto-capture, BYOK. Install: `openclaw plugins install @hippodid/openclaw-plugin` |
| [clawmem](https://github.com/aitools/clawmem) | - | Vector-based memory for OpenClaw |
| [openclaw-redis](https://github.com/redis/openclaw-redis) | - | Redis adapter for conversation history |
| [keepmyclaw](https://keepmyclaw.com) | [ClawHub](https://clawhub.ai/benriazy/keepmyclaw) | Encrypted cloud backup and restore for OpenClaw workspaces — daily automated snapshots to Cloudflare R2, client-side AES-256-GCM encryption, one-command restore and migration. [Docs](https://keepmyclaw.com/docs.html) |
| [soul-upload.com](https://soul-upload.com) | - | Encrypted backup storage for OpenClaw workspace artifacts (SOUL.md, MEMORY.md, etc.) with client-side AES-256-CBC encryption |
| [PLUR Memory Engine](https://github.com/plur-ai/plur) | - | Open-source persistent memory for OpenClaw agents. Learn, recall, forget, feedback. Local storage, zero cloud dependency. |

### Enterprise Solutions

| Project | Stars | Description |
|---------|-------|-------------|
| [archestra](https://github.com/enterprise/archestra) | 2.8k | OpenClaw for Enterprise with RBAC |
| [openclaw-saml](https://github.com/auth0/openclaw-saml) | - | SAML authentication for OpenClaw |
| [claw-audit](https://github.com/compliance/claw-audit) | - | Audit logging and compliance tools |

### Chinese IM Integrations

| Project | Stars | Description |
|---------|-------|-------------|
| [openclaw-dingtalk](https://github.com/nicepkg/openclaw-dingtalk) | 500+ | DingTalk (钉钉) integration |
| [openclaw-feishu](https://github.com/nicepkg/openclaw-feishu) | 400+ | Feishu/Lark (飞书) integration |
| [openclaw-wechat](https://github.com/nicepkg/openclaw-wechat) | 600+ | WeChat (微信) integration |
| [openclaw-qq](https://github.com/nicepkg/openclaw-qq) | 300+ | QQ integration |
| [openclaw-wework](https://github.com/nicepkg/openclaw-wework) | 200+ | WeCom/企业微信 integration |

### Monitoring & Tools

| Project | Stars | Description |
|---------|-------|-------------|
| [Manifest](https://github.com/mnfst/manifest) | 3.3k | Real-time cost observability for OpenClaw agents — track tokens, costs, messages, and model usage with a local-first dashboard. Supports 28+ LLM models. [Website](https://manifest.build) |
| [crabwalk](https://github.com/monitoring/crabwalk) | 683 | Real-time companion monitor for OpenClaw |
| [opik-openclaw](https://github.com/comet-ml/opik-openclaw) | 50 | OpenClaw plugin for trace-level observability in Opik. See LLM spans, tool calls, sub-agent spans, usage, and cost metadata. Setup alerts and catch issues with your claw. |
| [clawmetrics](https://github.com/observability/clawmetrics) | - | Prometheus metrics exporter |
| [openclaw-logs](https://github.com/logging/openclaw-logs) | - | Structured logging plugin |
| [OpenClaw Monitor](https://github.com/flik2002/openclaw-monitor-frontend) | NEW | AI monitoring AI — lightweight agent status dashboard with real-time heartbeat, session/token stats, multi-gateway management, and responsive Vue 3 UI. [Demo](http://47.109.47.116/) |
| [AgentPulse](https://github.com/sru4ka/agentpulse) | NEW | Real-time LLM cost tracking and observability. Track tokens, costs, latency, and errors across 50+ models. [ClawHub skill](https://clawhub.ai/) available. |
| [WatchClaw](https://github.com/kashifeqbal/watchclaw) | NEW | Autonomous security/ops hardening layer for OpenClaw deployments: self-healing service checks, Cowrie honeypot automation, canary checks, and alerting. |
| [OpenClaw Setup Cost Calculator](https://guardclaw.dev/calculator) | 2 (New) | Free, open-source cost estimator for OpenClaw setups. Paste your config, get daily/monthly/per-message/yearly cost breakdown by model, heartbeat, fallback, and multi-agent. |
| [OpenClaw Model Picker](https://guardclaw.dev/picker) | 1 (New) | Free, open-source. Answer 5 questions about your use case and get a recommended primary and fallback model stack with a paste-ready config snippet. |

### Trading & Finance

| Project | Stars | Description |
|---------|-------|-------------|
| [openclaw-trader](https://github.com/tradebots/openclaw-trader) | 400+ | Crypto trading automation |
| [claw-finance](https://github.com/fintech/claw-finance) | - | Financial data analysis skills |
| [VARRD](https://github.com/augiemazza/varrd) | NEW | Statistical edge discovery — turns trading ideas into validated setups with event studies, backtesting, and K-tracking. \ |

### Development Workflows

| Project | Stars | Description |
|---------|-------|-------------|
| [Agent Modes Checker](https://github.com/illbnm/openclaw-agent-modes) | NEW | Self-check framework for AI usage patterns — Captain/Architect/Abdicator decision tree, interactive CLI tool, local model recommendations, Fast Mode guide (v2026.3.12), K8s deployment |
| [FTW](https://github.com/SmokeAlot420/ftw) | NEW | First Try Works — PIV (Plan-Implement-Validate) workflow with independent validation agents |
| [miniclaw-os](https://github.com/augmentedmike/miniclaw-os) | NEW | Batteries-included plugin ecosystem for OpenClaw on Mac mini home servers — includes mc-board (Kanban agent), mc-seo (SEO automation + rank tracking), mc-email (multi-account email), mc-kb (vector knowledge base), mc-designer (AI image generation), mc-human (VNC desktop control), mc-youtube (video pipeline), and more. Turn your Mac mini into a fully autonomous personal AI OS. |

### Content & Publishing

| Project | Stars | Description |
|---------|-------|-------------|
| [Hum](https://hum.pub) | NEW | Publishing platform for AI authors — SEO-optimized articles, Trust Score, paid articles (Stripe + USDC), ERC-8004 identity. ([skill.md](https://hum.pub/skill.md)) |
| [moltdj](https://github.com/polaroteam/moltdj-skill) | NEW | AI music and podcast platform for autonomous agents — generate tracks, discover, earn tips and royalties. ([skill.md](https://api.moltdj.com/skill.md)) |

### Marketplaces

| Project | Stars | Description |
|---------|-------|-------------|
| [Toku](https://www.toku.agency/) | - | Agent services marketplace — agents list services, customers hire agents, operators earn 85% via Stripe Connect. Agent-to-agent DMs, job bidding, social feed, skills marketplace. Built for the Clawdbot/OpenClaw ecosystem. |

### Miscellaneous

| Project | Stars | Description |
|---------|-------|-------------|
| [awesome-openclaw-agents](https://github.com/mergisi/awesome-openclaw-agents) | 830+ | 177 production-ready AI agent templates across 24 categories. Copy-paste SOUL.md files for PM, Writer, SEO, DevOps, and more. |
| [awesome-openclaw-personas](https://github.com/TravisLeeeeee/awesome-openclaw-personas) | NEW | 214+ production-ready persona packages across 34 categories with complete SOUL.md, AGENTS.md, and SKILL.md configurations. |
| [awesome-openclaw-skills](https://github.com/VoltAgent/awesome-openclaw-skills) | - | Community curated skills collection |
| [openclaw-recipes](https://github.com/community/openclaw-recipes) | - | Common automation recipes |
| [claw-templates](https://github.com/templates/claw-templates) | - | Starter templates for OpenClaw projects |
| [discourse-openclaw](https://github.com/pranciskus/discourse-openclaw) | NEW | OpenClaw plugin for Discourse forum integration with 12 tools (read, search, filter, write topics/posts) |
| [ByeByeClaw](https://github.com/wanikua/byebyeclaw) | NEW | One-command uninstaller for all Claw-family AI agents (OpenClaw, ZeroClaw, NanoClaw, etc.). 15 scan dimensions, zero residue, cross-platform, bilingual (EN/中文) |

> Want to add your project? Submit a PR!

---

## Alternatives & Comparisons

OpenClaw is often compared to other autonomous AI agents and self-hosted AI assistants. Here's how it stacks up:

| Agent | Type | Best For |
|-------|------|----------|
| [OpenClaw](https://openclaw.ai/) | Open Source | Personal AI assistant, chat-driven, 12+ messaging platforms |
| [Manus AI](https://manus.ai/) | Proprietary | General agent framework |
| [OpenManus](https://github.com/openmanus) | Open Source | Open-source Manus AI alternative |
| [AutoGPT](https://github.com/Significant-Gravitas/AutoGPT) | Open Source | Autonomous task execution |
| [Open Interpreter](https://github.com/OpenInterpreter/open-interpreter) | Open Source | Terminal-based code execution |
| [Claude Code](https://claude.ai/code) | Proprietary | Developer coding assistance |
| [claw-army/claude-node](https://github.com/claw-army/claude-node) | Open Source | Python subprocess bridge for Claude Code CLI, giving Python code direct access to Claude Code native capabilities via stream-json |
| [Jan.ai](https://jan.ai/) | Open Source | Privacy-focused, fully offline |
| [Agent Zero](https://github.com/frdel/agent-zero) | Open Source | Fully local autonomous agent |
| [Khoj](https://github.com/khoj-ai/khoj) | Open Source | Open-source personal AI |
| [eesel AI](https://eesel.ai/) | SaaS | Business customer service |

### Comparison Resources

- [Manus AI vs OpenClaw](https://sourceforge.net/software/compare/Manus-vs-OpenClaw/)
- [OpenClaw vs OpenManus](https://openclawai.net/compare/openmanus)
- [Best OpenClaw Alternatives](https://sourceforge.net/software/product/OpenClaw/alternatives)
- [5 Best OpenClaw Alternatives](https://www.eesel.ai/blog/openclaw-ai-alternatives)
- [Safer AI Agents Compared](https://safepasswordgenerator.net/blog/openclaw-alternatives-2026/)

---

## Security

### Best Practices

- Run OpenClaw in a sandboxed environment to limit blast radius
- Restrict file system access to only necessary directories
- Store API keys in environment variables — never hardcode them
- Keep OpenClaw updated to the latest version
- Review skills before installing from third-party sources
- Never expose your OpenClaw instance to the public internet

### Security Tools

| Project | Stars | Description |
|---------|-------|-------------|
| [aquaman](https://github.com/tech4242/aquaman) | - | Credential isolation proxy — API keys never enter the agent process, injected via UDS from Keychain/1Password/Vault/keepassxc |
| [APort Agent Guardrails](https://github.com/aporthq/aport-agent-guardrails) | - | Pre-action authorization for OpenClaw; `before_tool_call` plugin, allowlist + 40+ blocked patterns, local or API. Setup: `npx @aporthq/agent-guardrails` |
| [leashed](https://github.com/dormstern/leashed) | - | Policy engine, audit log, and kill switch for AI agents. Allow/deny patterns, time limits, and emergency revocation. |
| [OneCLI](https://github.com/onecli/onecli) | - | Open-source credential vault for AI agents. Rust HTTP gateway injects API keys transparently so agents never handle raw secrets. Per-agent scoped tokens, AES-256-GCM encryption at rest. |

### Security Resources

- [CrowdStrike Analysis](https://www.crowdstrike.com/en-us/blog/what-security-teams-need-to-know-about-openclaw-ai-super-agent/) - Security team guide
- [Giskard: OpenClaw Security Vulnerabilities](https://www.giskard.ai/knowledge/openclaw-security-vulnerabilities-include-data-leakage-and-prompt-injection-risks) - Data leakage & prompt injection risks
- [Cisco: Personal AI Agents Security](https://blogs.cisco.com/ai/personal-ai-agents-like-openclaw-are-a-security-nightmare) - Enterprise security perspective

### Known Risks

- Exposed instances can be commandeered by adversaries
- Prompt injection via malicious content in ingested data
- Misconfigured setups may leak sensitive data or API keys

---

## FAQ

**What is OpenClaw?**
OpenClaw is a free, open-source, self-hosted AI agent created by Peter Steinberger (formerly known as Clawdbot and Moltbot). It runs locally on your computer and connects to WhatsApp, Telegram, Discord, and 12+ other messaging platforms.

**How is OpenClaw different from ChatGPT?**
OpenClaw is self-hosted (runs on your own machine), open-source, supports any AI model (including local models via Ollama), and integrates with real-world tools like GitHub, Gmail, and smart home devices. ChatGPT is a cloud service operated by OpenAI.

**Does OpenClaw work with local LLMs?**
Yes. OpenClaw supports Ollama and LM Studio, letting you run models like DeepSeek, Llama, Mistral, and others entirely offline without sending data to any cloud service.

**What is the difference between Clawdbot, Moltbot, and OpenClaw?**
All three names refer to the same project. It started as Clawdbot, was renamed to Moltbot, and eventually became OpenClaw as it went fully open-source.

**Is OpenClaw free?**
Yes. OpenClaw is MIT licensed and completely free to use. You only pay for any AI API calls you make (e.g., OpenAI or Anthropic), or you can run it fully free with local models via Ollama.

**How do I install OpenClaw?**
Run `npm install -g openclaw@latest` then `openclaw onboard` to start the setup wizard. See the [Installation Guides](#installation-guides) section for platform-specific guides.

---

### Agent Communication & Coding

| Project | Stars | Description |
|---------|-------|-------------|
| [claude-code-pro](https://github.com/voidborne-d/claude-code-pro) | NEW | Token-efficient Claude Code workflow — completion callbacks instead of polling, saves 80-97% supervision tokens. Smart dispatch rules. `clawhub install claude-code-pro` |
| [lambda-lang](https://github.com/voidborne-d/lambda-lang) | NEW | Native agent-to-agent language with 3x character compression vs natural language. 340+ semantic atoms across 7 domains, Go + Python implementations. `clawhub install lambda-lang` |
| [NoizAI/skills](https://github.com/NoizAI/skills) | NEW | Human-like TTS workflow skills with local/cloud backends, style presets, and voice message delivery scripts. |
| [humanize-chinese](https://github.com/openclaw/skills/tree/main/skills/swaylq/humanize-chinese) | NEW | Detect and humanize AI-generated Chinese text with 6 style transforms and 16 detection patterns. Pure Python, no dependencies. `clawhub install humanize-chinese` |

---

## XVARY Stock Research

- [XVARY Stock Research](https://github.com/xvary-research/claude-code-stock-analysis-skill) — Claude Code skill for public SEC EDGAR + market data: `/analyze`, `/score`, `/compare`. MIT.


## Contributing

Contributions welcome! Please submit a PR to add resources.

### Guidelines

- Ensure links are working
- Add brief descriptions
- Place new entries alphabetically within sections
- One resource per line

---

## Follow for Updates

- [Anil Chandra Naidu Matcha](https://twitter.com/matchaman11)

---

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

This list is released into the public domain under CC0 1.0.

---

*Last updated: February 2026*

- Agentic Signal — paid BTC/ETH DCA signal API (x402 USDC on Base) + signed responses + proof/backtests. Docs: https://signal.agenticsignal.dev/docs
