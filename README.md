<!-- iamhoi -->
### Hi, I'm Hoi

AI Tinkerer. I design and ship production software 0-to-1: I make the scope and technical calls, AI agents do the implementation. Through HOIBOY AI LTD I also build custom AI harnesses and agentic workflows for domain experts to own and operate.

**19,000+ commits across 20 repos · 1,700+ issues @ 97.8% close · 650+ PRs · 13,100+ evals gating every deploy · live broker API**

20+ years IT for non-technical businesses, 8 years at Canonical translating infrastructure realities for non-engineering stakeholders, 3 years of AI-augmented build on top. Two sides of the same coin: I ship production systems solo, and I hand the pattern to non-experts so they can own and run it themselves.

**The work**

Four production proof points across four different domains, built on the same harness. The flagship is the trading system; the harness generalises everything else.

- **auto_pb_swing_trader** (2025-2026, flagship 0-to-1): production AI-assisted swing trader I shipped solo end-to-end on Interactive Brokers' live broker API (~8 months to 0-to-1, then forward-tested and tuned). Real money, real broker, real failure modes. 11,535 commits, 1,154 issues at 99.2% close, 407 PRs, 13,100+ evals gating every deploy. 8 live strategies, dual-instance Rust data service with Redis leader election, Python controllers, React dashboard, fail-loud position authority, and an audit trail on every broker call. The order-flow and reconciliation engines handle cancel-repair loop prevention and degraded-state recovery. Real engineering depth, not a demo.
- **SST3-AI-Harness**: the multi-agent orchestration harness/framework behind all of it. Built from first principles before I'd heard of LangChain or CrewAI. 3 generations, stage-gated, evidence-enforced. Three AI models reviewing each other at increasing depth (Haiku surface, Sonnet logic, Opus architecture). 14 pre-commit hooks blocking false completions, drift, and accidental regressions at commit time. Engineering standards derived from real production failures, not theory. **Designed so a non-technical domain expert can own the workflow the harness drives.**
- **hoiboy.uk** (2026): live AI-assisted publishing platform. Different domain, same harness. Proof that the pattern travels.
- **ebay-seller-tool MCP** (2026): I run a small eBay reseller business on the side. Dogfooded MCP harness for that workflow: the reseller operates it daily without reading the code. I am both builder and end-user here, which is the tightest PM feedback loop I have. The external non-technical SME version of this pattern is the next step.

**Featured**

- [SST3-AI-Harness](https://github.com/hoiung/sst3-ai-harness): sanitised public extract of the methodology. The 5-stage workflow lifecycle, the Ralph 3-tier review, the 14 hooks, the automation scripts. The thing itself, not a write-up about it.
- [hoiboy.uk](https://hoiboy.uk): live publishing platform. Second production system on SST3.
- **HOIBOY AI LTD**: my consulting vehicle. Client case studies (CU Architects, Singer & Steel): [hoiboy.uk/consulting/portfolio](https://hoiboy.uk/consulting/portfolio/).
- **auto_pb_swing_trader**: production swing trader. Private repo (the trade secret). Interface proof via hoiboy.uk blog posts only.
- **tradebook_GAS** (2024-2025): the Google Sheets MVP that became auto_pb. Multiple Apps Script modules, a FastAPI bridge, IBKR bracket orders. Every column in the sheet became a database column in production.

**Before that**

8 years at Canonical (Ubuntu) running global data centre projects. The daily work was translating infrastructure realities for non-engineering stakeholders. Handed over procurement to a colleague who now leads it commercially. Trained and mentored a US-based data centre engineer, ran ICT-design workshops for a Taipei team (full autonomy in 6 months), and trained 5 junior support engineers across the global team on IT/AV for large sprint events (full team autonomy in 1 year). $1.25M/year in cost savings across the role, 8 internal awards.

Co-founded an international Brazilian Zouk dance school with my partner. Served as Programme Director formulating the event programmes. Led, trained, and coached a 15-person distributed planning team across multiple countries; worked with international dance instructors as event partners. 20+ international events, 35% revenue growth, 25% enrolment growth. Did this for ~7 years alongside the day job because I wanted to. Same capability-transfer pattern, different domain.

Before Canonical: System Administrator at SunGard with SC+ clearance for MET Police clients. Before that: serial entrepreneur (LED import/export, design and print, took a near-bankrupt family takeaway profitable in 4 years and exited).

I work effectively alone, alongside a domain team, or embedded with a subject matter expert who owns the problem. Peer and SME partnership, not direct-report management.

**Tech I actually use**

Languages: Python, Rust, JavaScript/React, TypeScript, Google Apps Script, SQL.

Platforms and infra: PostgreSQL, Redis, Docker, systemd, WSL2, Hugo, Cloudflare Pages, Git, GitHub Actions, pre-commit.

AI: Claude Code (primary driver), MCP servers.

Key libraries I've built with:
- Trading and backtesting: VectorBT, TA-Lib, ib-async and yatws (Interactive Brokers, Python and Rust), Finnhub and yfinance data feeds
- Data and API: pandas, NumPy, FastAPI, Pydantic, SQLAlchemy, Plotly, httpx
- Rust services: tokio, axum, reqwest, tokio-tungstenite, serde, tracing
- Testing and quality: pytest, Hypothesis, Playwright, ruff

**What I'm looking for**

The work I enjoy most is building production software 0-to-1. Framing the problem, making the technical calls, shipping in short cycles, then watching it run and tightening it. Build, test, observe, release, repeat. The trading platform proved I can take something from nothing to live and keep it running with real money on it. I want to do that again on a harder problem.

The other half is the same skill pointed at non-technical domains. Finance, legal, accounting, procurement, publishing, retail, customer support, events, and any other industry that can benefit from AI. SME businesses especially, since they don't have an engineering team to lean on. Every department with a subject matter expert can have its own AI harness, shaped around the work they already do. Both halves are the work I want.

If you're hiring for an AI Product Engineer, AI Enablement Engineer, AI Adoption Lead, AI Fluency Lead, vertical Forward Deployed Engineer, vertical AI Solutions Architect, AI Engineer IC (engineering-forward product companies where the end-user is a non-technical team), Applied AI Engineer IC, Algorithmic AI Engineer, AI Harness Engineer, or a hands-on AI Lead / Head of AI (small or founder-led team where you still build), get in touch.

Not looking for: Programme Manager, hands-off or exec Head or Director of AI (people management, no build surface), MLOps or Platform Engineer, frontier-lab FDE where the end-customer is another engineering team, pure-coaching roles without engineering build surface.

If any of this sounds like your kind of thing, come and connect with me on LinkedIn, have a read of my Tech & AI blog to see how I actually work, or join my Asians & Gingers in Tech community. All linked just below. Don't be shy, say hello.

<a href="https://www.linkedin.com/in/hoiung" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"></a> <a href="https://hoiboy.uk/tech-ai/" target="_blank"><img src="https://img.shields.io/badge/Tech%20%26%20AI%20Blog-hoiboy.uk-38BDF8?style=flat&logo=hugo&logoColor=white" alt="Tech & AI Blog"></a> <a href="https://hoiboy.uk/community/asians-gingers-in-tech/" target="_blank"><img src="https://img.shields.io/badge/Community-Asians%20%26%20Gingers%20in%20Tech-FF6B35?style=flat&labelColor=black" alt="Asians & Gingers in Tech community"></a>
<!-- iamhoiend -->
