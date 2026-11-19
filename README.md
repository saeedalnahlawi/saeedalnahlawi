# Saeed Al-Nahlawi

Financial analyst (BSc FinTech, Middle East University, Amman — graduated Sep 2026, GPA 3.24).
I value listed companies and publish the model, the data and the assumptions — including the ones I got
wrong.

**What is here:** reproducible equity research. Every number traces to a script and to a page in a filing.

### Pinned work

| Repo | What it does |
|---|---|
| [research-desk](https://github.com/saeedalnahlawi/research-desk) | Valuations of US-listed (SEC EDGAR), Amman Stock Exchange and GCC companies: data pipelines, SQL ratios, three valuation engines chosen by sector, published notes |
| ase-ratios *(planned)* | Three years of one ASE company → a printed ratio table, in one command |
| sql-drills *(planned)* | Daily SQL exercises against real financial data |

### How I work

- The method is chosen by sector: residual income for banks, EV/EBITDA and FCF DCF for telecoms, FCFF DCF
  for industrials. A generic DCF on a bank is the mistake I am trying not to make.
- Each model prints a reverse DCF — what the market price already believes — and refuses to produce a number
  when the inputs cannot support one.
- Every note states its limitations. The most useful thing I published was a correction: a 45% "upside" that
  dissolved when capex was checked against the audited statements.
- `research-desk` runs its checks on every push (see the green tick on the repo), so "it works" is something
  a reader can verify rather than take on trust.

### Elsewhere

- [LinkedIn](https://www.linkedin.com/in/saeed-al-nahlawi) — weekly notes on method, not recommendations
- Open to financial analyst, equity research and risk roles in Amman and the Gulf

Based in Amman, Jordan. Arabic (native), English (fluent).

_Personal research, for educational purposes only. Nothing here is investment advice._
