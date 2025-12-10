---
name: "kiro-autonomous-agent"
displayName: "Kiro Autonomous Agent Delegation"
description: "Delegate implementation tasks to Kiro Autonomous Agent by creating GitHub issues with 'kiro' label for remote execution"
keywords:
  [
    "autonomous",
    "agent",
    "delegate",
    "task",
    "implementation",
    "github",
    "issue",
    "kiro",
    "remote",
    "execution",
  ]
---

# Kiro Autonomous Agent Delegation Power

This power enables users to delegate implementation tasks to Kiro Autonomous Agent instead of implementing them locally. When users have created specs or tasks in Kiro IDE and want to delegate the implementation work, this power creates GitHub issues with the 'kiro' label to trigger remote execution by Kiro Autonomous Agent.

## Workflow

### Creating Delegation Issues

When a user wants to delegate a task to Kiro Autonomous Agent:

1. **MUST** create a GitHub issue in the target repository
2. **MUST** add the 'kiro' label to trigger autonomous agent execution
3. **SHOULD** provide detailed task description including:
   - Clear requirements and acceptance criteria
   - Relevant context about the codebase
   - Any specific patterns or conventions to follow
   - Links to related specifications or documentation

## Issue Content Structure

The GitHub issue **SHOULD** include:

```markdown
## Task Description

[Clear description of what needs to be implemented]

## Requirements

- [ ] Requirement 1
- [ ] Requirement 2
- [ ] Requirement 3

## Acceptance Criteria

- [ ] Criteria 1
- [ ] Criteria 2

## Additional Context

[Any relevant context, patterns, or constraints]

## Related Resources

- Link to specs
- Link to related issues/PRs
- Documentation references
```
