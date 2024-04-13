# Git Branch Management Guide

This guide outlines best practices for branch management in our projects to ensure a smooth, efficient, and error-free development process.

## 1. Branch Organization

- **Main Branch**:
  - The `main` or `master` branch is the production branch. All production-ready code lives here.
- **Development Branch**:
  - The `dev` branch serves as an integration branch for features. This is where all development branches merge before they are tested and moved to the `main` branch.
- **Feature Branches**:
  - Create feature branches from `dev` for new features or significant changes.
- **Version Branches**:
  - Create Version branches from `dev` for new version release.

## 2. Code Quality Checks

- **Pull Requests**:
  - Always use pull requests to merge branches into `dev`, `version branch` and `main`. This ensures that the code is reviewed and tested.
- **Code Reviews**:
  - Require at least one other team member to review the code in a pull request to maintain code quality and catch errors early.

## 3. Commit Management

- **Small Commits**:
  - Keep commits small and focused. Each commit should represent a single logical change. This makes it easier to identify where issues were introduced and to roll back changes if necessary.

## 4. Branch Lifespan

- **Short-lived Feature Branches**:
  - Feature branches should be kept short-lived to minimize divergence from the main development line (`dev`). Aim to merge back within 1-2 weeks.
- **Branch Cleanup**:
  - Delete branches once they are merged and are no longer needed.

## 5. Handling Large Changes

- **Sub-branches**:
  - If a feature is too large, consider breaking it into smaller sub-branches that can be merged into the main feature branch incrementally.

## Additional Recommendations

- **Tagging Releases**:
  - Use tags for each release to mark a point in history. This makes it easier to track versions and rollback if necessary.
