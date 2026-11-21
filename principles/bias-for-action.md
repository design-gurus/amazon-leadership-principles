# Bias for Action

Bias for Action means moving quickly and accepting a calculated risk when a decision can be reversed. A strong answer shows that the candidate knew which decisions were reversible, acted on those without waiting, and limited the damage in case the decision was wrong.

## What the interviewer listens for

- Time pressure, with a stated cost of waiting.
- Information that was missing at the moment of the decision.
- A judgment about reversibility. Amazon describes reversible decisions as two-way doors and irreversible ones as one-way doors.
- A safeguard, such as a rollback plan, a small first release, or a time limit on the experiment.

## Questions

1. Tell me about a time you acted without waiting for approval.
2. Describe a decision you made quickly with incomplete information.
3. Tell me about a calculated risk you took.
4. Give an example of a time you removed an obstacle that was slowing your team.
5. Tell me about a time you acted too quickly. What did you learn?
6. Describe a time you had to choose between more analysis and a deadline.

## Weak and strong answers

| Answer | What it contains |
|--------|------------------|
| Weak | Speed presented as a virtue, with no account of the risk and no plan for being wrong |
| Strong | The cost of delay in numbers, the reason the decision was reversible, the safeguard, and the outcome |

## Sample answer

> "On a Friday afternoon, our checkout error rate rose from 0.2 percent to 4 percent after a partner changed an address validation API. The owner of that integration was on a flight for six more hours, and I estimated that we were losing about 300 orders an hour. I could not fix the integration, but I could turn the validation off with a feature flag, which is a switch that changes behavior without a deployment. The risk was some badly formatted addresses, which our support team could correct later. I informed my manager in writing, disabled the flag, and watched the error rate return to 0.2 percent within five minutes. On Monday the owner fixed the integration, and we corrected 41 addresses by hand."

## Often paired with

- [Ownership](ownership.md): acting quickly on a problem that belongs to someone else.
- [Are Right, A Lot](are-right-a-lot.md): the interviewer may test the judgment behind the fast decision.

## Go deeper

- [Grokking Modern Behavioral Interview](https://www.designgurus.io/course/grokking-behavioral-interview?utm_source=github&utm_medium=repo&utm_campaign=amazon-leadership-principles&utm_content=principles-bias-for-action): worked answers and practice for every principle.
- [The STAR method](../guides/star-method.md): how to keep a fast-moving story in order.
