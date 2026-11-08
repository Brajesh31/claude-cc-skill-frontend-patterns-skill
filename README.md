# claude-cc-skill-frontend-patterns-skill

A Claude Code skill for applying maintainable frontend patterns across React, Next.js, state management, and performance-sensitive user interfaces.

## Overview

This skill focuses on frontend architecture and implementation practices that keep applications understandable as they grow. It covers component composition, state ownership, rendering behavior, performance, and practical UI engineering decisions.

## Main Topics

### Component Architecture

- Prefer composition over inheritance.
- Keep components focused on clear responsibilities.
- Separate reusable UI from feature-specific behavior.
- Define component interfaces with clear types.
- Avoid unnecessary prop drilling and excessive abstraction.

### State Management

- Keep state close to the component or feature that owns it.
- Distinguish local UI state from shared application state.
- Derive values where possible instead of duplicating state.
- Avoid unnecessary global state.
- Keep asynchronous state and error handling explicit.

### React and Next.js

- Use framework conventions for routing and data loading.
- Separate server and client responsibilities.
- Avoid unnecessary client-side JavaScript.
- Use appropriate loading and error boundaries.
- Keep rendering and data access predictable.

### Performance

- Measure before optimizing.
- Avoid unnecessary re-renders.
- Split code when it reduces initial loading cost.
- Optimize images and static assets.
- Use caching deliberately.
- Keep expensive work out of hot render paths.

## Installation

```bash
git clone https://github.com/Brajesh31/claude-cc-skill-frontend-patterns-skill.git ~/.claude/skills/cc-skill-frontend-patterns
```

## Usage

Invoke the skill for frontend implementation or architecture review:

```text
/cc-skill-frontend-patterns
```

Provide the framework version, project structure, UI requirements, state needs, and performance constraints.

## Recommended Workflow

1. Inspect the existing frontend architecture.
2. Identify component and feature boundaries.
3. Choose the simplest state model.
4. Reuse existing design-system components.
5. Implement responsive and accessible UI.
6. Add loading, empty, and error states.
7. Measure performance when needed.
8. Test behavior across target viewports.
9. Review bundle size and rendering behavior.

## Quality Checklist

- Components have clear responsibilities.
- State has a clear owner.
- Derived state is not duplicated.
- UI handles loading and failure.
- Forms and controls are accessible.
- Responsive behavior is tested.
- Performance decisions are measured.
- Existing project conventions are respected.

## Repository Contents

- `SKILL.md`: Main frontend development patterns.
- `README.md`: Component, state, and performance guidance.

## Practical Principle

A reusable component is useful when it reduces meaningful duplication. Do not build a component framework around a handful of simple views.
