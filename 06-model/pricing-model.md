# The Model · FinWise

>Pricing & Monetization. The pricing & packaging recommendation memo for FinWise.

## Stage + model

**Stage 2 — Revenue Expansion.** FinWise isn't in Stage 1 (Value Creation) — value is proven at $10M ARR with a real paying customer base, so the question isn't "does this work," it's "why isn't it converting more of the people who try it." It's also not yet Stage 3 (Optimization) — that stage assumes the model is set and revenue is growing, so the work left is tuning edges (segments, discounts, bundles). FinWise's economics are explicitly under pressure, which means the structural decisions — how the trial is packaged, where the paywall sits — haven't landed yet.

Evidence: (1) Only 2% of trial users convert to paid despite proven demand — the bottleneck is the conversion mechanism itself, not whether the product is valuable. (2) 40% one-year retention (60% churn post-conversion) shows even the users who do pay aren't durably committed, meaning the paid tier isn't yet capturing the right behavior or the right moment.

**Model: Reverse-trial + Freemium hybrid.** FinWise currently runs a pure reverse-trial — full premium access for a fixed window, then a hard cutoff. That structure is good at proving value fast (matches the Aha-moment design from Module 2: users see a personalized finding, like "$3,847 in uncategorized expenses," within their first session). But it's poorly suited to FinWise's actual usage pattern: financial management is a recurring habit (this is the same insight the Module 3 "Weekly Clear-to-Zero" mechanic was built around), not a one-time evaluation. A hard cutoff after 14 days assumes users decide fast; the data (2% conversion) says most don't. Subscription logic fits the continuous-value delivery, but only if paired with a free tier that keeps non-converters inside the habit loop instead of losing them entirely.

_____

## Recommendation

Replace the hard trial-expiration cutoff with a real, usable free tier: reconciliation, transaction categorization, and the account-connection flow stay free indefinitely. **Financial Modeling** — the forecasting/modeling output that represents FinWise's actual North Star ("reach first modeling output") — sits behind the paywall.

This is a **packaging bet** ("is packaging matched to value?"), not a price increase or a full model change: the price points don't move, the free/paid line does. The goal is to stop losing the 98% who don't convert in the trial window outright, and instead let them keep building habit on the free tier — creating a second, later opportunity to convert once they hit the modeling wall — rather than forcing a single high-stakes decision at Day 14.

Trade-off acknowledged: this sacrifices some of the urgency a hard cutoff creates (some users who might have converted under pressure may now just stay on the free tier longer). That's an accepted cost in exchange for turning acquisition into something that can compound instead of depending entirely on paid channels, which the brief flags as unsustainable.

_____

## Model signal

Financial Modeling Feature Usage % is the one leading indicator from prior usage analysis that showed a positive correlation with paid conversion (weak, but directionally real, unlike Import Feature Usage % which showed essentially none) — meaning it's the feature most associated with someone having outgrown the basics.

Success looks like: conversions clustering tightly around the point where a free-tier user first attempts to access Financial Modeling, rather than being scattered evenly across tenure — a tight cluster means the paywall is sitting exactly where users feel the need for more. A diffuse pattern (conversions unrelated to Financial Modeling attempts) would mean this isn't the right line, and the packaging bet failed even if some conversion lift shows up elsewhere.

Guardrail to watch: free-tier retention/engagement on reconciliation shouldn't collapse — if free users churn out entirely instead of sticking around to eventually hit the modeling wall, the free tier isn't doing its job of keeping them in the habit loop.

_____