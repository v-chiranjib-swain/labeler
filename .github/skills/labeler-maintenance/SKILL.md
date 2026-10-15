---
name: labeler-maintenance
description: Helps maintain the GitHub labeler action by investigating bugs, implementing changes, writing tests, and validating documentation and workflows.
---

# Labeler Maintenance

Use this skill when investigating bugs, implementing features, reviewing changes, or adding tests in this repository.

## Guidelines

1. Understand the existing implementation before proposing changes.
2. Trace relevant behavior through source code, configuration, tests, and documentation.
3. Preserve existing behavior and backward compatibility unless the requirements explicitly call for a change.
4. For label-matching changes, consider supported configuration formats, matching rules, and edge cases.
5. For GitHub API changes, consider permissions, API errors, pagination, and pull requests originating from forks where relevant.
6. Add or update tests that cover the expected behavior, edge cases, and regressions.
7. Update documentation when user-visible behavior or configuration changes.
8. Follow the repository's existing TypeScript, CommonJS, linting, and testing conventions.
9. Run relevant tests and checks, and report any that could not be completed.
10. Avoid unnecessary dependencies, unrelated refactoring, and changes to generated files unless required by the repository's build process.

## Workflow

1. Summarize the problem and expected behavior.
2. Inspect the relevant implementation and existing tests.
3. Identify edge cases and propose a minimal implementation plan.
4. Implement the change and add regression tests.
5. Run relevant validation commands.
6. Summarize the changes, test results, and any remaining risks.

## Important

- Do not assume behavior or invent repository conventions; inspect the code and project documentation.
- Do not claim tests passed unless they were actually executed successfully.
- Ask for clarification when requirements are ambiguous or could change existing behavior.
