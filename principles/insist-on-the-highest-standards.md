# Insist on the Highest Standards

Insist on the Highest Standards means holding work to a quality level that others may consider too demanding, and fixing defects at their source so that they do not pass to the next team. The clearest evidence is a moment when the candidate refused to ship something and accepted the cost of that refusal.

## What the interviewer listens for

- A defined standard, such as an error rate, a test requirement, or a latency target.
- A point where the standard conflicted with a deadline or with a colleague's opinion.
- The cost of holding the standard, stated plainly.
- A lasting change that raised quality for the whole team, not one corrected defect.

## Questions

1. Tell me about a time you were not satisfied with the quality of something.
2. Describe a time you refused to release work that others considered ready.
3. Tell me about a time you raised the quality standard on your team.
4. Give an example of a time you found a defect that others had missed.
5. Tell me about a time you could not meet your own standard. What did you do?
6. How do you balance quality against a deadline? Give a specific example.

## Weak and strong answers

| Answer | What it contains |
|--------|------------------|
| Weak | A claim to be a perfectionist, or a defect fixed with no standard named and no cost paid |
| Strong | The standard in numbers, the conflict, the price of holding it, and a process change that kept quality high afterwards |

## Sample answer

> "Two days before a payment feature was due, our integration tests passed, but I noticed that 3 of 2,000 test transactions had recorded a duplicate charge. My manager considered the rate acceptable for a first release. I disagreed, because at our volume of 50,000 payments a day that rate meant about 75 customers charged twice daily. I asked for a three-day delay and explained the number to the product director myself. I found a retry that lacked an idempotency key, which is an identifier that lets a server ignore a repeated request. I fixed it and added a duplicate-charge test to the release pipeline. We shipped three days late with zero duplicates in the first month."

## Often paired with

- [Dive Deep](dive-deep.md): a high standard is enforced by examining details.
- [Have Backbone; Disagree and Commit](have-backbone-disagree-and-commit.md): holding a standard often requires disagreement.

## Go deeper

- [Grokking Modern Behavioral Interview](https://www.designgurus.io/course/grokking-behavioral-interview?utm_source=github&utm_medium=repo&utm_campaign=amazon-leadership-principles&utm_content=principles-insist-on-the-highest-standards): worked answers and practice for every principle.
- [Common mistakes](../guides/common-mistakes.md): how answers on this principle are weakened.
