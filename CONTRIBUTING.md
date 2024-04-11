# Contributing to CONTRIBUTING.md

First off, thanks for taking the time to contribute! ❤️

All types of contributions are encouraged and valued. See the [Table of Contents](#table-of-contents) for different ways to help and details about how this project handles them. Please make sure to read the relevant section before making your contribution. It will make it a lot easier for us maintainers and smooth out the experience for all involved. The community looks forward to your contributions. 🎉

> And if you like the project, but just don't have time to contribute, that's fine. There are other easy ways to support the project and show your appreciation, which we would also be very happy about:
>
> - Star the project
> - Tweet about it
> - Refer this project in your project's readme
> - Mention the project at local meetups and tell your friends/colleagues

## Table of Contents

- [Code of Conduct](#code-of-conduct)
- [I Have a Question](#i-have-a-question)
- [I Want To Contribute](#i-want-to-contribute)
- [Reporting Bugs](#reporting-bugs)
- [Suggesting Enhancements](#suggesting-enhancements)
- [Your First Code Contribution](#your-first-code-contribution)
- [Styleguides](#styleguides)
- [Commit Messages](#commit-messages)

## Code of Conduct

This project and everyone participating in it is governed by the
[CODE_OF_CONDUCT](code_of_conduct.md).
By participating, you are expected to uphold this code. Please report unacceptable behavior
to ...
## I Have a Question

> If you want to ask a question, we assume that you have read the available [Documentation]().

Before you ask a question, it is best to search for existing [Issues](https://github.com/wraff/quartoDemo0/wiki) that might help you. In case you have found a suitable issue and still need clarification, you can write your question in this issue. It is also advisable to search the internet for answers first.

If you then still feel the need to ask a question and need clarification, we recommend the following:

- Open an [Issue](https://github.com/wraff/quartoDemo0/issues).
- Provide as much context as you can about what you're running into.
- Provide project and platform versions (nodejs, npm, etc), depending on what seems relevant.

We will then take care of the issue as soon as possible.

## I Want To Contribute

> ### Legal Notice
>
> When contributing to this project, you must agree that you have authored 100% of the content, that you have the necessary rights to the content and that the content you contribute may be provided under the project license.

### Reporting Bugs

#### Before Submitting a Bug Report

A good bug report shouldn't leave others needing to chase you up for more information. Therefore, we ask you to investigate carefully, collect information and describe the issue in detail in your report. Please complete the following steps in advance to help us fix any potential bug as fast as possible.

- Make sure that you are using the latest version.
- Determine if your bug is really a bug and not an error on your side e.g. using incompatible environment components/versions (Make sure that you have read the [documentation](https://github.com/wraff/quartoDemo0/wiki). If you are looking for support, you might want to check [this section](#i-have-a-question)).
- To see if other users have experienced (and potentially already solved) the same issue you are having, check if there is not already a bug report existing for your bug or error in the [bug tracker](issues?q=label%3Abug).
- Also make sure to search the internet (including Stack Overflow) to see if users outside of the GitHub community have discussed the issue.
- Collect information about the bug:
- Stack trace (Traceback)
- OS, Platform and Version (Windows, Linux, macOS, x86, ARM)
- Version of the interpreter, compiler, SDK, runtime environment, package manager, depending on what seems relevant.
- Possibly your input and the output
- Can you reliably reproduce the issue? And can you also reproduce it with older versions?

#### How Do I Submit a Good Bug Report?

> You must never report security related issues, vulnerabilities or bugs including sensitive information to the issue tracker, or elsewhere in public. Instead sensitive bugs must be sent by email to ....

We use GitHub issues to track bugs and errors. If you run into an issue with the project:

- Open an [Issue]()  issues/new. (Since we can't be sure at this point whether it is a bug or not, we ask you not to talk about a bug yet and not to label the issue.)
- Explain the behavior you would expect and the actual behavior.
- Please provide as much context as possible and describe the *reproduction steps* that someone else can follow to recreate the issue on their own. This usually includes your code. For good bug reports you should isolate the problem and create a reduced test case.
- Provide the information you collected in the previous section.

Once it's filed: your issue will be flagged as [feature request] first, and if we agree on it, we will label it as [feature],meaning it has been accepted and the feature will eventually be added to the project.

### Suggesting Enhancements

This section guides you through submitting an enhancement suggestion for CONTRIBUTING.md, **including completely new features and minor improvements to existing functionality**. Following these guidelines will help maintainers and the community to understand your suggestion and find related suggestions.

#### Before Submitting an Enhancement

- Make sure that you are using the latest version.
- Read the [documentation]() carefully and find out if the functionality is already covered, maybe by an individual configuration.
- Perform a [search](https://github.com/wraff/quartoDemo0/ussues) to see if the enhancement has already been suggested. If it has, add a comment to the existing issue instead of opening a new one.
- Find out whether your idea fits with the scope and aims of the project. It's up to you to make a strong case to convince the project's developers of the merits of this feature. Keep in mind that we want features that will be useful to the majority of our users and not just a small subset. If you're just targeting a minority of users, consider writing an add-on/plugin library.

#### How Do I Submit a Good Enhancement Suggestion?

Enhancement suggestions are tracked as [Gitlab issues](https://github.com/wraff/quartoDemo0/issues).

- Use a **clear and descriptive title** for the issue to identify the suggestion.
- Provide a **step-by-step description of the suggested enhancement** in as many details as possible.
- **Describe the current behavior** and **explain which behavior you expected to see instead** and why. At this point you can also tell which alternatives do not work for you.
- You may want to **include screenshots and animated GIFs** which help you demonstrate the steps or point out the part which the suggestion is related to. You can use [this tool](https://www.cockos.com/licecap/) to record GIFs on macOS and Windows, and [this tool](https://github.com/colinkeenan/silentcast) or [this tool](https://github.com/GNOME/byzanz) on Linux.
- **Explain why this enhancement would be useful** to most CONTRIBUTING.md users. You may also want to point out the other projects that solved it better and which could serve as inspiration.

### Your First Code Contribution

#### Pull Request Guidelines

Here are a few rules to follow in order to make code reviews and discussions go more smoothly before maintainers accept and merge your work:

- you MUST run the test suite
- you MUST write (or update) unit tests
- you SHOULD write documentation

Please, write [commit messages that make sense](#commit-messages), and [rebase your branch](http://git-scm.com/book/en/Git-Branching-Rebasing) before submitting your Pull Request.

You may be asked to [squash your commits](http://gitready.com/advanced/2009/02/10/squashing-commits-with-rebase.html)
too. This is to "clean" your Pull Request before merging it (we don't want commits such as `fix tests`, `fix 2`, `fix 3`, etc.).

Also, while creating your Pull Request on GitLab, you MUST write a description which gives the context and/or explains why you are creating it.

For further information about creating a Pull Request, please read [this blog post](http://williamdurand.fr/2013/11/20/on-creating-pull-requests/).

## Styleguides

### Commit Messages

We follow the [Conventional Commits](https://www.conventionalcommits.org/) convention for our commit messages. Please adhere to this format for all commits in this project to maintain a coherent and readable code history.

**Format of the commit message**

```html
<type>(<scope>): <subject>

<body>

<footer>
```

**Example of a commit message :**

```sh
git commit -m "feat: add new API endpoint"
```

**Allowed 'type' values:**

- **build** : Builds - changes that affect the build system or external dependencies
- **chores** : Chores - updating grunt tasks etc; no production code change
- **ci** : Continous Integration - chanhes to our CI configuration files and scripts
- **docs** : Documentation - changes to the documentation
- **feat** : Features - new feature for the user, not a new feature for build script
- **fix** : Bug fixes - bug fix for the user, not a fix to a build script
- **perf** : Performance Improvements - a code change that improves performance
- **refactor** : Code Refactoring - a code change that neither fixes a bug or adds a feature
- **reverts** : Reverts - reverts a previous commit
- **style** : Style - formatting, missing semi colons, etc; no production code change
- **test** : Tests - adding missing tests, refactoring tests; no production code change

**Example 'scope' values**

- init
- runner
- watcher
- config
- web-server
- proxy
- etc.
The 'scope' can be empty (e.g. if the change is a global or difficult to assign to a single component), in which case the parentheses are omitted. In smaller projects such as Karma plugins, the 'scope' is empty.

**Message body**

- Uses the imperative, present tense: “change” not “changed” nor “changes”
- Includes motivation for the change and contrasts with previous behavior

**Message footer**

- **Referencing issues** : Closed issues should be listed on a separate line in the footer prefixed with "Closes" keyword like this :

```sh
Closes#234
```

or in case of multiple issues :

```sh
Closes#123, #245, #992
```

- **Breaking changes** : a commit that has a footer BREAKING CHANGE:, or appends a ! after the type/scope, introduces a breaking API change (correlating with MAJOR in Semantic Versioning). A BREAKING CHANGE can be part of commits of any type.

**Useful websites**
<https://www.conventionalcommits.org/en/v1.0.0/>
<http://karma-runner.github.io/1.0/dev/git-commit-msg.html>

## Attribution

This guide is based on the **contributing.md**. [Make your own](https://contributing.md/)!
