# analysis.md
**Using AI to Compare, Evaluate, and Decide**

## Purpose of this document

This file explains how to use AI for **analysis**, not summarization.

Analysis means:

- Comparing options
- Evaluating information quality
- Weighing trade-offs
- Testing assumptions
- Understanding consequences before acting

AI can assist with analysis, but only when the user provides **clear structure and intent**.

## Core principle

**AI is strong at structured comparison.  
Humans remain responsible for judgment.**

If you ask vague questions, you get vague analysis.  
If you ask for conclusions without criteria, you get confident but shallow answers.

Good analysis requires you to specify:

- What is being compared
- How it should be evaluated
- Why the evaluation matters
- What constraints apply

## Common analysis failures

Understanding common mistakes helps prevent misuse.

### Mistake 1: Asking for “the best option”

AI cannot define “best” without criteria.

Poor prompt:
> Which option is best?

Improved:
> Compare these options using cost, risk, speed, and long-term impact.

### Mistake 2: Confusing summaries with analysis

Summaries restate information.  
Analysis evaluates it.

This:
> Summarize this report

Is not analysis yet.

### Mistake 3: Accepting confident answers without stress-testing

AI will sound confident even when assumptions are weak.

Good analysis includes:
- Counterarguments
- Edge cases
- Failure modes

## How to structure an analysis prompt

Strong analysis prompts usually contain four elements:

1. **Context**  
   What situation are we analyzing?

2. **Objective**  
   What decision or understanding is required?

3. **Criteria**  
   How should options or information be evaluated?

4. **Constraints**  
   What limits apply (time, budget, policy, risk tolerance)?

Clarity matters more than wording style.

## Core analysis prompt patterns

### 1. Option comparison

Use when choosing between alternatives.

**Prompt**
> Compare the following options.  
>  
> Context: [brief situation]  
> Options: [Option A, Option B, Option C]  
>  
> Evaluate them using these criteria:  
> - Cost  
> - Time to implement  
> - Risk  
> - Long-term impact  
>  
> Present the comparison in a table, then summarize the key trade-offs.

**Why this works**
- Forces explicit criteria
- Separates comparison from conclusions
- Makes trade-offs visible

### 2. Trade-off analysis

Use when no option is clearly good.

**Prompt**
> Analyze the trade-offs involved in choosing [Option X].  
>  
> Include:  
> - What is gained  
> - What is lost  
> - Who benefits  
> - Who absorbs the risk  
> - What problems this choice postpones rather than solves

**Why this works**
- Reduces shallow optimism
- Surfaces deferred consequences
- Encourages second-order thinking

### 3. Assumption testing

Use when a plan feels “obviously right”.

**Prompt**
> Analyze this plan and identify the key assumptions it depends on.  
>  
> For each assumption:  
> - Why it matters  
> - What happens if it is false  
> - How risky the assumption is

**Why this works**
- Reveals hidden fragility
- Helps prioritize validation
- Reduces surprise failures

### 4. Information quality evaluation

Use when assessing reports, claims, or recommendations.

**Prompt**
> Evaluate the quality of this information.  
>  
> Assess:  
> - Strength of evidence  
> - Missing or uncertain data  
> - Potential bias  
> - What would need to be true for the conclusion to hold

**Why this works**
- Prevents decisions based on weak foundations
- Encourages disciplined skepticism

### 5. Scenario analysis

Use when outcomes are uncertain.

**Prompt**
> Analyze this decision under three scenarios:  
> - Best case  
> - Most likely case  
> - Worst case  
>  
> For each scenario, explain impacts, risks, and early warning signs.

**Why this works**
- Prepares for variance, not just averages
- Improves resilience over prediction accuracy

## Using AI analysis outputs correctly

AI analysis should be treated as a **draft**, not a verdict.

Good practice includes:
- Asking follow-up questions
- Requesting counterarguments
- Challenging assumptions
- Narrowing scope iteratively

Example follow-up:
> Now argue against the conclusion you just gave.

## When not to use AI for analysis

Avoid outsourcing analysis when:

- Legal or regulatory accountability is unclear
- Ethical judgment is central
- Stakes are high and inputs are incomplete
- You are trying to justify a decision already made

AI is most useful **before** positions harden.

## Final reminder

Analysis is not about finding the correct answer.  
It is about understanding the problem well enough to decide responsibly.

AI can expand your view.  
You still decide.
