# troubleshooting-basics-software.md
**Using AI to Troubleshoot Software Problems Systematically**

## Purpose of this document

This file explains how to use AI to assist with **software troubleshooting**, with a focus on structured diagnosis rather than guessing fixes.

Software troubleshooting is about:

- Identifying where a failure occurs
- Determining whether the issue is code, configuration, environment, or usage
- Narrowing the problem space safely
- Avoiding repeated or fragile fixes
- Restoring expected behavior with minimal side effects

AI is most effective when used as a **diagnostic assistant**, not as an automatic repair tool.

## Core principle

**Most software issues are not bugs.  
They are mismatches between expectation, configuration, and reality.**

AI will try to fix whatever problem you describe.  
Your responsibility is to describe the problem accurately.

## Common software troubleshooting failures

### Failure 1: Treating every issue as a code bug

Many software issues are caused by:
- Configuration errors
- Environment differences
- Permissions or access changes
- Incorrect assumptions about behavior

AI needs to know whether code changes are even in scope.

### Failure 2: Ignoring recent changes

Most software failures follow change.

If you do not describe:
- Deployments
- Updates
- Configuration edits
- Dependency changes

AI will troubleshoot blindly.

### Failure 3: Troubleshooting without a baseline

If you cannot describe what “working” looks like, troubleshooting has no anchor.

## How to structure a software troubleshooting prompt

Strong software troubleshooting prompts include:

1. **Observed behavior**  
   What is happening now?

2. **Expected behavior**  
   What should be happening?

3. **Environment**  
   OS, platform, version, runtime, dependencies.

4. **Recent changes**  
   What changed before the issue appeared?

5. **Scope**  
   Single user, single system, or widespread?

6. **Constraints**  
   Downtime tolerance, access limits, rollback ability.

Precision beats verbosity.

## Core software troubleshooting prompt patterns

### 1. Classification first

Use this before attempting fixes.

**Prompt**
> Based on this behavior, help me classify the issue as one of the following:  
> code, configuration, environment, dependency, permissions, or usage.

**Why this works**
- Prevents premature code changes
- Narrows investigation scope
- Improves troubleshooting efficiency

### 2. Error interpretation

Use when error messages exist.

**Prompt**
> Explain what this error message indicates.  
>  
> Include:  
> - What subsystem it relates to  
> - Common causes  
> - What it does NOT usually mean

**Why this works**
- Reduces misinterpretation
- Prevents chasing irrelevant causes
- Improves signal-to-noise ratio

### 3. Environment comparison

Use when issues appear inconsistently.

**Prompt**
> Compare the working and non-working environments.  
>  
> Identify differences that could plausibly explain the issue.

**Why this works**
- Surfaces hidden mismatches
- Explains “works on my machine” problems
- Encourages systematic comparison

### 4. Step-by-step isolation

Use when multiple components are involved.

**Prompt**
> Propose a step-by-step approach to isolate the failing component.  
>  
> Prioritize steps that are low-risk and reversible.

**Why this works**
- Reduces blast radius
- Increases learning per step
- Avoids destructive testing

### 5. Fix validation

Use after a fix is applied.

**Prompt**
> How can I verify that this fix actually resolved the root cause and not just the symptom?

**Why this works**
- Prevents false resolution
- Reduces recurrence
- Encourages disciplined closure

## Using AI outputs correctly

AI suggestions should be treated as:
- Hypotheses
- Diagnostic leads
- Structured checklists

Good follow-up questions include:
- What assumptions does this fix rely on?
- What would cause this issue to return?
- What logs or signals would confirm this diagnosis?

## When not to use AI for software troubleshooting

Avoid using AI when:

- Systems are safety-critical
- Production impact is severe and time-sensitive
- Legal or compliance boundaries are unclear
- You cannot safely test or roll back changes

In these cases, AI can still help **after stabilization**, during root cause analysis.

## Final reminder

Effective troubleshooting is disciplined elimination, not clever fixes.

AI can help you think systematically.  
You still observe, test, and decide.
