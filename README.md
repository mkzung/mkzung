### Max Gorbuk

I check whether published numbers are true. Most of what I find looks fine and is
not: trading volume that no transfer supports, a price copied from another venue,
a company valuation that nobody has tested since its last funding round.

Studying for the Master in Analytics & Management at London Business School.
Research Analyst at the Stanford GSB Venture Capital Initiative under
Prof. Ilya Strebulaev.

#### What I found

[Tokenized stocks](https://github.com/mkzung/xstocks-price-discovery) trade both
on an exchange and in on-chain pools. The exchange sets the price and the pools
follow, on 21 of the 23 days I could rank.

[Two chains publish DEX volume](https://github.com/mkzung/dex-volume-integrity)
that the transfers underneath do not support. Counted from the transfers, not
from an aggregator. Three more signatures are in the
[DN Institute wiki](https://github.com/1712n/dn-institute/pulls?q=author%3Amkzung+is%3Amerged),
and the same mints, screened on a central book and in Solana pools, are in
[tokenized-equity-wash-trading](https://github.com/mkzung/tokenized-equity-wash-trading).

Mutual funds have to report a value every month for the private companies they
hold, even when nothing has traded.
[unicorn-valuation-disagreement](https://github.com/mkzung/unicorn-valuation-disagreement)
measures how far apart different managers value the same company on the same
day, from SEC filings only. SSRN working paper.

#### Open source

87 pull requests merged in 18 organisations, most of them in
[ccxt](https://github.com/ccxt/ccxt/pulls?q=author%3Amkzung+is%3Amerged),
[QuantConnect/Lean](https://github.com/QuantConnect/Lean/pulls?q=author%3Amkzung+is%3Amerged)
and the UK AI Security Institute's
[inspect_evals](https://github.com/UKGovernmentBEIS/inspect_evals/pulls?q=author%3Amkzung+is%3Amerged),
and 15 more organisations.

It is usually the same bug. A project writes down a rule and never checks it, or
a shared test runs against a list that is missing half the classes it should
cover. Feed it something degenerate and the answer comes back finite and wrong.

I wrote the Inspect AI implementation of
[Do-Not-Answer](https://github.com/mkzung/inspect-evals-do-not-answer), which UK
AISI's inspect_evals
[lists](https://github.com/UKGovernmentBEIS/inspect_evals/tree/main/register/do_not_answer),
with an adversarial suite registered beside it.
[lm-refusal-eval](https://github.com/mkzung/lm-refusal-eval) measures the same
thing and re-runs byte-identically from the same seed.

#### Elsewhere

Named contributor on the WEF and Stanford GSB report *[The Future of Venture
Capital](https://www.weforum.org/publications/the-future-of-venture-capital-unlocking-liquidity-and-growth/)*
(2026). Founded MedAI, Rospatent-registered clinical decision support for
paediatrics, running in ten clinics.

Python, pandas and Polars, Solana and EVM data, Inspect AI, some Rust and C++.

[gorbuk.com](https://gorbuk.com) · [LinkedIn](https://linkedin.com/in/gorbuk) ·
[Stanford](https://profiles.stanford.edu/gorbuk) · gorbuk@stanford.edu
