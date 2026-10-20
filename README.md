# Paywall Audit — TapScanner

**Live:** https://bterzic123.github.io/tapscanner-paywall-audit/
**Prototype on a phone:** https://bterzic123.github.io/tapscanner-paywall-audit/?open=proto

Five ranked paywall ideas for TapScanner, each backed by a number from Adapty's
[State of Paywalls 2026](https://adapty.io/state-of-paywalls/?utm_source=paywall-audit&utm_medium=github-pages&utm_campaign=sop_2026&utm_content=tapscanner),
a scorecard of the live paywall against the report, and a clickable rebuild of the paywall
and the close moment in TapScanner's own design (Today / Proposed switch, report pins).

## The ideas

| # | Idea | Report anchor | Outcome | Label |
| :-- | :-- | :-- | :-- | :-- |
| 1 | Put the free trial on the yearly plan | 5.3 annual-forward layout; 2.4 pre-selection | ARPU +25–40% | Observed in winning A/B tests |
| 2 | Give a second chance on close | 4.5 second-chance paywalls (4% of apps; beat the main paywall in 45%) | ARPU +10–15% | Based on Adapty data |
| 3 | Show how the trial works | 5.3 trial explainer; 3.4 timeline on 24% of trial paywalls | ARPU +12–36% | Observed in winning A/B tests |
| 4 | Bring your own proof to the paywall | 5.3 social proof; 3.1 used by 27% | CR +10–30% | Observed in winning A/B tests |
| 5 | Shorten the weekly trial to three days | 2.6 trial length by plan; 5.2 trial wins 60% of LTV tests | Finding, no range | Report finding |

## Slice used

All categories (TapScanner's App Store category is Business, which the report does not cover).
Largest iOS region: Europe. Most TapScanner revenue is on Google Play and the report is App Store
only, so the audit compares paywall setup and quotes market-wide test findings, not price or
conversion benchmarks.

## Grounding

Prices (39,99 €/year, 4,49 €/week, 7-day trial, Save 85%), the headline, the feature carousel, the
reminder toggle, the 130M+ line and the Skystone review come from TapScanner's own iOS screens.
The 29,99 € offer price is TapScanner's “Unlimited Access – Yearly” price on its German App Store
listing. Impact ranges are observed lifts from winning A/B tests in State of Paywalls 2026 and
Adapty's own data, not measured results for TapScanner.

## Run locally

```
python3 -m http.server 8000
```
