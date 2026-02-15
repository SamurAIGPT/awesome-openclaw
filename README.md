# Awesome OpenClaw [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated collection of resources, tools, skills, tutorials, and articles for **OpenClaw** — the open-source AI agent that's taking the world by storm.

OpenClaw (formerly Moltbot, originally Clawdbot) is a free and open-source autonomous AI agent created by Peter Steinberger. It runs locally, connects to 50+ integrations, and lets you chat with AI through WhatsApp, Telegram, Discord, and more.

[![GitHub stars](https://img.shields.io/github/stars/openclaw/openclaw?style=social)](https://github.com/openclaw/openclaw)

<img width="1536" height="1024" alt="oc" src="https://github.com/user-attachments/assets/dc60b4c4-18f4-4ebd-a5b9-8294d2e924ab" />

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
- [Ruleskill](https://ruleskill.com) - We want to verify your code for the RuleSkill Protocol. Claim your badge.

---

## Official Resources

- [OpenClaw Website](https://openclaw.ai/) - Official homepage
- [OpenClaw GitHub](https://github.com/openclaw/openclaw) - Main repository (150k+ stars)
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
# Install via npm
npm install -g openclaw@latest

# Or via pnpm
pnpm add -g openclaw@latest

# Run onboarding wizard
openclaw onboard --install-daemon
```

### First Steps

1. Run `openclaw onboard` to start the setup wizard
2. Choose your AI provider (Anthropic Claude, OpenAI, or local via Ollama)
3. Connect a messaging platform (Telegram, WhatsApp, Discord, etc.)
4. Start chatting with your personal AI assistant!

### Dashboard

Access the web dashboard at `http://localhost:18789/` to chat and manage your agent.

---

## Installation Guides

| Guide | Platform | Description |
|-------|----------|-------------|
| [Official Getting Started](https://docs.openclaw.ai/start/getting-started) | All | Official setup guide |
| [Codecademy Tutorial](https://www.codecademy.com/article/open-claw-tutorial-installation-to-first-chat-setup) | All | Installation to first chat |
| [Hostinger Guide](https://www.hostinger.com/tutorials/how-to-set-up-openclaw) | VPS | Private server setup |
| [DigitalOcean One-Click](https://www.digitalocean.com/community/tutorials/how-to-run-openclaw) | Cloud | One-click deployment |
| [LMStudio Setup](https://nwosunneoma.medium.com/how-to-setup-openclaw-with-lmstudio-1960a8046f6b) | Local | Run with local models |
| [Docker Setup](https://habr.com/en/articles/992720/) | Docker | Container deployment |
| [Afternoon Setup Guide](https://amankhan1.substack.com/p/how-to-get-clawdbotmoltbotopenclaw) | All | Quick setup walkthrough |

---

## Skills & Plugins

### Skill Registries

- [ClawHub](https://clawhub.ai/) - Official skill store (700+ skills)
- [AgentFund](https://github.com/RioTheGreat-ai/agentfund-skill) - Crowdfunding platform for AI agents (milestone-based escrow on Base)
- [ClawdTalk](https://github.com/team-telnyx/clawdtalk-client) - Phone calling and SMS for OpenClaw. Call your AI agent from any phone with deep tool integration for calendar, Jira, web search, and more. Powered by Telnyx.
- [awesome-openclaw-skills](https://github.com/VoltAgent/awesome-openclaw-skills) - Community curated collection
- [openclaw/skills](https://github.com/openclaw/skills) - Official skills repository
- [openclaw/clawhub](https://github.com/openclaw/clawhub) - Skill directory source
- [Skills.sh](https://skills.sh/openclaw/openclaw) - Skill discovery platform

### Popular Skill Categories

| Category | Description |
|----------|-------------|
| Productivity | Calendar, email, task management |
| Development | GitHub, code review, deployments |
| Smart Home | Hue, HomeKit, IoT control |
| Communication | Email drafting, message scheduling |
| Research | Web browsing, PDF summarization |
| Entertainment | Spotify, media control |

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

- [Full Extension Ecosystem Guide](https://help.apiyi.com/en/openclaw-extensions-ecosystem-guide-en.html)

---

## MCP Support

OpenClaw supports the Model Context Protocol (MCP) for extended capabilities.

### MCP Resources

- [MCP Adapter Plugin](https://github.com/androidStern-personal/openclaw-mcp-adapter) - Expose MCP tools as native agent tools
- [Native MCP Support Issue](https://github.com/openclaw/openclaw/issues/4834) - Feature discussion
- [MCP Server PR #5121](https://github.com/openclaw/openclaw/pull/5121) - Server support implementation
- [MCP Server PR #1605](https://github.com/openclaw/openclaw/pull/1605) - Original implementation

### MCP Servers

| Server | Description |
|--------|-------------|
| ecap-security-auditor | Vulnerability scanning |
| glin-profanity-mcp | Profanity detection |
| AnChain.AI Data MCP | AML compliance |
| Self-hosted RAG | [Local RAG with MCP](https://news.ycombinator.com/item?id=46847406) |

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
| [webclaw](https://github.com/ibelick/webclaw) | 155+ | Fast, minimal web client for OpenClaw |
| [openclaw-web](https://github.com/anthropics/openclaw-web) | - | Official web interface |
| [clawterm](https://github.com/nicholaschen/clawterm) | - | Terminal-based OpenClaw client |
| [PinchChat](https://github.com/MarlBurroW/pinchchat) | - | Open-source webchat UI with ChatGPT-like interface, live tool call visualization, multi-session management, token tracking, streaming, PWA, 8 languages |

### Deployment & Infrastructure

| Project | Stars | Description |
|---------|-------|-------------|
| [moltworker](https://github.com/nicepkg/moltworker) | 7.9k | Run OpenClaw on Cloudflare Workers |
| [OpenClawInstaller](https://github.com/getinstall/OpenClawInstaller) | 1.3k | One-click deployment tool for OpenClaw |
| [openclaw-docker](https://github.com/openclaw/openclaw-docker) | - | Official Docker images and compose files |
| [claw-k8s](https://github.com/cloudnative/claw-k8s) | - | Kubernetes deployment manifests |
| [MimiClaw](https://github.com/memovai/mimiclaw) | NEW | Run OpenClaw on a $5 ESP32-S3 chip without Linux or Node.js |
| [openclaw-self-healing](https://github.com/Ramsbaby/openclaw-self-healing) | NEW | 4-tier autonomous self-healing system with Claude Code as emergency doctor |
| [PhoneClaw](https://github.com/rohanarun/phoneclaw) | NEW | Automate all android phone apps  |

### Memory & Storage

| Project | Stars | Description |
|---------|-------|-------------|
| [memU](https://github.com/memulabs/memU) | 8k | Persistent memory layer for proactive agents |
| [clawmem](https://github.com/aitools/clawmem) | - | Vector-based memory for OpenClaw |
| [openclaw-redis](https://github.com/redis/openclaw-redis) | - | Redis adapter for conversation history |

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
| [crabwalk](https://github.com/monitoring/crabwalk) | 683 | Real-time companion monitor for OpenClaw |
| [clawmetrics](https://github.com/observability/clawmetrics) | - | Prometheus metrics exporter |
| [openclaw-logs](https://github.com/logging/openclaw-logs) | - | Structured logging plugin |

### Trading & Finance

| Project | Stars | Description |
|---------|-------|-------------|
| [openclaw-trader](https://github.com/tradebots/openclaw-trader) | 400+ | Crypto trading automation |
| [claw-finance](https://github.com/fintech/claw-finance) | - | Financial data analysis skills |

### Development Workflows

| Project | Stars | Description |
|---------|-------|-------------|
| [FTW](https://github.com/SmokeAlot420/ftw) | NEW | First Try Works — PIV (Plan-Implement-Validate) workflow with independent validation agents |

### Miscellaneous

| Project | Stars | Description |
|---------|-------|-------------|
| [awesome-openclaw-skills](https://github.com/VoltAgent/awesome-openclaw-skills) | - | Community curated skills collection |
| [openclaw-recipes](https://github.com/community/openclaw-recipes) | - | Common automation recipes |
| [claw-templates](https://github.com/templates/claw-templates) | - | Starter templates for OpenClaw projects |

> Want to add your project? Submit a PR!

---

## Alternatives & Comparisons

| Agent | Type | Best For |
|-------|------|----------|
| [OpenClaw](https://openclaw.ai/) | Open Source | Personal AI assistant, chat-driven |
| [Manus AI](https://manus.ai/) | Proprietary | General agent framework |
| [OpenManus](https://github.com/openmanus) | Open Source | Manus alternative |
| [Claude Code](https://claude.ai/code) | Proprietary | Developer coding assistance |
| [Jan.ai](https://jan.ai/) | Open Source | Privacy-focused, offline |
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

- Run OpenClaw in a sandboxed environment
- Limit file system access to necessary directories
- Use environment variables for API keys
- Regularly update to the latest version
- Review skills before installing
- Don't expose instances to the public internet

### Security Tools

| Project | Stars | Description |
|---------|-------|-------------|
| [aquaman](https://github.com/tech4242/aquaman) | - | Credential isolation proxy — API keys never enter the agent process, injected via UDS from Keychain/1Password/Vault/keepassxc |

### Security Resources

- [CrowdStrike Analysis](https://www.crowdstrike.com/en-us/blog/what-security-teams-need-to-know-about-openclaw-ai-super-agent/) - Security team guide

### Known Risks

- Exposed instances can be commandeered by adversaries
- Malicious instructions can be embedded in ingested data
- Misconfigured setups may leak sensitive data

---

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
