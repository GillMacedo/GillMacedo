# Hi, I'm Giulliano

I'm a lead software engineer. I build free, open-source MCP servers, skills and plugins for Claude, and I'm learning more about AI engineering along the way.

[LinkedIn](https://www.linkedin.com/in/giulliano/) · [X / Twitter](https://x.com/giumacedo)

## MCP servers

### For AI developers

| Project | What it does |
|---|---|
| [stalemodel](https://github.com/GillMacedo/stalemodel) | Catch outdated AI model names in code, and look up current models, prices and limits |

### For backend and databases

| Project | What it does |
|---|---|
| [slowplan](https://github.com/GillMacedo/slowplan) | Find why a PostgreSQL query is slow from its EXPLAIN output, without connecting to your database |
| [stuckgo](https://github.com/GillMacedo/stuckgo) | Find what a stuck or leaking Go program is waiting on from a goroutine dump, without connecting to it |

### For business data

These work on your local CSV files.

| Project | What it does | For |
|---|---|---|
| [tiedout](https://github.com/GillMacedo/tiedout) | Match bank statements to invoices from CSV files | Bookkeeping |
| [samecontact](https://github.com/GillMacedo/samecontact) | Find duplicate customers and contacts in CSV exports | CRM and sales |
| [chargescout](https://github.com/GillMacedo/chargescout) | Find subscriptions, price increases and double charges in a bank statement CSV | Business spending |
| [runwaystock](https://github.com/GillMacedo/runwaystock) | Find what to reorder, stockout dates and dead stock from sales and stock CSVs | Inventory |
| [lapsewatch](https://github.com/GillMacedo/lapsewatch) | Find customers who stopped buying, and the revenue at risk, from an orders CSV | Customer retention |
| [latepayers](https://github.com/GillMacedo/latepayers) | See who owes you money, how late each invoice is, and who to chase first, from an invoice CSV | Accounts receivable |

## Skills and plugins

### Backend and operations

| Project | What it does | Type |
|---|---|---|
| [beforeitbroke](https://github.com/GillMacedo/beforeitbroke) | Build an incident timeline of what changed before production broke, from git, GitHub and Kubernetes | Skill |
| [kubestepup](https://github.com/GillMacedo/kubestepup) | Plan a Kubernetes upgrade one minor version at a time and find what would block it | Skill |
| [whyredci](https://github.com/GillMacedo/whyredci) | Explain a failed GitHub Actions run, and whether it looks new, already failing or flaky | Skill |
| [gosturdy](https://github.com/GillMacedo/gosturdy) | Find production risks in a Go service: missing timeouts, no graceful shutdown, unlimited database pools | Skill |
| [missingenv](https://github.com/GillMacedo/missingenv) | Find environment variables your code reads but your deploy files don't set | Skill |
| [stillused](https://github.com/GillMacedo/stillused) | Find columns and tables your migrations drop or rename while code still uses them | Skill |

### Claude Code

| Project | What it does | Type |
|---|---|---|
| [permwhy](https://github.com/GillMacedo/permwhy) | Debug Claude Code permission prompts and lint the allow and deny rules in `settings.json` | Plugin |

## Templates

### Agent harnesses

| Project | What it does |
|---|---|
| [shiftbaton](https://github.com/GillMacedo/shiftbaton) | Run Claude Code in long headless shifts with file handoff, a spend limit and a kill switch |

## Install

MCP servers, skills and plugins install as Claude Code plugins:

```bash
claude plugin marketplace add GillMacedo/lapsewatch
claude plugin install lapsewatch@lapsewatch-marketplace
```

Swap `lapsewatch` for any of those repos. MCP servers also run through `npx`, and for templates, click **Use this template** on GitHub.

## What I'm learning

- AI engineering
- Building MCP servers, skills and plugins that agents can find and use

## Links

- LinkedIn: [giulliano](https://www.linkedin.com/in/giulliano/)
- X / Twitter: [@giumacedo](https://x.com/giumacedo)
