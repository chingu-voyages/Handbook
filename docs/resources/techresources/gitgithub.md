# Git Workflow

![Team git/GitHub workflow](./assets/Team_git_workflow.jpeg)

## Importance of Good Practices

Your project's source code is its single most important artifact. The loss or
corruption of your code base is a catastrophic event that can impact not just
your project, but also your [reputation](https://about.gitlab.com/2017/02/01/gitlab-dot-com-database-incident/) as a professional developer.

This makes it critical that your team defines the process that everyone on the
team will rigidly adhere to when making and promoting changes. The good news is
that despite its importance, establishing a solid Git Workflow isn't difficult
and both Git and GitHub are battle-tested tools.

## Setting Up Your Local Git Repo

Chingu requires that our teams maintain their projects in
[GitHub](https://github.com/). While there are other alternatives, such as
BitBucket and GitLab, centralizing on a common cloud-based service greatly
simplifies the process of familiarizing Chingus new to git and cloud-based
source code management. It also simplifies our monitoring process since there's
only one such service to interface with.

Git maintains a record of your participation and activity against your team's git
repo - commits, issues, pull requests, and pull request reviews to name just a
few. However, in order to correctly attribute the work you perform to you they
have to know who you are. This is important since prospective employers will
use the metrics in your GitHub profile to evaluate your capabilities, based on
your project work.

To ensure that git and GitHub properly collect and attribute your activities
follow these instructions to set up your GitHub user name and email address.
Make sure that the email address you set up in your local git matches the email
address in your GitHub Profile.

- [Customizing Git - Git Configuration](https://git-scm.com/book/en/v2/Customizing-Git-Git-Configuration)
- [About commit email addresses](https://docs.github.com/en/github/setting-up-and-managing-your-github-user-account/setting-your-commit-email-address) (GitHub)

## Working / Development / Master Branch Workflow

There are multiple workflow models you can choose to adopt, but if you are new
to Git and GitHub, one type of Git workflow is presented here. This model is
based on the assumption that your team will set up a skeleton repo in GitHub
from which all team members will then clone to their computers

### Git Branches

A three-level hierarchy of branches is created, through which changes are
promoted.

- ***Working branches*:** Individual branches created by each developer when
they are working on changes and bug fixes. There are 3 basic types of
branches: **fix**, **feature**, and **refactor**. For example:
`feature/course-review`.
- ***Development***: Reflects the code for the next release. Developers work in
working branches, which are then pulled into this branch. All code pulled into
this branch must be tested and undergo peer review as part of the PR process.
- ***Master***: Only updated from the development branch Pull Requests. This
branch always reflects the current production release that is seen by live
users.

## The Workflow

![Git Workflow](./assets/Using_Git_GitHub_in_a_Team.png)

1. Once the skeleton repo is built in GitHub, team members will clone it to their individual computers. Working branches are created for specific features and
tasks (like bug fixes).
2. All normal development activities occur on team members' individual
computers. **Commits should be frequent** and each commit should have a
discrete, atomic purpose.
3. **Changes should be frequently pushed to the matching working branch** on
GitHub. This ensures that if a computer is lost, stolen, or malfunctions, your
work will still be available to the rest of your team
4. From time to time, you may also need to pull working branches to your
individual computer. For example, you'll need to do this if/when you help
another team member with one of their tasks.
5. Once a feature has been unit tested, a Pull Request (PR) should be created
to fold it into the development branch. It's always a good idea to require that
PRs be reviewed by another member of the team. This helps to ensure that the
quality of the app is maintained.
6. When a group of features are ready to be promoted to Production, they
should be thoroughly tested together. Then, a Pull Request should be created
in order to move them into the master branch which reflects the code base
that's in Production or soon to be promoted to Production.
7. Once the PR to the master branch has been completed, you are then ready to
release its contents into your Production runtime environment.

### Git Pull Requests

#### Writing the Pull Request

1. Include the **purpose of the Pull Request**. For example: "This makes login/register windows close when clicking outside the box".
2. If the change is visual, make sure to **include a screenshot** or GIF.
3. Consider providing an overview of **why the work is taking place** (with any relevant links); don’t assume familiarity with the history.
4. **Be explicit about what feedback you want**, if any: a quick pair of eyes on the code, discussion on the technical approach, critique on design, a review of copy, etc..
5. **Be explicit about when you want feedback.** If the Pull Request is a work in progress, say so. A prefix of `[WIP]` in the title is a simple, common pattern to indicate this.
6. **@mention individuals** that you specifically want to involve in the discussion, and mention why.

#### Reviewing a Pull Request

1. **Understand the issue** that is being fixed, or the feature being added. Check the description on the pull, and check out the related issue. If you don’t understand something, ask the submitter for clarification.
2. **Reproduce the bug** (or the lack of feature) in the destination branch, usually `development`. The referenced issue will help you here. If you’re unable to reproduce the issue, contact the issue submitter for clarification.
3. **Check out the pull** and test it. Does the feature work? Is the issue fixed? Does it have any nasty side effects? Try to create suspect inputs. If it operates on the value of a field, try things like strings (including an empty string), null, numbers, or dates. Try to think of edge cases that might break the code.
4. **Merge the target branch**. It is possible that tests or the linter have been updated in the target branch since the pull was submitted. Merging the pull could cause the core to start failing.
5. **Read the code**. Understanding the changes will help you find additional things to test. Contact the submitter if you don’t understand something.
6. **Go line-by-line**. Are there style guide violations? Strangely named variables? Magic numbers? Do the abstractions make sense to you? Are things arranged in a testable way?
7. **Speaking of tests:** are they there? If a new function was added, does it have tests? Do the tests, well, TEST anything? Do they just run the function or do they properly check the output?
8. **Suggest improvements.** If there are changes needed, be explicit and comment on the lines in the code that you’d like changed. You might consider suggesting fixes. If you can’t identify the problem, animated screenshots can help reviewers understand what’s going on.
9. **Hand it back.** If you found issues, re-assign the submitter to the pull to address them. Repeat until mergeable.
10. **Hand it off.** If you’re the first reviewer and everything looks good but the changes are more than a few lines, hand the pull to someone else to take a second look. Again, try to find the right person to assign it to.
11. **Merge the code.** When everything looks good, merge into the target branch. Check the labels on the pull to see if backporting is required, and perform the backport if so.

## References

- [GitHub Guides](https://guides.github.com/)
- [GitHub Help](https://help.github.com/)
- [tryGit](https://try.github.io/levels/1/challenges/1)
- [Chingu Video: How to use git & GitHub in a Team](https://youtu.be/0HizvYgNPA0)
- [Chingu Video: How to Undo a git commit](https://youtu.be/ZoIBdFuj8_M)
- [Chingu Video: How to Delete git commits](https://youtu.be/Wjd8iEcCSM4)
