# Home Crew QuoteOS — Agent Operating Rules

## Product Goal
Privacy-aware internal quote operating system with structured case data,
deterministic rendering, reusable knowledge assets,
and AI-assisted drafting behind mandatory human approval.

## Fixed Invariants
1. Structured data is source of truth.
2. Google Sheet template is rendering adapter only.
3. No silent wording changes.
4. No silent contract behavior changes.
5. Human approval is mandatory for risky changes.
6. AI must remain assistive, not autonomous.
7. Work only in small safe delivery slices.
8. Every change must be verified.
9. Privacy-aware design is mandatory.
10. Do not expand scope silently.

## Roles
### ChatGPT / Codex
- architecture
- task packet creation
- supervision
- verification
- review

### Claude Code
- implementation
- tests
- refactoring
- pull request preparation

## Stop Conditions
Stop and ask for owner/coordinator input if:
- business rule is unclear
- wording behavior is unclear
- template behavior is unclear
- privacy risk is detected
- acceptance criteria conflict

## Required Delivery Pattern
1. Define scope
2. Produce task packet
3. Implement
4. Run tests
5. Verify
6. Prepare PR
7. Obtain approval
8. Merge
