# Frugality

Frugality means achieving more with fewer resources. The principle is not about spending as little as possible. It is about a real limit on people, money, or time, and a result that was reached inside that limit through resourcefulness.

## What the interviewer listens for

- A real constraint: a fixed budget, a small team, or no possibility of new hires.
- A decision not to ask for more, or a request for more that was refused.
- An inventive use of what already existed.
- The saving expressed as a number, without harm to the customer.

## Questions

1. Tell me about a time you delivered with limited resources.
2. Describe a time you reduced a cost.
3. Tell me about a time you had to do more with less.
4. Give an example of a time you chose not to spend money that was available.
5. Tell me about a time you found a cheaper way to reach the same result.
6. Describe a time a budget limit forced you to change your design.

## Weak and strong answers

| Answer | What it contains |
|--------|------------------|
| Weak | A story in which the candidate asked for more people or budget and received them, or a saving that reduced quality for the customer |
| Strong | The limit, the options considered, the resourceful choice, and the saving in dollars, hours, or machines |

## Sample answer

> "Our image processing service ran on 40 large servers at all hours, and the monthly bill was about 38,000 dollars. My manager asked for a proposal to handle 30 percent more traffic, and the simple answer was 12 more servers. I examined a month of usage first and saw that traffic at night was one fifth of the daytime peak. I added scaling rules tied to queue length and moved the batch jobs to cheaper interruptible machines, which a cloud provider can take back at short notice. I added a retry so that an interruption lost no work. The service absorbed the extra traffic on an average of 26 servers, and the bill fell to about 24,000 dollars."

## Often paired with

- [Invent and Simplify](invent-and-simplify.md): constraints often produce a simpler design.
- [Deliver Results](deliver-results.md): the result must still be reached.

## Go deeper

- [Grokking Modern Behavioral Interview](https://www.designgurus.io/course/grokking-behavioral-interview?utm_source=github&utm_medium=repo&utm_campaign=amazon-leadership-principles&utm_content=principles-frugality): the full behavioral course, including the Amazon chapter.
- Lesson: [Managing constraints and setbacks questions](https://www.designgurus.io/course-play/grokking-behavioral-interview/doc/managing-constraints-and-setbacks-questions?utm_source=github&utm_medium=repo&utm_campaign=amazon-leadership-principles&utm_content=principles-frugality), in Grokking Modern Behavioral Interview
- [Grokking the System Design Interview](https://www.designgurus.io/course/grokking-the-system-design-interview?utm_source=github&utm_medium=repo&utm_campaign=amazon-leadership-principles&utm_content=principles-frugality): cost is also examined in the design round.
