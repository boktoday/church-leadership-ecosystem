# 🚀 Church Leadership Ecosystem Setup Guide

## What Is OpenClaw?

**OpenClaw** is a personal AI assistant you run on your own devices. It answers you on the channels you already use:

- WhatsApp, Telegram, Slack, Discord, Signal, iMessage
- Voice on macOS/iOS/Android
- Live Canvas

**NeuroFamily** is designed as a drop-in agent system for **[OpenClaw](https://openclaw.ai/)**.

---

## Prerequisites

- OpenClaw installed
- AI provider (OpenRouter, MiniMax, or LMStudio)
- Basic command line

---

## Installation

### Step 1: Install OpenClaw

```bash
curl -sL https://get.openclaw.ai | bash
openclaw gateway start
```

### Step 2: Add Church Agents

```bash
git clone https://github.com/boktoday/church-leadership-ecosystem.git ~/.openclaw/agents/church
```

### Step 3: Configure

```bash
openclaw config edit
```

Add your AI provider.

### Step 4: Restart

```bash
openclaw gateway restart
```

---

## Choosing Your Denomination

When you first chat, tell the Church Navigator:

- "We're a Protestant church"
- "We're a Catholic parish"
- "We're a synagogue"
- "We're a mosque"

They'll route you to the right specialists.

---

## Channels

Connect Telegram, WhatsApp, Discord, etc. See main docs.

---

## What Agents Can Help With

### All Denominations
- Pastoral care
- Administration
- Communications
- Prayer teams

### Christian
- Worship planning
- Youth/children's ministry
- Outreach
- Discipleship

### Catholic
- Liturgy
- RCIA
- Faith formation
- Social justice

### Jewish
- Rabbinic teaching
- Cantor/music
- Education
- Shabbat

### Muslim
- Imam duties
- Youth programs
- Community
- Quran education

---

## Disclaimer

AI support for religious leadership — not replacement for human pastoral care, theological decision-making, or professional advice.

---

*Built to empower religious leaders.*
