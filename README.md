# Harika Docs Marketplace

A collection of Claude Code plugins for technical writers.

## SME Question Builder

This plugin reviews feature descriptions, ticket text, or meeting notes
and suggests questions to ask a subject matter expert before writing documentation.

It provides:
- A summary of known information.
- Up to eight prioritized SME questions.
- An explanation of why each answer is needed.

## Requirements

Claude Code must be installed and signed in.

## Install locally

Start Claude Code from the my-docs-marketplace folder, then run:

```text
/plugin marketplace add ./
/plugin install sme-question-builder@harika-docs
```

## Use

Run this command followed by your notes:

```text
/sme-question-builder:sme-questions Project owners can archive a project from the Settings page. Archived projects become read-only.
```

Review the generated questions before sending them to an SME.
The plugin identifies information gaps; it does not verify product behavior.

## Author

Harika