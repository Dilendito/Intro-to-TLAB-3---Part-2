# Intro-to-TLAB-3---Part-2
## Context Setting
Establish what was already done before this A/B test. What are some questions you can ask to get more information on what has already been measured, analyzed, or attempted? List them below...

* Have we run any similar A/B tests on this specific feature in the past, and if so, what were the key takeaways or failures?
* Are there any existing baseline metrics, historical data dashboards, or previous exploratory analyses I should review before diving into this new dataset?
* What specific hypotheses were already explored or completely ruled out by the team before initiating this current test?

## Goal Alignment
Align with stakeholders on what success means before interpreting any numbers.

* What is the absolute primary Key Performance Indicator (KPI) we are trying to move with this test, and what target percentage increase signifies a definitive "win" for NotGPT?
* Are there any secondary or "guardrail" metrics we need to monitor to ensure we aren't accidentally tanking other areas of the platform while improving this one?
* If the results are statistically significant but the actual lift is incredibly small, would we still consider the engineering effort of implementing the change worth it?

## Define Over-performance
Consider what it would mean if the treatment dramatically exceeded expectations.

* If this treatment completely blows our primary metric out of the water, are our current data pipelines and infrastructure actually prepared to handle a full 100% rollout right away?
* What is the threshold where the results are *so* good that we should immediately suspect a tracking error, bot activity, or data anomaly rather than genuine user behavior?

## Data Sourcing
Reflect on what other data sources you can use to answer your stakeholders exploratory goals.

* Beyond the core A/B test event logs, do we have access to qualitative user feedback or customer support tickets that might explain the *why* behind the numbers?
* Can we cross-reference this test data with demographic or user segmentation tables to see if the treatment impacted specific user groups differently?
