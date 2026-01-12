# coding.md
**Using AI to Assist with Coding Without Losing Control**

## Purpose of this document

This file explains how to use AI to assist with **coding tasks** while maintaining correctness, clarity, and ownership.

AI can help you write code faster, understand unfamiliar code, and explore solutions.  
It cannot understand your system context unless you provide it.

Good use of AI in coding improves productivity.  
Poor use creates fragile, unmaintainable systems.

## Core principle

**AI can generate code.  
You are responsible for its correctness, security, and maintainability.**

Treat AI as a junior assistant that works fast but lacks context.

## What AI is good at in coding

AI is effective at:

- Generating boilerplate
- Explaining existing code
- Translating between languages
- Suggesting alternative implementations
- Highlighting potential issues

AI struggles with:
- Hidden system constraints
- Business logic nuances
- Security implications
- Long-term architectural impact

## Common coding failures when using AI

### Failure 1: Copy-pasting without understanding

Code that is not understood cannot be maintained or debugged.

AI output should always be reviewed and reasoned through.

### Failure 2: Omitting context

Without knowing:
- Language version
- Framework
- Runtime environment
- Existing architecture

AI will guess.

### Failure 3: Asking for final solutions too early

Jumping straight to “write the code” skips design thinking.

Use AI first to explore options and constraints.

## How to structure a coding prompt

Strong coding prompts usually include:

1. **Goal**  
   What should the code do?

2. **Context**  
   Language, framework, environment.

3. **Constraints**  
   Performance, security, compatibility, style.

4. **Integration points**  
   Where the code fits into the existing system.

5. **Level of abstraction**  
   Pseudocode, example, or production-ready code.

Clarity reduces rework.

## Core coding prompt patterns

### 1. Design-first prompting

Use before writing code.

**Prompt**
> Help me design a solution for this problem.  
>  
> Explain the approach, trade-offs, and risks before writing any code.

**Why this works**
- Encourages thinking before implementation
- Prevents premature complexity
- Improves solution quality

### 2. Controlled code generation

Use when you know what you want built.

**Prompt**
> Generate code that does the following.  
>  
> Language/version:  
> Framework (if any):  
> Constraints:  
>  
> Keep the solution simple and readable.

**Why this works**
- Limits scope
- Improves relevance
- Produces reviewable output

### 3. Code explanation

Use when inheriting or reviewing code.

**Prompt**
> Explain what this code does, line by line, and highlight any risky or unclear parts.

**Why this works**
- Improves understanding
- Reveals hidden assumptions
- Aids onboarding

### 4. Debugging assistance

Use when code behaves unexpectedly.

**Prompt**
> This code is producing this behavior.  
>  
> Help me reason through possible causes before suggesting fixes.

**Why this works**
- Prevents blind patching
- Encourages diagnosis
- Aligns with problem-solving principles

### 5. Refactoring support

Use when improving existing code.

**Prompt**
> Suggest ways to refactor this code for readability and maintainability without changing behavior.

**Why this works**
- Improves code quality
- Preserves functionality
- Encourages incremental improvement

## Validating AI-generated code

Before accepting AI-generated code:

- Read it fully
- Run it in a controlled environment
- Test edge cases
- Consider security implications
- Check alignment with coding standards

If you cannot explain the code, do not deploy it.

## When not to use AI for coding

Avoid relying on AI when:

- Writing security-critical code
- Implementing complex business rules
- Making architectural decisions
- Compliance requirements are strict

AI can assist, but responsibility cannot be delegated.

## Final reminder

AI accelerates coding.  
It does not replace design, review, or accountability.

Use AI to think faster.  
Write code you are prepared to own.
