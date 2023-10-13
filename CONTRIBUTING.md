# Contributing to Starbeam

:+1::tada: First off, thanks for taking the time to contribute! :tada::+1:

The following is a set of guidelines for contributing to Starbeam, Starbeam Development and its packages, which are hosted in the [Starbeam Organization](https://github.com/starbeamjs) on GitHub. These are mostly guidelines, not rules. Use your best judgment, and feel free to propose changes to this document in a pull request.

#### Table Of Contents

[Code of Conduct](#code-of-conduct)

[In Progress](#in-progress)

[How Do I Submit a (Good) Bug Report?](#how-do-i-submit-a-good-bug-report)

## Code of Conduct

This project and everyone participating in it is governed by the [Starbeam Code of Conduct](https://github.com/starbeamjs/.github/blob/main/CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code

## In Progress

This document is a work in progress and is still being actively written. Please bear with us!

## How Do I Submit A (Good) Bug Report?

Bugs are tracked as [GitHub issues](https://guides.github.com/features/issues/). After you've determined which repository your bug is related to, create an issue on that repository.

Explain the problem and include additional details to help maintainers reproduce the problem:

- **Use a clear and descriptive title** for the issue to identify the problem.
- **Provide specific examples to demonstrate the steps**. Include links to files or GitHub projects, or copy/pasteable snippets, which you use in those examples. If you're providing snippets in the issue, use [Markdown code blocks](https://help.github.com/articles/markdown-basics/#multiple-lines).
- **Describe the behavior you observed after following the steps** and point out what exactly is the problem with that behavior.
- **Explain which behavior you expected to see instead and why.**
- **If the problem wasn't triggered by a specific action**, describe what you were doing before the problem happened and share more information using the guidelines below.

Provide more context by answering these questions:

- **Can you reproduce the problem in dev mode and production mode?** If the problem only occurs in one of the two modes, state that explicitly.
- **Does the problem occur when building a project that uses Starbeam or when running it in a browser?**
- **Are you building a library or an app with Starbeam?**
- **What build process are you using to build the project that included Starbeam?** Be as specific as possible. Include:
  - the build system (e.g. Webpack, Vite) and the version you are using in your project (using a command like `pnpm why @starbeam/universal`).
  - the version of Node you are using
  - 
- **Did the problem start happening recently** (e.g. after updating to a new version of Starbeam) or was this always a problem?
- If the problem started happening recently, **can you reproduce the problem in an older version of Starbeam?** What's the most recent version in which the problem doesn't happen?).
- **Can you reliably reproduce the issue?** If not, provide details about how often the problem happens and under which conditions it normally happens.

Include details about your configuration and environment:

- **Which version of Starbeam are you using?** You can get the exact version from your package manager with a command like `pnpm why starbeam`
- **Which browser did the problem occur in?** If the problem occurs in a browser, which browser did the problem occur in. If possible, test in multiple browser engines (test in Firefox and Safari if possible). Determine whether it's a problem with a specific browser or whether it happens in all browsers. 
- **Which [packages](#starbeam-and-packages) do you have installed?** You can get that list by using the `list` command in your package manager (i.e. `pnpm list --filter "@starbeam/*"`)

## Background

This guide was originally modified from [Atom's CONTRIBUTING.md] by [@wycats](https://github.com/wycats). It is now maintained by Starbeam's maintainers and contributors.
