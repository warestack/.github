<p align="center">
  <img src="https://avatars.githubusercontent.com/u/68270387?s=200&v=4" alt="Warestack logo" width="72" />
</p>

<h1 align="center">Warestack</h1>

<p align="center"><strong>Put your engineering standards into practice.</strong></p>

<p align="center">
  <a href="https://github.com/marketplace/warestack">Install on GitHub</a>
  · <a href="https://www.warestack.com">Explore the product</a>
  · <a href="https://documentation.warestack.com/">Documentation</a>
  · <a href="https://calendly.com/warestack/intro-call">Book a demo</a>
</p>

Release checks still depend on someone remembering them. Follow-ups become manual chasing. Delivery updates mean piecing together pull requests, tickets and deployments.

Warestack connects **Rules, Chains and Reports** so your team can make agreed standards checkable, coordinate follow-through and inspect the evidence behind delivery answers.

<a href="https://www.warestack.com">
  <img src="https://raw.githubusercontent.com/warestack/.github/main/profile/media/warestack.png" alt="Warestack dashboard: rule interpretation, configured chain steps and report evidence rows" width="100%" />
</a>

*Product UI adapted from Warestack's dashboard components. All images use fictional sample data; they are not customer results or unmodified console screenshots.*

## Rules — make standards checkable

Start with a catalog rule or describe a supported check in plain English. Review its interpretation and named evidence, then enable it for the teams, repositories or paths where it applies. Findings stay tied to the change; unavailable evidence is explicit.

For example, inspect whether a migration change includes rollback notes alongside the relevant PR body and changed path. That checks for the notes, not the safety of a rollback.

## Chains — coordinate follow-through

Choose what starts a chain, its ordered steps and destinations, and when it stops. Keep a Slack live card current, remind a reviewer until a review arrives, announce a deployment or deliver a saved report.

Review the configuration before enabling. For chains that write to GitHub, run and review a successful dry run of the current definition. Connecting a tool does not enable every action.

## Reports — answer with evidence

Ask delivery questions in plain English, inspect the interpreted query and supporting rows, then save or schedule the report for Slack or email. Export CSV or add an evidence-linked brief when useful. Missing production evidence stays **unknown**.

Analytics adds delivery and review metrics with definitions, period comparisons and repository breakdowns.

| Rules | Chains | Reports |
| --- | --- | --- |
| [![Rule interpretation beside a finding and source evidence](https://raw.githubusercontent.com/warestack/.github/main/profile/media/rules.png)](https://www.warestack.com/product/rules) | [![Configured chain trigger, steps, stop condition and message preview](https://raw.githubusercontent.com/warestack/.github/main/profile/media/chains.png)](https://www.warestack.com/product/chains) | [![Delivery report with source rows, deployment links and unknown evidence](https://raw.githubusercontent.com/warestack/.github/main/profile/media/reports.png)](https://www.warestack.com/product/reports) |

## Start with a scope you can inspect

1. Install Warestack and connect your GitHub organization.
2. Select the repositories, standards and evidence you want to start with.
3. Inspect findings and test configured follow-through before enabling it.
4. Use Reports to answer a delivery question and open the records behind it.

Rules report findings first. Requiring a Warestack check in GitHub branch protection is a separate, opt-in choice.

## Integrations and availability

**GitHub** supplies change and delivery evidence. **Slack** supports configured follow-up and report delivery. **Linear** connects linked issue context with the delivery workflow. Jira Cloud support is **in progress**; confirm availability and project setup.

[Explore integrations](https://www.warestack.com/integrations) · [Security](https://www.warestack.com/security)

## Pricing

- **Free:** $0, up to five enabled repositories and no usage charges.
- **Pro — planned:** $49 per space/month plus usage beyond included allowances; no per-seat charge. Confirm availability and terms before purchase.
- **Enterprise:** agreed usage, retention and support terms.

These are shared Warestack platform plans. [See current pricing and allowances](https://www.warestack.com/pricing).

## Open source

[Watchflow](https://github.com/warestack/watchflow) is our separate open-source project for context-aware GitHub guardrails. Explore its repository for its own features, setup and license.
