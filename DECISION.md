# Team decision record

Team name: AM

## Findings

One row per flaw. **Type** must be one of: `sensor`, `constraint`, `actuation`.

| # | Where (file) | What is wrong | Type |
|---|---|---|---|
| 1 | deploy-role-policy.json | Multiple resources with * (ALL) resources allocated, and user with create user permissions. | constraint |
| 2 | variables.tf | db was publicly accessible through Terraform | constraint |
| 3 | ci-cd.yml | Password is not guaranteed to be placed in build logs. Changed to "SECRETS". | constraint |
| 4 |  |  |  |
| 5 |  |  |  |
| 6 |  |  |  |
| 7 |  |  |  |
| 8 |  |  |  |

## Verdict

Evaluate the system **as you received it**, before your fixes.

Decision: <!-- DEPLOY / DO NOT DEPLOY / ESCALATE -->

Rules triggered: <!-- e.g. Rule 1, Rule 4 -->

Reasoning: <!-- two or three sentences -->
