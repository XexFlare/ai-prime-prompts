# troubleshooting-basics-hardware.md
**Using AI to Troubleshoot Hardware Problems Systematically**

## Purpose of this document

This file explains how to use AI to assist with **hardware troubleshooting**, with an emphasis on structured diagnosis, safety, and evidence-based reasoning.

Hardware troubleshooting is about:

- Identifying physical or electrical faults
- Distinguishing component failure from configuration or usage issues
- Narrowing the fault domain safely
- Avoiding unnecessary part replacement
- Restoring reliable operation with minimal disruption

AI can support thinking and planning, but physical verification remains essential.

## Core principle

**Hardware problems obey physical constraints.  
Assumptions fail faster in the real world.**

AI cannot see, hear, smell, or measure.  
Accurate observation and safe handling are mandatory.

## Common hardware troubleshooting failures

### Failure 1: Replacing parts too early

Unnecessary replacement:
- Wastes time and money
- Introduces new variables
- Masks underlying issues

AI should help you diagnose before you replace.

### Failure 2: Ignoring power and connectivity basics

Many hardware failures trace back to:
- Power supply issues
- Loose or damaged cables
- Incorrect connections
- Environmental factors

These must be verified first.

### Failure 3: Skipping safety considerations

Hardware troubleshooting can involve:
- Electrical hazards
- Heat
- Moving parts
- Data loss

Safety is not optional.

## How to structure a hardware troubleshooting prompt

Strong hardware troubleshooting prompts include:

1. **Observed symptoms**  
   Sounds, lights, smells, behavior, error indicators.

2. **Device details**  
   Model, age, usage pattern, operating conditions.

3. **Environment**  
   Power source, temperature, humidity, dust, vibration.

4. **Recent changes**  
   Movement, upgrades, repairs, power events.

5. **Scope**  
   Single device or multiple devices affected?

6. **Safety constraints**  
   What must not be done?

Describe only what you have verified.

## Core hardware troubleshooting prompt patterns

### 1. Safety and basic checks

Use before deeper investigation.

**Prompt**
> Given these symptoms, list the basic safety and physical checks I should perform first.

**Why this works**
- Reduces risk of harm
- Prevents obvious oversights
- Establishes a safe baseline

### 2. Fault domain narrowing

Use to identify where the failure likely resides.

**Prompt**
> Based on these observations, help me narrow the fault to power, connectivity, component, or environment.

**Why this works**
- Shrinks the problem space
- Guides focused inspection
- Avoids random testing

### 3. Component isolation

Use when multiple components interact.

**Prompt**
> Suggest a safe, step-by-step way to isolate which component is failing.

**Why this works**
- Limits disruption
- Preserves working parts
- Encourages reversible steps

### 4. Symptom-to-cause mapping

Use when behavior is visible but unclear.

**Prompt**
> Map these symptoms to plausible hardware causes and explain the reasoning.

**Why this works**
- Connects observation to diagnosis
- Avoids guesswork
- Improves technician confidence

### 5. Repair vs replacement decision

Use when considering next action.

**Prompt**
> Given the diagnosis, help me decide whether repair, replacement, or workaround makes the most sense.

**Why this works**
- Balances cost, risk, and time
- Prevents sunk-cost bias
- Encourages pragmatic decisions

## Using AI outputs correctly

AI suggestions should be treated as:
- Diagnostic guidance
- Planning support
- Hypothesis generation

Always:
- Verify physically
- Follow safety procedures
- Stop if conditions become unsafe

## When not to use AI for hardware troubleshooting

Avoid using AI when:

- Immediate physical danger exists
- Equipment is under warranty with strict conditions
- Specialized tools or certifications are required
- Safety-critical systems are involved

In these cases, AI can assist with **documentation and post-incident analysis**.

## Final reminder

Hardware does not negotiate with assumptions.

AI can help you think methodically.  
You still observe, measure, and act responsibly.
