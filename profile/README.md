# Warestack

Inspect the interpretation, evidence and actions behind engineering delivery.

A pull request can have passing CI, requested changes and an unresolved rule finding at the same time. A merged pull request can still have no linked production deployment. Warestack keeps those states visible alongside their source records.

**Rules** evaluate selected delivery standards. **Chains** run configured follow-up. **Reports** answer questions over the recorded changes and expose the query and rows behind the result.

[Install on GitHub](https://github.com/marketplace/warestack) · [Documentation](https://documentation.warestack.com/) · [Product](https://www.warestack.com)

![Current and proposed versions of a saved agent-evaluated interpretation](https://raw.githubusercontent.com/warestack/.github/main/profile/media/rules-interpretation.png)

*Reconstructed product UI with fictional sample data. The images show selected workflows, not customer results or unmodified production screenshots.*

## Review an interpretation before enabling a check

Choose a catalog rule or describe a supported check. Inspect its interpretation, the selected evidence and the scope where it will run. Findings remain tied to the change; incomplete or unavailable evidence is explicit.

For **saved agent-evaluated interpretations**, the console keeps a current version and compares it with a proposed version. Re-interpret proposes changes to the checks; review the diff, then choose Keep current or Adopt. Existing findings keep their recorded interpretation, while later evaluations use the adopted version. Model metadata records which model produced the saved interpretation.

[Custom-rule authoring and updates](https://documentation.warestack.com/model-context-protocol) are documented separately from rule evaluation.

For example, a check for rollback notes can inspect the PR body and changed migration path. Its result establishes whether the notes are present. A reviewer still assesses whether the proposed rollback is safe.

![Draft rule, source excerpt and evaluation result](https://raw.githubusercontent.com/warestack/.github/main/profile/media/rules-evaluation.png)

![One reporting-only finding and its source evidence on GitHub](https://raw.githubusercontent.com/warestack/.github/main/profile/media/github-check.png)

*The sample Warestack finding is reporting-only. Other GitHub checks or branch protection can still prevent merge.*

## Configure what happens next

A Chain defines a trigger, conditions, ordered steps, destination and stop condition. Use it to maintain a Slack live card, follow up on a requested review, announce a production deployment or run and deliver a saved report.

Review the definition and recipients before enabling it. Chains that write to GitHub require a reviewed dry run of the current definition. Execution history records what ran and its outcome.

![Chain definition with trigger, steps, destination and stop condition](https://raw.githubusercontent.com/warestack/.github/main/profile/media/chains-review.png)

## Inspect the result and the records behind it

Describe a delivery question, review the interpreted query and preview the supporting rows. Save the report, export CSV, or configure a Chain to run and deliver it. A brief can summarize a report with links to its evidence.

Missing deployment evidence stays **unknown**. Delivery and review metrics retain their definitions, selected period and repository breakdowns where evidence exists.

![Interpreted report question, supporting rows and evidence gaps](https://raw.githubusercontent.com/warestack/.github/main/profile/media/reports-evidence.png)

## Install, inspect, then enable

1. Install the GitHub App and select its repository access.
2. Choose the rule and reporting scope you want to inspect.
3. Review interpretations, findings and report rows.
4. Configure and enable only the Chains you need.

Installation does not enable every rule or action. Requiring Warestack Rules in GitHub branch protection is a separate, opt-in choice.

**GitHub** provides change and delivery records. **Slack** supports configured follow-up and report delivery. **Linear** connects linked issue context. **Jira Cloud** support is in progress; confirm availability and project setup.

[Integration details](https://www.warestack.com/integrations) · [Permissions and data handling](https://www.warestack.com/security) · [Support](https://www.warestack.com/support)

## Plans

- **Free:** $0, up to five enabled repositories, no usage charges.
- **Pro — planned:** $49 per space/month plus usage beyond included allowances, with no per-seat charge. Availability and terms are confirmed before purchase.
- **Enterprise:** agreed usage, retention and support terms.

[Current pricing and allowances](https://www.warestack.com/pricing)

## Open source

[Watchflow](https://github.com/warestack/watchflow) is Warestack's separate open-source project for context-aware GitHub guardrails. Its repository documents its own features, setup and license.
