# Contributing

The following is a set of guidelines for contributing to `dlisio-notebooks`.

Some of the ways you can help:

- Submitting bug reports: see
  [Issues](https://github.com/equinor/dlisio-notebooks/issues).
- Proposing code for bug fixes and new features, then [making a pull
  request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests).
- Fixing typos and generally improving the documentation.
- Writing tutorials, examples, and how-to documents.

## Pull request process

1. Work on your own fork of the main repo.
1. Push your commits and make a draft pull request.
1. Check that your pull request passes all tests.
1. When all tests have passed and you are happy with your changes, change your
   pull request to "ready for review", and ask for a code review.

### Commits

We strive to keep a consistent and clean git history and all contributions
should adhere to the following:

1. All tests should pass on all commits
1. A commit should do one atomic change on the repository
1. The commit headline should be descriptive and in the imperative.
1. The commit description should be added to commits which require context
   (explanation why the commit was introduced, reasoning for taken decisions,
   important information about commit consequences, etc).
1. Remove metadata and the output from Jupyer notebooks before creating a
   commit to minimise noise in the commits and corresponding diffs.
