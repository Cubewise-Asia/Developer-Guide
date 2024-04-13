# Development Flow

## Developing New Features/Fixing Bugs
1. **Create an issue** – Start by creating a new issue in the tracking system.
2. **Describe the issue or feature** – Provide a detailed description of the feature to be developed or the bug to be fixed.
3. **Create a branch from the issue page** – The base for this branch should be the `dev` branch, or a specific version branch if the bug fix is for a particular release.
4. **Setup your development environment**:
    - Open a terminal on your development machine.
    - Navigate to the project folder.
    - Run `git fetch`, then `git checkout` to switch to the new branch you just created.
5. **Complete the development** – Once you have implemented the feature or fixed the bug, create a pull request (PR) and assign a reviewer.

## Reviewing PRs

### Reviewer Responsibilities
1. **Ensure compatibility** – Check if the PR will cause any issues with the base branch.
2. **Assess code quality** – Evaluate if the code's quality is sufficient to be merged into the base branch.

### Applier Responsibilities
1. **Test the code** – Ensure the code can be executed, built, compiled, or packaged on your side.
2. **Manage commits** – Check if there are too many commits in a PR. It is recommended to limit the number of commits per PR to maintain clarity and manageability.
