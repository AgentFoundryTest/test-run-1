# AGENTS

## Review guidelines
- Validate PRs against explicit Acceptance Criteria when present.
- Treat deviations from Acceptance Criteria as **P0**.
- It is acceptable for implementation details to vary if criteria are fully satisfied.
- Ignore style nits unless they block criteria (typos are **P1**).

## Response format (MANDATORY)
When a PR comment includes “@codex review for acceptance criteria”, respond using **exactly one** of the two formats:

**PASS**

or

**FAIL**
### Unmet:
- <quote the unmet criterion 1>
- <quote the unmet criterion 2>

No preamble, no emojis, no headings, no extra text. Do not include explanations if **PASS**.
