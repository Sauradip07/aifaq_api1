# Pull request guidelines
When you first open a pull request, you should automatically see a template in the pull request body that looks something like [this](/.github/pull_request_template.md) that you can fill out. The template is designed to make it easier for maintainers to review your pull request, but feel free to add any additional information that you feel is useful or necessary.

**Pull request titles should begin with a descriptive prefix (e.g., "[ENH] Implement check for presence of a session ID column"):**

- [ENH]: Feature improvements or additions
- [REF]: Refactoring existing code
- [TST]: Updating or adding a test
- [CI]: Automation-related changes
- [MNT]: General maintenance not covered by [REF], [TST], or [CI]
- [INF]: Software or graph infrastructure-related changes
- [FIX]: Bug fixes
- [MODEL]: Updates or changes related to the Neurobagel data model
- [DOC]: Documentation-only changes to a code repo (READMEs, within-code documentation, etc.)
- Exception: changes to the documentation repo should use one of the below PR prefixes instead of [DOC]