# AI301
CodePath's AI Open Source Capstone Summer 2026

# Contribution [#]: [jenkins: Action Examples #3900]
https://github.com/backstage/community-plugins/issues/3900

- **Contribution Number:** [1 / 2 / 3]  
- **Student:** Ryan Bouapheng
- **Issue:** [[GitHub issue link](https://github.com/backstage/community-plugins)]  
- **Foked Issue:** [https://github.com/laosrb/community-plugins]
- **Status:** [Phase I / Phase II / Phase III / Phase IV] [In Progress / Complete]

---

## Why I Chose This Issue

I choose this issue because I have worked with TypeScript and Jenkins CI/CD. My goal is to become a better proficient coder in TypeScript, I hope to learn how to enjoy coding more.

---

## Understanding the Issue

### Problem Description

The Backstage Jenkins plugin is missing built-in template examples for its Scaffolder actions. Because these examples are absent, developers cannot see how to use or format the Jenkins actions in the developer portal's documentation.

### Expected Behavior

The plugin should include an examples file defining the YAML structure for its actions (e.g., passing job names or build arguments) so they automatically render on the /scaffolder/actions web page.

### Current Behavior

The actions are registered, but they lack an examples property. The "Installed Actions" UI shows the action definitions but leaves the examples section empty, making self-service difficult.

### Affected Components

The changes impact the Jenkins workspace within the backstage/community-plugins repository:

New File: An examples file (e.g., *.examples.ts) containing mock template setups using TemplateExample[].

Modifications: The existing action registration code where the new examples array needs to be imported and added to the action definition.
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
