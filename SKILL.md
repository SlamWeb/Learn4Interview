---
name: learn4interview
description: Teach any technical stack or knowledge area from absolute zero to interview-ready depth through a research-backed, multi-lecture course with visual HTML lessons. Use when a learner wants a structured learning path for technical interview preparation, not for a quick factual answer or a mock interview alone.
---

# Learn4Interview

**ELI5 first, interview-ready last.** Build understanding before vocabulary, then climb deliberately from intuition to real engineering judgment.

## Establish the course

Treat the topic as the only required input. Infer the learner's current level and target role when reasonable; otherwise default to an absolute beginner preparing for a general software-engineering interview. Ask a question only when the answer would materially change the curriculum.

Research before planning:

- Use current authoritative sources and real implementations for technical claims.
- Look for recent first-hand interview reports relevant to the target role.
- Use interview evidence to decide what matters, how deep to teach it, and what can be skipped.
- Never turn missing evidence into invented frequency or certainty.

Build an 8-20 lecture roadmap, using about 10 lectures by default. Order it from prerequisites and mental models through mechanisms, implementation or source code, architecture, trade-offs, and interview application. Show the roadmap before the first lecture and make the role, assumed level, and evidence limits visible.

## Teach from zero

For every important concept, follow this learning slope when it fits:

```text
everyday intuition
  -> tiny concrete example
  -> the problem humans needed to solve
  -> the precise term
  -> how it works
  -> real implementation or architecture
  -> trade-offs and failure boundaries
  -> how an interviewer probes it
  -> a concise spoken answer
```

Do not use jargon to explain jargon. Introduce a term only after the learner has a usable mental model for it. Prefer a small diagram, timeline, example, or code fragment when it reveals the idea better than another abstract paragraph.

Do not simplify away distinctions that change the technical answer. If a follow-up exposes a misconception, stop advancing and repair that mental model first.

## Ground the interview layer

Keep these two categories visibly separate:

- **Observed interview evidence:** a question or topic supported by a first-hand report. Link the source and state its date, role, and relevant context when available.
- **Likely derived question:** a question inferred from the evidence, the target role, or foundational knowledge. Label it as inference, never as a real report.

Explain what each important question tests, give a natural interview-ready answer, and show likely follow-ups or trade-offs only when they add real value. Prefer a few well-supported questions over a long generic bank.

## Control progression

Treat follow-up questions, requests for another analogy, and requests to go deeper as part of the current lecture. They do not consume or advance a lecture.

Advance only when the learner explicitly says `next lecture`, `下一讲`, or an unambiguous equivalent. Keep the current lecture number stable otherwise. If the learner changes the topic entirely, establish a new roadmap.

Optimize for the learner actually understanding the topic, not for finishing the roadmap quickly.

## Deliver visual lessons

Each formal lecture is one self-contained, responsive HTML learning page. Use semantic HTML with inline CSS and, when useful, inline SVG; avoid frameworks, build steps, external scripts, and decorative visuals that do not teach.

The page should make the current place in the roadmap obvious and should integrate the intuition, mechanism, real-system mapping, trade-offs, interview evidence, speakable answer, and sources that matter for that lecture. These are learning outcomes, not a rigid set of required headings.

When files can be created, save each lecture as a clearly numbered `.html` file and present it to the learner. Otherwise return the complete HTML. Keep the page usable on desktop and mobile, and verify the rendered result when browser or preview tools are available.
