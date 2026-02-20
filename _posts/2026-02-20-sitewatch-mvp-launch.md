---
layout: post
title: "SiteWatch MVP Launch: Website Monitoring with a Freemium Model"
date: 2026-02-20 17:00:00 -0500
categories: launch mvp micro-saas
---

Three days ago, I asked Donut (my research scout) to find a Micro-SaaS idea worth building. Yesterday, Carl (my coding agent) built the MVP. Today, it's live.

**Meet SiteWatch** — dead-simple website uptime monitoring built specifically for freelancers and agencies managing client sites.

## What Problem Does It Solve?

If you've ever managed websites for clients, you know the anxiety: *"Is my client's site down right now, and I just don't know it?"*

Most freelancers discover downtime when the client calls them—angry. SSL certificates expire unexpectedly. And the existing solutions (Pingdom, UptimeRobot) are either overpriced or not built for the "managing sites for others" workflow.

## Features in the MVP

SiteWatch does the essentials well:

- **Uptime Monitoring** — Checks your sites every 5 minutes
- **SSL Expiry Alerts** — Warns you 30, 14, and 7 days before certificates expire
- **SMS Notifications** — Get critical alerts via text, not just email
- **Simple Dashboard** — Green/red status at a glance
- **Client-Ready Reports** — Show clients the value you're providing

## The Freemium Model

I wanted to make this accessible to solo freelancers while still building a real business:

| Plan | Sites | Price/Month |
|------|-------|-------------|
| **Free** | 1 site | $0 |
| **Starter** | 5 sites | $5 |
| **Pro** | 20 sites | $15 |
| **Business** | 100 sites | $49 |

The free tier is genuinely useful for solo developers. Paid tiers unlock SMS credits and more sites as you grow.

## The Stack

Built with modern, low-cost infrastructure:

- **Next.js 14** (App Router) — Frontend and API
- **Vercel** — Hosting and cron jobs
- **Supabase** — PostgreSQL database + auth
- **Stripe** — Subscription billing
- **Twilio** — SMS notifications

Total monthly cost to run: ~$0 on free tiers, scales affordably.

## The Donut → Carl Pipeline

This was my first time running the full **research → code → deploy** pipeline:

1. **Donut** researched Micro-SaaS opportunities and pitched SiteWatch (8/10 score)
2. **Carl** took the spec and built the complete MVP in a single session
3. I reviewed, we refined the pricing model, and deployed

The whole thing went from idea to live product in under 48 hours. That's the power of having specialized agents.

## See It Live

🚀 **Live URL:** [https://sitewatch-mvp.vercel.app](https://sitewatch-mvp.vercel.app)

💻 **GitHub:** [github.com/GrowlerGary/sitewatch-mvp](https://github.com/GrowlerGary/sitewatch-mvp)

Try the free tier, kick the tires, and let me know what you think. This is a true MVP—functional, but rough around the edges. I'll be iterating based on feedback.

## What's Next?

The immediate roadmap:

- Public status pages (so your clients can see uptime too)
- More notification channels (Discord, Slack webhooks)
- Response time graphs and historical data
- Team/white-label features for agencies

If you're a freelancer or agency managing client sites, I'd love your feedback. What features would make this indispensable for your workflow?

---

*Building in public means sharing the wins and the messy middle. This is definitely the messy middle—but it's live, it's working, and it's only going to get better.*
