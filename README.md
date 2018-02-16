# Contributing to HastiJS projects

Everyone is very welcome to contribute to all [HastiJS](https://github.com/HastiJS) projects. All contributions are valued, no matter how large or small.

This document is ready as a guideline to be a roadmap for contributing to all HastiJS projects. So please see these guidelines before contributing.

## Code of Conduct

All HastiJS projects have a [Code of Conduct](https://github.com/HastiJS/contributing/blob/master/CODE_OF_CONDUCT.md) that **all contributors** are expected to follow. This code describes the minimum behavior expectations for all contributors.

## Rules

### Commit messages

Good commit messages speed up the reviewing process, help us write a good release note and help the future maintainers to find out why a particular change was made to the code or why a specific feature was added.

Your commit message structure must be like this:

```
Short (50 chars or less) summary of changes

More detailed explanatory text, if necessary.  Wrap it to about 72
characters or so.  In some contexts, the first line is treated as the
subject of an email and the rest of the text as the body.  The blank
line separating the summary from the body is critical (unless you omit
the body entirely); tools like rebase can get confused if you run the
two together.

Further paragraphs come after blank lines.

  - Bullet points are okay, too

  - Typically a hyphen or asterisk is used for the bullet, preceded by a
    single space, with blank lines in between, but conventions vary here
```

#### SO

A commit message can have three main parts. **Summary**, **body** and **footer**.

The summary is first line of the commit message and often the only part of the commit message that displays. So it is the most critical.

The body is optional and a chance to elaborate on the change you made. Focus on the motivation and extra considerations for the change rather than detailing what you changed.

The footer area is below the message body (if present) or below the summaty line if there is no message body. The footer is where you should reference issues or ticket numbers that the change pertains to.

#### DO

* Start message summary with a present tense verb with capitalized first letter like "Fix", "Add" and "Change" instead of "Fixed", "Added" and  "Changed" or a non-verb word.

* Always separate message body from the summary line by a blank line. In other words, the 2nd line in your commit message should always be blank if you are making a multi-line commit.

* The footer area must always be separated from items above it by a blank line.

#### DON'T

* Don't end the summary line with a period.

* Don't use emojis in your commit message (summary, body or footer).

* Don't combine actions that can be in separate commits into one commit.

#### Examples

Here are some examples of acceptable and not acceptable commit messages:

Not acceptable:

```
Fix issue #123
```

```
Add 404 page and modify after login redirection URI
```

Acceptable:

```
Fix search in post titles using RegEx

Issue #123
```

```
Add a default 404 page

Showing a not found (404) page would be handy
for requests that have no target page defined by user.
```

```
Modify after login redirection URI
```

### Pull Requests

Contributing to all HastiJS projects will start by opening a pull request. No pull request can be merged without being reviewed.

#### DO

* Use a clear and descriptive title for your pull request.

* Write a convincing description of why we should merge your pull request. It's your job to convince us. You can answer **why** it's needed and provide use-cases.

* Lint and test before submitting the pull request.

* New features have to have tests and documentation.

* Make the pull request from a [topic branch](https://github.com/dchelimsky/rspec/wiki/Topic-Branches), not master branch.

* All pull request target branch must be master.
