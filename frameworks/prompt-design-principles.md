# prompt-design-principles.md
**How to Design Prompts That Produce Reliable, Useful Results**

## Purpose of this document

This file explains the **principles behind effective prompt design**, independent of any specific AI model or tool.

It is not a list of tricks.  
It is a guide to thinking clearly before asking.

Good prompts are a reflection of good thinking.  
AI exposes confusion faster than people do.

## Core idea

**Prompt design is intent design.**

If your intent is unclear, the output will be unclear.  
If your intent is conflicted, the output will be inconsistent.

Well-designed prompts communicate:
- What matters
- What does not
- What kind of thinking is required

## Principle 1: Clarity beats cleverness

Complex wording does not improve results.  
Clear structure does.

Prefer:
- Simple sentences
- Explicit instructions
- Concrete terms

Avoid:
- Metaphors
- Vague goals
- Overloaded prompts

If a human would ask for clarification, the AI will guess.

## Principle 2: Separate thinking from answering

Asking for conclusions too early leads to shallow output.

Design prompts in stages:
1. Understand the problem
2. Explore options or explanations
3. Evaluate trade-offs
4. Decide or summarize

Example:
> First, help me understand the problem.  
> Then, analyze possible approaches.  
> Only after that, suggest a recommendation.

This improves depth and reliability.

## Principle 3: Provide criteria, not opinions

AI cannot infer what you value.

Instead of:
> Is this a good idea?

Use:
> Evaluate this idea using cost, risk, scalability, and long-term impact.

Criteria anchor reasoning.  
Opinions drift.

## Principle 4: Constrain the output deliberately

Unbounded prompts produce unfocused results.

Constraints can include:
- Length
- Format
- Tone
- Audience
- Risk tolerance

Example:
> Respond in bullet points, focusing on operational risks only.

Constraints improve usefulness more than detail.

## Principle 5: Make assumptions explicit

Hidden assumptions weaken outputs.

Good prompts surface them:
> List the assumptions you are making in this analysis.

This allows you to challenge or validate them.

## Principle 6: Match the prompt to the task

Different tasks require different prompt styles.

- Reasoning prompts explore understanding
- Analysis prompts compare and evaluate
- Decision-support prompts clarify action
- Problem-solving prompts diagnose causes
- Writing prompts shape communication

Misaligned prompts produce misleading results.

## Principle 7: Use AI iteratively, not once

Good prompts evolve.

Start broad, then narrow:
- Ask follow-up questions
- Request counterarguments
- Refine scope
- Adjust constraints

Iteration is a strength, not a failure.

## Principle 8: Treat AI output as a draft

AI output is a starting point.

Always:
- Review critically
- Ask “what’s missing?”
- Challenge conclusions
- Adapt to context

If you accept output without scrutiny, the prompt failed.

## Principle 9: Avoid prompting to confirm bias

Prompts can be used to justify decisions already made.

This reduces quality and increases risk.

Better prompt:
> What is the strongest argument against this approach?

Good prompt design invites disagreement.

## Principle 10: Design for reuse

Strong prompts can be reused and adapted.

Reusable prompts:
- Avoid model-specific instructions
- Focus on structure, not syntax
- Scale across domains

This keeps your prompting durable over time.

## Common prompt design mistakes

- Asking multiple conflicting tasks at once
- Mixing analysis and writing unintentionally
- Leaving success criteria undefined
- Overloading prompts with unnecessary detail
- Treating AI as an authority

Most failures are design failures, not model failures.

## Final reminder

Prompting is not about getting answers faster.  
It is about asking better questions.

AI reflects the quality of your thinking.  
Design prompts that deserve good answers.
