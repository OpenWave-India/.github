# Contributing to OpenWave India projects

Thanks for your interest in contributing! This guide applies to every OpenWave India repository that doesn't have its own `CONTRIBUTING.md`. If a repository has one, follow that instead, since it covers project-specific setup and checks.

## Picking up work

1. Look for issues labelled `good first issue` or `help wanted` in the repository you're interested in.
2. **Comment on the issue before you start**, saying how you plan to approach it, so that two people don't work on the same thing. A maintainer will confirm.
3. If you stop working on an issue, say so on the issue so someone else can pick it up.
4. Ask questions on the issue if anything is unclear. Acceptance criteria in the issue are what reviewers check.

### One issue at a time

To give everyone a chance, especially people making their first contribution:

- Work on **one issue at a time**. Claim the next one after your pull request is merged.
- Issues labelled `good first issue` are for **first-time contributors**. After your first merged pull request, please leave them for newcomers and pick `help wanted` or other issues instead.
- Pull requests for issues that weren't assigned to you, or beyond the one-at-a-time limit, may be closed so others can take the issue.
- If there's no update on an assigned issue for **7 days**, a maintainer may unassign it so someone else can take it. If you need more time, just comment on the issue.

Have an idea that isn't an issue yet? Open an issue (or a discussion in the [community repository](https://github.com/OpenWave-India/community/discussions)) and describe the problem before writing a large change.

## Pull requests

- Fork the repository and branch from `main` with a short descriptive name, for example `fix/windows-encoding` or `docs/setup-guide`.
- Keep each pull request to **one issue**. Don't include unrelated changes, such as reformatting other files or editing lines the issue doesn't mention.
- Before opening the pull request, check the **Files changed** tab to make sure only the intended changes are included.
- Link the issue in the description (`Closes #12`) and explain how you tested the change.
- Run the project's tests and linters locally. CI must pass before a pull request can be merged.
- Respond to review comments with new commits. Please don't force-push over them while a review is in progress.
- Write commit messages in the imperative mood ("Add JUnit report format").

## Quality expectations

- Bug fixes come with a test that fails without the fix.
- Tests should check behavior, not only that code runs.
- Don't claim features, benchmarks, or results that the code doesn't implement.
- Update the documentation when you change user-facing behavior.

## Recognition

Once your pull request is merged, you're credited in the repository's contributors list and changelog where the project keeps them.

## Code of Conduct

By participating, you agree to follow the [Code of Conduct](CODE_OF_CONDUCT.md).
