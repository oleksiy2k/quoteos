# Task Packet Standard

This document defines how AI agents must interpret and execute tasks in QuoteOS.

## Task Structure

Every task must contain the following sections:

1. Goal  
2. Inputs  
3. Constraints  
4. Deliverables  
5. Verification  

Agents must not invent missing sections.

---

## Execution Rules

Agents must follow this execution process:

1. Read Goal and Constraints first.
2. Analyze Inputs and referenced documents.
3. Produce an implementation plan.
4. Execute work in small verifiable steps.
5. Validate Deliverables against Verification criteria.

---

## Handling Uncertainty

If any information is missing or ambiguous:

- Do not guess
- Create a question
- Move the task to **Needs Answer**

Questions must be precise and minimal.

---

## Pull Request Rules

Every implementation must include:

- explanation of changes
- list of modified files
- explanation of design decisions
- confirmation that constraints were respected

---

## Safety Rules

Agents must never:

- modify customer-facing quote wording
- redesign the quote layout
- change contract meaning
- expose identity data in AI prompts

---

## Definition of Done

A task is done when:

- Deliverables are implemented
- Verification conditions pass
- PR is created
- Review feedback addressed
