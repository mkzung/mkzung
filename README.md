### Max Gorbuk

Researcher at **Stanford GSB's Venture Capital Initiative** (Prof. Ilya Strebulaev), incoming **MSc Analytics & Management, London Business School** (Aug 2026).

I work on questions where the reported number and the real one differ: fabricated trading volume, which venue actually sets a price, what a private valuation headline is worth. Everything below is public, reproducible from committed data, and checked in CI.

**15 pull requests merged upstream across 8 organisations**, including [Apache Arrow](https://github.com/apache/arrow/pull/50475) (C++ dictionary index types), [Polars](https://github.com/pola-rs/polars/pull/28220), [ccxt](https://github.com/ccxt/ccxt/pulls?q=author%3Amkzung+is%3Amerged) (3), [freqtrade](https://github.com/freqtrade/freqtrade/pull/13361), [DefiLlama](https://github.com/DefiLlama/DefiLlama-Adapters/pull/19900), the UK AI Security Institute's [inspect_evals](https://github.com/UKGovernmentBEIS/inspect_evals/pulls?q=author%3Amkzung+is%3Amerged) (3), Nethermind (2) and the DN Institute wiki (3).

- Named contributor on the WEF x Stanford GSB report *[The Future of Venture Capital](https://www.weforum.org/publications/the-future-of-venture-capital-unlocking-liquidity-and-growth/)* (2026; with Gompers, Kaplan, Weisbach).
- Founder of **MedAI**, a Rospatent-registered pediatric clinical decision-support system, live in 10 clinics and ranked #57 in Russia's Top-1000 University Startups.

---

#### Does the reported volume mean anything

- **[dex-volume-integrity](https://github.com/mkzung/dex-volume-integrity)**: on-chain census of fabricated volume in low-cap pools on Base and BNB Chain, counted from transfers rather than from an aggregator.
- **[gate-xstocks-wash-analysis](https://github.com/mkzung/gate-xstocks-wash-analysis)** and **[solana-xstocks-wash-analysis](https://github.com/mkzung/solana-xstocks-wash-analysis)**: the same tokenized stocks screened on a centralised book and in Solana pools, then compared.
- **[tokenized-equity-wash-trading](https://github.com/mkzung/tokenized-equity-wash-trading)**: the working paper the two build into, with cross-venue evidence one mint at a time.
- **[bybit-wash-trading-analysis](https://github.com/mkzung/bybit-wash-trading-analysis)**, **[cbk-scheduled-wash-analysis](https://github.com/mkzung/cbk-scheduled-wash-analysis)**, **[mcrt-pump-dump-analysis](https://github.com/mkzung/mcrt-pump-dump-analysis)**: three signatures on one exchange, a recurring-clip wash, a fixed-clock bot and a one-hour pump. Published in the DN Institute wiki.

#### Which venue sets the price

- **[xstocks-price-discovery](https://github.com/mkzung/xstocks-price-discovery)**: Gonzalo-Granger weights and Hasbrouck shares on 24 tokenized stocks quoted at once on Gate and in Solana pools. The exchange leads in 21 of 23 rankable pair-days, and the quieter a token's pool, the more the exchange prints against it, at a rank correlation of -0.93. Every number in the write-up is re-read out of the committed CSVs by a checker that fails the build if one drifts.

#### What a private valuation headline is worth

- **[unicorn-valuation-disagreement](https://github.com/mkzung/unicorn-valuation-disagreement)**: public-data triangulation of unicorn marks against mutual-fund N-PORT filings. Working paper on SSRN.
- **[vc-pattern-notebooks](https://github.com/mkzung/vc-pattern-notebooks)**: unicorn formation and fund-cohort analysis on venture-stage data.

#### Do refusal benchmarks measure what they claim

- **[inspect-evals-do-not-answer](https://github.com/mkzung/inspect-evals-do-not-answer)**: the Do-Not-Answer safeguard benchmark as an Inspect AI eval, with an adversarial jailbreak suite. **Merged into the UK AI Security Institute's [inspect_evals](https://github.com/UKGovernmentBEIS/inspect_evals/tree/main/register/do_not_answer)** and listed in their README, maintained upstream by me.
- **[lm-refusal-eval](https://github.com/mkzung/lm-refusal-eval)**: refusal-rate harness for open-weight models, byte-identical across reruns.
- **[do-not-answer-environment](https://github.com/mkzung/do-not-answer-environment)**: the same benchmark as a Prime Intellect verifiers environment.

#### Tools I needed and could not find

- **[alphaforge](https://github.com/mkzung/alphaforge)**: cross-sectional backtesting and factor research, a panel of prices in and a long-short book out.
- **[morpho-vault-counterfactuals](https://github.com/mkzung/morpho-vault-counterfactuals)**: historical replay and stress testing for Morpho vaults, six risk detectors.
- **[fundarb](https://github.com/mkzung/fundarb)**: cross-venue funding-rate arbitrage for perpetuals.

---

**Stack:** Python, pandas/Polars, on-chain data (Solana, EVM), Inspect AI, Rust (Anchor), C++ where a fix needs it.

[gorbuk.com](https://gorbuk.com) · [LinkedIn](https://linkedin.com/in/gorbuk) · [Stanford profile](https://profiles.stanford.edu/gorbuk) · gorbuk@stanford.edu
