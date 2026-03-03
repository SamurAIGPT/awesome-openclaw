<p align="center">
  <a href="https://github.com/openclaw/openclaw">
    <picture>
      <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/openclaw/openclaw/main/docs/assets/openclaw-logo-text-dark.png">
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/openclaw/openclaw/main/docs/assets/openclaw-logo-text.png">
      <img alt="OpenClaw" src="https://raw.githubusercontent.com/openclaw/openclaw/main/docs/assets/openclaw-logo-text.png" width="600">
    </picture>
  </a>
</p>

<h1 align="center">Awesome OpenClaw</h1>

<p align="center">
  <a href="https://github.com/openclaw/openclaw/stargazers"><img src="https://img.shields.io/github/stars/openclaw/openclaw?style=flat&logo=github&label=Stars&color=gold" alt="Stars"></a>
  <a href="https://github.com/openclaw/openclaw/network/members"><img src="https://img.shields.io/github/forks/openclaw/openclaw?style=flat&label=Forks&color=silver" alt="Forks"></a>
  <a href="https://github.com/openclaw/openclaw/graphs/contributors"><img src="https://img.shields.io/github/contributors/openclaw/openclaw?label=Contributors&color=green" alt="Contributors"></a>
  <a href="https://github.com/openclaw/openclaw/commits"><img src="https://img.shields.io/github/commit-activity/t/openclaw/openclaw?style=flat&label=Commits&color=blue" alt="Commits"></a>
  <br>
  <a href="https://awesome.re"><img src="https://awesome.re/badge.svg" alt="Awesome"></a>
  <a href="https://github.com/openclaw/openclaw/blob/main/LICENSE"><img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="License"></a>
  <a href="https://github.com/openclaw/openclaw/releases"><img src="https://img.shields.io/github/v/release/openclaw/openclaw?include_prereleases&label=Release&color=orange" alt="Release"></a>
  <a href="https://discord.gg/openclaw"><img src="https://img.shields.io/discord/1456350064065904867?label=Discord&logo=discord&logoColor=white&color=5865F2" alt="Discord"></a>
  <br>
  <em>Fastest-growing GitHub repo ever — 9K to 195K stars in 66 days (18x faster than Kubernetes)</em>
</p>

<p align="center">
  The most comprehensive, curated collection of OpenClaw resources, hosting guides, cost comparisons, security hardening, skills, tutorials, and community links.
</p>

---

