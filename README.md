### Hi, I'm Max 👋

Researcher at **Stanford GSB's Venture Capital Initiative** under Prof. Ilya Strebulaev. **Named contributor (Acknowledgements)** on the published WEF / Stanford GSB Insight Report ["The Future of Venture Capital: Unlocking Liquidity and Growth"](https://www.weforum.org/publications/the-future-of-venture-capital-unlocking-liquidity-and-growth/) (May 2026, 46 pages) — co-credited alongside Paul Gompers (Harvard), Steven Kaplan (Chicago Booth), and Michael Weisbach (Ohio State).

Architected an **AI research-automation pipeline** (Python · n8n · OpenAI API) that compressed per-study processing from **~1 week of manual work to ~10 minutes at ~$0.80/study**; maintain Python pipelines over **PitchBook · WRDS · SDC Platinum** (>2M rows) for the Initiative's **1,500+ unicorn flagship** analysis (referenced in section 3 of the published WEF report).

Founder of **MedAI** — Rospatent-registered (№2025662413) clinical decision-support system for pediatric vaccination under immunosuppressive therapy. Live in **3 clinics, 25 physicians**; first-week deployment flagged an incorrect vaccine dose, preventing a potential adverse event. Ranked **#57 in Russia's Top-1000 University Startups 2025**.

Concurrently shipping AI-automation tooling (Python + OpenAI API + n8n) for a 120-person construction firm.

Incoming Master in Analytics & Management at London Business School (London, Aug 2026 start).

🔗 [LinkedIn](https://linkedin.com/in/gorbuk) · [Stanford profile](https://profiles.stanford.edu/gorbuk) · gorbuk@stanford.edu

---

#### Recent

- **[ethbtc-suspicious-patterns](https://github.com/mkzung/ethbtc-suspicious-patterns)** — six-detector forensic analysis of ETH/BTC market data ([live dashboard](https://mkzung.github.io/ethbtc-suspicious-patterns/) · [PR #24 on 1712n/market-data-challenge](https://github.com/1712n/market-data-challenge/pull/24)). DN Institute Challenge #492 submission. **99.9994% one-sided buy size with zero price impact** + identical-clip burst signature 13× across 22h. 46/46 pytest, byte-identical reproducibility, CI on Py 3.10/3.11/3.12.
- **[lm-refusal-eval](https://github.com/mkzung/lm-refusal-eval)** — reproducible refusal-rate evaluation harness for open-weight LLMs. Pluggable HuggingFace + OpenAI + Anthropic adapters, rule-based + LLM-judge, Wilson + Newcombe statistical CIs, provenance schema for byte-identical reruns. **336/336 pytest, mypy --strict, ruff clean.** Motivated by FAR.AI's robustness-scaling work.
- **[morpho-vault-counterfactuals](https://github.com/mkzung/morpho-vault-counterfactuals)** — counterfactual replay over live Morpho MetaMorpho vaults (Ethereum). Six detectors over the bad-debt frontier with Pydantic-frozen state + nightly cron pulling Steakhouse USDC. 65/65 pytest.
- **[kamino-vault-counterfactuals](https://github.com/mkzung/kamino-vault-counterfactuals)** — Solana port of the above via Kamino. 95/95 pytest, six detectors, historical replay command, base58-correct synthetic fixtures.
- **[drift-funding-monitor](https://github.com/mkzung/drift-funding-monitor)** — cross-venue funding-rate monitor (Hyperliquid live; Drift / Orderly / Backpack scaffolded). 97/97 pytest, per-symbol funding-interval discovery, basis-aware drawdown gate.
- **[solana-vault-thresholds](https://github.com/mkzung/solana-vault-thresholds)** — Anchor 0.30.1 / Rust on-chain program. Sticky-edge breach semantics, immutable audit-trail events, `has_one` account validation, monotonic-slot guard on metric updates.
- **[contract-tracker](https://github.com/mkzung/contract-tracker)** — production email-driven contract-approval tracker for a construction firm. IMAP + RFC-5322 thread reconstruction + OpenAI JSON-mode classifier + Streamlit dashboard. Python, SQLAlchemy, APScheduler, systemd.
- **[fundarb](https://github.com/mkzung/fundarb)** — cross-venue funding-rate arbitrage CLI for crypto perpetuals (**Hyperliquid + Orderly + Backpack**); Ed25519 + EIP-712 signing, async venue clients. **Used for live signal generation and execution on personal capital.**

#### What I work on

- **Data engineering** — ETL/ELT pipelines, schema design, reproducible analysis, automation tooling
- **Crypto market microstructure** — wash-trading detection, perpetual-futures funding-rate arbitrage, on-chain forensics
- **Applied AI / LLM workflows** — OpenAI API automation, n8n orchestration, structured-output classifiers, clinical decision support
- **VC research** — unicorn formation, time-to-unicorn dynamics, founder/team factors

#### Skills

`Python` · `SQL` · `pandas` · `numpy` · `scipy` · `pytest` · `SQLAlchemy` · `Docker` · `Git` · `GitHub Actions (CI/CD)` · `n8n` · `OpenAI API` · `PostgreSQL` · `MongoDB` · `Streamlit`
