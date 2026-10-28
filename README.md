<img src="https://raw.githubusercontent.com/smaroot-tech-edward/smaroot-tech-edward/main/smaroot-banner.png" alt="Smaroot — AI agents, SaaS and automation" width="100%" />

# Business software, backed by our own product engineering

I'm **Edward Aming, CTO at Smaroot (慧根智研)**, a software development company based in Beijing, China. We build our own automation products and help businesses improve applications, connect systems and turn manual handoffs into dependable workflows.

**[Self-developed products & engineering](ENGINEERING.md) · [Runnable components](https://github.com/smaroot-tech-edward/smaroot-components) · [Contact Edward](CONTACT.md)**

## What we build ourselves

| Product | Engineering focus | Explore |
|---|---|---|
| **Huimei Engine** | AI content operations, task orchestration, action adapters and execution receipts | [Product](https://www.smaroot.tech/products/huimei) |
| **Matrix Browser** | Persistent browser profiles, session lifecycle, automation access and operational visibility | [Product](https://www.smaroot.tech/products/matrix-browser) |
| **Matrix Mobile** | Android Bridge, device Hub, Web console and MCP/REST integration | [Product](https://www.smaroot.tech/products/matrix-mobile) |
| **HuiYing Studio** | AI-assisted video creation workflows | [Product](https://www.smaroot.tech/products/huiying) |
| **Smaroot Commerce** | Merchant operations and customer-facing business workflows | [Product](https://www.smaroot.tech/products/commerce) |

Read the [engineering overview](ENGINEERING.md) for the building blocks, architecture and their relationship to our public code.

## Inspect working code

### Durable tasks and runtime contracts

[**smaroot-components**](https://github.com/smaroot-tech-edward/smaroot-components) contains independently written public components for:

- **Durable task claims:** tenant-scoped keys, input-conflict protection and results that survive reopening the database.
- **Honest execution receipts:** distinguish `submitted`, `confirmed` and `unknown`; an expired lease leads to reconciliation rather than a blind retry.
- **Runtime negotiation:** require a compatible version, ready provider and the capabilities the job actually needs.

The Python standard-library implementation includes an offline example, architecture notes and **12 behavior checks**, including an eight-claim concurrency test.

### Form-to-CRM webhook deduplication

[**webhook-idempotency-demo**](https://github.com/smaroot-tech-edward/webhook-idempotency-demo) demonstrates duplicate submission handling, conflicting input and validation, with four acceptance checks and fictional CRM data.

## How this helps your project

| You need | A concrete starting point |
|---|---|
| Repair an existing application | Reproduce one failure, agree the expected result, fix and verify the affected journey |
| Connect an API or CRM | Define trigger → output, record mapping, duplicate handling and an observable receipt |
| Build a business application | Define users, permissions, core data and one valuable end-to-end workflow |
| Add AI or automation | Separate planning from execution, keep human approval where needed and retain execution evidence |

We agree deliverables, acceptance checks, exclusions, price cap and available delivery window before starting.

## Talk to Edward

In one sentence: **what starts your workflow, and what should happen next?**

**[Telegram @DARKINGDATA](https://t.me/DARKINGDATA) · [WeChat QR / contact options](CONTACT.md) · [edward@smaroot.tech](mailto:edward@smaroot.tech)**

WhatsApp is available on request through Telegram or email.

[Company website and consultation](https://www.smaroot.tech/?utm_source=github&utm_medium=github_profile&utm_campaign=software_services) · [Smaroot on LinkedIn](https://www.linkedin.com/company/smaroot-tech/)

慧根智研｜自研产品、自动化组件、业务系统与 API/CRM 集成。先明确交付与验收，再确认价格和排期。
