# Warestack

Warestack helps engineering teams ship independently while keeping shared standards visible in everyday delivery.

Your standards already live in repository instructions, review expectations, and work-item requirements. Warestack turns supported standards into checks for pull requests and delivery workflows, showing what was assessed, which evidence was used, and what needs attention.

[Install on GitHub](https://github.com/marketplace/warestack) · [Documentation](https://documentation.warestack.com/) · [Explore Warestack](https://www.warestack.com)

## Check the standards your team works by

Some expectations are straightforward to validate: a linked issue has an owner, or a change has the required human approvals. Others need context: whether the change matches the linked work, includes meaningful testing evidence, or follows supported repository instructions.

Warestack combines deterministic validators with agentic checks so teams can assess both kinds of expectation.

Use it to:

- Check linked work items, ownership, and workflow state.
- Assess alignment between a pull request and its linked issue.
- Check review requirements and supporting evidence.
- Apply supported written standards within the relevant repository scope.
- Record findings against the change, with unavailable evidence made explicit.

![Draft rule, source excerpt and evaluation result](https://raw.githubusercontent.com/warestack/.github/main/profile/media/rules-evaluation.png)

*Reconstructed product UI with fictional sample data. The images show selected workflows, not customer results or unmodified production screenshots.*

## Keep the evidence close to the decision

Review the interpretation of a custom rule before enabling it. Inspect the evidence behind a finding and see what remains unresolved.

![Current and proposed versions of a saved agent-evaluated interpretation](https://raw.githubusercontent.com/warestack/.github/main/profile/media/rules-interpretation.png)

Start with reporting. Require the Warestack Rules check in GitHub branch protection when you want selected rules to gate merges.

![One reporting-only finding and its source evidence on GitHub](https://raw.githubusercontent.com/warestack/.github/main/profile/media/github-check.png)

*The sample Warestack finding is reporting-only. Other GitHub checks or branch protection can still prevent merge.*

## Connect checks with follow-up and reporting

**Rules** assess engineering standards and record findings.

**Chains** run configured follow-up, such as maintaining a Slack live card, following up on a review, or delivering a saved report.

![Chain definition with trigger, steps, destination and stop condition](https://raw.githubusercontent.com/warestack/.github/main/profile/media/chains-review.png)

**Reports** answer delivery questions and expose the query and supporting records behind the result.

![Interpreted report question, supporting rows and evidence gaps](https://raw.githubusercontent.com/warestack/.github/main/profile/media/reports-evidence.png)

GitHub provides change and delivery records. Linear adds linked work-item context. Slack brings configured follow-up into the team's workflow. Jira Cloud support is in progress; confirm availability and project setup.

## Start with a small scope

Install the GitHub App, select the repositories, and enable the standards you want to assess. Review the first findings, tune the rules, and choose which follow-up or enforcement to enable.

[Get started](https://documentation.warestack.com/) · [Permissions and data handling](https://www.warestack.com/security) · [Support](https://www.warestack.com/support)

## Plans

- **Free:** $0, up to five enabled repositories, no usage charges.
- **Pro — planned:** $49 per space/month plus usage beyond included allowances, with no per-seat charge. Availability and terms are confirmed before purchase.
- **Enterprise:** agreed usage, retention and support terms.

[Current pricing and allowances](https://www.warestack.com/pricing)

## Open source

[Watchflow](https://github.com/warestack/watchflow) is our separate open-source project for context-aware GitHub guardrails. Its repository documents its features, setup, and license.
