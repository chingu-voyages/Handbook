# Contributors Guide

![Developer writing an article](./assets/Developer_contributing_to_OSS.jpeg)

## Overview

We wholeheartedly encourage contributions and corrections to this Handbook. Your participation serves a dual purpose: it enhances the Handbook's quality while providing you with valuable experience in open-source practices, including collaborative Git and GitHub workflows, and the submission of changes through Pull Requests to our Admin Team for review.

## How to Contribute

When you see a correction that needs to be made, how to make part of the
Handbook clearer or more concise, or you have an idea for new information
that would be helpful to all Chingu's simply follow these steps:

1. Fork this repo
2. Create a working branch and make the desired changes.
3. Test your changes locally.
4. Push your working branch to GitHub
5. Open a [Pull Request](https://github.com/chingu-voyages/Handbook/pulls)
   in this repository

There's no need to assign a specific reviewer. When you create your PR one of
Chingu Admins will claim it and will start the review process.

As part of the review we'll use the GitHub PR you've created to ask questions
and make suggestions when appropriate. Our goal is to partner with you to make
the Handbook even better.

When this is complete we'll merge your PR into the Handbook!

## Guidelines

1. You should always create a [working branch](#working-branch-names) for your
   changes and PR them from it to the `development` branch. Once your change has
   been approved and merged by the Admin Team into `development` they will create
   a new PR to merge it into the `main branch`.

2. Use simple phrasing and terminology whenever possible. Remember that there
   Chingu's from 150+ countries and English is not everyone's first language so
   it's important that the Handbook be both clear and concise.

3. The best improvements to the Handbook address confusion and questions you
   have had that the current version didn't answer. Improvements don't have to be
   large to have a big impact for Chingu's.

4. If you include images use [Mermaid](https://mermaid.js.org/intro/) whenever
   possible. If you find that you must use another diagramming tool please use
   the free diagramming tool [draw.io](https://www.drawio.com/) and place a copy
   of the diagram file (`.drawio`) and the `png` images exported from it into the
   subdirectory containing the Markdown file where it's used.

   For example, if you create a new workflow diagram for the Pair Programming
   Guide you would place the file `pairprog_workflow.drawio` and the
   `pairprog_workflow.png` image you export from it into the `/docs/pairprog`
   subdirectory.

## Tips

### Working Branch Names

Format your working branches as `purpose/descriptive-name`.

`purpose` is any of the following:

- `fix` - fix a problem in the Handbook
- `feature` - add new content to the Handbook
- `refactor` - change to formatting or structure

The working branch name should be descriptive, but no longer than necessary.
You may also with to include an issue number in it if one was created for
this fix or feature.

For example, `fix/correct-spelling-123` would be used for a working branch
created to fix a spelling error reported by issue #123 in this repo.

### Commits

If you are making a large change start by creating an issue in this repo to
define what you intend to do and assign it to **_Chingu Admins_**. One of our
Admins will review your proposal and provide feedback. This will make sure
you don't spend a lot of time and effort on a change that can't be
accepted. It might also lead to ideas that would make your idea even better.

For large changes make sure you create small atomic commits. Regardless of how
big a change is you should create [good commit messages](https://chiamakaikeanyi.dev/how-to-write-good-git-commit-messages/)
