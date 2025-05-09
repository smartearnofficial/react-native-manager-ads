# Introduction

First, thank you for considering contributing to React Native Google Mobile Ads! It's people like you that make the open source community such a great community! 😊

We welcome any type of contribution, not just code. You can help with;

- **QA**: file bug reports, the more details you can give the better (e.g. platform versions, screenshots SDK versions & logs)
- **Docs**: improve reference coverage, add more examples, fix typos or anything else you can spot.
  - At the bottom of every page on our docs site you can click the `Edit this page` button to go to that pages markdown file or view the [documents](https://github.com/invertase/react-native-google-mobile-ads/tree/main/docs) directly
- **Community**: presenting the project at meetups, organizing a dedicated meetup for the local community, ...
- **Code**: take a look at the [open issues](issues). Even if you can't write code, commenting on them, showing that you care about a given issue matters.

## Project Guidelines

### How can we help you get comfortable contributing?

It is normal for a first pull request to be a potential fix for a problem but moving on from there to helping the project's direction can be difficult.

We try to help contributors cross that barrier by offering good first step issues (labeled `good-first-issue`). These issues can be fixed without feeling like you are stepping on toes. Ideally, these are non-critical issues that are well defined. They will be purposely avoided by mature contributors to the project, to make space for others.

Additionally issues labeled with the `Help:` prefix can also be picked up, these may not necessarily require code changes but rather help with debugging and finding the cause of the issue whether it's a bug or a users incorrect setup of the library or project.

We aim to keep all project discussion inside GitHub issues. This is to make sure valuable discussion is accessible via search. If you have questions about how to use the library, or how the project is running - GitHub issues are the go-to tool for this project.

### What if you only know how to develop for one platform?

This is normal don't worry - not everyone can develop native code for Obj-C and Java, we understand that.

Although we won't merge Pull Requests unless they support all applicable platforms, we do however recommend that you still submit a PR
for the Platform that you do know and then label it as either `Help: iOS` or `Help: Android` (or post a comment requesting it to be labeled).
This will allow other contributors to help add the missing platform support by making changes to your existing PR.

### Our expectations on you as a contributor

To quote [@alloy](https://github.com/alloy) from [this issue](https://github.com/Moya/Moya/issues/135):

> Do not ever feel bad for not contributing to open source.

We want contributors to provide ideas, keep the ship shipping and to take some of the load from others. It is non-obligatory; we’re here to get things done in an enjoyable way. :trophy:

We do ask though that you follow the conduct guidelines set out in our [Code of Conduct](/CODE_OF_CONDUCT.md) throughout your contribution journey.

### What about if you have problems that cannot be discussed in a public issue?

You can reach out to us directly via Discord direct messages or Twitter if you'd like to discuss something privately, alternatively you can also email us at `oss[at]invertase.io`

#### Project Owners

- [Salakar](https://github.com/Salakar)
  - Twitter: [@mikediarmid](https://twitter.com/mikediarmid)
  - Discord: `Salakar#1337`
- [Ehesp](https://github.com/Ehesp)
  - Twitter: [@elliothesp](https://twitter.com/elliothesp)
  - Discord: `Alias#3980`

## Code Guidelines

### Your First Contribution

Working on your first Pull Request? You can learn how from this _free_ series, [How to Contribute to an Open Source Project on GitHub](https://egghead.io/series/how-to-contribute-to-an-open-source-project-on-github).

## Local Setup

To get started locally the following steps are required:

### Step 1: Clone the repository

```bash
git clone https://github.com/smartearnofficial/react-native-manager-ads.git
cd react-native-manager-ads
```

### Step 2: Install test project dependencies

```bash
yarn
```

## Submitting code for review

All code changes should be submitted as a pull request to the `main` branch.

The bigger the pull request, the longer it will take to review and merge. Try to break down large pull requests in smaller chunks that are easier to review and merge. It is also always helpful to have some context for your pull request. What was the purpose? Why does it matter to you? Tag in any linked issues.

To aid review we also ask that you fill out the PR template as much as possible.

> Please use draft pull requests if the pull request is not yet complete.

### Your PR title

We use the [Conventional Commits](https://www.conventionalcommits.org/) format throughout the project. Your Pull Request title should be
in this format; however your commits themselves do not need to follow this format as all PRs are eventually squash merged.

#### Examples

- `docs(consent, ios): added extra example for GDPR flow on iOS`
- `tests(perf): should throw invalid arg error`
- `fix(insterstial, android): fixed NPE crash`
- `feat(video): add support for video load timeouts`

See the [Conventional Commits](https://www.conventionalcommits.org/) specification for more information.

### Code review process

Pull Requests to the `main` branch require one or more peer-review approvals and passing status checks before they can be merged.

Reviews of Pull Requests are based on the following acceptance criteria:

- Does the PR provide cross-platform support?
  - i.e. if adding a new feature then does the implementation provide iOS and Android support.
  - Pull Requests should not be merged unless both platforms are supported (unless the feature is specific to one platform only)
- If APIs have changed;
  - Has the documentation been updated?
  - Have the TypeScript types been added?
- Have the tests been updated or new tests been added to test newly implemented or changed functionality.
  - E2E tests.
  - Other tests through Jest.
- Do all CI checks pass.

Once a PR is merged into the `main` branch; new versions of the changed packages are automatically created and published to NPM.

## [No Brown M&M's](http://en.wikipedia.org/wiki/Van_Halen#Contract_riders)

If you made it all the way to the end, bravo dear user, we love you. You can include the 🔥 emoji at the bottom of your issue or PR to signal to us that you did in fact read this file and are trying to conform to it as best as possible: `:fire:`.
