# The Validation · FinWise

Experimentation Methods. The experiment brief: method, hypothesis, guardrail, and read date.

## Method

Standard A/B Test. Single, self-contained onboarding change tested on a stable population of new trial sign-ups — no shared-environment contamination, no urgent per-user cost that would need a bandit's real-time reallocation. Standard test gives the cleanest signal without overcomplicating it.

## Experiment name

Import-First Onboarding Test

## Objective

Increase the number of trial users who import financial data and reach their first modeling output, via the redesigned onboarding flow.

## Hypothesis + primary metric

If we replace FinWise's current onboarding with the import-first flow (intent tap → connect account → personalized headline finding), then **Get Started Import Feature Usage %** will increase — our strongest leading indicator toward paid conversion based on prior funnel and usage analysis.

**Success threshold:** 15% relative increase within the first 14 days of a trial (an assumed target — no formal MDE calculated).

## Guardrail + read date

**Guardrail:** **Trial-to-Paid Conversion Rate** must not drop below its historical floor of ~1.87%.

**Read date:** **Day 14** of each trial cohort's window. Decided before launch — no peeking early.

## What's being tested

Current experience = original onboarding flow. New experience = the redesigned 3-screen import-first flow. Target segment = all new trial sign-ups during the test window.

## Predicted outcome

Import % rises ≥15% relative within 14 days, Trial-to-Paid holds at or above 1.87%.

**If successful:** Roll out to 100% of new trials, then test the weekly engagement mechanic next.

**If unsuccessful:** Check the guardrail and session data for friction; consider a shorter 2-screen version, or revisit whether Import % is the right leading indicator given its weak observed correlation with conversion so far.

## Data Studio

[FinWise experiment report](https://datastudio.google.com/reporting/b2944a82-ee57-47f7-b838-fa9599111d8a)
