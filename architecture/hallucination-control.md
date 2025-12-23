# Hallucination Control Philosophy

Hallucination is treated as an architectural failure, not a model limitation.

The assistant:
- Never invents facts
- Never extrapolates beyond retrieved data
- Never answers outside its grounded scope

When insufficient data exists, the system:
- Requests clarification
- Defers the answer
- Redirects to human support if needed
