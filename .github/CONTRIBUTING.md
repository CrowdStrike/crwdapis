# Contributing

_Welcome!_ We're excited you want to take part in the CrowdStrike community!

Please review this document for details regarding getting started with your first contribution, tools
you'll need to install as a developer, and our development and Pull Request process. If you have any
questions, please let us know by posting your question in the [discussion board](https://github.com/CrowdStrike/crwdapis/discussions).

## Code of Conduct

Please refer to CrowdStrike's general [Code of Conduct](https://opensource.crowdstrike.com/code-of-conduct/)
and [contribution guidelines](https://opensource.crowdstrike.com/contributing/).

## How you can contribute

- See something? Say something! Submit a [bug report](https://github.com/CrowdStrike/crwdapis/issues/new?assignees=&labels=bug%2Ctriage&template=bug.md&title=) to let the community know what you've experienced or found.
  - Please propose new features on the discussion board first.
- Join the [discussion board](https://github.com/CrowdStrike/crwdapis/discussions) where you can:
  - [Interact](https://github.com/CrowdStrike/crwdapis/discussions/categories/general) with other members of the community
  - [Start a discussion](https://github.com/CrowdStrike/crwdapis/discussions/categories/ideas) or submit a [feature request](https://github.com/CrowdStrike/crwdapis/issues/new?assignees=&labels=enhancement%2Ctriage&template=feature_request.md&title=)
  - Provide [feedback](https://github.com/CrowdStrike/crwdapis/discussions/categories/q-a)
  - [Show others](https://github.com/CrowdStrike/crwdapis/discussions/categories/show-and-tell) how you are using `crwdapis` today
- Submit a [Pull Request](#pull-requests)

### Commit Message Formatting and Hygiene

We use [_Conventional Commits_](https://www.conventionalcommits.org/en/v1.0.0/) formatting for commit
messages, which we feel leads to a much more informative change history. Please familiarize yourself
with that specification and format your commit messages accordingly.

Another aspect of achieving a clean, informative commit history is to avoid "noise" in commits.
Ideally, condense your changes to a single commit with a well-written _Conventional Commits_ message
before submitting a PR. In the rare case that a single PR is introducing more than one change, each
change should be a single commit with its own well-written message.

## Pull Requests

All code changes should be submitted via a Pull Request targeting the `main` branch. We are not assuming
that every merged PR creates a release, so we will not be automatically creating new SemVer tags as
a side effect of merging your Pull Request. Instead, we will manually tag new releases when required.

### Code Coverage

While we feel like achieving and maintaining 100% code coverage is often an untenable goal with
diminishing returns, any changes that reduce code coverage will receive pushback. We don't want
people to spend days trying to bump coverage from 97% to 98%, often at the expense of code clarity,
so there is room for responsible interpretation.
