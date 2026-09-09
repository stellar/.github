# How to contribute to a Stellar project

Your contributions to the [Stellar network](https://www.stellar.org/) will help improve the world’s
financial infrastructure.

We want to make it as easy as possible to contribute to Stellar in ways that make the network grow
and thrive. There are a few guidelines that we ask contributors to follow so that we all work
effectively together.

> [!TIP]
> The Stellar network is open, decentralised, and programmable. For many ideas you may have, they can
> be built without changes to the projects hosted here. Want to contribute to Stellar? Build on Stellar!
> And share your feedback in the forums listed below.

To contribute to the work of maintaining the projects hosted here the biggest impact contributions
are in discussions, sharing new ideas, reporting bugs, and sharing experience reports.

## Getting Started

* Make sure you have a [GitHub account](https://github.com/signup/free)
* Read the [Stellar Code of Conduct][coc], as all content, comments, pull requests and other
  contributions must comply with it
* Create discussions at https://github.com/orgs/stellar/discussions with problems and new ideas,
  or participate in existing discussions
* Create proposals at https://github.com/stellar/stellar-protocol after sharing ideas in a
  discussion first
* Create GitHub issues for bugs and feature requests that target specific projects

## Reporting Bugs and Requesting Features

First search for an existing issue and join a relevant discussion if an existing issue is present.

After confirming an issue does not already exist, create a GitHub issue with:
  * The concrete problem that needs solving.
  * For bugs, include a minimal reproducer with the expected and actual behavior.
  * Relevant alternatives, if any, and their tradeoffs.
  * Verify everything reported before submitting. Do not submit speculative findings or generated
    lists of possible issues.

## Pull Requests

Projects hosted here only accept pull requests for issues with the `help wanted` label. Unsolicited
pull requests will be closed without an explanation and reported as spam. Making changes requires
deep architectural knowledge, a good understanding of system constraints, and an idea about the
project roadmap. Many Stellar projects facilitate financial transactions or are dependencies to many
other projects. Correctness is critical and thoughtful evolution of behaviour and APIs is paramount.
However, maintainer and reviewer time is limited. External contributors often do not have the context
required and reviewing takes the maintainers' focus away from high-priority work that's been
discussed in the discussion forums and issues.

Key things to keep in mind when creating a pull request:
* Confirm, does the pull request narrowly address an open issue and have you been assigned?
* Fork the project's repository and submit the pull request from a branch in your fork.
* Link the approved issue and keep the pull request narrowly within the scope of that issue.

## AI-Assisted Contributions

The use of AI tools to improve productivity and the quality of contributions is encouraged. AI assistance does not, however, change the responsibilities or standards that apply to the human contributor.

Before exposing other community members to AI-assisted content, the human submitter is responsible for:

- Reviewing and verifying all generated content, including code, tests, code comments, documentation, issues, pull-request descriptions, review feedback, chat messages, forum posts, and other project or community communications. Appropriate tests and checks must be performed where applicable.
- Ensuring the contribution is correct, relevant, and appropriate for the project, including its security, reliability, maintainability, and adherence to project standards.
- Ensuring they have the right to submit the contribution, including compliance with applicable copyright, licensing, attribution, and other third-party requirements.
- Fully understanding the contribution. The submitter must be able to explain it in their own words, including its context, assumptions, design choices, tradeoffs, and implications, and be able to answer questions and validate changes arising during review.
- Taking full responsibility for the contribution. AI assistance does not transfer responsibility for errors, omissions, security issues, licensing problems, or other consequences to the AI tool or its provider.
- Respecting the time and attention of other community members. AI must not be used to generate high volumes of low-quality or speculative contributions, or to shift the burden of understanding, verification, debugging, or cleanup onto reviewers and maintainers.

AI tools must not autonomously publish contributions or communications including code changes, issues, reviews, chat messages, or forum posts to community channels without human review. AI-assisted contributions are held to the same standards as contributions produced without AI assistance.

## Additional Resources

* [Explore our APIs](https://developers.stellar.org/docs)
* [Stellar Developer Discord](https://discord.com/invite/stellardev)

This document is inspired by:

* https://github.com/puppetlabs/puppet/blob/master/CONTRIBUTING.md
* https://github.com/thoughtbot/factory_girl_rails/blob/master/CONTRIBUTING.md
* https://github.com/rust-lang/rust/blob/master/CONTRIBUTING.md

[help-wanted]: https://github.com/issues?q=is%3Aopen+is%3Aissue+user%3Astellar+label%3A%22help+wanted%22
[commit-msg]: https://github.com/erlang/otp/wiki/Writing-good-commit-messages
[coc]: https://github.com/stellar/.github/blob/master/CODE_OF_CONDUCT.md
