<!-- iamhoi -->
### Hi, I'm Hoi

AI Enablement Engineer. I help non-technical domain experts integrate AI into their actual work, building customised harnesses and agentic workflows they can own and operate.

20+ years IT for non-technical businesses, 8 years at Canonical translating infrastructure realities for non-engineering stakeholders, 3 years of AI-augmented build on top. The consistent line across all of it is helping non-experts use technology.

**The work**

Four production proof points across four different domains, built on the same harness. The flagship is the trading system; the harness generalises everything else.

- **auto_pb_swing_trader** (2025-2026, flagship 0-to-1): production AI-assisted swing trader I shipped solo in 9 months end-to-end on Interactive Brokers' live broker API. Real money, real broker, real failure modes. 10,000+ commits across 4 repos at 99.4% issue close rate, 1,860+ issues, 11,100+ evals gating every deploy. 8 live strategies (TP33/TP50/TP100/TPS33/TPS50/MB100/MBS100/PX80), dual-instance Rust data service with Redis leader election, Python controllers, React dashboard, fail-loud position authority, audit trail on every broker call. Unified Order Flow subsystem (36+ fixes, 211 tests) and Reconciliation engine (34 gaps, 40/40 repair tests, cancel-repair loop prevention, degraded-state handling). This is the engineering depth behind the enablement work.
- **SST3-AI-Harness**: the multi-agent orchestration harness/framework behind all of it. Built from first principles before I'd heard of LangChain or CrewAI. 3 generations, stage-gated, evidence-enforced. Three AI models reviewing each other at increasing depth (Haiku surface, Sonnet logic, Opus architecture). 14 pre-commit hooks blocking false completions, drift, and accidental regressions at commit time. Engineering standards derived from real production failures, not theory. **Designed so a non-technical domain expert can own the workflow the harness drives.**
- **hoiboy.uk** (2026): live AI-assisted publishing platform. Different domain, same harness. Proof that the pattern travels.
- **ebay-seller-tool MCP** (2026): I run a small eBay reseller business on the side. Dogfooded MCP harness for that workflow: the reseller operates it daily without reading the code. I am both builder and end-user here, which is the tightest PM feedback loop I have. The external non-technical SME version of this pattern is the next step.

**Featured**

- [SST3-AI-Harness](https://github.com/hoiung/SST3-AI-Harness): sanitised public extract of the methodology. The 5-stage workflow lifecycle, the Ralph 3-tier review, the 14 hooks, the 23 automation scripts. The thing itself, not a write-up about it.
- [hoiboy.uk](https://hoiboy.uk): live publishing platform. Second production system on SST3.
- **auto_pb_swing_trader**: production swing trader. Private repo (the trade secret). Interface proof via hoiboy.uk blog posts only.
- **tradebook_GAS** (2024-2025): the Google Sheets MVP that became auto_pb. 24 modules of Apps Script, FastAPI bridge, IBKR bracket orders. Every column in the sheet became a database column in production.

**Before that**

8 years at Canonical (Ubuntu) running global data centre projects. The daily work was translating infrastructure realities for non-engineering stakeholders. Knowledge transfer to Alex Micouleau on procurement (now IS Commercial Lead). Trained and mentored Michael Salois (Data Centre Engineer, US-based). Ran ICT-design workshops for Kevin Yeh and Nancy Chen (Taipei-based; full autonomy in 6 months). Trained 5 junior STS support team members (Global) on IT/AV for large sprint events (full team autonomy in 1 year). $1.25M/year in cost savings across the role, 8 internal awards.

Co-founded an international Brazilian Zouk dance school with my partner Domi. Served as Programme Director formulating the event programmes. Led, trained, and coached a 15-person distributed planning team across multiple countries; worked with international dance instructors as event partners. 20+ international events, 35% revenue growth, 25% enrolment growth. Did this for ~7 years alongside the day job because I wanted to. Same capability-transfer pattern, different domain.

Before Canonical: System Administrator at SunGard with SC+ clearance for MET Police clients. Before that: serial entrepreneur (LED import/export, design and print, took a near-bankrupt family takeaway profitable in 4 years and exited).

I work effectively alone, alongside a domain team, or embedded with a subject matter expert who owns the problem. Peer and SME partnership, not direct-report management.

**Tech I actually use**

Python, Rust, JavaScript/React, TypeScript, Google Apps Script, PostgreSQL, Redis, Docker, Claude Code, MCP servers, Git, GitHub Actions, pre-commit, systemd, WSL2.

**What I'm looking for**

The trading platform runs. It compounds. I'm not trying to build a bigger one.

What I want next is to take the harness pattern into non-technical domains where AI adoption is genuinely hard. Finance, legal, accounting, procurement, publishing, retail, customer support, events, coaching, and any other industry that can benefit from AI. SME businesses especially, since they don't have an engineering team of their own to lean on. Every department with a subject matter expert needs its own AI harness, shaped around their actual workflow. That's the interesting problem and that's the work I want to do.

If you're hiring for an AI Enablement Engineer, AI Adoption Lead, AI Fluency Lead, vertical Forward Deployed Engineer, vertical AI Solutions Architect, Staff or Principal AI Engineer IC (engineering-forward product companies where the end-user is a non-technical team), Applied AI Engineer IC, Algorithmic AI Engineer, or AI Harness Engineer, get in touch.

Not looking for: Programme Manager, Head or Director of AI, MLOps or Platform Engineer, frontier-lab FDE where the end-customer is another engineering team, pure-coaching roles without engineering build surface.

<a href="https://www.linkedin.com/in/hoiung" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
<!-- iamhoiend -->
