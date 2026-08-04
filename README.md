### Max Gorbuk

Stanford GSB Venture Capital Initiative (Prof. Ilya Strebulaev). Incoming MSc Analytics & Management, London Business School, Aug 2026.

I work where the reported number and the real one differ. Everything below is public and reproducible from committed data.

**15 pull requests merged upstream across 8 organisations**: [Apache Arrow](https://github.com/apache/arrow/pull/50475), [Polars](https://github.com/pola-rs/polars/pull/28220), [ccxt](https://github.com/ccxt/ccxt/pulls?q=author%3Amkzung+is%3Amerged) x3, [freqtrade](https://github.com/freqtrade/freqtrade/pull/13361), [DefiLlama](https://github.com/DefiLlama/DefiLlama-Adapters/pull/19900), UK AI Security Institute's [inspect_evals](https://github.com/UKGovernmentBEIS/inspect_evals/pulls?q=author%3Amkzung+is%3Amerged) x3, Nethermind x2, [DN Institute](https://github.com/1712n/dn-institute/pulls?q=author%3Amkzung+is%3Amerged) x3.

- Named contributor, WEF x Stanford GSB, *[The Future of Venture Capital](https://www.weforum.org/publications/the-future-of-venture-capital-unlocking-liquidity-and-growth/)* (2026, with Gompers, Kaplan, Weisbach).
- Founder of MedAI: pediatric clinical decision support, Rospatent-registered, live in 10 clinics.

---

**Which venue sets the price.** [xstocks-price-discovery](https://github.com/mkzung/xstocks-price-discovery): 24 tokenized stocks quoted at once on Gate and in Solana pools. The exchange leads 21 of 23 rankable pair-days, and the quieter a pool the more the exchange prints against it, at a rank correlation of -0.93. Every number in the write-up is re-read out of the data in CI.

**Is the reported volume real.** [dex-volume-integrity](https://github.com/mkzung/dex-volume-integrity) counts fabricated volume on Base and BNB Chain from transfers rather than from an aggregator. [gate-xstocks](https://github.com/mkzung/gate-xstocks-wash-analysis) and [solana-xstocks](https://github.com/mkzung/solana-xstocks-wash-analysis) screen the same mints on both venues; [tokenized-equity-wash-trading](https://github.com/mkzung/tokenized-equity-wash-trading) is the paper they build into. Three signatures on one exchange, published in the DN Institute wiki: [recurring-clip wash](https://github.com/mkzung/bybit-wash-trading-analysis), [a fixed-clock bot](https://github.com/mkzung/cbk-scheduled-wash-analysis), [a one-hour pump](https://github.com/mkzung/mcrt-pump-dump-analysis).

**What a private valuation headline is worth.** [unicorn-valuation-disagreement](https://github.com/mkzung/unicorn-valuation-disagreement): unicorn marks triangulated against mutual-fund N-PORT filings, public data only. SSRN working paper. Earlier notebooks in [vc-pattern-notebooks](https://github.com/mkzung/vc-pattern-notebooks).

**Do refusal benchmarks measure what they claim.** [inspect-evals-do-not-answer](https://github.com/mkzung/inspect-evals-do-not-answer): Do-Not-Answer with an adversarial jailbreak suite, merged into UK AISI's [inspect_evals](https://github.com/UKGovernmentBEIS/inspect_evals/tree/main/register/do_not_answer) and maintained upstream by me. [lm-refusal-eval](https://github.com/mkzung/lm-refusal-eval): the same measurement, byte-identical across reruns.

**Quant tooling.** [alphaforge](https://github.com/mkzung/alphaforge): cross-sectional backtesting and factor research. [morpho-vault-counterfactuals](https://github.com/mkzung/morpho-vault-counterfactuals): six risk detectors replayed against Morpho vault history. [fundarb](https://github.com/mkzung/fundarb): funding-rate arbitrage across venues.

---

Python, pandas/Polars, Solana and EVM data, Inspect AI, Rust, C++ where a fix needs it.

[gorbuk.com](https://gorbuk.com) · [LinkedIn](https://linkedin.com/in/gorbuk) · [Stanford](https://profiles.stanford.edu/gorbuk) · gorbuk@stanford.edu
