---
type: decision_request
agent: [agent-profile-id]
date: YYYY-MM-DD
urgency: [low | medium | high | blocking]
status: pending
context: "[One sentence: what decision is needed and why now]"
---

# Decision Request: [Title]

## Context

[Full background for the Human-in-Charge. Answer:]
- What you are trying to accomplish
- Why this decision point was reached
- What constraints exist (time, cost, compatibility, reversibility)
- What is at stake with each choice

---

## Question

> [The single, precise decision to be made. One sentence. Unambiguous.]

---

## Options

### Option A: [Name]

**Description:** [One paragraph.]

**Pros:**
- [Specific advantage]
- [Specific advantage]

**Cons:**
- [Specific drawback]
- [Specific drawback]

**Implications:** [Effort, downstream impact, risks, reversibility]

---

### Option B: [Name]

**Description:** [One paragraph.]

**Pros:**
- [Specific advantage]
- [Specific advantage]

**Cons:**
- [Specific drawback]
- [Specific drawback]

**Implications:** [Effort, downstream impact, risks, reversibility]

---

### Option C: [Name] *(if applicable)*

**Description:** [One paragraph.]

**Pros:**
- [Specific advantage]

**Cons:**
- [Specific drawback]

**Implications:** [Effort, downstream impact, risks, reversibility]

---

## Comparison Matrix

| Criteria            | Option A          | Option B          | Option C          |
|---------------------|-------------------|-------------------|-------------------|
| Effort              | [Low/Med/High]    | [Low/Med/High]    | [Low/Med/High]    |
| Risk                | [Low/Med/High]    | [Low/Med/High]    | [Low/Med/High]    |
| Reversibility       | [Easy/Hard]       | [Easy/Hard]       | [Easy/Hard]       |
| Alignment with goal | [Low/Med/High]    | [Low/Med/High]    | [Low/Med/High]    |
| [Custom criterion]  | [Rating]          | [Rating]          | [Rating]          |

---

## Agent Recommendation

**Recommended:** Option [X]

**Rationale:** [Why. If genuinely balanced, say so and name the deciding factor for the human.]

**Confidence:** [Low / Medium / High]

---

## Related Work

- **Specs / ADRs:** [Links]
- **Tasks blocked:** [Task IDs or WP references]
- **Prior discussion:** [Links to PR comments, Slack threads, meeting notes]

---

## Timeline

**Decision needed by:** YYYY-MM-DD

**Impact if delayed:** [What gets blocked, what deadline is at risk]

**Current workaround:** [If any temporary measure is in place, describe it and its expiry]

---

## Decision

*Human-in-Charge fills this section.*

**Chosen:** [Option X / Custom approach]

**Rationale:** [Why this option was chosen]

**Conditions / Constraints:** [Any conditions under which this decision applies or should be revisited]

**Date:** YYYY-MM-DD

**Follow-up required:**
- [ ] Create or update implementation task
- [ ] Update specification or ADR
- [ ] Notify affected stakeholders
- [ ] Other: [Specify]
