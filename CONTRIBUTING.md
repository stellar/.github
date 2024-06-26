# How to contribute to a Stellar project

Your contributions to the [Stellar network](https://www.stellar.org/) will help improve the world’s
financial infrastructure, faster.

We want to make it as easy as possible to contribute changes that help the Stellar network grow and
thrive. There are a few guidelines that we ask contributors to follow so that we can merge your
changes quickly.

## Getting Started

* Make sure you have a [GitHub account](https://github.com/signup/free).
* Create a GitHub issue for your contribution, assuming one does not already exist.
  * Clearly describe the issue including steps to reproduce if it is a bug.
* Fork the repository on GitHub.

### Minor Changes

#### Documentation

For small changes to comments and documentation, it is not
always necessary to create a new GitHub issue. In this case, it is
appropriate to start the first line of a commit with 'doc' instead of
an issue number.

## Finding things to work on

The first place to start is always looking over the current GitHub issues for the project you are
interested in contributing to. Issues marked with [help wanted][help-wanted] or are usually pretty
self-contained and a good place to get started.

Stellar.org also uses these same GitHub issues to keep track of what we are working on. If you see
any issues that are assigned to a particular person or have the `in progress` label, that means
someone is currently working on that issue this issue in the next week or two.

Of course, feel free to create a new issue if you think something needs to be added or fixed.


## Making Changes

* Create a feature branch from where you want to base your work.
  * This is usually the main (or master) branch.
  * Please avoid working directly on the `main` (or `master`) branch.
* Make sure you have added the necessary tests for your changes and make sure all tests pass.

## Submitting Changes

* All content, comments, pull requests and other contributions must comply with the
  [Stellar Code of Conduct][coc].
* Push your changes to a topic branch in your fork of the repository.
* Submit a pull request to the repository in the Stellar
  organization.
  * Include a descriptive [commit message][commit-msg].
  * Changes contributed via pull request should focus on a single issue at a time.
  * Rebase your local changes against the `main` branch. Resolve any conflicts that arise.


At this point you're waiting on us. We like to at least comment on pull requests within three
business days (typically, one business day). We may suggest some changes, improvements or
alternatives.

# Additional Resources

* [Explore our APIs](https://developers.stellar.org/docs)
* [Stellar Developer Discord](https://discord.com/invite/stellardev)

This document is inspired by:

* https://github.com/puppetlabs/puppet/blob/master/CONTRIBUTING.md
* https://github.com/thoughtbot/factory_girl_rails/blob/master/CONTRIBUTING.md
* https://github.com/rust-lang/rust/blob/master/CONTRIBUTING.md

[help-wanted]: https://github.com/issues?q=is%3Aopen+is%3Aissue+user%3Astellar+label%3A%22help+wanted%22
[commit-msg]: https://github.com/erlang/otp/wiki/Writing-good-commit-messages
[coc]: https://github.com/stellar/.github/blob/master/CODE_OF_CONDUCT.md
