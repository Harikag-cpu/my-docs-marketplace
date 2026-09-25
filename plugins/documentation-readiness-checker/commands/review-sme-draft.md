---
description: Review an SME-provided documentation draft and identify information that is missing, unclear, or requires verification.
argument-hint: [draft or file]
---

# Review SME Draft

Review the SME-provided draft from a technical documentation perspective.

The purpose of this review is not to rewrite the documentation. The purpose is to identify gaps that should be clarified with the SME before the documentation is finalized.

Review the draft for:

1. Missing prerequisites
2. Missing configuration or setup information
3. Missing or unclear procedural steps
4. Missing expected results
5. Missing screenshots or visuals
6. Missing field, option, or UI descriptions
7. Missing limitations or known constraints
8. Missing permissions, roles, or access requirements
9. Unsupported assumptions
10. Terminology that needs clarification
11. Information that appears technically ambiguous
12. Information that requires SME verification

Do not invent or assume missing technical information.

For every gap, explain why clarification is needed and generate a specific question that can be sent to the SME.

## Output

Organize the findings under:

### Critical gaps
Information required before the documentation can be completed.

### Clarifications needed
Information that is unclear or ambiguous.

### Screenshots or visuals needed
Places where a screenshot, diagram, or other visual may help the user.

### SME questions
Provide a concise list of questions that the technical writer can send directly to the SME.

If sufficient information is already provided for an area, do not generate unnecessary questions.`