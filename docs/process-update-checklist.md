# Process Update: Checklist & Template

Purpose: A lightweight checklist and template for proposing and applying updates to process documents in docs/.

## When to use
- When adding, clarifying, or changing process documentation.
- When a documented gap or recurring confusion is identified.

## Checklist before submitting a PR
- [ ] Proposed content is scoped to a single process document or a clearly related set.
- [ ] Content aligns with existing language and structure of docs/.
- [ ] Acceptance criteria or review checklist is included.
- [ ] Stakeholders identified and notified (PdM, PM, QA, DevOps as applicable).
- [ ] Links to related docs and issues are included.

## Update template (use in PR description)
- Summary: Short description of the change
- Files changed: list of docs/ files updated
- Rationale: why this is needed
- Acceptance criteria:
  - Content aligns with existing process docs
  - Update improves clarity or closes a documented gap
  - Proposed content has been reviewed with stakeholders (if needed)
- Validation steps: how reviewers can validate the change (read-through, checklist, test scenario)

## Example PR body
Summary:
- Expand role definitions to include Scrum Master, QA Lead, UX, BA, DevOps and an expanded Stakeholder section.

Files changed:
- docs/octoacme-roles-and-personas.md
- docs/process-update-checklist.md

Rationale:
- Provide clearer responsibilities and handoffs to reduce ambiguity during planning and releases.

Acceptance criteria:
- [ ] Doc wording aligns with existing docs
- [ ] Reviewer confirms improved clarity
- [ ] Stakeholder review completed (if required)
