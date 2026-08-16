### Max Gorbuk

I work on the gap between the reported number and the real one: fabricated volume, who actually sets a price, what a private valuation headline is worth.

Nothing ships until a checker can fail it.

Stanford GSB Venture Capital Initiative (Prof. Ilya Strebulaev). MSc Analytics & Management, London Business School, from Aug 2026.

39 pull requests merged upstream across 12 organisations, in [ccxt](https://github.com/ccxt/ccxt/pulls?q=author%3Amkzung+is%3Amerged) x12, [QuantConnect/Lean](https://github.com/QuantConnect/Lean/pulls?q=author%3Amkzung+is%3Amerged) x7, [nautilus_trader](https://github.com/nautechsystems/nautilus_trader/pulls?q=author%3Amkzung+is%3Amerged) x4, UK AI Security Institute's [inspect_evals](https://github.com/UKGovernmentBEIS/inspect_evals/pulls?q=author%3Amkzung+is%3Amerged) x3 and [inspect_ai](https://github.com/UKGovernmentBEIS/inspect_ai/pulls?q=author%3Amkzung+is%3Amerged), [DN Institute](https://github.com/1712n/dn-institute/pulls?q=author%3Amkzung+is%3Amerged) x3, [aeon](https://github.com/aeon-toolkit/aeon/pulls?q=author%3Amkzung+is%3Amerged) x2, [Nethermind](https://github.com/NethermindEth/execution-payloads-benchmarks/pulls?q=author%3Amkzung+is%3Amerged) x2, and one each in [Gymnasium](https://github.com/Farama-Foundation/Gymnasium/pulls?q=author%3Amkzung+is%3Amerged), [Apache Arrow](https://github.com/apache/arrow/pull/50475), [Polars](https://github.com/pola-rs/polars/pull/28220), [freqtrade](https://github.com/freqtrade/freqtrade/pull/13361) and [DefiLlama](https://github.com/DefiLlama/DefiLlama-Adapters/pull/19900).

Mostly the same shape of bug: an invariant the project documents but never checks, a shared test that runs against a registry missing half its classes, or an input degenerate enough that the answer comes back finite and wrong.

#### Market forensics

- [xstocks-price-discovery](https://github.com/mkzung/xstocks-price-discovery): which venue prices a tokenized stock. The exchange leads 21 of 23 rankable pair-days, and the quieter a pool, the more the exchange prints against it, at a rank correlation of -0.93.
- [dex-volume-integrity](https://github.com/mkzung/dex-volume-integrity): fabricated volume on Base and BNB Chain, counted from transfers rather than from an aggregator.
- [tokenized-equity-wash-trading](https://github.com/mkzung/tokenized-equity-wash-trading): the same mints screened on a centralised book and in Solana pools. Three more signatures published in the [DN Institute wiki](https://github.com/1712n/dn-institute/pulls?q=author%3Amkzung+is%3Amerged).

#### Private-market valuation

- [unicorn-valuation-disagreement](https://github.com/mkzung/unicorn-valuation-disagreement): unicorn marks triangulated against mutual-fund N-PORT filings, public data only. SSRN working paper.

#### LLM evaluation

- [inspect-evals-do-not-answer](https://github.com/mkzung/inspect-evals-do-not-answer): Do-Not-Answer with an adversarial jailbreak suite, merged into UK AISI's [inspect_evals](https://github.com/UKGovernmentBEIS/inspect_evals/tree/main/register/do_not_answer) and maintained upstream by me.
- [lm-refusal-eval](https://github.com/mkzung/lm-refusal-eval): the same measurement, byte-identical across reruns.

Also: [alphaforge](https://github.com/mkzung/alphaforge) (factor backtesting), [morpho-vault-counterfactuals](https://github.com/mkzung/morpho-vault-counterfactuals) (six risk detectors on Morpho vault history), [fundarb](https://github.com/mkzung/fundarb) (funding-rate arbitrage).

Elsewhere: named contributor on the WEF x Stanford GSB report *[The Future of Venture Capital](https://www.weforum.org/publications/the-future-of-venture-capital-unlocking-liquidity-and-growth/)* (2026), and founder of MedAI, Rospatent-registered pediatric clinical decision support, live in 10 clinics.

Off the clock I trace a family line back to a man born around 1770, held to the same evidence rule, which nineteenth-century parish clerks did nothing to make easier.

Python, pandas/Polars, Solana and EVM data, Inspect AI, Rust, C++ where a fix needs it.

[gorbuk.com](https://gorbuk.com) · [LinkedIn](https://linkedin.com/in/gorbuk) · [Stanford](https://profiles.stanford.edu/gorbuk) · gorbuk@stanford.edu
