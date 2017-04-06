# GitHub Tips!
Some tips for using GitHub effectively for Network Canvas people.

## Contents

TOC to go here.

## General Stuff

### What is GitHub, and why do we use it?
Github is a place for us to store our application code, centrally. Each developer has a working copy of the code on their computer, but GitHub gives us a way to synchronise our work so that we can collaborate. It is built on a technology called "Git", which is used via the command line. GitHub provides a graphical user interface through it's website, along with social/project management components that make it more useful.

The general GitHub development workflow for Network Canvas looks like this:

* The project team and the lead developer break the development process down into smaller chunks on the project board, for specific discussion.
* Once we believe we have something ready to implement, a developer is assigned to the issue/task.
* The developer creates a _feature branch_ where they work independently on this task.
* Once complete, the feature branch is merged back into the master branch, which closes the issue.

### GitHub Glossary

#### Repository (or Repo)

A repository is the top level "container" on GitHub. It usually contains an entire piece of software, along with build tools, documentation, issues, and so on. In our project, we have separate repositories for Network Canvas, Architect, and Server.

#### Forking - the process at the heart of git.

Forking a project on GitHub, the entire projects repository gets copied to your GitHub account, including the files and the change history. Forking allows you to make edits without disrupting anything others are working on. Also, the upstream is easily kept 'clean', and you can experiment uninhibited in your fork. Inviting contributions from out of the team is easy (see Pull request).

#### Branch

A branch is an instance of a repository, branched off the shared change history at a certain point. Usually, branching occurs to keep order and track of progress when working on different topics in the same repository. In our project, we use 'feature branches', meaning that each feature we implement happens in its own branch called 'feature-xxx'.

#### Pull request

If the work in a branch is complete, it can be merged into upstream via a "pull request". This invites the owners of a repository to merge in code. As anyone can just fork, branch, change and request a pull (into upstream) this makes it easy to invite collaboration from outside of the team. The discussion board on a pull request is also a prolific environment for discussions.

#### Cloning

This is the process that creates a copy of a repository on your local machine. It is worth noting that you can also edit (and preview) files directly on GitHub - just make sure you are working on a branch/fork not to disrupt everyone's merge process.

#### Pushing

"Pushing" sends your local copy back to GitHub to be synchronised. This also means that your changes become visible to anyone looking at our repositories, since the changes will be visible on GitHub. For this reason, it is important to ensure that you do not push commits containing private or sensitive data.

#### Commit

A "commit" is the smallest unit of contribution to a GitHub project,
Should often be done and with unambiguous, concise and informative commit messages. Builds the smallest entity in the revision history. Commit messages are visible in a plethora of views.
Contact GitHub API Training Shop Blog About


### What about if I am not a developer?
GitHub is still _very_ important! Over the years, GitHub has expanded to include features for project management, issue management, and documentation.

You do not need to "clone" (GitHub parlance for creating your own copy) our code to contribute via GitHub. 

## Markdown

GitHub uses a language called Markdown to format the content of comments, issues, and many other aspects you may wish to contribute to.

[General overview](https://help.github.com/articles/basic-writing-and-formatting-syntax/)

[More advanced guide](https://guides.github.com/features/mastering-markdown/)

## GitHub Issues

## GitHub Project Boards


## How do I...
