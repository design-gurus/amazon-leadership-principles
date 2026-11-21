# Invent and Simplify

Invent and Simplify means finding a better way to do something and removing complexity that no longer justifies its cost. Interviewers value the simplification half at least as much as the invention half, because removing a step or a system is harder to justify than adding one.

## What the interviewer listens for

- A process or system that was more complicated than the problem required.
- An idea that came from the candidate, including ideas adapted from another team or field.
- Something removed: a step, a service, a configuration option, or a manual task.
- A measured effect on time, errors, or cost.

## Questions

1. Tell me about a time you made something simpler.
2. Describe an innovative solution you created for a problem.
3. Tell me about a time you removed a process or a feature.
4. Give an example of a time you solved a problem in a way nobody had tried before.
5. Tell me about a time your new idea was rejected. What happened next?
6. Describe a time you borrowed an idea from another team to solve your problem.

## Weak and strong answers

| Answer | What it contains |
|--------|------------------|
| Weak | A new tool or framework adopted because it was modern, with no statement of what became simpler |
| Strong | The original complexity in numbers, the idea, what was deleted, and the before and after measurement |

## Sample answer

> "Releasing our mobile backend required a 23-step checklist, and an engineer spent about three hours on every release. Two of the last five releases had failed because a step was skipped. I mapped the steps and found that 14 of them only verified earlier steps. I wrote a single pipeline stage that ran those checks automatically and blocked the release on failure, and I proposed deleting four steps that protected against a system we had retired. The checklist dropped to five steps and the release time to 25 minutes. We went from one release every two weeks to three a week, with no failed release in the next quarter."

## Often paired with

- [Frugality](frugality.md): a simpler system usually costs less to run.
- [Think Big](think-big.md): interviewers often ask how far the idea could extend.

## Go deeper

- [Grokking Modern Behavioral Interview](https://www.designgurus.io/course/grokking-behavioral-interview?utm_source=github&utm_medium=repo&utm_campaign=amazon-leadership-principles&utm_content=principles-invent-and-simplify): worked answers and practice for every principle.
- [The STAR method](../guides/star-method.md): how to structure the answer.
