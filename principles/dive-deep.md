# Dive Deep

Dive Deep means staying connected to the details and checking them personally when a summary and the facts do not agree. The strongest answer describes a summary that was wrong and explains how the candidate discovered this by examining the underlying data.

## What the interviewer listens for

- A metric, a report, or an explanation that the candidate had reason to doubt.
- Direct examination: logs, raw records, traces, or source code.
- The specific finding, with its numbers.
- The follow-up questions the interviewer asks next. Expect two or three levels of "why", and prepare the technical detail.

## Questions

1. Tell me about a time the data did not match what you were told.
2. Describe the most difficult problem you have debugged.
3. Tell me about a time you found the root cause of a recurring problem.
4. Give an example of a time you questioned a metric.
5. Tell me about a time you had to understand an unfamiliar system in detail.
6. Describe a time when looking at the details changed a decision.

## Weak and strong answers

| Answer | What it contains |
|--------|------------------|
| Weak | A statement that the candidate values data, or a problem solved by someone else's analysis |
| Strong | The doubt, the exact method of investigation, the root cause, and an answer that remains precise under repeated follow-up questions |

## Sample answer

> "Our dashboard showed an average API latency of 120 milliseconds, yet one enterprise customer kept reporting timeouts. The team's explanation was a network problem on the customer's side. I pulled the raw request logs for that customer and found that 2 percent of their requests took more than 10 seconds, which the average had hidden. All of the slow requests fetched accounts with more than 5,000 child records. I read the query and saw that it loaded each child record separately. I rewrote it as one batched query and added a 99th percentile latency chart to the dashboard. The customer's timeouts stopped, and the 99th percentile fell from 10 seconds to 400 milliseconds."

## Often paired with

- [Are Right, A Lot](are-right-a-lot.md): details are how judgment gets tested.
- [Insist on the Highest Standards](insist-on-the-highest-standards.md): a defect found in the details often becomes a quality decision.

## Go deeper

- [Grokking Modern Behavioral Interview](https://www.designgurus.io/course/grokking-behavioral-interview?utm_source=github&utm_medium=repo&utm_campaign=amazon-leadership-principles&utm_content=principles-dive-deep): worked answers with the follow-up questions interviewers ask.
- Lesson: [Technical competence and quality questions](https://www.designgurus.io/course-play/grokking-behavioral-interview/doc/technical-competence-and-quality-questions?utm_source=github&utm_medium=repo&utm_campaign=amazon-leadership-principles&utm_content=principles-dive-deep), in Grokking Modern Behavioral Interview
- [The STAR method](../guides/star-method.md): how to prepare for follow-up questions.
