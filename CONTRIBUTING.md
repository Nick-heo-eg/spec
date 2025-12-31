# Contributing to AJT

AJT is a **log schema**, not a policy enforcement tool.

## What we accept

- **Use cases**: Real-world examples of logging AI decisions
- **Schema refinements**: Minimal additions that serve common needs
- **Integrations**: Examples for popular frameworks (LangChain, LlamaIndex, etc.)

## What we don't accept

- Policy opinions (what "should" be logged)
- Enforcement mechanisms (how to "force" logging)
- Prescriptive guidance on risk levels or decision codes

## How to contribute

1. Open an issue describing the use case
2. If adding a field: explain why existing fields don't suffice
3. Keep examples under 50 lines
4. No dependencies beyond standard library (examples may use frameworks)

## Philosophy

AJT solves one problem: **"After an incident, can you explain what happened?"**

The answer is a structured log line. Everything else is out of scope.
