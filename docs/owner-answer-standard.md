# Owner Answer Standard

This document defines how the owner or coordinator must answer blocking questions.

## Purpose

Answers must be short, explicit, and operationally usable by AI agents.

## Required Format

Every answer should contain:

1. Decision
2. Reason
3. Constraints
4. Examples (if available)

## Standard Response Template

Decision:
[chosen option]

Reason:
[why this option is correct]

Constraints:
[what must not be changed]

Examples:
[optional examples or files]

## Rules

- Do not answer vaguely
- Do not say "use your judgment" for business-critical behavior
- If uncertain, mark the answer as provisional
- If wording, pricing, or contract meaning is involved, be explicit

## Example

Decision:
Photos and Materials tab is internal-only.

Reason:
It is used operationally and should not appear in the client-facing PDF.

Constraints:
Do not expose internal material notes to the client output.

Examples:
Current PDF sent to customers does not include this tab.
