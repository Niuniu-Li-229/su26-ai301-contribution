# Contribution 1: Improve osv-scanner `--help` documentation

**Contribution Number:** 1  
**Student:** Wanjing Yang  
**Issue:** https://github.com/google/osv-scanner/issues/570  
**Project:** [google/osv-scanner](https://github.com/google/osv-scanner)  
**Status:** Phase I In Progress

---

## Why I Chose This Issue

I chose issue [#570](https://github.com/google/osv-scanner/issues/570) in `google/osv-scanner`, "Improve osv-scanner `--help` documentation." osv-scanner is Google's tool for finding known vulnerabilities in a project's dependencies using the OSV database, and right now its `--help` output is incomplete: it doesn't list all of the available `--format` options, it has no link to the web documentation, and there is no generated `man` page. This matters because the `--help` text is the first place users look to understand a CLI, so missing or out-of-date help directly hurts the tool's usability and discoverability. "Fixed" means the help lists every format option, links to the docs, and a man page is generated from shared source so it can't drift from the web docs.

I'm interested in this because:

1. **The scope is small and clearly bounded.** The issue spells out three concrete sub-tasks, so I know exactly what "done" looks like and can scope my PR without risk of scope creep.
2. **It's an approachable on-ramp to a new language.** The project is written in Go, which is new to me, but documentation/CLI help-text work is a gentle way to learn a codebase, and I can ramp up quickly with Claude Code.
3. **The project is very actively maintained.** osv-scanner merges contributor PRs almost daily, so a well-scoped fix has a realistic path to actually being reviewed and merged.
4. **I want to learn** how a real-world Go CLI structures its flags and help output, and how a project generates a `man` page from a single source of truth so docs stay in sync.

The issue is labeled `good first issue` and `documentation`, is open, unassigned, and has no existing pull request, so it's available for me to claim.

---

## Understanding the Issue

### Problem Description

[In your own words, what's broken or missing?]

### Expected Behavior

[What should happen?]

### Current Behavior

[What actually happens?]

### Affected Components

[Which parts of the codebase are involved?]

---

## Reproduction Process

### Environment Setup

[Notes on setting up your local development environment - challenges you faced, how you solved them]

### Steps to Reproduce

1. [Step 1]
2. [Step 2]
3. [Observed result]

### Reproduction Evidence

- **Commit showing reproduction:** [Link to commit in your fork]
- **Screenshots/logs:** [If applicable]
- **My findings:** [What you discovered during reproduction]

---

## Solution Approach

### Analysis

[Your analysis of the root cause - what's causing the issue?]

### Proposed Solution

[High-level description of your fix approach]

### Implementation Plan

Using UMPIRE framework (adapted):

**Understand:** [Restate the problem]

**Match:** [What similar patterns/solutions exist in the codebase?]

**Plan:** [Step-by-step implementation plan]
1. [Modify file X to do Y]
2. [Add function Z]
3. [Update tests]

**Implement:** [Link to your branch/commits as you work]

**Review:** [Self-review checklist - does it follow the project's contribution guidelines?]

**Evaluate:** [How will you verify it works?]

---

## Testing Strategy

### Unit Tests

- [ ] Test case 1: [Description]
- [ ] Test case 2: [Description]
- [ ] Test case 3: [Description]

### Integration Tests

- [ ] Integration scenario 1
- [ ] Integration scenario 2

### Manual Testing

[What you tested manually and results]

---

## Implementation Notes

### Week [X] Progress

[What you built this week, challenges faced, decisions made]

### Week [Y] Progress

[Continue documenting as you work]

### Code Changes

- **Files modified:** [List]
- **Key commits:** [Links to important commits]
- **Approach decisions:** [Why you chose certain approaches]

---

## Pull Request

**PR Link:** [GitHub PR URL when submitted]

**PR Description:** [Draft or final PR description - much of the content above can be adapted]

**Maintainer Feedback:**
- [Date]: [Summary of feedback received]
- [Date]: [How you addressed it]

**Status:** [Awaiting review / Iterating / Approved / Merged]

---

## Learnings & Reflections

### Technical Skills Gained

[What you learned technically]

### Challenges Overcome

[What was hard and how you solved it]

### What I'd Do Differently Next Time

[Reflection on your process]

---

## Resources Used

- [Link to helpful documentation]
- [Tutorial or Stack Overflow post that helped]
- [GitHub issues or discussions that helped]
