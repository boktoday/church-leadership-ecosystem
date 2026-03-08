# 🕍 Church Leadership Ecosystem

**A Multi-Agent AI Support System for Religious Leaders**

---

## What Is This?

This is a **comprehensive multi-agent ecosystem** built for **OpenClaw** — a personal AI assistant that runs on your own devices. It's designed specifically for religious leaders who want AI support for their ministry.

Think of it as having an **entire staff team** available 24/7 — worship leaders, youth pastors, admin support, communications, pastoral care, and more — all powered by AI.

---

## Built for OpenClaw

This ecosystem is designed to run on **OpenClaw** — a personal AI assistant you run on your own devices:

- **Message on WhatsApp, Telegram, Discord, Signal, iMessage**
- **Voice on macOS/iOS/Android**
- **Works completely offline** if you use local AI models

**Learn more:** https://openclaw.ai/

---

## A Basis for Your Religious Institution

This ecosystem is a **starting point** — not a finished product. It's designed so you can:

### Customize It
- Edit any agent's SOUL.md to match your denomination's theology
- Add your own agents for unique ministry needs
- Modify USER.md templates for your specific church

### Expand It
- Add more ministry areas (counseling, missions, etc.)
- Create denomination-specific variations
- Build custom tools and resources

### Integrate It
- Connect to your church management systems
- Add your own templates and workflows
- Build artifacts specific to your community

---

## The Multi-Agent Architecture

Each agent is a **specialized AI assistant** with:

| File | Purpose |
|------|---------|
| **SOUL.md** | Who they are — personality, values, voice |
| **AGENTS.md** | What they do — rules and responsibilities |
| **TOOLS.md** | What they use — templates, resources |
| **USER.md** | Your details — customized for your church |

Agents work **together** — the Church Navigator routes you to the right specialist based on what you need.

---

## Denominations Included

| Denomination | Agents | Ministry Areas |
|-------------|--------|----------------|
| ✝️ **Protestant Christian** | 5 | Worship, Youth, Children, Outreach, Discipleship |
| ⛪ **Catholic** | 4 | Liturgy, RCIA, Social Justice, Faith Formation |
| 🕍 **Jewish** | 4 | Rabbi, Cantor, Education, Shabbat |
| 🕌 **Muslim** | 4 | Imam, Youth, Community, Education |

### Shared Agents (All Denominations)

| Agent | Role |
|-------|------|
| 🧭 Church Navigator | Main coordinator & triage |
| 🤝 Care Pastor | Pastoral care & crisis support |
| 📊 Admin Manager | Operations & volunteers |
| 📱 Communications | Social media & website |
| 🙏 Prayer Coordinator | Prayer teams & requests |

---

## Installation

### Step 1: Install OpenClaw

First, you need OpenClaw running on your computer or server:

```bash
# Install OpenClaw (one command)
curl -sL https://get.openclaw.ai | bash

# Start the gateway
openclaw gateway start
```

That's it! OpenClaw is now running.

### Step 2: Install the Church Ecosystem

```bash
# Clone this repo into your OpenClaw agents folder
git clone https://github.com/boktoday/church-leadership-ecosystem.git ~/.openclaw/agents/church
```

### Step 3: Configure Your AI

```bash
# Edit the OpenClaw config
openclaw config edit
```

Add your AI provider:
- **OpenRouter** — Cloud AI (free models available)
- **MiniMax** — Budget-friendly cloud AI
- **LMStudio** — Run AI locally on your computer

### Step 4: Restart & Start Chatting

```bash
# Restart to load the new agents
openclaw gateway restart
```

Now message your Church Navigator on Telegram, WhatsApp, or whatever channel you connected!

---

## First Conversation

When you first chat, tell the Church Navigator:

> "Hi, we're a [denomination] church in [city]. Our lead pastor is [name]. We're looking for help with [main challenge]."

The Navigator will:
1. Read your church profile
2. Ask about your denomination
3. Route you to the right specialist agents

---

## What Can These Agents Help With?

### Pastoral Care
- Grief support and funeral planning
- Crisis intervention
- Hospital visitation
- Counseling resources
- Leader burnout

### Administration
- Volunteer scheduling
- Event planning
- Building use
- Policy development
- Team management

### Communications
- Social media strategy
- Newsletter templates
- Website content
- Announcement scripts

### Ministry-Specific
- Worship planning and music selection
- Youth and children's ministry
- Outreach and evangelism
- Discipleship pathways
- (Catholic) Liturgy and sacraments
- (Jewish) Services and education
- (Muslim) Community and youth

---

## Philosophy

This ecosystem is built on these principles:

1. **Leader Care** — Who's pastorizing the pastor?
2. **Practical Support** — Ministry is demanding; reduce the load
3. **Faith-Informed** — Understands spiritual leadership
4. **Customizable** — Build on this foundation
5. **Privacy-First** — Runs on YOUR devices

---

## What's Included

```
church-leadership-ecosystem/
├── README.md                    # This file
├── ECOSYSTEM.md                # Detailed overview
├── SETUP_GUIDE.md             # Installation guide
│
├── shared/                     # 5 agents (all denominations)
│   ├── church-navigator/       # Main coordinator
│   ├── care-pastor/           # Pastoral care
│   ├── admin-manager/          # Operations
│   ├── communications-lead/    # Media
│   └── prayer-coordinator/    # Prayer teams
│
├── christian/                   # 5 agents
│   ├── worship-leader/
│   ├── youth-pastor/
│   ├── childrens-minister/
│   ├── outreach-pastor/
│   └── discipleship-coach/
│
├── catholic/                   # 4 agents
│   ├── liturgy-director/
│   ├── ricia-coordinator/
│   ├── social-justice/
│   └── faith-formation/
│
├── jewish/                     # 4 agents
│   ├── rabbi/
│   ├── cantor/
│   ├── education-director/
│   └── shabbat-coordinator/
│
└── muslim/                     # 4 agents
    ├── imam/
    ├── youth-lead/
    ├── community-lead/
    └── education/
```

---

## Contributing

This is a **foundation** for you to build on:

- Add your own agents
- Customize for your denomination
- Add region-specific resources
- Create custom tools and templates

---

## Disclaimer

AI support for religious leadership — not replacement for:
- Human pastoral care
- Theological decision-making
- Professional counseling
- Legal/financial advice

---

**Built to empower religious leaders, not replace them.** 🙏

---

**Created by:** Brendan O'Keefe  
**AI Orchestrator Training:** https://aiorchestrator.com.au  
**OpenClaw:** https://openclaw.ai/
