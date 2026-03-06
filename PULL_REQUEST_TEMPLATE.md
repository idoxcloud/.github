## Description

**What** changed:

**Why** (motivation / problem being solved):

**How** (approach taken):

Fixes # <!-- issue number -->

---

## Type of Change

- [ ] Bug fix (non-breaking change which fixes an issue)
- [ ] New feature (non-breaking change which adds functionality)
- [ ] Breaking change (fix or feature that would cause existing functionality to not work as expected)
- [ ] Refactor (no functional change)
- [ ] Performance improvement
- [ ] Documentation update only
- [ ] Configuration / infrastructure change
- [ ] Tests (adding or updating test cases only)

---

## Screenshots / Demo

<!-- Attach before/after screenshots or a screen recording for any UI changes.
     Remove this section if not applicable. -->

| Before | After |
|--------|-------|
|        |       |

---

## Testing

**Test coverage:**
- [ ] Unit tests added / updated
- [ ] Integration tests added / updated
- [ ] Manually tested locally
- [ ] Tested in UAT environment

**Steps to reproduce / test:**

1.
2.
3.

---

## Deployment Notes

<!-- Does this PR require any special steps to deploy?
     e.g., environment variable changes, database migrations, feature flags, cache invalidation.
     Remove if not applicable. -->

- [ ] No special steps required
- [ ] Requires the following:

**Rollback plan:**

---

## Author Checklist

- [ ] My code follows the style guidelines of this project
- [ ] I have performed a self-review of my code
- [ ] I have commented my code, particularly in hard-to-understand areas
- [ ] I have made corresponding changes to the documentation, if applicable
- [ ] My PR title follows [conventional commits](https://www.conventionalcommits.org/en/v1.0.0/#summary) format
- [ ] My PR title uses only lowercase characters
- [ ] My PR title references a Jira ticket e.g. `fix: resolve login redirect [JIRA-123]`
- [ ] I have considered security implications of this change
- [ ] I have considered the performance impact of this change
- [ ] No new warnings or lint errors are introduced

---

## Peer Testing Checklist

> ℹ️ **When peer testing is complete, comment `peer tested` for the PR checks to pass.**

<details>
<summary>Team notes for peer testers (click to expand)</summary>

Council Direct GB uses the form builder from `idoxcloud-common` rather than `idoxcloud-common-php8`.

</details>

**To be completed by a peer tester (not the PR author)**

- [ ] **PR readiness** — No unresolved Copilot suggestions; all relevant checks and tests are passing
- [ ] **Meets requirements** — The change addresses all ticket / story criteria
- [ ] **Verified testing steps** — Followed the "Testing" section; steps pass as described
- [ ] **Works as expected** — Main features and edge cases behave correctly
- [ ] **No obvious bugs** — No errors, crashes, or unexpected issues found
- [ ] **UI / UX** — Visuals, text, and interactions are correct; no typos *(if applicable)*
- [ ] **Error handling** — Handles invalid inputs and errors gracefully
- [ ] **Test coverage** — New / updated logic is covered by tests as needed
- [ ] **No breaking changes** — Existing features still work
- [ ] **Readable code** — Code is clear, well-organised, and follows team conventions
- [ ] **Docs / comments** — Relevant documentation and code comments are updated
- [ ] **Security & performance** — No security or major performance issues introduced *(if applicable)*

**Peer Tester:** @____________

**Peer Tester Notes:**
