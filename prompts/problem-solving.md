# problem-solving.md
**Using AI to Diagnose Problems Before Attempting Solutions**

## Purpose of this document

This file explains how to use AI for **problem-solving**, with an emphasis on diagnosis before action.

Problem-solving is about:

- Understanding what is actually wrong
- Separating symptoms from root causes
- Avoiding premature solutions
- Reducing repeated failures
- Making fixes that last

AI is most useful at the **diagnostic stage**, not as an instant solution engine.

## Core principle

**Most problems are solved poorly because they are defined poorly.**

AI will attempt to fix whatever problem you describe, even if the description is wrong.

Clear problem definition is more important than fast solutions.

## Common problem-solving failures

### Failure 1: Jumping straight to solutions

Poor prompt:
> How do I fix this?

This assumes the problem is already understood.

Improved:
> Help me understand what might be causing this issue.

### Failure 2: Treating symptoms as causes

Recurring issues are often misdiagnosed because visible symptoms are easier to describe than underlying causes.

AI should be used to explore **why**, not just **what**.

### Failure 3: Providing incomplete context

AI cannot infer missing details reliably.

Omitting environment, constraints, or recent changes leads to fragile solutions.

## How to structure a problem-solving prompt

Strong problem-solving prompts usually include:

1. **Observed symptoms**  
   What is happening? Be specific.

2. **Expected behavior**  
   What should be happening instead?

3. **Context**  
   Environment, system, people, or process involved.

4. **Recent changes**  
   What changed before the problem appeared?

5. **Constraints**  
   Time, tools, permissions, or risk limits.

Accuracy matters more than completeness.

## Core problem-solving prompt patterns

### 1. Problem clarification

Use when the problem statement is unclear.

**Prompt**
> Help me clarify this problem.  
>  
> Based on the symptoms, what questions should I answer before attempting a solution?

**Why this works**
- Exposes missing information
- Improves problem framing
- Prevents wasted effort

### 2. Symptom-to-cause exploration

Use when causes are uncertain.

**Prompt**
> Given these symptoms, list possible underlying causes.  
>  
> Group them by category and explain how each could produce the observed behavior.

**Why this works**
- Avoids single-cause fixation
- Encourages systematic thinking
- Expands diagnostic coverage

### 3. Root cause analysis

Use when recurrence matters.

**Prompt**
> Perform a root cause analysis of this issue.  
>  
> Identify:  
> - Immediate cause  
> - Contributing factors  
> - Systemic or process-level causes

**Why this works**
- Separates surface issues from deeper ones
- Improves long-term fixes
- Reduces repeat incidents

### 4. Elimination strategy

Use when multiple causes are possible.

**Prompt**
> Suggest a step-by-step approach to eliminate possible causes safely.  
>  
> Prioritize steps that are low-risk and high-information.

**Why this works**
- Prevents disruptive trial-and-error
- Increases learning per action
- Preserves system stability

### 5. Solution evaluation

Use after a fix is proposed.

**Prompt**
> Evaluate this proposed solution.  
>  
> Consider:  
> - What it addresses  
> - What it does not address  
> - Risks or side effects  
> - Likelihood of recurrence

**Why this works**
- Prevents fragile fixes
- Encourages defensive thinking
- Improves solution quality

## Using AI outputs correctly

AI-generated solutions should be treated as **hypotheses**, not answers.

Good follow-up actions include:
- Validating assumptions
- Testing in controlled environments
- Asking for alternative explanations
- Reviewing failure modes

Example follow-up:
> What would make this solution fail?

## When not to use AI for problem-solving

Avoid using AI when:

- Safety-critical systems are involved
- Legal or compliance implications are unclear
- You lack sufficient context to describe the problem accurately
- Immediate expert intervention is required

AI supports problem-solving best **before** irreversible actions are taken.

## Final reminder

Solving the wrong problem efficiently is still failure.

AI can help you slow down and think clearly.  
You still define the problem, choose the fix, and own the outcome.
