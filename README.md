<div align="center">

# Hey, I'm Ramil 👋

**.NET Developer · AI Enthusiast · Building things that work**

[![Telegram](https://img.shields.io/badge/Telegram-@ekleziast56-2CA5E0?style=flat-square&logo=telegram&logoColor=white)](https://t.me/ekleziast56)
[![GitHub](https://img.shields.io/badge/GitHub-ekleziast-181717?style=flat-square&logo=github)](https://github.com/ekleziast)

</div>

---

### 🧑‍💻 About me

- 25 y.o. backend developer from Russia, currently based in Vietnam 🇻🇳
- Building production Telegram bots, AI-powered services, and open-source tools
- Contributing to [OpenClaw](https://github.com/openclaw/openclaw) — an open-source AI assistant platform
- Arctic Code Vault Contributor 🏔️

### 🔧 Tech Stack

**Backend** — C#, .NET 8, ASP.NET Core, Entity Framework Core, SignalR, Redis, PostgreSQL  
**AI/ML** — Stable Diffusion, ComfyUI, RunPod, Python  
**Frontend** — TypeScript, React, Next.js, Payload CMS  
**Blockchain** — TON SDK, smart contracts, sniper bots  
**Infra** — Docker Compose, Nginx, GitHub Actions, Linux, CUDA  
**Voice & AI Agents** — OpenClaw, Whisper, Piper TTS, ElevenLabs

### 🚀 What I build

#### 🎨 AI Image Generation Platform

My main project — a production SaaS Telegram bot for AI image generation with a full distributed backend:

- **Distributed GPU nodes** — worker nodes connect to the server via **SignalR WebSockets**, pick tasks from a queue, process them on GPU, and report results back in real-time. Nodes auto-reconnect and requeue interrupted tasks
- **Redis pub/sub task pipeline** — multi-stage async processing: `create → enqueue → dispatch → process → complete/error`. Each stage is a separate queue worker, making the system resilient and observable
- **Dynamic ComfyUI workflow builder** — server-side workflow composition with a builder pattern: injects images, masks, LoRA configs, and model parameters into ComfyUI API format on the fly
- **Multi-provider payments** — Stripe, YooKassa, Telegram Stars (XTR), TON wallet — unified payment processing with webhook handlers and subscription management
- **Admin dashboard** — advanced analytics: revenue by period, churn rate, cohort analysis, UTM attribution with full referral tree traversal (up to 10 levels), language segmentation, time-to-first-purchase stats, processing mode trends
- **Subscription & credit system** — tiered plans, daily claims, credit-based usage tracking, giveaways
- **Scheduled jobs** — Quartz-based health checks, cleanup tasks, payment processing
- **Full Docker Compose stack** — API + WebApp + Admin Panel + Payload CMS website + PostgreSQL + Redis + MongoDB + Nginx with SSL

> C# / .NET 8 / SignalR / Redis / PostgreSQL / Docker / Quartz / EF Core

#### 🐦 Kiwi Voice

Voice interface for AI assistants — wake word detection, speaker recognition, streaming TTS, real-time barge-in. Python.

#### 🔗 Other projects

- **RunPod Infra** — custom Docker images for ComfyUI on serverless GPU
- **Blockchain tools** — TON wallet integrations & trading bots in C#
- **Open Source** — contributions to [OpenClaw](https://github.com/openclaw/openclaw), ComfyUI ecosystem, TonSdk.NET

### 📊 Stats

<div align="center">
  <img src="./profile/stats.svg" height="165" alt="GitHub Stats" />
  <img src="./profile/top-langs.svg" height="165" alt="Top Languages" />
</div>

---

<div align="center">
  <i>I like shipping things, not talking about shipping things.</i>
</div>
