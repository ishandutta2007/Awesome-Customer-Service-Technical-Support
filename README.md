# Awesome-Customer-Service-Technical-Support

# Awesome-Customer-Service-Technical-Support
**Top Customer Service Technical Support (Opensource) 🌟 Star if you like it! 🌟**

**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Ticketing, SLAs, Knowledge-Centered Service & Self-Hosted Technical Support Desks*
**Last updated: November 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Customer Service & Technical Support**. These tools enable support teams to manage technical tickets, track SLAs, escalate incidents, and resolve issues across email, chat, and portals—from fully managed enterprise suites with AI agents and asset management to self-hosted helpdesks that give organizations complete ownership of their support data.

**Examples** include Jira Service Management, Zendesk Support, Freshdesk, ServiceNow CSM, Salesforce Service Cloud, Zoho Desk, HappyFox, Intercom, Kayako, and Atlassian Support (the category leaders in commercial space).

**Open-source emphasis**: This section is expanded with every relevant project for self-hosted technical support, ITSM, and open ticketing infrastructure. **Critical note**: The open-source technical support landscape is anchored by **Frappe Helpdesk** (unlimited agents, SLAs, ERPNext integration) and **OTOBO** (OTRS lineage with free ITSM packages) . **Request Tracker** remains the veteran for granular per-queue permissions . No open-source project matches Jira Service Management's Atlassian ecosystem integration or ServiceNow's enterprise CMDB depth, but for core technical ticketing and SLAs, the open-source options are production-proven.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Jira Service Management](https://www.atlassian.com/software/jira/service-management)**
  **ITSM and technical support desk** within the Atlassian ecosystem. **Pricing**: **Free up to 3 agents**; **Standard from ~$19,700/year for 100 agents** (rising to ~$21,000 from 13 Oct 2026); **Premium ~$55,000/year for 100 agents**; Enterprise quote-only. Customer Service Management included at **$1 per resolution** on paid tiers . **Free tier**: Yes, 3 agents with unlimited customers. **Best for**: teams already on Jira wanting dev-to-support integration—**trade-off**: pricing restructuring Oct 2026; AI features tied to Atlassian Guard.

- **[Zendesk Support](https://www.zendesk.com/)**
  **Enterprise support suite** with omnichannel ticketing. **Pricing**: **Support Team $19/agent/month** (entry); **Suite Team $55/agent/month** (adds messaging, help center, AI); **Suite Professional $115/agent/month**; **Advanced AI add-on $50/agent/month** stacks on top . **Free tier**: No free plan; **14-day trial**. **Best for**: teams wanting the most mature omnichannel support—**trade-off**: add-ons stack; Suite Team + Advanced AI reaches ~$105/agent/month .

- **[Freshdesk](https://www.freshworks.com/freshdesk/)**
  **Support ticketing** with Freddy AI. **Pricing**: **Growth ~$15–19/agent/month** (annual); **Pro ~$49/agent/month**; **Enterprise ~$89/agent/month** (includes Freddy AI Insights). **Freddy AI Copilot $29/agent/month add-on** on Pro and Enterprise; **500 free AI Agent sessions**, then **$49 per 100 overage** . **Free tier**: **No free plan** on current pricing page; 14-day trial. **Best for**: mid-market teams wanting Zendesk-comparable features at lower cost—**trade-off**: AI Copilot costs extra even on Enterprise; no audit logs below Enterprise .

- **[ServiceNow CSM](https://www.servicenow.com/)**
  **Enterprise customer service management** on ServiceNow platform. **Pricing**: **~$100–$200/fulfiller/month** at smallest band, falling to **$38–$90 above 2,500 seats**; **Now Assist AI adds ~$25–$75/fulfiller/month** on pre-2026 contracts; April 2026 tiers meter AI via assist allocation . **Free tier**: None. **Best for**: large enterprises needing CSM integrated with ITSM and CMDB—**trade-off**: complex licensing; 30% median saving possible by correcting fulfiller counts before renewal .

- **[Salesforce Service Cloud](https://www.salesforce.com/)**
  **Enterprise service platform** with case management and Einstein AI. **Pricing**: **Starter Suite $25/user/month**; **Pro Suite $100/user/month**; **Enterprise $165/user/month**; **Unlimited $330/user/month**; **Agentforce add-ons** extra . **Free tier**: 30-day free trial; no credit card . **Best for**: large enterprises already on Salesforce—**trade-off**: implementation requires Salesforce admin; costs climb steeply above Pro Suite .

- **[Zoho Desk](https://www.zoho.com/desk/)**
  **Support ticketing** within Zoho ecosystem. **Pricing**: **Free up to 3 agents**; **Express $7/agent/month** (5-user cap, includes AI Agents); **Standard $14/agent/month**; **Professional $23/agent/month** (Zia AI, telephony); **Enterprise $40/agent/month** (multi-brand, 50 light agents included) . **Free tier**: Yes, 3 agents. **Best for**: SMBs wanting affordable ticketing with genuine free tier—**trade-off**: Express capped at 5 users; advanced AI requires Professional+.

- **[HappyFox](https://www.happyfox.com/)**
  **Help desk software** with workflow automation. **Pricing**: **Starting at ~$24/month** per third-party listings; tiered by agents . **Free tier**: Not specified in results; trial available. **Best for**: SMBs wanting workflow automation without enterprise pricing—**trade-off**: limited public pricing detail.

- **[Intercom](https://www.intercom.com/)**
  **AI-first support platform** with Fin AI Agent. **Pricing**: **Essential from $0.99/seat/month** (annual) plus **Fin at $0.99 per outcome** (minimum monthly commitment applies); **Advanced $85/seat/month**; **Expert $132/seat/month**; **Copilot add-on $29/agent/month**; **Pro add-on $100/month** . **Free tier**: No permanent free tier; trial available. **Best for**: teams wanting AI resolution priced per outcome—**trade-off**: seat + per-outcome costs stack; Fin requires minimum commitment .

- **[Kayako](https://kayako.com/)**
  **AI-first support platform** with resolution-based pricing. **Pricing**: **$1 per AI resolution**—no per-seat fees, no add-ons; if AI escalates to human, you don't pay. No minimums, no commitments . **Free tier**: Trial available; no permanent free plan . **Best for**: teams wanting predictable AI-first costs without seat fees—**trade-off**: less feature depth than Zendesk/Freshdesk as processes grow .

- **[Atlassian Support](https://www.atlassian.com/)** (**Not a vendor product**)
  **Atlassian's own support services** for their products. **Note**: This is Atlassian's customer support for their software, **not a standalone helpdesk platform available for purchase**. Organizations seeking support software should evaluate Jira Service Management or third-party options.

## Open-Source GitHub Projects

- **[Frappe Helpdesk](https://github.com/frappe/helpdesk)**
  **Open-source ticketing and customer support app** (AGPL-3.0) — **the most practical open-source helpdesk for teams on Frappe/ERPNext**, with ~3.4k stars and active releases . **Features**: **Tickets, SLAs, and customer portal** with **no per-agent fees**; SLAs with business hours and auto-assignment by priority/type/team/workload; **unlimited agents**; sign-in via Google, Microsoft, or custom OIDC; **customer sync with ERPNext**; call logging via Twilio/Exotel . **Tech stack**: Python (Frappe Framework), Vue.js, MariaDB/Redis. **Deploy**: Self-hosted (Frappe bench) or **Frappe Cloud at $5/month** . **Trade-off**: **No live chat or WhatsApp channel**; self-hosting requires full Frappe stack . **Best for**: ERPNext/Frappe teams wanting support tickets integrated with their ERP—especially those wanting unlimited agents without seat fees.

- **[OTOBO](https://github.com/RotherOSS/otobo)**
  **Open-source ticketing and IT service management** (GPL-3.0) — **the maintained fork of OTRS**, with free ITSM packages . **Features**: **ITSM add-on packages free to download**; OpenID Connect, LDAP, and RADIUS sign-in in free code; runs on MariaDB, MySQL, PostgreSQL, or Oracle; **customer self-service portal included** . **Tech stack**: Perl, Apache/Nginx. **Deploy**: Self-hosted. **Trade-off**: **Production servers need 8 GB RAM minimum (16 GB recommended)**; vendor support starts at €3,900/year . **Best for**: IT and service teams wanting OTRS-style service desk without license fees.

- **[Request Tracker (RT)](https://github.com/bestpractical/rt)**
  **Open-source ticket tracker** (GPL-2.0) — **the veteran for granular per-queue permissions**, maintained by Best Practical, v6.0.3 (May 2026) . **Features**: **Rights per queue, group, and role**; **asset tracking built in**; **REST 2 API** in core; RT 6 allows ticket page layout rearranging . **Tech stack**: Perl, MySQL/PostgreSQL/Oracle/SQLite. **Deploy**: Self-hosted. **Trade-off**: **No official Docker image for production**; SSO needs web server module . **Best for**: IT and operations teams needing detailed per-queue rights and full change history.

### Additional Strong Open-Source Options

- **UVdesk** — PHP/Symfony helpdesk (OSL-3.0) with **unlimited agents, teams, and mailboxes** in free edition; email tickets + customer portal + knowledge base . **Note**: **No SSO for agents, no audit log**; no new release since September 2025. **Best for**: small teams on PHP hosting needing email ticketing.
- **Libredesk** — Open-source support inbox in Go (single binary) for email and live chat . **Note**: New and worth watching—verify maturity before production. **Best for**: teams wanting a lightweight Go-based helpdesk.

**Frameworks for building custom systems**: Choose **Frappe Helpdesk** for unlimited agents on Frappe/ERPNext, **OTOBO** for ITSM lineage, and **Request Tracker** for granular permissions—each serves a distinct operational profile. **None of these match Jira Service Management's ecosystem integration or ServiceNow's CMDB depth**, but for core technical ticketing and SLAs, the open-source options cover most needs.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, license (for open-source), and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Customer service platforms handling support conversations must comply with data protection regulations (GDPR, CCPA, etc.) and implement appropriate access controls for customer data.
- **The "ITSM-integrated" vs. "omnichannel support" vs. "AI-resolution" vs. "self-hosted helpdesk" distinction is critical.** **Jira Service Management** is **ITSM-integrated**—it connects dev and support workflows. **Zendesk, Freshdesk, and Zoho Desk** are **omnichannel support platforms**—email, chat, social, and voice. **Intercom and Kayako** are **AI-resolution platforms**—outcome or resolution-based pricing. **ServiceNow and Salesforce** are **enterprise CX/CSM platforms**—deep integration with broader enterprise systems. **Frappe Helpdesk, OTOBO, and Request Tracker** are **self-hosted helpdesks**—you own the infrastructure. **Choose based on whether you need ITSM integration, omnichannel breadth, AI resolution, or self-hosted control.**
- **Jira Service Management pricing is restructuring in October 2026.** For 100 agents, Standard rises from ~$19,700 to ~$21,000/year; Premium from ~$51,000 to ~$55,000/year . **Budget for the increase if renewing after 13 Oct 2026.**
- **Freshdesk has no free plan.** The free tier disappeared by October 2026; only a 14-day trial remains. **Freddy AI Copilot costs $29/agent/month extra even on Enterprise** .
- **Kayako's $1-per-resolution model is unique.** No per-seat fees, no add-ons, no minimums—you pay only when AI fully resolves without human escalation . **For teams with high AI resolution rates, it can be dramatically cheaper than seat + AI add-on models.**
- **ServiceNow licensing is per fulfiller, not per user.** 20–40% of fulfiller seats often belong to people who never work queues—correcting this before renewal can save ~30% . **Model your actual queue workers, not headcount.**
- **Frappe Helpdesk is the best open-source option for unlimited agents.** No per-agent fees, SLAs with business hours, ERPNext sync, and $5/month Frappe Cloud hosting. **The trade-off**: no live chat or WhatsApp; requires Frappe stack for self-hosting.
- **Pricing opacity varies.** Zendesk, Freshdesk, Zoho Desk, Intercom, Kayako, and Jira Service Management publish tiered pricing. ServiceNow, Salesforce, and HappyFox require sales contact or quote-based engagement. **Validate with direct vendor conversations against your agent count and feature needs.**
- Self-hosted open-source solutions require proper infrastructure (Frappe stack for Helpdesk, 8 GB+ RAM for OTOBO), security hardening, and ongoing maintenance. **Support data includes customer PII and technical details**—ensure your deployment meets your organization's privacy and compliance requirements before migrating production support.

---

**Made for support leads, IT teams, and organizations building transparent technical support solutions.**
Let's make Customer Service & Technical Support more open, data-driven, and resolution-friendly.
