# Branch Protection Rules

To maintain code quality and ensure a stable codebase, the following branch protection rules are enforced:

## Main Branch (`main`)

1. **Require Pull Request Reviews**

    - At least 1 reviewer must approve the pull request before merging.
    - Reviewers should check for:
        - Code quality.
        - Adherence to coding standards.
        - Passing tests.

2. **Restrict Direct Pushes**
    - Only maintainers can push directly to `main` in exceptional cases.

## Develop Branch (`develop`)

1. **Require Pull Request Reviews**

    - At least 1 reviewer must approve the pull request before merging.
