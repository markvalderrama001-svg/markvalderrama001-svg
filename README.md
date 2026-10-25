## Mark Valderrama, CPA · Finance Engineer

I'm a CPA who builds AI automation. Mostly for accounting and finance, but also for content, operations, and my own businesses I run with my sons.

I started in audit at PwC in 2004, worked my way up to controller, and was interim corporate controller during an IPO. These days I spend most of my time building with Claude Code: MCP servers that connect AI to ERPs, close workflows written as Claude skills, FP&A reporting, and the integrations that hold it all together.

My rule for anything that touches the books: **Claude drafts, a human posts.** If you want to see what that means in code, start with [xero-card-coding](https://github.com/markvalderrama001-svg/xero-card-coding). It's how I run my own business books.

Everything here runs on made-up data and has a demo you can run. I rebuilt these from scratch as clean versions of tools I use for real, so the commit history is short on purpose.

### Finance engineering

| Repo | What it does |
|---|---|
| [xero-card-coding](https://github.com/markvalderrama001-svg/xero-card-coding) | Codes credit card charges in Xero from past history and won't post until every line has a human decision |

Other things I've built:

- ERP selection playbook: test script, scoring model and a sandbox-only evaluation method
- ERP MCP connector: consolidated statements from the trial balance and draft-only journal entries
- AP close automation across multiple spend accounts: cutoff, GL coding and memo cleanup
- Month-end close playbooks as Claude skills, with tie-outs and sign-off gates
- Write controls for AI agents that touch the general ledger, written like a SOX control matrix
- FP&A reporting with drill-down to transactions and a parallel-run check before cutover
- Technical accounting research agents for ASC 842, ASC 740 and statutory accounting
- A read-only GL assistant so executives can ask the books questions
- HR-to-finance sync with an approval-chain controls test
- An executive financial dashboard that checks itself every time it loads

### AI content and writing systems

| Repo | What it does |
|---|---|
| [ai-content-engine](https://github.com/markvalderrama001-svg/ai-content-engine) | A team of five AI agents (writer, reviewer, polisher, humanizer, info-gain judge) with gates, backups before every publish, and drift checks |
| [ai-writing-quality-playbook](https://github.com/markvalderrama001-svg/ai-writing-quality-playbook) | My humanization, fact-check and citation SOPs turned into code that fails a weak draft and passes a good one |
| [claude-prompt-builder-skill](https://github.com/markvalderrama001-svg/claude-prompt-builder-skill) | A Claude skill that turns one messy sentence into a solid prompt |

### Data pipelines and integrations

| Repo | What it does |
|---|---|
| [comment-intel](https://github.com/markvalderrama001-svg/comment-intel) | Turns thousands of YouTube comments into ranked video ideas every morning, and never pays to read the same comment twice |
| [asana-trello-migrator](https://github.com/markvalderrama001-svg/asana-trello-migrator) | Moved three production boards from Asana to Trello like an ERP cutover: backup first, load, reconcile, zero missing |
| [youtube-metadata-bulk](https://github.com/markvalderrama001-svg/youtube-metadata-bulk) | Bulk title and description edits with a preview, a change log and an undo button |

### Built with my son

| Repo | What it does |
|---|---|
| [tastytrade-mcp](https://github.com/markvalderrama001-svg/tastytrade-mcp) | 42-tool brokerage MCP server for the wheel, LEAPS and market sentiment, plus performance tracking that strips out deposits and compares to SPY and QQQ. Live orders sit behind an operator switch and a per-order confirmation |
| [trading-dashboard](https://github.com/markvalderrama001-svg/trading-dashboard) | A read-only dashboard for the same book. The server, not the browser, decides what it's allowed to call |

Built by my 11-year-old, with parent supervision, on weekends. He'd like you to know his custodial account beat QQQ and the S&P 500 this year, and it did. (He's not available for hire. He has homework. I'm joking!) Not investment advice.

### For my kids

| Repo | What it does |
|---|---|
| [alpha-school-coach](https://github.com/markvalderrama001-svg/alpha-school-coach) | How I run mastery-based learning at home: a Claude coach that keeps me on track as the "guide," a tutor that gives my kids hints instead of answers, and a weekly progress summary |

**What I build with:** Python, TypeScript, Claude and Claude Code, MCP, Google Apps Script, Cloudflare Workers, SQLite

**Systems I've run:** Sage Intacct, NetSuite, Xero, Ramp, Rippling, bill.com, Concur, Adaptive Planning, PowerBI

**Accounting:** consolidation, month-end close, FP&A, SOX, ASC 606, ASC 842, ASC 740, statutory (SSAP)

Austin, TX · [LinkedIn](https://www.linkedin.com/in/markvalderrama/)