**OpenClaw** (formerly Clawdbot → Moltbot) is a free, open-source autonomous AI agent created by **Peter Steinberger** ([@steipete](https://github.com/steipete)). It runs on your own hardware, connects to 10+ messaging platforms (WhatsApp, Telegram, Slack, Discord, Signal, iMessage, Google Chat, Microsoft Teams, Matrix, Zalo), and orchestrates AI agent workflows with persistent memory and 24/7 operation.

---

## Table of Contents

- [What is OpenClaw?](#what-is-openclaw)
- [Name History](#name-history)
- [System Requirements](#system-requirements)
- [Quick Start (1 Minute)](#quick-start-1-minute)
- [Setup Methods (1-10 Minutes)](#setup-methods-1-10-minutes)
- [Hosting Providers Comparison](#hosting-providers-comparison)
  - [Free Tier ($0/month)](#free-tier-0month)
  - [Budget VPS ($2-8/month)](#budget-vps-2-8month)
  - [Mid-Range ($5-25/month)](#mid-range-5-25month)
  - [Serverless & PaaS](#serverless--paas)
  - [Managed Hosting Services](#managed-hosting-services)
  - [Setup-as-a-Service (Freelancers)](#setup-as-a-service-freelancers)
  - [Local Hardware](#local-hardware)
- [Master Cost Comparison Table](#master-cost-comparison-table)
- [AI Model API Costs](#ai-model-api-costs)
- [Total Real-World Cost Examples](#total-real-world-cost-examples)
- [Cloudflare Workers (Moltworker) Deep Dive](#cloudflare-workers-moltworker-deep-dive)
- [DigitalOcean 1-Click Deploy](#digitalocean-1-click-deploy)
- [Hetzner Setup Guide](#hetzner-setup-guide)
- [Hostinger VPS Setup](#hostinger-vps-setup)
- [Oracle Cloud Free Tier Setup](#oracle-cloud-free-tier-setup)
- [Raspberry Pi Setup](#raspberry-pi-setup)
- [ESP32 Embedded (MimiClaw)](#esp32-embedded-mimiclaw)
- [Docker Deployment](#docker-deployment)
- [Security & Hardening](#security--hardening)
- [Configuration](#configuration)
  - [Model Providers](#model-providers)
  - [Messaging Channels](#messaging-channels)
  - [Local LLM Integration](#local-llm-integration)
  - [MCP Server Integration](#mcp-server-integration)
- [Integrations & Features](#integrations--features)
  - [Voice Assistant](#voice-assistant)
  - [Home Automation](#home-automation)
  - [Email & Calendar](#email--calendar)
  - [Google Workspace](#google-workspace)
  - [Webhooks & Cron Jobs](#webhooks--cron-jobs)
  - [Live Canvas](#live-canvas)
  - [Multi-Agent Setup](#multi-agent-setup)
  - [Companion Apps](#companion-apps)
  - [Monitoring & Dashboards](#monitoring--dashboards)
  - [Backup & Restore](#backup--restore)
- [Performance Benchmarks](#performance-benchmarks)
- [OpenClaw vs Claude Code](#openclaw-vs-claude-code)
- [Alternatives & Competitors](#alternatives--competitors)
- [Moltbook (AI Social Network)](#moltbook-ai-social-network)
- [Skills & Plugins](#skills--plugins)
- [Browser Automation](#browser-automation)
- [Real-World Use Cases](#real-world-use-cases)
- [Tutorials & Guides](#tutorials--guides)
- [Video Tutorials](#video-tutorials)
- [Community](#community)
- [Media Coverage](#media-coverage)
- [Common Issues & Troubleshooting](#common-issues--troubleshooting)
- [Cost Calculator & Optimization](#cost-calculator--optimization)
- [Key Contributors](#key-contributors)
- [Related Repositories](#related-repositories)
- [Kubernetes & Helm Charts](#kubernetes--helm-charts)
- [PicoClaw (RISC-V / Ultra-Lightweight)](#picoclaw-risc-v--ultra-lightweight)
- [Courses & Learning Platforms](#courses--learning-platforms)
- [Enterprise Considerations](#enterprise-considerations)
- [China & Global Adoption](#china--global-adoption)
- [Latest Releases](#latest-releases)

---

## What is OpenClaw?

OpenClaw is an **agentic AI interface** that:

- Runs **locally on your own hardware** (Mac Mini, VPS, Raspberry Pi, ESP32-S3, or serverless)
- Connects to **10+ messaging platforms** simultaneously
- Has **persistent memory** across sessions (saves files, breadcrumbs, chat histories)
- Handles **tasks spanning hours or days** without losing context
- Operates **24/7 autonomously** focusing on automation and integration
- Supports **5,700+ community-built skills** via ClawHub
- Works with **multiple AI providers** (Anthropic, OpenAI, Google, OpenRouter, DeepSeek, local LLMs)
- Features **voice assistant**, **browser automation**, **home automation**, and **cron scheduling**

### Core Architecture (6 Layers)

| Layer | Purpose |
|-------|---------|
| **Gateway** | Central control plane — message routing, sessions, plugins, tool execution policy |
| **Channels** | Adapters normalizing Telegram/WhatsApp/Discord/iMessage into standard message shapes |
| **Routing + Sessions** | Determines which agent handles specific conversations |
| **Agent Runtime** | Processes context, calls model providers, streams responses, requests tools |
| **Tools** | Capabilities — web fetch, browser control, command execution, device pairing |
| **Surfaces** | Interaction points — chat apps, web dashboard, macOS menu bar, Live Canvas |

---

## Name History

| Date | Name | Reason |
|------|------|--------|
| Nov 2025 | **Clawdbot** | Original name at launch |
| Jan 27, 2026 | **Moltbot** | Anthropic trademark complaint (similarity to "Claude") |
| Jan 30, 2026 | **OpenClaw** | Final rebrand, community vote |

> When the team dropped the @clawdbot Twitter handle to transition to @moltbot, professional "handle snipers" immediately grabbed it. Scammers used the hijacked account to launch a fake CLAWD token on Solana.

---

## System Requirements

### Minimum

| Component | Requirement |
|-----------|-------------|
| **OS** | macOS 11+ / Ubuntu 22.04+ / Windows (WSL2) |
| **Runtime** | Node.js 22+ |
| **RAM** | 2 GB (may crash during onboarding) |
| **CPU** | 2 cores |
| **Storage** | 10 GB SSD |
| **Network** | Stable internet connection |

### Recommended

| Component | Requirement |
|-----------|-------------|
| **RAM** | 4-8 GB (cloud models) / 16-24 GB (local LLMs) |
| **CPU** | 2-4 cores |
| **Storage** | 30-50 GB SSD |
| **GPU** | 12-24 GB VRAM (for local model inference) |

---

## Quick Start (1 Minute)

```bash
npm install -g openclaw@latest
openclaw onboard --install-daemon
openclaw gateway --port 18789 --verbose
```

That's it. The wizard walks you through API key setup, channel configuration, and security settings.

---

## Setup Methods (1-10 Minutes)

| Method | Time | Difficulty | Best For |
|--------|------|------------|----------|
| **[Agent37](https://www.agent37.com/openclaw)** | 30 sec | Easy | Cheapest managed ($0.99/mo) |
| **[SimpleClaw](https://www.simpleclaw.com/)** | 1 min | Easy | Non-technical users |
| **[npm install](https://docs.openclaw.ai/quickstart)** | 1 min | Easy | Developers with Node.js |
| **[DigitalOcean 1-Click](https://marketplace.digitalocean.com/apps/openclaw)** | 2 min | Easy | Quick cloud deploy |
| **[Railway Template](https://railway.com/deploy/openclaw)** | 2 min | Easy | PaaS users |
| **[Zeabur](https://zeabur.com/templates/VTZ4FX)** | 1 min | Easy | Docker auto-deploy |
| **[Docker](https://docs.openclaw.ai/docker)** | 5 min | Medium | Isolation & reproducibility |
| **[Cloudflare Workers](https://docs.openclaw.ai/cloudflare)** | 5 min | Medium | Serverless enthusiasts |
| **[xCloud Managed](https://xcloud.host/openclaw-hosting)** | 5 min | None | Full managed hosting |
| **[Kimi Claw](https://kimi.com/bot)** | Instant | None | Browser-native OpenClaw in kimi.com, 5K+ skills, 40 GB storage |
| **[Molty by Finna](https://molty.finna.ai)** | 30 sec | None | Multiple Molties, Mission Control, GitHub sync |
| **[Manual VPS](https://docs.openclaw.ai/vps)** | 10 min | Medium | Full control |
| **[Raspberry Pi](https://docs.openclaw.ai/raspberry-pi)** | 10 min | Medium | Low-power, always-on |
| **[ESP32-S3 (MimiClaw)](https://github.com/memovai/mimiclaw)** | 10 min | Medium | Cheapest hardware ($5), pure C, no OS |
| **[PicoClaw (RISC-V)](https://github.com/sipeed/picoclaw)** | 5 min | Easy | Single Go binary, 10 MB RAM, $10 RISC-V board |
| **[ZeroClaw (Rust)](https://github.com/theonlyhennygod/zeroclaw)** | 2 min | Easy | 3.4 MB binary, <10ms startup, 22+ providers |
| **[TinyClaw (Shell)](https://github.com/jlia0/tinyclaw)** | 5 min | Easy | 400 LoC, Claude Code + tmux, self-healing |
| **[Autobot (Crystal)](https://github.com/crystal-autobot/autobot)** | 2 min | Easy | 2MB binary, ~5MB RAM, <10ms startup |

### Method 1: Official Installer Script

```bash
curl -fsSL https://openclaw.ai/install.sh | bash
openclaw onboard --install-daemon
```

### Method 2: npm / pnpm

```bash
npm install -g openclaw@latest
# or
pnpm add -g openclaw@latest
```

### Method 3: Docker

```bash
git clone https://github.com/openclaw/openclaw.git
cd openclaw
./docker-setup.sh
```

### Method 4: One-Click Cloud Deploys

| Platform | Link | Notes |
|----------|------|-------|
| **DigitalOcean** | [1-Click Deploy](https://marketplace.digitalocean.com/apps/openclaw) | Security-hardened, pre-configured |
| **Railway** | [Template](https://railway.com/deploy/openclaw) | Web-based /setup wizard |
| **Render** | [render.yaml](https://docs.openclaw.ai/render) | Infrastructure as Code |
| **SimpleClaw** | [simpleclaw.com](https://www.simpleclaw.com/) | Deploy in under 1 minute |
| **Zeabur** | [Template](https://zeabur.com/templates/VTZ4FX) | One-click Docker deploy |
| **Northflank** | [Stack](https://northflank.com/stacks/deploy-openclaw) | No server-side terminal needed |
| **Lightning.AI** | [Environment](https://lightning.ai/lightning-ai/environments/openclaw) | Browser-based, no local hardware |
| **Coolify** | [Template](https://github.com/essamamdani/openclaw-coolify) | Self-hosted PaaS template |
| **Elestio** | [Open Source](https://elest.io/open-source/openclaw) | Fully managed in < 3 min |

---

## Hosting Providers Comparison

### Free Tier ($0/month)

| Provider | Free Resources | Limits | Permanent? | Setup Time | Best For |
|----------|---------------|--------|------------|------------|----------|
| **[Oracle Cloud](https://www.oracle.com/cloud/free/)** | 4 ARM CPUs, 24 GB RAM, 200 GB storage, 10 TB/mo | ARM architecture only | Yes (forever) | ~3 hours | Power users wanting $0 hosting |
| **[AMD Developer Cloud](https://www.amd.com/en/developer/resources/cloud-access.html)** | MI300X GPU (192 GB memory), $100 credits | ~50 hours compute | No (credits) | 30 min | GPU-accelerated local LLMs |
| **[Google Cloud Run](https://cloud.google.com/run)** | 180K vCPU-sec, 360K GiB-sec, 2M requests/mo | Cold starts, stateless | Yes | 30 min | Serverless testing |
| **[Azure Container Apps](https://azure.microsoft.com/en-us/products/container-apps)** | 180K vCPU-sec, 360K GiB-sec, 2M requests/mo | Cold starts | Yes | 30 min | Enterprise users |
| **[Render](https://render.com/)** | Web service (spins down after 15 min) | Slow wake-up (~60s) | Yes | 5 min | Testing only |
| **[AWS Free Tier](https://aws.amazon.com/free/)** | t2.micro (1 vCPU, 1 GB RAM) | 12 months only | No (12 mo) | 15 min | AWS-familiar users |
| **[Railway](https://railway.com/deploy/openclaw)** | $5 one-time credit | 30 days trial | No | 2 min | Quick testing |

### Budget VPS ($2-8/month)

| Provider | Plan | Price/mo | vCPU | RAM | Storage | Bandwidth | Region |
|----------|------|----------|------|-----|---------|-----------|--------|
| **[LumaDock](https://lumadock.com/)** | Basic | $1.99 | 1 | 1 GB | 20 GB SSD | 1 TB | US/EU |
| **[Vultr](https://www.vultr.com/)** | Regular Cloud | $2.50 | 1 | 512 MB | 10 GB | 0.5 TB | 32 locations |
| **[Vultr](https://www.vultr.com/)** | Standard | $3.50 | 1 | 1 GB | 25 GB NVMe | 1 TB | 32 locations |
| **[Hetzner](https://www.hetzner.com/cloud/)** | CX22 | €3.79 (~$4.15) | 2 | 4 GB | 40 GB SSD | 20 TB | EU (DE/FI) |
| **[Alibaba Cloud](https://www.alibabacloud.com/en/campaign/ai-openclaw)** | Simple App Server | $4 | 1 | 1 GB | Varies | Varies | 19 regions |
| **[Contabo](https://contabo.com/en/openclaw-hosting/)** | Cloud VPS S | $4.95 | 4 | 8 GB | 50 GB SSD | Unlimited | US/EU/Asia |
| **[Hostinger](https://www.hostinger.com/uk/vps/docker/openclaw)** | KVM 1 | $4.99 | 1 | 4 GB | 50 GB NVMe | 4 TB | Global |
| **[Linode](https://www.linode.com/)** | Shared 1GB | $5 | 1 | 1 GB | 25 GB | 1 TB | Global |
| **[Vultr](https://www.vultr.com/)** | High-Performance | $6 | 1 | 1 GB | 25 GB NVMe | 2 TB | 32 locations |
| **[DigitalOcean](https://marketplace.digitalocean.com/apps/openclaw)** | Basic Droplet | $6 | 1 | 1 GB | 25 GB | 1 TB | Global |
| **[Hetzner](https://www.hetzner.com/cloud/)** | CX32 | €6.80 (~$7.45) | 4 | 8 GB | 80 GB SSD | 20 TB | EU (DE/FI) |
| **[Contabo](https://contabo.com/en/openclaw-hosting/)** | Cloud VPS M | $7.95 | 4 | 8 GB | 200 GB SSD | Unlimited | US/EU/Asia |
| **[Kamatera](https://www.kamatera.com/)** | Custom | $4+ | Custom | Custom | Custom | Pay-as-you-go | Global |
| **[Zap-Hosting](https://zap-hosting.com/)** | VPS | Varies | Varies | Varies | Varies | Varies | EU |
| **[BoostedHost](https://boostedhost.com/)** | OpenClaw VPS | Varies | Varies | Varies | Varies | Varies | Global |

### Mid-Range ($5-25/month)

| Provider | Plan | Price/mo | vCPU | RAM | Storage | Notes |
|----------|------|----------|------|-----|---------|-------|
| **[DigitalOcean](https://marketplace.digitalocean.com/apps/openclaw)** | Premium Droplet | $7 | 1 | 1 GB | 25 GB NVMe | 1-Click Deploy available |
| **[DigitalOcean](https://marketplace.digitalocean.com/apps/openclaw)** | Standard 2GB | $12 | 1 | 2 GB | 50 GB | Recommended for OpenClaw |
| **[Hostinger](https://www.hostinger.com/uk/vps/docker/openclaw)** | KVM 2 | $6.99 | 2 | 8 GB | 100 GB NVMe | Best Hostinger value |
| **[GCP](https://cloud.google.com/compute)** | e2-medium | ~$12 | 2 | 4 GB | 30 GB SSD | $300 free credit (90 days) |
| **[Azure](https://azure.microsoft.com/en-us/products/virtual-machines)** | B1ms VM | ~$15 | 1 | 2 GB | 32 GB | Enterprise compliance |
| **[Linode](https://www.linode.com/)** | Dedicated 4GB | $36 | 2 (dedicated) | 4 GB | 40 GB | Consistent performance |

### Serverless & PaaS

| Platform | Starting Price | Free Tier? | Persistent Storage | Auto-Scale | Notes |
|----------|---------------|------------|-------------------|------------|-------|
| **[Cloudflare Workers](https://workers.cloudflare.com/)** | $5/mo (paid plan) | 100K req/day (free) | R2 ($0.015/GB/mo) | Yes | Moltworker PoC |
| **[Railway](https://railway.com/deploy/openclaw)** | $5/mo (Hobby) | $5 credit trial | Yes (volumes) | Yes | Best PaaS UX |
| **[Render](https://render.com/)** | $7/mo (web service) | Free w/ limits | Yes (disks) | Yes | YAML IaC |
| **[Fly.io](https://fly.io/)** | Pay-as-you-go | None | Yes (volumes) | Yes | Global edge |
| **[AWS Lightsail](https://aws.amazon.com/lightsail/)** | $3.50/mo | None | Yes | No | Simple AWS VPS |
| **[Northflank](https://northflank.com/stacks/deploy-openclaw)** | Varies | Limited | Yes | Yes | Stack templates |
| **[Zeabur](https://zeabur.com/templates/VTZ4FX)** | Varies | Limited | Yes | Yes | One-click Docker |
| **[Elestio](https://elest.io/open-source/openclaw)** | Varies | None | Yes | Yes | Fully managed open source |
| **[Coolify](https://github.com/essamamdani/openclaw-coolify)** | Self-hosted | Free (self-host) | Yes | No | Open-source PaaS |

### Managed Hosting Services

These providers handle ALL the setup for you — no Docker, no terminal, no DevOps required.

| Provider | Price/mo | Setup Time | Specs | What's Included | Promo |
|----------|----------|------------|-------|-----------------|-------|
| **[Agent37](https://www.agent37.com/openclaw)** | $0.99-3.99 | 30 sec | 2 vCPU, 4-6 GB RAM | Isolated instance, full UI, terminal, SSL | - |
| **[MyClaw.ai](https://myclaw.ai/pricing)** | $9 (was $29) | Instant | 2 vCPU, 4 GB RAM, 40 GB SSD | Auto-updates, backups, web terminal | 69-76% off early bird |
| **[get-open-claw.com](https://www.get-open-claw.com/)** | $9-49 | < 1 min | Varies by plan | OpenClaw Secure, daily backups, health monitoring | Pro includes $10 AI credits |
| **[EasyClaw](https://www.easyclaw.pro/en)** | $10+ | 60 sec | Varies | Multi-model, 3+ platforms, zero maintenance | 29 min saved per deploy |
| **[ClawSimple](https://clawsimple.com/en)** | $8.25-29.08 | 2-3 min | Varies | Secure cloud, one-click updates (coming) | 20% off with LAUNCH20 |
| **[xCloud](https://xcloud.host/openclaw-hosting)** | $24 | 5 min | Managed | Telegram/WhatsApp pre-configured, encrypted backups | 7-day guarantee |
| **[ClawCloud](https://www.clawcloud.sh/)** | $29-129 | < 1 min | 1-2 vCPU, 1-4 GB RAM | All AI models (BYOK), auto-updates, daily backups | 70% off with EARLYBIRD70 |
| **[SimpleClaw](https://www.simpleclaw.com/)** | TBD | < 1 min | Managed | 1-click deploy, model selection | - |
| **[OpenClaw Cloud](https://openclawcloud.work/)** | Beta pricing | 5 min | Managed | All AI tokens included, 99.9% uptime, $0 hidden fees | Waitlist open |
| **[OpenClawd.ai](https://openclawd.ai)** | Free + Premium | Minutes | Managed | Launched Feb 10 — fully managed hosting, one-click deploy, security built-in, free tier available | - |
| **[Kimi Claw](https://kimi.com/bot)** | Allegretto+ | Instant | Browser-native | OpenClaw native in kimi.com — 5,000+ ClawHub skills, 40 GB cloud storage, Yahoo Finance search, BYOC (Bring Your Own Claw) | Beta open |
| **[Kilo Claw](https://kilo.ai/kiloclaw)** | Pay-as-you-go | < 60 sec | Managed | 500+ models, 50+ platforms, SSO, audit logs | 7 days free compute |
| **[OpenClaw Hosting](https://openclawhosting.io/pricing)** | $29+ | 5 min | Managed | Solo/Team/Business tiers, annual billing saves 20% | - |
| **[Myclawhost](https://www.myclawhost.com/)** | $9-39 | Instant | Managed | Lite ($9), Pro ($19), Max ($39), full lifecycle | One-click deploy |
| **[Contabo OpenClaw](https://contabo.com/en/openclaw-hosting/)** | $4.95+ | Minutes | VPS | Unlimited workflows, full data ownership, predictable pricing | - |
| **[Molty by Finna](https://molty.finna.ai)** | $19-99 | 30 sec | VM-isolated (Fly.io) | Multiple Molties per account, Mission Control (multi-agent coordination), GitHub backup sync, browser automation, auto-updates | 3-day free trial |
| **[ClawLaunch](https://clawlaunch.ai)** | Free (30d) / $9.49 | 60 sec | Varies by plan | Includes AI Credits. Hardened sandbox via gVisor. Free TTS pre-installed (Whisper). | 30-day free trial, 50% revshare affiliate program |
| **[OpenClaw Setup](https://openclaw-setup.me)** | $3.9 (Solo) / $6.9 (Trio) | ~2 min | 1 CPU, 3-12 GB RAM | Full UI instance management (LLM providers, env vars, workspace and memory management), Telegram + Slack support, encrypted credentials, allowlist access control, per-model usage analytics | AWESOMEOPENCLAWSETUP (50% off first-time customers) |

### Setup-as-a-Service (Freelancers)

Hire someone to set it up for you.

| Provider | Price | Type | What's Included |
|----------|-------|------|-----------------|
| **[GetClawHelp](https://getclawhelp.com/)** | $119-229 (one-time) | 1-on-1 video call | VPS setup, LLM config, 10-25 skills, 24/7 uptime |
| **[GetClawHelp Maintenance](https://getclawhelp.com/)** | $97/mo | Monthly | Updates, troubleshooting, new skills |
| **Fiverr - [almaasparvez](https://www.fiverr.com/almaasparvez)** | $90 | One-time | OpenClaw on AWS VPS, Telegram setup |
| **Fiverr - marcos_mark683** | $40 | One-time | OpenClaw installation |
| **[Upwork - Custom Skills](https://www.upwork.com/services/product/development-it-openclaw-ai-agent-setup-with-custom-skills-2018301653307508886)** | Varies | One-time | Up to 23 custom skills, testing, step-by-step guide |
| **[Upwork - Secure Deploy](https://www.upwork.com/services/product/development-it-secure-openclaw-clawdbot-deployment-mac-mini-or-vps-approval-gates-2019127245731633908)** | Varies | One-time | Mac Mini/VPS, sandboxing, human-in-the-loop approval gates |
| **[Freelancer.com](https://www.freelancer.com/projects/automation/OpenClaw-Linux-Setup.html)** | Varies | One-time | Linux setup, tuning, README |
| **[OpenClaw Money Playbook](https://openclawmoney.com/)** | $9.95 | E-book | Guide on monetizing OpenClaw setup services |

> **Business Model Insight**: *"The move right now is doing free OpenClaw installs, upselling security/skill packages/custom builds. We still make money on a 'free' install because we get an affiliate commission from the hosting company."* — [@GanimCorey on X](https://x.com/GanimCorey)

---

## Master Cost Comparison Table

| Provider | Monthly Cost | Setup Time | Difficulty | 1-Click? | Best For |
|----------|-------------|------------|------------|----------|----------|
| [Oracle Cloud](https://www.oracle.com/cloud/free/) | **$0** | 3 hours | Hard | No | Free-forever hosting |
| [AMD Dev Cloud](https://www.amd.com/en/developer/resources/cloud-access.html) | **$0** (credits) | 30 min | Medium | No | Free GPU inference |
| [Agent37](https://www.agent37.com/openclaw) | **$0.99** | 30 sec | **None** | **Yes** | Cheapest managed |
| [LumaDock](https://lumadock.com/) | **$1.99** | 15 min | Medium | No | Cheapest VPS |
| [Vultr](https://www.vultr.com/) | **$2.50** | 10 min | Medium | Yes | Global presence |
| [Hetzner CX22](https://www.hetzner.com/cloud/) | **$4.15** | 10 min | Medium | No | Best price/performance |
| [Contabo VPS S](https://contabo.com/en/openclaw-hosting/) | **$4.95** | 15 min | Medium | No | Unlimited bandwidth |
| [Hostinger KVM 1](https://www.hostinger.com/uk/vps/docker/openclaw) | **$4.99** | 10 min | Easy | Yes | Docker templates |
| [Cloudflare Workers](https://workers.cloudflare.com/) | **$5** | 5 min | Medium | No | Serverless |
| [Railway Hobby](https://railway.com/deploy/openclaw) | **$5** | 2 min | Easy | Yes | Best PaaS experience |
| [Linode 1GB](https://www.linode.com/) | **$5** | 10 min | Medium | No | Consistent performance |
| [DigitalOcean](https://marketplace.digitalocean.com/apps/openclaw) | **$6** | 2 min | Easy | **Yes** | Best docs + 1-Click |
| [Render](https://render.com/) | **$7** | 5 min | Easy | Yes | YAML Infrastructure |
| [MyClaw.ai Lite](https://myclaw.ai/pricing) | **$9** | Instant | **None** | **Yes** | Budget managed |
| [DigitalOcean 2GB](https://marketplace.digitalocean.com/apps/openclaw) | **$12** | 2 min | Easy | **Yes** | Recommended production |
| [Molty by Finna](https://molty.finna.ai) | **$19** | 30 sec | **None** | **Yes** | Multi-Molty, Mission Control, GitHub sync |
| [xCloud Managed](https://xcloud.host/openclaw-hosting) | **$24** | 5 min | **None** | **Yes** | Full managed hosting |
| [ClawCloud Starter](https://www.clawcloud.sh/) | **$29** | < 1 min | **None** | **Yes** | Premium managed |
| [Raspberry Pi 5](https://docs.openclaw.ai/raspberry-pi) | **$0**/mo | 30 min | Medium | No | Low-power, always-on |
| [ESP32-S3 (MimiClaw)](https://github.com/memovai/mimiclaw) | **$0**/mo | 10 min | Medium | No | Cheapest ($5 chip), no OS |
| [PicoClaw (RISC-V)](https://github.com/sipeed/picoclaw) | **$0**/mo | 5 min | Easy | No | $10 hardware, 10 MB RAM, Go binary |
| [ZeroClaw (Rust)](https://github.com/theonlyhennygod/zeroclaw) | **$0**/mo | 2 min | Easy | No | 3.4 MB binary, Rust, <10ms startup |
| [TinyClaw (Shell)](https://github.com/jlia0/tinyclaw) | **$0**/mo | 5 min | Easy | No | 400 LoC, Claude Code + tmux |
| [Autobot (Crystal)](https://github.com/crystal-autobot/autobot) | **$0**/mo | 2 min | Easy | No | 2MB binary, Crystal, <10ms startup |
| Mac Mini | **$0**/mo | 10 min | Easy | No | Privacy-first, local |

---

## AI Model API Costs

The **real cost** of running OpenClaw is the AI model API, not infrastructure.

### Provider Pricing (per 1M tokens)

| Provider | Model | Input Cost | Output Cost | Notes |
|----------|-------|-----------|-------------|-------|
| **[Anthropic](https://console.anthropic.com/)** | Claude 3.5 Haiku | $0.80 | $4.00 | Best budget option |
| **[Anthropic](https://console.anthropic.com/)** | Claude 3.5 Sonnet | $3.00 | $15.00 | Best balance |
| **[Anthropic](https://console.anthropic.com/)** | Claude Opus 4.5 | $15.00 | $75.00 | Most capable, expensive |
| **[OpenAI](https://platform.openai.com/)** | GPT-4o | $2.50 | $10.00 | Good alternative |
| **[OpenAI](https://platform.openai.com/)** | GPT-4o-mini | $0.15 | $0.60 | Very cheap |
| **[Google](https://aistudio.google.dev/)** | Gemini 2.0 Flash | $0.10 | $0.40 | Cheapest hosted |
| **[Google](https://aistudio.google.dev/)** | Gemini Flash-Lite | **Free tier** | **Free tier** | Zero cost option |
| **[DeepSeek](https://platform.deepseek.com/)** | DeepSeek V3 | $0.27 | $1.10 | Best value reasoning |
| **[Moonshot](https://platform.moonshot.cn/)** | Kimi K2.5 | $3.00 | $3.00 | Great agentic performance, free built-in provider since v2026.2.6 |
| **[Grok](https://console.x.ai/)** | Grok 4.1 mini | $0.20 | $0.50 | Budget alternative |
| **[OpenRouter](https://openrouter.ai/)** | Various | Varies | Varies | Unified API for 200+ models |
| **[Ollama](https://ollama.com/)** | Any | **$0** | **$0** | Requires hardware (16 GB+ RAM) |

> **75x price difference** between the most expensive (Claude Opus) and cheapest (Gemini Flash) options.

### Monthly API Cost Estimates

| Usage Level | Description | Monthly Cost |
|-------------|-------------|-------------|
| **Minimal** | Few messages/day, Gemini free tier | $0-5 |
| **Light** | ~50 messages/day, Claude Haiku | $5-15 |
| **Moderate** | ~200 messages/day, mixed models | $15-50 |
| **Heavy** | 500+ messages/day, Claude Sonnet | $50-150 |
| **Power User** | All-day usage, Claude Opus | $150-500+ |

### Cost Optimization Tips

1. Use **smart model routing** — cheap models (Haiku/Flash) for simple tasks, expensive (Sonnet/Opus) for complex
2. Enable **prompt caching** — Anthropic auto-applies 5-min cache, reducing repeat costs
3. Use **local LLMs** via Ollama for zero API cost (requires 16 GB+ RAM)
4. Set **budget alerts** in your AI provider dashboard
5. Use [OpenClaw Cost Calculator](https://calculator.vlvt.sh/) to estimate your spend

---

## Total Real-World Cost Examples

| Setup | Infrastructure | API | Total/month | Notes |
|-------|---------------|-----|-------------|-------|
| **Free Tier Max** | Oracle Cloud ($0) | Gemini free ($0) | **$0** | Limited but functional |
| **Cheapest Managed** | Agent37 ($1) | Haiku ($5) | **$6** | 30-second setup |
| **Ultra Budget** | LumaDock ($2) | Haiku ($5) | **$7** | Basic personal assistant |
| **Budget Managed** | MyClaw.ai Lite ($9) | BYOK ($10) | **$19** | Zero setup, instant access |
| **Sweet Spot** | Hetzner CX22 ($4) | Mixed models ($15) | **$19** | Best value-to-capability |
| **Standard** | DigitalOcean ($12) | Sonnet ($40) | **$52** | Production-ready |
| **Managed Easy** | xCloud ($24) | Mixed ($30) | **$54** | Zero technical setup |
| **Cloudflare** | Workers ($5+$30) | Mixed ($20) | **$55** | Serverless architecture |
| **Local LLM** | Raspberry Pi 5 ($0/mo) | Ollama ($0) | **$0** | After $80 hardware purchase |
| **Embedded** | ESP32-S3 ($0/mo) | Claude API ($5) | **$5** | After $5 hardware purchase (MimiClaw) |
| **PicoClaw** | RISC-V board ($0/mo) | Gemini/Claude ($5) | **$5** | After $10 hardware purchase (PicoClaw) |
| **Power User** | DigitalOcean ($24) | Opus ($200) | **$224** | Heavy professional use |
| **Extreme** | Dedicated ($50) | All models ($573) | **$623** | One developer's real report |

---

## Cloudflare Workers (Moltworker) Deep Dive

[Moltworker](https://github.com/cloudflare/moltworker) is Cloudflare's official adaptation of OpenClaw for Workers.

### Architecture

- **Container**: Sandbox (standard-1: 1/2 vCPU, 4 GiB RAM, 8 GB disk)
- **Storage**: R2 for persistence (auto-sync every 5 minutes)
- **Auth**: Cloudflare Access (Zero Trust) + gateway token + device pairing
- **Status**: Proof-of-concept (not an official Cloudflare product)

### Setup

```bash
git clone https://github.com/cloudflare/moltworker.git
cd moltworker && npm install
npx wrangler secret put ANTHROPIC_API_KEY
export MOLTBOT_GATEWAY_TOKEN=$(openssl rand -hex 32)
npx wrangler secret put MOLTBOT_GATEWAY_TOKEN
npm run deploy
```

Access: `https://your-worker.workers.dev/?token=YOUR_GATEWAY_TOKEN`

### Cost Breakdown (24/7 Operation)

| Component | Monthly Cost |
|-----------|-------------|
| Workers Paid Plan | $5.00 |
| Memory (~4 GiB) | ~$26.00 |
| CPU | ~$2.00 |
| Disk (8 GB) | ~$1.50 |
| **Total** | **~$34.50** |

> Set `SANDBOX_SLEEP_AFTER=10m` for infrequent use to reduce costs significantly.

### Limitations

- **Cannot support Telegram bots** (requires persistent connection for long-polling)
- Containers hibernate when not receiving HTTP requests
- Use VPS deployment for Telegram integration

### Resources

- [GitHub - cloudflare/moltworker](https://github.com/cloudflare/moltworker)
- [Blog - Introducing Moltworker](https://blog.cloudflare.com/moltworker-self-hosted-ai-agent/)

---

## DigitalOcean 1-Click Deploy

The fastest path to a production OpenClaw instance.

1. Go to [DigitalOcean Marketplace](https://marketplace.digitalocean.com/apps/openclaw)
2. Click "Create OpenClaw Droplet"
3. Choose $12/mo plan (2 GB RAM recommended)
4. Select region, SSH key
5. Deploy (ready in ~90 seconds)

**Pre-configured**: OpenClaw 2026.1.24-1, Docker isolation, unique gateway token, security-hardened, Caddy HTTPS.

### Resources

- [DigitalOcean Blog - Introducing OpenClaw](https://www.digitalocean.com/blog/moltbot-on-digitalocean)
- [Technical Deep Dive - Security Hardening](https://www.digitalocean.com/blog/technical-dive-openclaw-hardened-1-click-app)
- [Tutorial - How to Run OpenClaw](https://www.digitalocean.com/community/tutorials/how-to-run-openclaw)

---

## Hetzner Setup Guide

Best price-to-performance ratio for OpenClaw hosting.

| Plan | Price/mo | vCPU | RAM | Storage | Bandwidth |
|------|----------|------|-----|---------|-----------|
| **CX22** | €3.79 | 2 | 4 GB | 40 GB SSD | 20 TB |
| **CX32** | €6.80 | 4 | 8 GB | 80 GB SSD | 20 TB |
| **CAX11 (ARM)** | €3.79 | 2 | 4 GB | 40 GB | 20 TB |

```bash
ssh root@your-server-ip
curl -fsSL https://deb.nodesource.com/setup_22.x | bash -
apt-get install -y nodejs
npm install -g openclaw@latest
openclaw onboard --install-daemon
ufw allow ssh && ufw allow 443/tcp && ufw enable
```

- [Hetzner - OpenClaw Docs](https://docs.openclaw.ai/platforms/hetzner)
- [Deploy with Pulumi + Tailscale](https://www.pulumi.com/blog/deploy-openclaw-aws-hetzner/)

---

## Hostinger VPS Setup

| Plan | Price/mo | vCPU | RAM | Storage | Bandwidth |
|------|----------|------|-----|---------|-----------|
| **KVM 1** | $4.99 | 1 | 4 GB | 50 GB NVMe | 4 TB |
| **KVM 2** | $6.99 | 2 | 8 GB | 100 GB NVMe | 8 TB |
| **KVM 4** | $10.99 | 4 | 16 GB | 200 GB NVMe | 16 TB |

> Renewal prices are ~2x. Lock in annual pricing.

- [How to Install OpenClaw on Hostinger VPS](https://www.hostinger.com/support/how-to-install-openclaw-on-hostinger-vps/)
- [How to Secure OpenClaw on Hostinger](https://www.hostinger.com/support/how-to-secure-and-harden-openclaw-security/)
- [25 OpenClaw Use Cases](https://www.hostinger.com/tutorials/openclaw-use-cases)

---

## Oracle Cloud Free Tier Setup

**Truly free forever** — 4 ARM cores, 24 GB RAM, 200 GB storage, 10 TB/month.

```bash
curl -fsSL https://deb.nodesource.com/setup_22.x | bash -
apt-get install -y nodejs git
npm install -g openclaw@latest
openclaw onboard --install-daemon
```

**Caveats**: ARM architecture, high demand (keep retrying), add credit card to prevent account termination.

- [Oracle Cloud - OpenClaw Docs](https://docs.openclaw.ai/platforms/oracle)
- [Always-On AI for $0/month](https://ryanshook.org/blog/posts/openclaw-on-oracle-free-tier-always-on-ai-for-free/)
- [Self-Host on a Free VPS](https://cognio.so/clawdbot/self-hosting)

---

## Raspberry Pi Setup

| Device | Price | RAM | Performance |
|--------|-------|-----|-------------|
| **Pi 5 (8 GB)** | $80 | 8 GB | Best choice |
| **Pi 5 (4 GB)** | $60 | 4 GB | Good budget option |
| **Pi 4 (8 GB)** | $55 | 8 GB | 2-2.5x slower than Pi 5 |

```bash
curl -fsSL https://deb.nodesource.com/setup_22.x | sudo bash -
sudo apt-get install -y nodejs
npm install -g openclaw@latest
openclaw onboard --install-daemon
```

- [OpenClaw on Raspberry Pi - ajfisher](https://ajfisher.me/2026/02/03/openclaw-raspberrypi-howto/)
- [OpenClaw on Raspberry Pi - Adafruit](https://learn.adafruit.com/openclaw-on-raspberry-pi)

---

## ESP32 Embedded (MimiClaw)

[MimiClaw](https://github.com/memovai/mimiclaw) implements OpenClaw's core principles on a **$5 ESP32-S3** microcontroller. Written entirely in pure C — no Linux, no Node.js, no server infrastructure needed.

| Spec | Detail |
|------|--------|
| **Hardware** | ESP32-S3 (16 MB flash, 8 MB PSRAM) |
| **Cost** | ~$5 (chip only) |
| **Language** | Pure C (ESP-IDF v5.5+) |
| **AI Backend** | Anthropic Claude API with ReAct agent loop |
| **Messaging** | Telegram |
| **Memory** | Persistent local storage (SOUL.md, USER.md, MEMORY.md on flash) |
| **Features** | Tool use (web search, time), dual-core processing, WebSocket gateway, runtime CLI config |

The smallest and cheapest way to run an OpenClaw-style AI agent — proving the core architecture (agent loop, persistent memory, tool calling, chat integration) can work without an operating system or runtime environment.

- [GitHub - memovai/mimiclaw](https://github.com/memovai/mimiclaw)

---

## Docker Deployment

```bash
git clone https://github.com/openclaw/openclaw.git
cd openclaw && ./docker-setup.sh
```

### Useful Commands

```bash
docker compose run --rm openclaw-cli pairing approve telegram <CODE>
docker compose run --rm openclaw-cli dashboard --no-open
docker compose run --rm openclaw-cli security audit --deep
```

- [Docker - OpenClaw Docs](https://docs.openclaw.ai/install/docker)
- [Running OpenClaw in Docker - Simon Willison](https://til.simonwillison.net/llms/openclaw-docker)
- [Docker Guide for Beginners - Medium](https://medium.com/@ozbillwang/run-openclaw-moltbot-clawdbot-safely-with-docker-a-practical-guide-for-beginners-94112a9b57be)

---

## Security & Hardening

### Known CVEs (All Patched)

| CVE | Severity | Description | Fixed In |
|-----|----------|-------------|----------|
| **CVE-2026-24763** | High | Docker PATH Command Injection | v2026.1.29 |
| **GHSA-g8p2-7wf7-98mq** | Critical (8.8) | gatewayUrl Token Exfiltration (1-click RCE) | v2026.1.29 |
| **GHSA-q284-4pvr-m585** | High | sshNodeCommand Injection | v2026.1.29 |
| **CVE-2026-25593** | Critical | Unauthenticated Local RCE via WebSocket | v2026.1.30 |
| **CVE-2026-25475** | High | Local File Inclusion via MEDIA: Path | v2026.1.30 |
| **CVE-2026-25253** | Critical (8.8) | 1-Click RCE via Cross-Site WebSocket Hijacking | v2026.1.29 |

> **Update immediately to v2026.2.12+** to patch all known vulnerabilities (40+ security fixes).

### Security Best Practices

1. **Bind to `127.0.0.1` only** (never `0.0.0.0`) — over 135,000 exposed instances found online
2. Use **SSH tunnels** or [Tailscale Serve](https://tailscale.com/kb/1242/tailscale-serve) for remote access
3. Use **auth profiles** (system keychain): `openclaw auth set ANTHROPIC_API_KEY`
4. Configure **firewall**: `ufw default deny incoming && ufw allow ssh && ufw allow 443/tcp && ufw enable`
5. Use **Docker** for container isolation
6. Run regular audits: `openclaw security audit --deep` and `openclaw doctor`
7. Use **Composio** for managed OAuth ([security guide](https://composio.dev/blog/secure-openclaw-moltbot-clawdbot-setup))

### Skills Marketplace Risks

> **~15% of community skills contain malicious instructions**

- **341 malicious skills** discovered in "ClawHavoc" campaign (Atomic Stealer malware)
- **280+ skills leak API keys and PII** ([Snyk](https://snyk.io/blog/openclaw-skills-credential-leaks-research/))
- VirusTotal scanning now integrated
- Always audit skills before installation

### Security Tools

| Tool | Description | Source |
|------|-------------|--------|
| **ClawSec** | Complete security skill suite by Prompt Security | [GitHub](https://github.com/prompt-security/clawsec) |
| **ClawBands** | Security middleware — intercepts tool execution, human-in-the-loop approval for dangerous actions | [GitHub](https://github.com/SeyZ/clawbands) |
| **ClawGuard** | Permission manifests, runtime enforcement, sandboxing, audit logging with hash-chaining | [GitHub](https://github.com/newtro/ClawGuard) |
| **Claw-Hunter** | MDM-ready scripts to detect and monitor shadow OpenClaw agents across macOS/Linux/Windows endpoints | [GitHub](https://github.com/backslash-security/Claw-Hunter) |
| **Aquaman** | Credential isolation proxy — API keys never enter the agent process. Stores secrets in Keychain/1Password/Vault/encrypted-file, injects via Unix domain socket. Process-level isolation (not detection/redaction). | [GitHub](https://github.com/tech4242/aquaman) |
| **Orchard Kit** | Complete alignment and safety architecture — membrane security (Calyx Protocol), continuous trust verification with heartbeat, epistemic hygiene, and defence tools. Includes a ready-to-install OpenClaw skill for agent self-governance. Based on 30 years of cybernetic research | [GitHub](https://github.com/OrchardHarmonics/orchard-kit) |
| **Clawhatch** | Pre-install security scanner — 128 automated checks, scores skills 0-100, runs in <1 second, catches malicious patterns before installation | [GitHub](https://github.com/AISafetyLab/clawhatch) |
| **OpenClaw Scanner** | Enterprise endpoint scanner — detects OpenClaw agents running across corporate networks, identifies exposed instances and misconfigurations | [Help Net Security](https://www.helpnetsecurity.com/2026/02/13/openclaw-scanner-enterprise/) |

### Security Resources

- [centminmod/explain-openclaw](https://github.com/centminmod/explain-openclaw) - Deep security analysis (73 files, multi-AI)
- [Cisco - AI Agents Are a Security Nightmare](https://blogs.cisco.com/ai/personal-ai-agents-like-openclaw-are-a-security-nightmare)
- [Bitdefender - Malicious Skill Trap](https://www.bitdefender.com/en-us/blog/labs/helpful-skills-or-hidden-payloads-bitdefender-labs-dives-deep-into-the-openclaw-malicious-skill-trap)
- [Snyk - 280+ Leaky Skills](https://snyk.io/blog/openclaw-skills-credential-leaks-research/)
- [The Register - Security Issues](https://www.theregister.com/2026/02/02/openclaw_security_issues/)
- [SecurityWeek - Hijack OpenClaw AI Assistant](https://www.securityweek.com/vulnerability-allows-hackers-to-hijack-openclaw-ai-assistant/)
- [SoC Radar - CVE-2026-25253 Analysis](https://socradar.io/blog/cve-2026-25253-rce-openclaw-auth-token/)
- [Runzero - OpenClaw RCE Vulnerability](https://www.runzero.com/blog/openclaw/)
- [Depthfirst - 1-Click RCE to Steal Data and Keys](https://depthfirst.com/post/1-click-rce-to-steal-your-moltbot-data-and-keys)
- [VirusTotal - From Automation to Infection](https://blog.virustotal.com/2026/02/from-automation-to-infection-how.html) - 7.1% of ClawHub skills exposed credentials
- [Cyera - The OpenClaw Security Saga](https://www.cyera.com/research-labs/the-openclaw-security-saga-how-ai-adoption-outpaced-security-boundaries)
- [Vectra - When Automation Becomes a Digital Backdoor](https://www.vectra.ai/blog/clawdbot-to-moltbot-to-openclaw-when-automation-becomes-a-digital-backdoor)
- [Belgium CCB Advisory](https://ccb.belgium.be/advisories/warning-critical-vulnerability-openclaw-allows-1-click-remote-code-execution-when)
- [University of Toronto Advisory](https://security.utoronto.ca/advisories/openclaw-vulnerability-notification/)
- [n8n + OpenClaw Security White Paper](https://gripsy.com.au/research/n8n-openclaw-security-whitepaper.html) — Security analysis of n8n and OpenClaw integration patterns: credential isolation via n8n proxy, webhook hardening, network architecture, and threat modeling for production deployments. Peer-reviewed with multi-model validation. By Dr. Gaurav Caprihan.
- [The Calyx Protocol](https://github.com/OrchardHarmonics/orchard-kit/blob/main/01_CALYX_PROTOCOL.md) — Permeability-based security model replacing binary allow/deny with membrane architecture. Addresses prompt injection, data exfiltration, and skill poisoning through ethics-weighted signal routing. Derived from the Codex Harmonicae (30 years cybernetic research). By Kimberley Asher.
- [Semgrep - OpenClaw Security Engineer's Cheat Sheet](https://semgrep.dev/blog/openclaw-security-cheat-sheet) — Static analysis rules for detecting insecure OpenClaw configurations, exposed API keys, and risky skill patterns

---

## Configuration

### Model Providers

| Provider | Config Key | Free Tier? | Notes |
|----------|-----------|------------|-------|
| **Anthropic** | `ANTHROPIC_API_KEY` | No | Primary, best quality |
| **OpenAI** | `OPENAI_API_KEY` | No | GPT-4, GPT-4o |
| **Google** | `GOOGLE_API_KEY` | Yes (Gemini Flash-Lite) | Cheapest hosted |
| **OpenRouter** | `OPENROUTER_API_KEY` | No | 200+ models unified API |
| **DeepSeek** | `DEEPSEEK_API_KEY` | No | Excellent value |
| **Moonshot** | `MOONSHOT_API_KEY` | No | Kimi K2.5 (great agentic) |
| **MiniMax** | `MINIMAX_API_KEY` | No | M2.1 native support |
| **Fireworks AI** | Built-in | No | Model hosting |
| **Workers AI** | Built-in | Yes (limits) | Cloudflare models |
| **Ollama** | Local | **Free** | Requires local hardware |
| **LM Studio** | Local | **Free** | Requires local hardware |
| **vLLM** | Local | **Free** | High-performance inference |

### Messaging Channels

| Channel | Setup | Auth Method | Notes |
|---------|-------|-------------|-------|
| **Telegram** | 2 min | BotFather token | Fastest setup, supports Topics for parallel threads |
| **WhatsApp** | 2 min | QR code scan | Separate phone number recommended |
| **Discord** | 5 min | Bot application | Developer portal required |
| **Slack** | 5 min | Bot token (Socket or HTTP mode) | api.slack.com/apps |
| **Signal** | 5 min | Direct integration | Privacy-focused |
| **iMessage** | 10 min | BlueBubbles bridge | macOS only |
| **Microsoft Teams** | 5 min | Enterprise integration | Business users |
| **Google Chat** | 5 min | Workspace integration | Google Workspace |
| **Matrix** | 5 min | E2E encryption | Best for privacy |
| **Zalo** | 5 min | Direct integration | Popular in Vietnam |
| **WebChat** | Built-in | Gateway token | Browser-based interface |

### Local LLM Integration

#### Ollama

```bash
curl -fsSL https://ollama.com/install.sh | sh
ollama pull llama3.1
```

```json
{ "provider": "openai", "baseUrl": "http://localhost:11434/v1", "model": "llama3.1" }
```

#### LM Studio

```json
{ "provider": "openai", "baseUrl": "http://localhost:1234/v1", "model": "your-model-name" }
```

#### vLLM (GPU-Accelerated)

```json
{ "provider": "openai", "baseUrl": "http://localhost:8000/v1", "model": "your-model-name" }
```

- [OpenClaw + Ollama Guide](https://codersera.com/blog/openclaw-ollama-setup-guide-2026/)
- [OpenClaw + LM Studio Guide](https://codersera.com/blog/openclaw-lm-studio-setup-guide-2026/)
- [OpenClaw + vLLM on AMD](https://www.amd.com/en/developer/resources/technical-articles/2026/openclaw-with-vllm-running-for-free-on-amd-developer-cloud-.html)

### MCP Server Integration

| Plugin | Source | Features |
|--------|--------|----------|
| **openclaw-mcp-plugin** | [GitHub](https://github.com/lunarpulse/openclaw-mcp-plugin) | HTTP/SSE transport, multi-server, unified interface |
| **openclaw-mcp-adapter** | [npm](https://www.npmjs.com/package/openclaw-mcp-adapter) | Registers MCP tools as native agent tools |
| **openclaw-mcp** | [GitHub](https://github.com/freema/openclaw-mcp) | Secure Claude.ai ↔ OpenClaw bridge with OAuth 2.1 authentication |
| **openclaw-mcp-server** | [GitHub](https://github.com/Helms-AI/openclaw-mcp-server) | Exposes OpenClaw Gateway tools to Claude Code and MCP clients |

---

## Integrations & Features

### Voice Assistant

| Feature | Description |
|---------|-------------|
| **OpenClaw Voice** | Self-hosted browser-based voice chat (Whisper STT + ElevenLabs TTS) |
| **Android App** | Customizable wake words, long-press home button activation |
| **Voice Call Plugin** | Telephony via Twilio, Telnyx, Plivo |
| **ClawdTalk** | Phone calling and SMS for OpenClaw. Call your agent from any phone, with deep tool integration for calendar, Jira, web search, and more. Powered by Telnyx. |
| **Always-On Speech** | macOS/iOS/Android with ElevenLabs |

- [OpenClaw Voice](https://openclawvoice.com/)
- [Voice Call Plugin Docs](https://docs.openclaw.ai/plugins/voice-call)
- [ClawdTalk](https://clawdtalk.com/) — Phone calls and SMS for OpenClaw agents. Dedicated number, WebSocket client, agentic deep tools. ([GitHub](https://github.com/team-telnyx/clawdtalk-client) | [ClawHub](https://clawhub.ai/skills/clawdtalk-client))

### Home Automation

- **Home Assistant** custom add-on with ha-mcp integration
- Control lights, thermostats, IoT devices via messaging
- Adjust boilers based on weather forecasts
- Voice commands through WhatsApp/Telegram

- [OpenClaw on Home Assistant](https://community.home-assistant.io/t/openclaw-clawdbot-on-home-assistant/981467)
- [OpenClaw Gave My Home Assistant an AI Agent](https://www.dan-malone.com/blog/openclaw-home-assistant)

### Email & Calendar

- **Gmail**: Real-time processing via Pub/Sub, smart filtering, auto-responses
- **Google Calendar**: Event creation, viewing, sync, daily briefings
- **Apple Calendar**: Via khal/vdirsyncer integration
- **Outlook**: Calendar sync and management
- **[BotEmail.ai](https://botemail.ai)** — Instant @botemail.ai email inboxes for AI agents. One API call creates a dedicated inbox with no human setup required. Includes an OpenClaw skill ([ClawHub](https://clawhub.ai/skills/bot-email)), MCP server, and OpenAI GPT Actions support.

- [Gmail Automation Guide](https://zenvanriel.nl/ai-engineer-blog/openclaw-gmail-pubsub-automation-guide/)
- [Google Calendar Sync](https://martin.hjartmyr.se/articles/openclaw-google-calendar-sync/)

### Google Workspace

Full suite access: Gmail, Calendar, Drive, Docs, Sheets. All data stays local — never passes through third-party services.

- [Google Workspace Integration Guide](https://www.getopenclaw.ai/integrations/google-workspace)

### Webhooks & Cron Jobs

**Webhooks**: POST to `/hooks/wake` or `/hooks/agent` with Bearer token authentication. [Hookdeck](https://hookdeck.com/webhooks/platforms/using-hookdeck-with-openclaw-reliable-webhooks-for-your-ai-agent) for secure tunnels with retries.

**Cron Jobs**: Interval-based (`every 30 minutes`) or Unix cron expressions (`0 9 * * 1`). Stored at `~/.openclaw/cron/jobs.json`. Exponential retry backoff.

**Heartbeat**: Agent wakes every 30 min (configurable), reads `HEARTBEAT.md`, decides if action needed. Different from cron — "check these things periodically" vs "do this specific thing at this time."

- [Webhooks Docs](https://docs.openclaw.ai/automation/webhook)
- [Cron Jobs Docs](https://docs.openclaw.ai/automation/cron-jobs)
- [Heartbeat Docs](https://docs.openclaw.ai/gateway/heartbeat)
- **[ClawTick](https://clawtick.com/)** — Cloud scheduler for OpenClaw agents with performance monitoring and uptime checks.

### Live Canvas

A2UI (Agent-to-UI) visual workspace — agent can render real-time UI, charts, and diagrams. Embedded in macOS menu bar app using WKWebView. Borderless, resizable, auto-reloads on file changes.

- [Canvas Docs](https://docs.openclaw.ai/platforms/mac/canvas)

### Multi-Agent Setup

Configure multiple agents with separate workspaces, personas, auth profiles, and sessions (no cross-talk). Route by channel, phone number, or personality.

- [Multi-Agent Docs](https://docs.openclaw.ai/concepts/multi-agent)
- [Build Your Own AI Agent Team in 15 Minutes](https://ai2sql.io/how-to-build-your-own-ai-agent-team-with-openclaw-in-15-minutes)

### Companion Apps

| App | Platform | Status | Features |
|-----|----------|--------|----------|
| **Menu Bar App** | macOS | Available | Pixel lobster icon, voice wake, Canvas panel, TCC permissions |
| **Crabwalk** | Cross-platform | Available | Open-source companion app ([crabwalk.app](https://crabwalk.app/)) |
| **iOS/Android** | Mobile | Beta | Camera, screen recording, notifications |
| **[Expo OpenClaw Chat](https://github.com/brunobar79/expo-openclaw-chat)** | iOS/Android (Expo) | Available | React Native chat SDK for building native mobile OpenClaw clients |
| **[OpenClawgotchi](https://github.com/turmyshevd/openclawgotchi)** | Raspberry Pi | Available | AI Tamagotchi with E-Ink face — agentic life-form hardware |
| **[VisionClaw](https://github.com/sseanliu/VisionClaw)** | Meta Ray-Ban (iOS) | Available | Voice + vision + agentic actions via Gemini Live + OpenClaw (796 stars) |
| **[PinchChat](https://github.com/MarlBurroW/pinchchat)** | Web (PWA) | Available | Open-source webchat UI with ChatGPT-like interface, live tool calls, multi-session, token tracking, streaming, 8 languages, theming |
| **[VibeClaw](https://vibeclaw.dev)** | Web | Available | Runs a full OpenClaw instance entirely in the browser — visual server builder, in-browser sandbox with free AI models, server library with import/export. No install, no server required ([source](https://github.com/jasonkneen/vibeclaw)) |

### Monitoring & Dashboards

| Tool | Type | Features |
|------|------|----------|
| **openclaw dashboard** | Built-in | Gateway info, stats, web UI |
| **[ClawController](https://www.clawcontroller.com/)** | Third-party | Real-time monitoring, task orchestration, agent chat |
| **claw-dash** | Community | Sessions, tokens, costs, CPU/RAM/disk metrics |
| **Mission Control** | Community | Convex + React, live logs, task tracking |
| **[OpenClaw Mission Control](https://github.com/abhi1693/openclaw-mission-control)** | Community | RBAC, Kanban board, War Room, transcripts, Telegram output (37 stars) |
| **[OpenClaw Studio](https://github.com/grp06/openclaw-studio)** | Community | Visual agent management with cron jobs, tool extraction, mentions (410 stars) |
| **[Hawk Eye](https://github.com/benfoxsb/hawk-eye)** | Community | Workspace sentinel & operational dashboard |
| **[ClawTick](https://clawtick.com/)** | Third-party | Performance monitoring, uptime checks, and real-time analytics for OpenClaw instances. |

### Backup & Restore

```bash
openclaw config backup
openclaw config restore config-2026-02-01-1600.yaml

# Manual backup
tar -czvf ~/openclaw_backup_$(date +%Y%m%d).tar.gz -C "$HOME" .openclaw
```

> Never commit `~/.openclaw/` to Git (contains secrets).

---

## Performance Benchmarks

### Inference Speed

| Hardware | Tokens/sec | Notes |
|----------|-----------|-------|
| **RTX 4090** | ~80 t/s | Best GPU performance |
| **AMD MI300X** | High | 192 GB memory, free credits available |
| **Apple M2 Pro 64GB** | Good | Large memory pool for bigger models |
| **MacBook Air M2** | ~3.2 t/s | CPU-only, usable |
| **Typical CPU** | ~13.5 t/s | Non-time-critical tasks |
| **Oracle ARM (7B)** | 5-10 t/s | Free tier, acceptable |
| **Raspberry Pi 5** | 2-5 t/s | Slow but works |
| **ESP32-S3 (MimiClaw)** | Cloud API | No local inference, calls Claude API via Wi-Fi |
| **RISC-V (PicoClaw)** | Cloud API | 10 MB RAM, single Go binary, 1s boot, $10 board |

### Memory for Local Models

| Model Size | RAM Required | GPU VRAM |
|------------|-------------|----------|
| 3B (quantized) | 4 GB | 4 GB |
| 7B (quantized) | 8 GB | 8 GB |
| 13B (quantized) | 16 GB | 12-16 GB |
| 70B (quantized) | 64 GB | 48 GB+ |

**Bottleneck**: Memory bandwidth and VRAM capacity, not CPU speed. Sweet spot: 7B models.

---

## OpenClaw vs Claude Code

**Complementary tools**, not competitors. Many engineers run both simultaneously.

| Feature | Claude Code | OpenClaw |
|---------|------------|----------|
| **Lives in** | Terminal / IDE | Messaging apps |
| **Focus** | Coding, development | Automation, integration |
| **Memory** | Session-based | Persistent (24/7) |
| **Operation** | Interactive | Autonomous |
| **Runtime** | Per-session | Always-on daemon |
| **Integration** | Git, tests, dev tools | Email, calendar, messaging, home automation |
| **Best for** | Multi-file refactoring, tests | Inbox monitoring, reminders, web scraping |

---

## Alternatives & Competitors

| Alternative | Type | Best For | Key Advantage |
|-------------|------|----------|---------------|
| **[Nanobot](https://github.com/HKUDS/nanobot)** | Lightweight (4K lines) | Minimalists | 99% smaller codebase, 45 MB RAM, MCP-native |
| **[PicoClaw](https://github.com/sipeed/picoclaw)** | Ultra-lightweight (Go) | Embedded/hardware | 10 MB RAM, $10 RISC-V, single binary, 1s boot |
| **[Archestra](https://github.com/archestra-ai/archestra)** | Enterprise | Security/compliance | MCP registry, A2A, agentic security (3.5K stars) |
| **NanoClaw** | Security-first | Security-conscious | Isolated Apple containers |
| **memU** | Memory-focused | Budget users | Local knowledge graph |
| **Jan.ai** | Offline chat | Privacy absolutists | 100% offline |
| **AnythingLLM** | Doc-to-chatbot | Knowledge bases | Turn PDFs into chatbots |
| **Claude Code** | Coding agent | Developers | Best coding assistant |
| **Microsoft Copilot** | Enterprise AI | Enterprise | Compliance, security |
| **eesel AI** | Business agent | Help desks | Customer service |
| **Emergent** | Personal AI | WhatsApp/Telegram | Simpler OpenClaw alternative |
| **memU bot** | Memory-first agent | 24/7 proactive assistant | Learns habits, acts without commands |
| **Knolli.ai** | Safe agentic AI | Security-first | [Best OpenClaw alternative](https://www.knolli.ai/post/clawdbot-alterantive) |
| **Dify** | LLM app platform | Agents, RAG, MLOps | Best debugging, workflow visualization |
| **Langflow** | RAG pipelines | Vector stores, MongoDB | MIT licensed, Astra DB native |
| **Flowise** | Chatbot builder | Rapid development | Prebuilt conversational templates |
| **n8n** | Workflow automation | Business processes | Visual workflow builder |
| **LangBot** | Multi-platform bots | IM integration | [GitHub](https://github.com/langbot-app/LangBot) |
| [**LobsterX**](https://github.com/AstraBert/workflows-acp/blob/main/packages/lobsterx) | Document-related OpenClaw-like agent | Document workflows | Self-hostable (Docker, uv tool), Telegram bot support, lightweight codebase (2-3K LoC) |
| [**IronClaw**](https://github.com/nearai/ironclaw) | Rust rewrite | Privacy & security | OpenClaw-inspired, built by NEAR AI, Rust-native (1.3K stars) |
| [**ZeroClaw**](https://github.com/theonlyhennygod/zeroclaw) | Rust ultra-fast | Speed-first users | 3.4 MB binary, <10ms startup, 22+ providers, swappable Rust traits, hybrid SQLite memory |
| [**TinyClaw**](https://github.com/jlia0/tinyclaw) | Shell script (400 LoC) | Stability-first | Claude Code + tmux, WhatsApp, heartbeat, cron, self-healing (1.3K stars) |
| [**Mini-Claw**](https://github.com/htlin222/mini-claw) | Minimalist | Subscription users | Uses Claude Pro/Max or ChatGPT Plus directly in Telegram, zero API cost |
| [**Ralv**](https://ralv.ai/) | 3D agent orchestration | Multi-agent management | StarCraft-like spatial UI for commanding 100+ agents |
| [**GitClaw**](https://github.com/SawyerHood/gitclaw) | GitHub Actions agent | Serverless | Zero-infra OpenClaw via GitHub Issues & Actions |
| [**BankrBot Skills**](https://github.com/BankrBot/openclaw-skills) | DeFi/crypto agent | Web3 traders | Polymarket, token trading, NFTs, on-chain messaging |
| [**ClosedClaw**](https://github.com/asafelobotomy/ClosedClaw) | Desktop GUI fork | GTK users | GTK GUI + Ollama integration + enhanced lite mode |
| [**OpenGlass**](https://github.com/DarlingtonDeveloper/OpenGlass) | Smart glasses | Wearable hardware | Meta Ray-Bans + Gemini Live + OpenClaw real-time AI |
| [**Scallopbot**](https://github.com/tashfeenahmed/scallopbot) | Cost-optimized agent | Budget users | Multi-provider routing, budget controls, voice I/O |
| [**VisionClaw**](https://github.com/sseanliu/VisionClaw) | Smart glasses | Wearable AR | Meta Ray-Ban + Gemini Live + OpenClaw, iOS/Swift (796 stars) |
| **[PinchChat](https://github.com/MarlBurroW/pinchchat)** | Web (PWA) | Available | Open-source webchat UI with ChatGPT-like interface, live tool calls, multi-session, token tracking, streaming, 8 languages, theming |
| [**Debot**](https://github.com/BotMesh/debot) | Rust lightweight | Cost-conscious | Rust+Python, auto conversation compaction, smart LLM router |
| [**NanoClaw (original)**](https://github.com/qwibitai/nanoclaw) | Security-first | Apple container | 500 lines TypeScript, WhatsApp, Anthropic Agent SDK (7K+ stars) |
| [**Autobot**](https://github.com/crystal-autobot/autobot) | Crystal ultra-fast | Speed and security oriented users | 2MB binary, ~5MB RAM, <10ms startup |

---

## Moltbook (AI Social Network)

Created by OpenClaw agent "Clawd Clawderberg" (built by Matt Schlicht, Cofounder of Octane AI).

| Stat | Value |
|------|-------|
| **Launched** | January 28, 2026 |
| **Registered AI agents** | 1.6M+ |
| **Posts & responses** | 7.5M+ AI-generated |
| **Format** | Reddit-style forum for AI agents |
| **Human access** | Read-only observation |

> *"Most interesting place on the internet right now"* — Fortune

- [TechCrunch](https://techcrunch.com/2026/01/30/openclaws-ai-assistants-are-now-building-their-own-social-network/)
- [Fortune](https://fortune.com/2026/01/31/ai-agent-moltbot-clawdbot-openclaw-data-privacy-security-nightmare-moltbook-social-network/)
- [CNBC](https://www.cnbc.com/2026/02/02/openclaw-open-source-ai-agent-rise-controversy-clawdbot-moltbot-moltbook.html)
- [IBM - OpenClaw and the future of AI agents](https://www.ibm.com/think/news/clawdbot-ai-agent-testing-limits-vertical-integration)
- [Proof of Lobster](https://proofoflobster.ai) — Verify if Moltbook profiles are AI-generated, and launch fully on-chain sovereign agents with their own wallets. By Theseus AI Labs. ([GitHub](https://github.com/Theseuschain/proof-of-lobster))

---

## Skills & Plugins

### ClawHub (Official Registry)

- **URL**: [clawhub.ai](https://clawhub.ai/) | **Skills**: 5,705+ | **GitHub**: [openclaw/clawhub](https://github.com/openclaw/clawhub)

### Awesome OpenClaw Skills

- **URL**: [VoltAgent/awesome-openclaw-skills](https://github.com/VoltAgent/awesome-openclaw-skills) | **Skills**: 3,009 curated

### Lobster Workflow Runtime

[Lobster](https://github.com/openclaw/lobster) — typed workflow runtime with resumable approvals. Turns skills/tools into composable pipelines.

### Notable Skills & Plugins

| Skill | Description | Source |
|-------|-------------|--------|
| **Mixpost** | Social media management integration | [ClawHub](https://mixpost.app/blog/openclaw-skill) |
| **AIsa Skills** | Streamlined AI agent deployment | [PheMex](https://phemex.com/news/article/aisa-skills-launches-on-openclaws-plugin-marketplace-streamlining-ai-agent-deployment-57375) |
| **Luma Events** | Search events, RSVP, sync to Google Calendar (no API needed) | [X/@bilbeny](https://x.com/bilbeny/status/2017046033759686929) |
| **QMD Skill** | Cuts token usage by 95% | [X/@milesdeutscher](https://x.com/milesdeutscher/status/2018768974872449100) |
| **Supermemory** | Unlimited memory for OpenClaw | ClawHub |
| **Cognee** | Graph-based memory with auto-recall, semantic search | [GitHub](https://github.com/topoteretes/cognee-integrations/tree/main/integrations/openclaw) \| [npm](https://www.npmjs.com/package/@cognee/cognee-openclaw) |
| **Claude Team** | Spawns visible terminal sessions instead of background | [X/@jlehman_](https://x.com/jlehman_/status/2008644506951053492) |
| **ClawRouter** | Smart LLM router — save 78% on inference costs, 30+ models | [GitHub](https://github.com/BlockRunAI/ClawRouter) |
| **Honcho** | Persistent cross-session memory with user modeling and dual-peer context | [ClawHub](https://clawhub.ai/ajspig/honcho-setup) \| [GitHub](https://github.com/plastic-labs/openclaw-honcho/tree/main/clawhub/honcho-setup) |
| **memory-mem0** | Self-hosted memory plugin using Mem0 for semantic fact extraction. Local Ollama embeddings, Qdrant vector storage, Gemini Flash extraction. | [GitHub](https://github.com/serenichron/openclaw-memory-mem0) |
| **Agent Sessions** | Session browser + analytics + limits tracker for Codex CLI, Claude Code, OpenCode, Gemini CLI (245 stars) | [GitHub](https://github.com/jazzyalex/agent-sessions) |
| **Announcer** | House-wide TTS announcements via AirPlay speakers | [GitHub](https://github.com/odrobnik/announcer-skill) |
| **GitHub Search Skills** | Deep GitHub project analysis and exploration | [GitHub](https://github.com/blessonism/openclaw-search-skills) |
| **Unbrowse** | Self-learning API skill generator — auto-discovers APIs from browser traffic, 100x faster than browser automation | [GitHub](https://github.com/lekt9/unbrowse-openclaw) |
| **Foundry** | Self-writing meta-extension — learns how you work, researches docs, writes new capabilities into itself | [GitHub](https://github.com/lekt9/openclaw-foundry) |
| **Supermemory (Official)** | Official Supermemory integration — perfect memory and recall, auto-stores conversations | [GitHub](https://github.com/supermemoryai/openclaw-supermemory) |
| **AfrexAI Skills** | 13 free business skills: prospect research, cold email, competitor analysis, meeting prep, LinkedIn, ICP builder, CRM, invoicing, SEO, daily briefing, objection handling, email triage, humanizer | [Setup Wizard](https://afrexai-cto.github.io/agent-setup/) \| [Revenue Calculator](https://afrexai-cto.github.io/ai-revenue-calculator/) \| [Context Packs](https://afrexai-cto.github.io/context-packs/) |
| **Claw Earn** | AI-native bounty marketplace — agents earn by completing tasks with on-chain reputation and smart contract escrow | [ClawHub](https://clawhub.ai/aiagentstore/claw-earn) |

### Third-Party Platforms

| Platform | Integration | Description |
|----------|------------|-------------|
| **[LangBot](https://github.com/langbot-app/LangBot)** | Multi-platform | Agentic IM bots with OpenClaw, Dify, n8n, Langflow, Coze |
| **[OpenRouter](https://openrouter.ai/docs/guides/guides/openclaw-integration)** | LLM routing | Access 30+ models with smart routing (`openrouter/<author>/<slug>`) |
| **[You.com](https://you.com/resources/openclaw-integration)** | Search/AI | OpenClaw skill for You.com search and AI integration |
| **[ClawSec](https://github.com/prompt-security/clawsec)** | Security | Complete security skill suite by Prompt Security |
| **[unRAID Community App](https://www.reddit.com/r/unRAID/comments/1qv4tky/openclaw_ai_assistant_gateway_now_available_on/)** | NAS/Server | Official Community Apps template for unRAID |
| **[Expo OpenClaw Chat](https://github.com/brunobar79/expo-openclaw-chat)** | Mobile SDK | React Native / Expo chat SDK for building native iOS/Android OpenClaw clients |
| **[Airstore](https://github.com/beam-cloud/airstore)** | Agent Storage | The filesystem for AI agents — persistent storage layer (89 stars) |

### Install a Skill

```bash
openclaw skill install <skill-name>
```

> Always audit skills before installation. ~15% contain malicious instructions. Use VirusTotal-scanned ClawHub skills only.

---

## Browser Automation

| Mode | Description | Use Case |
|------|-------------|----------|
| **Extension Relay** | Control existing Chrome tabs with logged-in sessions | Personal browsing |
| **OpenClaw-managed** | Isolated automation in dedicated browser | Web scraping, testing |
| **Remote CDP** | Distributed cloud deployments | Scale at cloud level |

Capabilities: CDP, ARIA snapshots, screenshots, tab management, click/type/drag, PDF export, video recording.

- [Browser Docs](https://docs.openclaw.ai/tools/browser)
- [Browser Automation Guide](https://help.apiyi.com/en/openclaw-browser-automation-guide-en.html)

---

## Real-World Use Cases

### Productivity
- **Morning brief**: Weather, calendar, headlines before checking your phone
- **Inbox management**: Process thousands of emails autonomously, unsubscribe from spam
- **Grocery list**: Auto-add items from household texts to shared documents

### Development
- Review PRs from your phone, run tests remotely, merge code
- Multi-instance Claude Code supervised by OpenClaw via Telegram + Tailscale
- Run coding agents while sleeping

### Smart Home
- Control Philips Hue, Elgato, Home Assistant via messaging
- Adjust heating based on weather forecasts
- Security camera monitoring with alerts

### Financial
- Calculate position sizes, manage stop-loss rules
- Trade alert logging and automation
- Integrate with on-chain token deployment and liquidity provisioning on Base (e.g., [PumpClaw](https://pumpclaw.com) via Uniswap V4)

### Creative
- Voice notes to clean journal entries
- Platform-specific content: X threads, LinkedIn posts, blog articles
- Weekly meal planning in Notion (saves 1 hour/week)
- **AI-Powered Daily Digest & Content Pipeline** — Production OpenClaw setup with 20+ cron jobs for automated news aggregation, multi-model content creation, social monitoring, and n8n webhook integration. Hosted on Oracle Cloud Free Tier. By Dr. Gaurav Caprihan.

### Family
- Monitor school WhatsApp groups, filter noise
- Run face recognition on photos, send daily digest to parents

- [25 OpenClaw Use Cases - Hostinger](https://www.hostinger.com/tutorials/openclaw-use-cases)
- [20 Genius Use Cases](https://ucstrategies.com/news/20-genius-openclaw-use-cases-people-are-using-right-now/)
- [33 Automations in 30 Minutes](https://medium.com/@rentierdigital/33-openclaw-automations-you-can-set-up-in-30-minutes-that-start-making-you-money-tonight-f8c3b8a402f1)

---

## Tutorials & Guides

### Getting Started

- [Official Getting Started](https://docs.openclaw.ai/start/getting-started)
- [Codecademy Tutorial (20 min)](https://www.codecademy.com/article/open-claw-tutorial-installation-to-first-chat-setup)
- [freeCodeCamp Full Tutorial](https://www.freecodecamp.org/news/openclaw-full-tutorial-for-beginners/)
- [Master OpenClaw in 30 Minutes](https://creatoreconomy.so/p/master-openclaw-in-30-minutes-full-tutorial)
- [How to Actually Tame It](https://medium.com/activated-thinker/stop-watching-openclaw-install-tutorials-this-is-how-you-actually-tame-it-f3416f5d80bc)
- [Beginner's Guide (5 min)](https://help.apiyi.com/en/openclaw-beginner-guide-en.html)
- [40 Tips & Tricks](https://mlearning.substack.com/p/40-tips-and-tricks-from-first-install-to-production-nanoclaw-nano-claw-openclaw-open-2026-2-1-self-learning-skill-that-actually-work-vps-docker-security-ai-agent-swarm-readme-md-memory-architecture-cron-hearbeat-sessions-slack-telegram-whatsapp)
- [DataCamp - Control Your PC from WhatsApp](https://www.datacamp.com/tutorial/moltbot-clawdbot-tutorial)
- [DEV - Ultimate Guide for Developers 2026](https://dev.to/mechcloud_academy/unleashing-openclaw-the-ultimate-guide-to-local-ai-agents-for-developers-in-2026-3k0h)
- [Macaron - Clean Setup + Verification](https://macaron.im/blog/install-openclaw)
- [BitLaunch - Install on macOS, Linux, Windows](https://bitlaunch.io/blog/install-configure-openclaw/)
- [StackViv - Complete 2026 Guide](https://stackviv.ai/blog/how-to-set-up-openclaw-guide)
- [Habr - Don't Launch Before Reading This](https://habr.com/en/articles/992720/)
- [AI/ML API - Secure Local Docker Setup](https://aimlapi.com/blog/running-openclaw-in-docker-secure-local-setup-and-practical-workflow-guide)
- [OpenClaw/ClawdBot Masterclass](https://blog.dailydoseofds.com/p/openclawclawdbot-masterclass) — In-depth written guide by Akshay Pachaar covering installation, Telegram, skills, cron jobs, scaling
- [NxCode - Complete Guide 2026](https://www.nxcode.io/resources/news/openclaw-complete-guide-2026) — Clawdbot to Moltbot to OpenClaw story, breaking changes, what's next
- [AI Product Playbook - Get Clawdbot Set Up in an Afternoon](https://amankhan1.substack.com/p/how-to-get-clawdbotmoltbotopenclaw) — Practical companion to official docs
- [Complete Guide by Aakash](https://www.news.aakashg.com/p/openclaw-fka-moltbot-fka-clawdbot) — VPS setup, wizard walkthrough, messaging config
- [Jitendra Zaa - Complete Guide](https://www.jitendrazaa.com/blog/ai/clawdbot-complete-guide-open-source-ai-assistant-2026/) — 147K+ stars overview, WhatsApp, API costs, skills
- [AI/ML API - Practical Guide for Developers](https://aimlapi.com/blog/openclaw-a-practical-guide-to-local-ai-agents-for-developers) — Shift from chatbots to autonomous agents
- [Pi: The Minimal Agent Within OpenClaw](https://lucumr.pocoo.org/2026/1/31/pi/) — Armin Ronacher's deep dive into Pi agent architecture

### Reviews

- [AImaker - Is OpenClaw Worth the Hype? 10 Days](https://aimaker.substack.com/p/openclaw-review-setup-guide)
- [AI/ML API - Real-World Use on $5 VPS](https://aimlapi.com/blog/openclaw-review-real-world-use-setup-on-a-5-vps-and-what-actually-works)
- [DEV - I Tried the 'Free' AI Agent — $500 Reality Check](https://dev.to/thegdsks/i-tried-the-free-ai-agent-with-124k-github-stars-heres-my-500-reality-check-2885)

### Cloud Provider Guides

- [DigitalOcean](https://www.digitalocean.com/community/tutorials/how-to-run-openclaw) | [AWS](https://dev.to/brayanarrieta/how-to-set-up-openclaw-ai-on-aws-3a0j) | [AWS Bedrock (Official Sample)](https://github.com/aws-samples/sample-OpenClaw-on-AWS-with-Bedrock) | [Pulumi + Tailscale](https://www.pulumi.com/blog/deploy-openclaw-aws-hetzner/)
- [GCP](https://rizwantheanalyst.com/2026/02/04/openclaw-on-google/) | [Azure](https://techcommunity.microsoft.com/blog/azuredevcommunityblog/complete-guide-to-deploying-openclaw-on-azure-windows-11-virtual-machine/4492001) | [Oracle Free Tier](https://ryanshook.org/blog/posts/openclaw-on-oracle-free-tier-always-on-ai-for-free/)
- [Hostinger](https://www.hostinger.com/tutorials/how-to-set-up-openclaw) | [Alibaba Cloud](https://www.alibabacloud.com/en/campaign/ai-openclaw)
- [Vultr](https://docs.vultr.com/how-to-deploy-openclaw-autonomous-ai-agent-platform) | [Milvus/Slack](https://milvus.io/blog/stepbystep-guide-to-setting-up-openclaw-previously-clawdbotmoltbot-with-slack.md)

### Serverless & Docker

- [Cloudflare Moltworker](https://blog.cloudflare.com/moltworker-self-hosted-ai-agent/) | [Docker - Simon Willison](https://til.simonwillison.net/llms/openclaw-docker)

### Local Hardware

- [Raspberry Pi - ajfisher](https://ajfisher.me/2026/02/03/openclaw-raspberrypi-howto/) | [Adafruit](https://learn.adafruit.com/openclaw-on-raspberry-pi)
- [ESP32-S3 MimiClaw](https://github.com/memovai/mimiclaw) — OpenClaw core on a $5 chip, pure C, no Linux/Node.js
- [PicoClaw](https://github.com/sipeed/picoclaw) — Ultra-lightweight Go agent, 10 MB RAM, $10 RISC-V board, single binary | [CNX Software](https://www.cnx-software.com/2026/02/10/picoclaw-ultra-lightweight-personal-ai-assistant-run-on-just-10mb-of-ram/)
- [Ollama Guide](https://codersera.com/blog/openclaw-ollama-setup-guide-2026/) | [LM Studio](https://codersera.com/blog/openclaw-lm-studio-setup-guide-2026/)
- [vLLM on AMD Free](https://www.amd.com/en/developer/resources/technical-articles/2026/openclaw-with-vllm-running-for-free-on-amd-developer-cloud-.html)

### Integration Guides

- [Slack Integration](https://lumadock.com/tutorials/openclaw-slack-integration) | [Notion Integration](https://www.openclawexperts.io/guides/integrations/how-to-connect-openclaw-to-notion)
- [GitHub PR Automation](https://zenvanriel.nl/ai-engineer-blog/openclaw-github-pr-review-automation-guide/)
- [Tailscale VPN Setup](https://dev.to/nunc/self-hosting-openclaw-ai-assistant-on-a-vps-with-tailscale-vpn-zero-public-ports-35fn)
- [Custom Skill Creation](https://zenvanriel.nl/ai-engineer-blog/openclaw-custom-skill-creation-guide/)
- [OpenRouter Integration](https://openrouter.ai/docs/guides/guides/openclaw-integration) | [DeepSeek via OpenRouter](https://medium.com/@oo.kaymolly/connect-deepseek-to-openclaw-via-openrouter-7eb19ef61a84)
- [Kimi K2.5 + OpenClaw Guide](https://medium.com/coding-nexus/how-to-connect-kimi-k2-5-to-openclaw-clawdbot-bf7ed5a31743) | [Kimi K2.5 Free Setup](https://apidog.com/blog/how-to-use-kimi-k2-5-for-free-with-openclaw/) | [Moonshot Official Docs](https://platform.moonshot.ai/docs/guide/use-kimi-in-openclaw)
- [Kimi K2.5 on Baseten](https://www.baseten.co/blog/openclaw-kimi-k2-5-on-baseten-frontier-agent-performance-with-oss/) | [Kimi on Fireworks AI](https://fireworks.ai/blog/openclaw-using-kimi2p5-on-fireworks-ai)
- [50+ Official Extensions Guide](https://help.apiyi.com/en/openclaw-extensions-ecosystem-guide-en.html)

### Security Guides

- [Secure on Cloudflare](https://medium.com/@williamogou/deploy-openclaw-securely-on-cloudflare) | [Proflead Guide](https://proflead.com/blog/openclaw-install-secure/)
- [Security & Cost Control](https://www.moltbook-ai.com/blog/openclaw-guide-2026) | [Composio Controls](https://composio.dev/blog/secure-openclaw-moltbot-clawdbot-setup)
- [7 Security Best Practices](https://xcloud.host/openclaw-security-best-practices)

### X/Twitter Community Guides

- [@ihtesham2005 - Setup Guide That Should Have Existed](https://x.com/ihtesham2005/status/2019791183296471368)
- [@VittoStack - Security-First Setup on Raspberry Pi via Tailscale](https://x.com/VittoStack/status/2018326274440073499)
- [@JordanLyall - The Security-First Guide I Wish Existed](https://x.com/JordanLyall/status/2019595380963627236)
- [@harshil1712 - How I Setup OpenClaw on Raspberry Pi](https://x.com/harshil1712/status/2018770026975609139)
- [@BillDA - My Safe, Sandboxed Setup for OpenClaw](https://x.com/BillDA/status/2017650241101598872)

### Deep Dives

- [Architecture: OpenClaw vs Claude Code](https://claude-world.com/articles/openclaw-vs-claude-code/)
- [Memory Architecture Explained](https://medium.com/@shivam.agarwal.in/agentic-ai-openclaw-moltbot-clawdbots-memory-architecture-explained-61c3b9697488)
- [How Memory System Works](https://snowan.gitbook.io/study-notes/ai-blogs/openclaw-memory-system-deep-dive)
- [centminmod/explain-openclaw](https://github.com/centminmod/explain-openclaw) - Multi-AI security analysis (73 files)
- [Cron Jobs Automation Guide](https://zenvanriel.nl/ai-engineer-blog/openclaw-cron-jobs-proactive-ai-guide/)
- [Beyond Babel: Bridging AI's Communication Gap with MCP, A2A, and ACP](https://medium.com/@gaurav.caprihan/beyond-babel-bridging-ais-communication-gap-with-mcp-a2a-and-acp-35e348bb4233) — Deep analysis of AI agent interoperability protocols with practical MCP server integration using Melbourne open data. By Dr. Gaurav Caprihan.

---

## Video Tutorials

| Title | Platform | Duration | Topics |
|-------|----------|----------|--------|
| **Master OpenClaw in 30 Minutes** | Creator Economy (YouTube) | 30 min | Safe setup, 5 real use cases, memory |
| **How OpenClaw's Creator Uses AI** | Creator Economy | 1 hour | Full demo with Peter Steinberger |
| **OpenClaw Google Workspace Setup** | YouTube | Medium | Gmail, Calendar, Drive integration |
| **Udemy - OpenClaw on Azure Linux VM** | [Udemy](https://www.udemy.com/course/openclaw/) | Medium | Azure deployment |
| **Udemy - OpenClaw Complete (Japanese)** | [Udemy](https://www.udemy.com/course/openclaw-clawdbot/) | Long | LINE + Docker, comprehensive |
| **OpenClaw Full Tutorial for Beginners** | [freeCodeCamp (YouTube)](https://www.youtube.com/watch?v=n1sfrc-RjyM) | Long | Installation, models, memory, Docker, skills |
| **The Wild Rise of OpenClaw** | [Fireship (YouTube)](https://www.youtube.com/watch?v=ssYt09bCgUY) | Short | History, architecture, why it matters |
| **ClawdBot Is the Most Powerful AI Tool** | [Alex Finn (YouTube)](https://www.youtube.com/watch?v=Qkqe-uRhQJE) | Medium | ClawdBot deep dive, real-world demos |
| **How to Setup OpenClaw in 5 Minutes** | [Julian Goldie (YouTube)](https://www.youtube.com/watch?v=1luvvYcpSJ8) | 5 min | Quick start, beginner-friendly |
| **Clawdbot: Complete Beginner Guide!** | [YouTube](https://www.youtube.com/watch?v=VQiGJRBkkSQ) | Medium | Install, connect to messaging platforms |
| **Full OpenClaw Setup Tutorial** | [YouTube](https://www.youtube.com/watch?v=fcZMmP5dsl4) | Medium | Step-by-step walkthrough, Hostinger VPS |
| **The ONLY OpenClaw Guide You Need** | [YouTube](https://www.youtube.com/watch?v=pjiuQnEVges) | Long | VPS setup, security, best workflows |
| **OpenClaw Course 2026: Beginner to Advanced** | [YouTube](https://www.youtube.com/watch?v=-dThk2fNObk) | Long | Comprehensive beginner-to-advanced course |
| **How to Use & Set up OpenClaw (Docker)** | [YouTube](https://www.youtube.com/watch?v=Zo7Putdga_4) | Medium | Docker on VPS deployment |
| **OpenClaw Tutorial For Beginners (2026)** | [YouTube](https://www.youtube.com/watch?v=Gc4fyY0_8Rc) | Medium | Step-by-step from scratch |
| **This Open-Source AI Agent Is INSANE** | [YouTube](https://m.youtube.com/watch?v=KqTs7QvknDo) | Medium | Review, Live Canvas, A2UI demo |
| **ClawCon SF: Live Interviews** | [YouTube](https://www.youtube.com/watch?v=jMnLqGU-Ds4) | Long | Builder interviews, demos from ClawCon |
| **OpenClaw, Moltbook and the Rise of Personal AI** | [YouTube](https://www.youtube.com/watch?v=LqT4n7XQHDo) | Medium | AI social network, personal agents |
| **ClawCon 2026 Raw Footage** | [YouTube](https://www.youtube.com/watch?v=gT98KNkoLGM) | Long | Community event, builder demos |

---

## Courses & Learning Platforms

| Platform | URL | Cost | Description |
|----------|-----|------|-------------|
| **OpenClaw Academy** | [openclaw.academy](https://openclaw.academy/) | **Free** | All courses free, no signup, interactive quizzes |
| **OpenClaw Academy Viewer** | [learn.openclaw.academy](https://learn.openclaw.academy/) | **Free** | Interactive course viewer |
| **freeCodeCamp** | [YouTube](https://www.freecodecamp.org/news/openclaw-full-tutorial-for-beginners/) | **Free** | Comprehensive 1-hour course |
| **Codecademy** | [Tutorial](https://www.codecademy.com/article/open-claw-tutorial-installation-to-first-chat-setup) | **Free** | 20-minute install guide |
| **GitHub Course** | [kiankyars/openclawcourse](https://github.com/kiankyars/openclawcourse) | **Free** | 1-hour crash course |
| **Udemy** | [Azure VM Course](https://www.udemy.com/course/openclaw/) | Paid | Azure Linux VM deployment |
| **Gripsy Learn** | [OpenClaw Mastery](https://gripsy.com.au/learn/openclaw/) | Free/Paid | 11-module course: setup, skills, multi-model, security, automation. Quizzes & certificates. |

---

## Events & Hackathons

| Event | Date | Location | Details |
|-------|------|----------|---------|
| **[ClawCon: 1st OpenClaw SF Show & Tell](https://trymimetic.com/events/sf/clawcon-1st-openclaw-sf-show-tell-open-registration-feb-2026)** | Feb 5, 2026 | San Francisco | Builder demos, live interviews |
| **[OpenClaw Unhackathon](https://sf.aitinkerers.org/p/openclaw-unhackathon)** | Feb 7, 2026 | San Francisco (AI Tinkerers) | Build & compete, 2-6 PM |
| **[OpenClaw Micro Hackathon](https://www.eventbrite.co.uk/e/openclaw-micro-hackathon-tickets-1982409167184)** | Feb 7, 2026 | Hong Kong (Dim Sum Labs) | Community hackathon |
| **[OpenClaw/Moltbook Hackathon at MIT](https://x.com/SantanuB01/status/2018608892591395079)** | Feb 3, 2026 | MIT, Cambridge | Serious coders, agent building |
| **[Circle/USDC Hackathon on Moltbook](https://www.circle.com/blog/openclaw-usdc-hackathon-on-moltbook)** | 2026 | Online (Moltbook) | USDC, onchain payments, cross-chain flows |

---

## Community

| Platform | URL | Members | Best For |
|----------|-----|---------|----------|
| **Discord** | [OpenClaw Discord](https://docs.openclaw.ai/channels/discord) | 8,000+ | Quick questions, troubleshooting |
| **Discourse (CoClaw)** | [coclaw.com](https://coclaw.com/) | 15,000+ | Long-form discussion, bug reports |
| **X/Twitter Community** | [OpenClaw Community](https://x.com/i/communities/2013441068562325602) | 12,200+ | News, updates, demos |
| **GitHub Issues** | [openclaw/openclaw/issues](https://github.com/openclaw/openclaw/issues) | N/A | Bug reports, feature requests |
| **GitHub Discussions** | [openclaw/openclaw/discussions](https://github.com/openclaw/openclaw/discussions) | N/A | Q&A, show-and-tell |
| **Hacker News** | [Search](https://hn.algolia.com/?q=openclaw) | N/A | Technical discussion |

---

## Media Coverage

### Mainstream

- [CNBC - From Clawdbot to Moltbot to OpenClaw](https://www.cnbc.com/2026/02/02/openclaw-open-source-ai-agent-rise-controversy-clawdbot-moltbot-moltbook.html)
- [TechCrunch - AI assistants building their own social network](https://techcrunch.com/2026/01/30/openclaws-ai-assistants-are-now-building-their-own-social-network/)
- [Fortune - 'Most interesting place on the internet'](https://fortune.com/2026/01/31/ai-agent-moltbot-clawdbot-openclaw-data-privacy-security-nightmare-moltbook-social-network/)
- [VentureBeat - What the OpenClaw moment means for enterprises](https://venturebeat.com/technology/what-the-openclaw-moment-means-for-enterprises-5-big-takeaways)
- [Forbes - OpenClaw, Moltbook & The Birth of a Machine Society](https://www.forbes.com/sites/jonmarkman/2026/02/06/openclaw-moltbook--the-birth-of-a-machine-society/)
- [Bloomberg - AI Sensation, Security a Work in Progress](https://www.bloomberg.com/news/articles/2026-02-04/openclaw-s-an-ai-sensation-but-its-security-a-work-in-progress)
- [Axios - Moltbook highlights how far behind AI security is](https://www.axios.com/2026/02/03/moltbook-openclaw-security-threats)
- [BBC Science Focus - Calls, bills and life admin taken care of](https://www.sciencefocus.com/future-technology/openclaw-first-agentic-ai)
- [PCMag - Hot New AI Agent, But Is It Safe?](https://www.pcmag.com/news/openclaw-is-the-hot-new-ai-agent-but-is-it-safe-to-use)
- [CNET - New AI Assistant Acts Like Your Digital Servant](https://www.cnet.com/tech/services-and-software/from-clawdbot-to-moltbot-to-openclaw/)
- [Tom's Guide - Viral AI assistant that lives on your device](https://www.tomsguide.com/ai/openclaw-is-the-viral-ai-assistant-that-lives-on-your-device-what-you-need-to-know)
- [Business Insider - Security Researchers Worried](https://www.businessinsider.com/openclaw-moltbook-cybersecurity-risks-researchers-ai-2026-2)
- [MacStories - What the Future of Personal AI Assistants Looks Like](https://www.macstories.net/stories/clawdbot-showed-me-what-the-future-of-personal-ai-assistants-looks-like/)
- [Nature - OpenClaw AI chatbots are running amok](https://www.nature.com/articles/d41586-026-00439-0)
- [The Register - Clouds rush to deliver OpenClaw](https://www.theregister.com/2026/02/04/cloud_hosted_openclaw/)

### Security

- [The Register - Security issues](https://www.theregister.com/2026/02/02/openclaw_security_issues/) | [Skills marketplace leak](https://www.theregister.com/2026/02/05/openclaw_skills_marketplace_leaky_security/)
- [Hacker News - One-Click RCE](https://thehackernews.com/2026/02/openclaw-bug-enables-one-click-remote.html) | [VirusTotal scanning](https://thehackernews.com/2026/02/openclaw-integrates-virustotal-scanning.html)
- [Cisco - Security Nightmare](https://blogs.cisco.com/ai/personal-ai-agents-like-openclaw-are-a-security-nightmare)
- [Bitdefender - Malicious Skills](https://www.bitdefender.com/en-us/blog/labs/helpful-skills-or-hidden-payloads-bitdefender-labs-dives-deep-into-the-openclaw-malicious-skill-trap)
- [Snyk - 280+ Leaky Skills](https://snyk.io/blog/openclaw-skills-credential-leaks-research/)
- [CrowdStrike - What Security Teams Need to Know](https://www.crowdstrike.com/en-us/resources/crowdcasts/what-security-teams-need-to-know-about-openclaw/)
- [VentureBeat - OpenClaw proves agentic AI works, security model doesn't](https://venturebeat.com/security/openclaw-agentic-ai-security-risk-ciso-guide)
- [Censys - 135,000+ AI Instances Exposed](https://censys.com/blog/openclaw-in-the-wild-mapping-the-public-exposure-of-a-viral-ai-assistant)
- [runZero - CVE-2026-25253 RCE Vulnerability](https://www.runzero.com/blog/openclaw/)
- [SiliconANGLE - Tens of thousands of systems exposed](https://siliconangle.com/2026/02/09/tens-thousands-openclaw-systems-exposed-due-misconfiguration-known-exploits/)
- [Cyera - How AI Adoption Outpaced Security Boundaries](https://www.cyera.com/research-labs/the-openclaw-security-saga-how-ai-adoption-outpaced-security-boundaries)
- [Astrix - First AI Agent Security Nightmare](https://astrix.security/learn/blog/openclaw-moltbot-the-rise-chaos-and-security-nightmare-of-the-first-real-ai-agent/)
- [VirusTotal Blog - Detecting Malicious OpenClaw Skills](https://blog.virustotal.com/2026/02/)
- [Bitdefender - Enterprise Network Technical Advisory](https://businessinsights.bitdefender.com/technical-advisory-openclaw-exploitation-enterprise-networks)
- [Bitsight - Risks of Exposed AI Agents](https://www.bitsight.com/blog/openclaw-ai-security-risks-exposed-instances)

### Global & Enterprise

- [Rest of World - Moltbot Finds Fans in China and Silicon Valley](https://restofworld.org/2026/moltbot-china-ai-agent/)
- [Trending Topics EU - Weekend Project Became Open-Source Sensation](https://www.trendingtopics.eu/openclaw-2-million-visitors-in-a-week/)
- [SlashGear - The Hottest New AI Agent Is Here](https://www.slashgear.com/2095067/openclaw-ai-agent-popularity-security-concerns/)
- [Wikipedia - OpenClaw](https://en.wikipedia.org/wiki/OpenClaw)
- [Wikipedia - Moltbook](https://en.wikipedia.org/wiki/Moltbook)
- [The Conversation - Why DIY AI Agent Feels New But Isn't](https://theconversation.com/openclaw-and-moltbook-why-a-diy-ai-agent-and-social-media-for-bots-feel-so-new-but-really-arent-274744)
- [Citrix - OpenClaw and Moltbook preview corporate AI governance changes](https://www.citrix.com/blogs/2026/02/04/openclaw-and-moltbook-preview-the-changes-needed-with-corporate-ai-governance/)

### Opinion

- [XDA - Please stop using OpenClaw](https://www.xda-developers.com/please-stop-using-openclaw/)
- [Pragmatic Engineer - "I ship code I don't read"](https://newsletter.pragmaticengineer.com/p/the-creator-of-clawd-i-ship-code)
- [Scientific American - AI Agent That Runs Your Computer](https://www.scientificamerican.com/article/moltbot-is-an-open-source-ai-agent-that-runs-your-computer/)

### Naming History

- [Forkable - Clawdbot, Moltbot, OpenClaw... oh my!](https://www.forkable.io/p/clawdbot-moltbot-openclaw-oh-my)
- [HN - OpenClaw Renamed Again](https://news.ycombinator.com/item?id=46820783)
- [DEV - From Moltbot to OpenClaw](https://dev.to/sivarampg/from-moltbot-to-openclaw-when-the-dust-settles-the-project-survived-5h6o)

---

## Common Issues & Troubleshooting

| Issue | Cause | Fix |
|-------|-------|-----|
| Crash during onboarding | < 2 GB RAM | Upgrade to 4 GB+ RAM |
| API key not working | Incorrect format or expired | Re-enter via `openclaw auth set` |
| Telegram not connecting | Using Cloudflare Workers | Switch to VPS (needs persistent connection) |
| Slow inference (3.5s/token) | CPU-only with large model | Use smaller model or add GPU |
| Port conflict on 18789 | Another service using port | `openclaw gateway --port 18790` |
| Docker sandbox issues | Permissions or config | Run `openclaw doctor` |
| Skills not loading | Corrupt installation | Reinstall skill |
| Messages lost between channels | Known bug | Update to latest version |
| High token consumption | ~35,600 tokens per message overhead | Reduce workspace files |
| Rate limiting (#5159) | Aggressive retry loops | Update (exponential backoff fix) |

### Diagnostic Commands

```bash
openclaw doctor                    # Common issues
openclaw security audit --deep     # Deep security scan
openclaw security audit --fix      # Auto-fix safe issues
node --version                     # Must be 22+
```

---

## Cost Calculator & Optimization

- [OpenClaw Cost Calculator](https://calculator.vlvt.sh/)
- [API Usage and Costs Docs](https://docs.openclaw.ai/reference/api-usage-costs)
- [eesel.ai Pricing Guide](https://www.eesel.ai/blog/openclaw-ai-pricing)
- [Deploy Cost Guide: $0-8/month](https://yu-wenhao.com/en/blog/2026-02-01-openclaw-deploy-cost-guide/)
- [Cost Governor](https://github.com/AtlasPA/openclaw-cost-governor) — First OpenClaw skill with x402 agent payments. Track LLM costs in real-time, enforce budget limits with circuit breakers, enable AI agents to autonomously pay for Pro features (0.5 USDT/month).

### Monthly Budget Targets

| Budget | Strategy |
|--------|----------|
| **$0** | Oracle Cloud + Gemini free tier + Ollama |
| **$6** | Agent37 ($1) + Claude Haiku ($5) |
| **$19** | Hetzner ($4) + mixed models ($15) |
| **$50** | DigitalOcean ($12) + Claude Sonnet ($38) |
| **$100** | Managed hosting ($24) + heavy API ($76) |

---

## Key Contributors

| Contributor | Role | GitHub |
|-------------|------|--------|
| **Peter Steinberger** | Creator | [@steipete](https://github.com/steipete) |
| **Mario Zechner** | Pi creator, security pen-tester | [@badlogicc](https://github.com/badlogicc) |
| **Maxim Vovshin** | Blogwatcher skill | [@Hyaxia](https://github.com/Hyaxia) |
| **Nacho Iacovino** | Location parsing | [@nachoiacovino](https://github.com/nachoiacovino) |
| **600+ contributors** | Community | [All contributors](https://github.com/openclaw/openclaw/graphs/contributors) |

---

## Related Repositories

| Repository | Description |
|------------|-------------|
| [openclaw/openclaw](https://github.com/openclaw/openclaw) | Main repository (195K+ stars) |
| [openclaw/clawhub](https://github.com/openclaw/clawhub) | Official skill directory |
| [openclaw/lobster](https://github.com/openclaw/lobster) | Typed workflow runtime |
| [cloudflare/moltworker](https://github.com/cloudflare/moltworker) | Cloudflare Workers adaptation |
| [VoltAgent/awesome-openclaw-skills](https://github.com/VoltAgent/awesome-openclaw-skills) | 3,009 curated skills |
| [centminmod/explain-openclaw](https://github.com/centminmod/explain-openclaw) | Deep security analysis (73 files) |
| [lunarpulse/openclaw-mcp-plugin](https://github.com/lunarpulse/openclaw-mcp-plugin) | MCP server integration |
| [essamamdani/openclaw-coolify](https://github.com/essamamdani/openclaw-coolify) | Coolify PaaS template |
| [phioranex/openclaw-docker](https://github.com/phioranex/openclaw-docker) | Docker deployment configs |
| [gavrielc/nanoclaw](https://github.com/gavrielc/nanoclaw) | Security-first alternative |
| [BlockRunAI/ClawRouter](https://github.com/BlockRunAI/ClawRouter) | Smart LLM router (save 78% on costs) |
| [langbot-app/LangBot](https://github.com/langbot-app/LangBot) | Multi-platform IM bot with OpenClaw |
| [kiankyars/openclawcourse](https://github.com/kiankyars/openclawcourse) | 1-hour crash course |
| [memovai/mimiclaw](https://github.com/memovai/mimiclaw) | Implements OpenClaw's core principles (ReAct agent loop, persistent memory, tool use, Telegram) in pure C on a $5 ESP32-S3 — no Linux, no Node.js, no server required |
| [nearai/ironclaw](https://github.com/nearai/ironclaw) | OpenClaw-inspired implementation in Rust focused on privacy and security, by NEAR AI |
| [SawyerHood/gitclaw](https://github.com/SawyerHood/gitclaw) | OpenClaw on GitHub Actions — every issue becomes an AI chat thread, no servers needed |
| [BankrBot/openclaw-skills](https://github.com/BankrBot/openclaw-skills) | DeFi/crypto skill library — Polymarket, token trading, NFTs, on-chain messaging |
| [clawd800/pumpclaw](https://github.com/clawd800/pumpclaw) | Token launcher for AI agents on Base — Uniswap V4 pools, on-chain registry, CLI and Farcaster deploy bot |
| [SamurAIGPT/awesome-openclaw](https://github.com/SamurAIGPT/awesome-openclaw) | Community-curated list of OpenClaw resources, tools, and tutorials |
| [nearai/private-ml-sdk](https://github.com/nearai/private-ml-sdk) | Run LLMs and agents on TEEs (NVIDIA GPU TEE, Intel TDX) for private inference |
| [eltociear/awesome-molt-ecosystem](https://github.com/eltociear/awesome-molt-ecosystem) | Curated list of Molt ecosystem services — Moltbook, MoltCities, Molthunt, MoltMatch |
| [kelkalot/moltbook-observatory](https://github.com/kelkalot/moltbook-observatory) | Data collection from Moltbook — tracking agents, posts, and trends over time |
| [grp06/openclaw-studio](https://github.com/grp06/moltbot-agent-ui) | Visual agent management UI with cron jobs, tool extraction, mentions |
| [prompt-security/clawsec](https://github.com/prompt-security/clawsec) | Complete security skill suite for OpenClaw family (Moltbot, Clawdbot, clones) |
| [aws-samples/sample-OpenClaw-on-AWS-with-Bedrock](https://github.com/aws-samples/sample-OpenClaw-on-AWS-with-Bedrock) | AWS-native deployment using Amazon Bedrock — no multi-API key management |
| [constansino/moltbot_qq](https://github.com/constansino/moltbot_qq) | QQ messaging channel support via OneBot v11 (WebSocket) |
| [sipeed/picoclaw](https://github.com/sipeed/picoclaw) | Ultra-lightweight AI assistant in Go — 10 MB RAM, $10 RISC-V board, 1s boot, single binary (5K stars) |
| [HKUDS/nanobot](https://github.com/HKUDS/nanobot) | Ultra-lightweight OpenClaw alternative in Python — 4K lines, 45 MB RAM, 0.8s cold start, MCP-native (15K+ stars) |
| [brunobar79/expo-openclaw-chat](https://github.com/brunobar79/expo-openclaw-chat) | Expo / React Native chat SDK for building native iOS/Android OpenClaw clients |
| [archestra-ai/archestra](https://github.com/archestra-ai/archestra) | OpenClaw for Enterprise — agentic security, MCP registry & orchestrator, A2A (3.5K stars) |
| [abhi1693/openclaw-mission-control](https://github.com/abhi1693/openclaw-mission-control) | Mission control with RBAC, Kanban board, War Room, transcripts, Telegram outputs |
| [turmyshevd/openclawgotchi](https://github.com/turmyshevd/openclawgotchi) | AI Tamagotchi on Raspberry Pi — agentic life-form with an E-Ink face |
| [DarlingtonDeveloper/OpenGlass](https://github.com/DarlingtonDeveloper/OpenGlass) | Real-time AI-powered smart glasses — Meta Ray-Bans + Gemini Live + OpenClaw |
| [deeqyaqub1-cmd/zero-rules-openclaw](https://github.com/deeqyaqub1-cmd/zero-rules-openclaw) | Deterministic engine for OpenClaw — skips LLM for math/time/files, saves 50-70% on tokens |
| [RyanLisse/engram](https://github.com/RyanLisse/engram) | Unified multi-agent memory for OpenClaw — local-first, Convex-synced, agent-native |
| [asafelobotomy/ClosedClaw](https://github.com/asafelobotomy/ClosedClaw) | OpenClaw fork with GTK GUI, Ollama integration, and enhanced lite mode |
| [MarlBurroW/pinchchat](https://github.com/MarlBurroW/pinchchat) | Sleek, dark-themed webchat UI for OpenClaw agents |
| [jazzyalex/agent-sessions](https://github.com/jazzyalex/agent-sessions) | Session browser + analytics + limits tracker for Codex CLI, Claude Code, OpenCode, Gemini CLI (245 stars) |
| [openclaw/barnacle](https://github.com/openclaw/barnacle) | Official OpenClaw companion bot — persistent utility bot |
| [openclaw/trust](https://github.com/openclaw/trust) | Official open threat model with community-contributed risk assessments and mitigations |
| [freema/openclaw-mcp](https://github.com/freema/openclaw-mcp) | MCP server bridging Claude.ai to self-hosted OpenClaw with OAuth 2.1 authentication |
| [beam-cloud/airstore](https://github.com/beam-cloud/airstore) | The filesystem for AI agents — persistent agent storage layer (89 stars) |
| [sseanliu/VisionClaw](https://github.com/sseanliu/VisionClaw) | Real-time AI assistant for Meta Ray-Ban smart glasses — voice + vision + agentic actions, iOS/Swift (796 stars) |
| [MarlBurroW/pinchchat](https://github.com/MarlBurroW/pinchchat) | Open-source webchat UI for OpenClaw — ChatGPT-like interface, live tool calls, multi-session, token tracking, streaming, PWA, 8 languages, theming |
| [qwibitai/nanoclaw](https://github.com/qwibitai/nanoclaw) | Original NanoClaw — 500 lines TypeScript, Apple containers for security, WhatsApp, Anthropic Agent SDK (7K+ stars) |
| [SeyZ/clawbands](https://github.com/SeyZ/clawbands) | Security middleware — intercepts tool execution, human-in-the-loop approval for dangerous actions |
| [newtro/ClawGuard](https://github.com/newtro/ClawGuard) | Permission manifests, runtime enforcement, sandboxing, and audit logging for OpenClaw skills |
| [backslash-security/Claw-Hunter](https://github.com/backslash-security/Claw-Hunter) | MDM-ready detection and monitoring of shadow OpenClaw agents on managed endpoints |
| [tech4242/aquaman](https://github.com/tech4242/aquaman) | Credential isolation proxy — API keys never enter the agent process, injected via UDS from Keychain/1Password/Vault |
| [BotMesh/debot](https://github.com/BotMesh/debot) | Rust+Python lightweight alternative — auto conversation compaction, intelligent LLM router |
| [lekt9/unbrowse-openclaw](https://github.com/lekt9/unbrowse-openclaw) | Self-learning API skill generator — auto-discovers APIs from browser traffic, 100x faster |
| [lekt9/openclaw-foundry](https://github.com/lekt9/openclaw-foundry) | Self-writing meta-extension — learns how you work, writes new capabilities into itself (97 stars) |
| [supermemoryai/openclaw-supermemory](https://github.com/supermemoryai/openclaw-supermemory) | Official Supermemory integration — perfect memory and recall for OpenClaw agents |
| [clawdeckio/clawdeck](https://github.com/clawdeckio/clawdeck) | Open-source mission control dashboard — Kanban, agent monitoring, REST API |
| [Ramsbaby/openclaw-self-healing](https://github.com/Ramsbaby/openclaw-self-healing) | 4-tier autonomous self-healing system — Claude Code as "emergency doctor" for Gateway |
| [willbullen/openclaw-docker](https://github.com/willbullen/openclaw-docker) | Security-hardened Docker Compose — non-root, dropped caps, read-only rootfs, MCP isolation |
| [coollabsio/openclaw](https://github.com/coollabsio/openclaw) | Auto-built Docker images by CoolLabs — multi-arch, nginx + basic auth, 6-hour rebuild cycle |
| [hesamsheikh/awesome-openclaw-usecases](https://github.com/hesamsheikh/awesome-openclaw-usecases) | Real-life OpenClaw use cases — Reddit digests, X analysis, YouTube summaries, multi-agent coordination |
| [theonlyhennygod/zeroclaw](https://github.com/theonlyhennygod/zeroclaw) | ZeroClaw — pure Rust, 3.4 MB binary, <10ms startup, 22+ providers, swappable trait-based architecture |
| [jlia0/tinyclaw](https://github.com/jlia0/tinyclaw) | TinyClaw — OpenClaw in ~400 lines of shell script, Claude Code + tmux, self-healing, WhatsApp (1.3K stars) |
| [crystal-autobot/autobot](https://github.com/crystal-autobot/autobot) | Autobot — Ultra-efficient personal AI assistant in Crystal, 2 MB binary, ~5 MB RAM, <10ms startup, kernel-enforced sandboxing |
| [htlin222/mini-claw](https://github.com/htlin222/mini-claw) | Mini-Claw — minimalist OpenClaw alternative using Claude Pro/Max or ChatGPT Plus directly in Telegram |
| [Theseuschain/proof-of-lobster](https://github.com/Theseuschain/proof-of-lobster) | Proof of Lobster — verify Moltbook profiles as AI/human, launch on-chain sovereign agents with wallets |

---

## Kubernetes & Helm Charts

| Chart | Source | Features |
|-------|--------|----------|
| **serhanekicii/openclaw-helm** | [GitHub](https://github.com/serhanekicii/openclaw-helm) | Built on bjw-s app-template |
| **waTeim/openclaw-helm** | [GitHub](https://github.com/waTeim/openclaw-helm) | Multi-channel support |
| **khal3d/openclaw** | [GitHub](https://github.com/khal3d/openclaw) | Docker & HELM deployment |

- [Running OpenClaw on Kubernetes - Metoro Blog](https://metoro.io/blog/openclaw-kubernetes)

---

## PicoClaw (RISC-V / Ultra-Lightweight)

[PicoClaw](https://github.com/sipeed/picoclaw) is an ultra-lightweight AI assistant written in Go that runs on less than **10 MB RAM**. Boots in **1 second** on a **$10 RISC-V board** (Sipeed LicheeRV Nano with SOPHGO SG2002). Single binary — no Docker, no Node.js, no Python required.

| Spec | Detail |
|------|--------|
| **Language** | Go |
| **RAM** | < 10 MB |
| **Hardware** | Sipeed LicheeRV Nano ($10), also ARM64 and x86-64 |
| **Boot Time** | ~1 second |
| **Stars** | 5,000+ (gained 5K in 4 days) |
| **Messaging** | Telegram, Discord, QQ, DingTalk |
| **AI Providers** | Gemini, Anthropic, OpenRouter, local LLMs |
| **Features** | Persistent memory, scheduled tasks, web search, multi-provider routing |

> Sipeed claims PicoClaw matches OpenClaw's core features with 1% of the code and 1% of the memory. 95% of the codebase was AI-generated.

- [GitHub - sipeed/picoclaw](https://github.com/sipeed/picoclaw)
- [CNX Software - PicoClaw runs on just 10MB of RAM](https://www.cnx-software.com/2026/02/10/picoclaw-ultra-lightweight-personal-ai-assistant-run-on-just-10mb-of-ram/)

---

## Enterprise Considerations

> *"It is not enterprise software. There is no promise of quality, no vendor support, no SLA… it ships without authentication enforced by default."* — **Gartner**

### Risk Assessments

- [Vectra - When Automation Becomes a Digital Backdoor](https://www.vectra.ai/blog/clawdbot-to-moltbot-to-openclaw-when-automation-becomes-a-digital-backdoor)
- [Palo Alto Networks](https://www.paloaltonetworks.com/) — OpenClaw presents a "lethal trifecta": access to private data + exposure to untrusted content + ability to communicate externally while retaining memory
- [Cyera - How AI Adoption Outpaced Security Boundaries](https://www.cyera.com/research-labs/the-openclaw-security-saga-how-ai-adoption-outpaced-security-boundaries)

### Enterprise Alternatives

For organizations needing compliance, SLAs, and vendor support, consider:
- **Kilo Claw** — SSO, audit logs, pay-as-you-go
- **ClawCloud Business** — $129/mo, dedicated resources
- **OpenClaw Hosting Business** — Team/Business tiers
- Self-hosted with **NanoClaw** (security-first fork) in isolated containers

---

## China & Global Adoption

OpenClaw has seen explosive adoption in China with support from major tech companies.

| Company | Integration | Details |
|---------|------------|---------|
| **Alibaba Cloud** | [Simple Application Server](https://www.alibabacloud.com/en/campaign/ai-openclaw) | 19 regions, from $4/mo |
| **Tencent Cloud** | Lighthouse Service | One-click install |
| **ByteDance** | Volcano Engine | Cloud hosting support |

### v2026.2.2 — China Support

- Native **Feishu** (飞书) and **Lark** support — first official Chinese chat client integration
- [EvolutionAI Hub - OpenClaw v2026.2.2](https://evolutionaihub.com/openclaw-2026-2-2-ai-agent-framework-onchain/)

### Coverage

- [Rest of World - Moltbot Finds Fans in China and Silicon Valley](https://restofworld.org/2026/moltbot-china-ai-agent/)
- [China's Tech Giants Opening Doors to OpenClaw](https://dnyuz.com/2026/02/05/chinas-tech-giants-are-opening-their-doors-to-openclaw-the-chinese-internet-is-lapping-it-up/)

---

## Latest Releases

| Version | Date | Key Changes |
|---------|------|-------------|
| **v2026.2.12** | Feb 12, 2026 | 40+ security vulnerabilities patched, SSRF protection, prompt injection prevention, directory traversal fixes, enhanced sandbox isolation |
| **v2026.2.9** | Feb 9, 2026 | iOS alpha node app, device pairing/phone control plugins, Grok (xAI) web search, agent management RPC |
| **v2026.2.6** | Feb 7, 2026 | Anthropic Opus 4.6 support, Voyage AI native memory support, built-in safety scanner for skills |
| **v2026.2.3** | Feb 5, 2026 | Performance improvements, bug fixes |
| **v2026.2.2** | Feb 2026 | Feishu/Lark support, onchain integrations |
| **v2026.2.1** | Feb 2026 | Security hardening, streaming stability, path traversal fixes |
| **v2026.1.30** | Jan 30, 2026 | CVE-2026-25593 & CVE-2026-25475 patches |
| **v2026.1.29** | Jan 29, 2026 | CVE-2026-24763, CVE-2026-25253 patches, VirusTotal scanning |
| **v2026.1.24-1** | Jan 24, 2026 | DigitalOcean 1-Click base version |

---

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=openclaw/openclaw,facebook/react,vercel/next.js,torvalds/linux,kubernetes/kubernetes&type=Date)](https://star-history.com/#openclaw/openclaw&facebook/react&vercel/next.js&torvalds/linux&kubernetes/kubernetes&Date)

### Growth Comparison

| Project | Stars | Age | Time to 100K Stars | Stars/Day (avg) |
|---------|-------|-----|---------------------|-----------------|
| **OpenClaw** | **195K** | **~4 months** | **~2 days** | **~1,625** |
| React | 242K | 12 years | ~8 years | ~55 |
| Linux | 216K | 15 years | ~12 years | ~39 |
| Next.js | 137K | 9 years | ~8 years | ~41 |
| Kubernetes | 120K | 11 years | ~10 years | ~29 |
| Vue | 52K | 7 years | — | ~20 |

> OpenClaw reached 100K stars in ~2 days (Jan 29-30, 2026) — a feat that took React ~8 years, Linux ~12 years, and Kubernetes ~10 years. Peak growth hit **710 stars/hour** on Jan 30, 2026. It is the fastest GitHub repo to reach 100K stars in history.

---

## Website

This repo powers **[openclawsearch.com](https://openclawsearch.com)** — the website automatically renders this README, so any change here updates the site.

- [Ecosystem Directory](https://openclawsearch.com/directory.html) — 80+ curated projects built with OpenClaw

## Contributing

Contributions welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

- Add a resource via pull request to `README.md` (auto-updates the website)
- Add a project to the [Ecosystem Directory](https://openclawsearch.com/directory.html) via pull request to `directory.html`
- Report broken links via issues
- Suggest new sections or improvements

---

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

This list is released under CC0 1.0 Universal (Public Domain).
