# Are Right, A Lot

Are Right, A Lot means making sound decisions when the information is incomplete, and being able to explain the reasoning. It also means looking for evidence against one's own view and changing position when that evidence is strong.

## What the interviewer listens for

- A real decision with more than one reasonable option.
- The information that was available and the information that was missing.
- An effort to test the candidate's own belief, such as asking a critic or running a small experiment.
- An honest account of a time the candidate was wrong and what changed afterwards.

## Questions

1. Tell me about a decision you made without all the data you wanted.
2. Describe a time you were wrong. How did you find out?
3. Tell me about a time you changed your mind because of new information.
4. Give an example of a judgment call that turned out well. How did you know it was correct?
5. Tell me about a time you disagreed with the data.
6. Describe a time you sought out an opinion that opposed yours.

## Weak and strong answers

| Answer | What it contains |
|--------|------------------|
| Weak | A decision that worked, presented as obvious, with no alternatives and no account of the reasoning |
| Strong | The options, the criteria used to choose, the test applied to the candidate's own assumption, and the outcome in numbers |

## Sample answer

> "Our search service was slow, and I believed the cause was the ranking model. Rewriting it would take six weeks. Before committing, I asked the engineer who disagreed most with me to list what would prove me wrong. She suggested tracing 500 slow requests. The traces showed that 70 percent of the latency came from a serial call to the inventory service, not from ranking. I dropped my proposal and we made that call parallel in four days. The 95th percentile latency fell from 1.8 seconds to 600 milliseconds. Since then I write down what would disprove my view before I propose any project longer than two weeks."

## Often paired with

- [Dive Deep](dive-deep.md): good judgment depends on checking the details.
- [Have Backbone; Disagree and Commit](have-backbone-disagree-and-commit.md): the interviewer may ask what happened when others disagreed.

## Go deeper

- [Grokking Modern Behavioral Interview](https://www.designgurus.io/course/grokking-behavioral-interview?utm_source=github&utm_medium=repo&utm_campaign=amazon-leadership-principles&utm_content=principles-are-right-a-lot): the full behavioral course, including the Amazon chapter.
- Lesson: [Problem solving and decision making questions](https://www.designgurus.io/course-play/grokking-behavioral-interview/doc/problem-solving-and-decision-making-questions?utm_source=github&utm_medium=repo&utm_campaign=amazon-leadership-principles&utm_content=principles-are-right-a-lot), in Grokking Modern Behavioral Interview
- [Grokking Staff Engineer Interview](https://www.designgurus.io/course/grokking-staff-engineer-interview?utm_source=github&utm_medium=repo&utm_campaign=amazon-leadership-principles&utm_content=principles-are-right-a-lot): technical judgment under uncertainty, for senior and principal candidates.
