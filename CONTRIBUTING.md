## OSEA Contributors Guide

Welcome to the Open Source and Energy Access (OSEA) contributors' guide. We appreciate your consideration of contributing to this repository and celebrate all the contributors who add value to the community. 
This document guides you through smooth paths to a meaningful contribution to the project. Following the guide implies respecting the maintainers and developers who manage and develop the projects. In return, they will reciprocate by addressing your issue, assessing and helping you finalise your pull requests until they are merged.
OSEA prioritizes and values its commitment to creating a safe and inclusive community where everyone can contribute and thrive. It is therefore essential to ensure that everyone adheres to our [Code of Conduct](./CODE_OF_CONDUCT.md).

## Getting Started

Review the existing issues and the discussion thread to ensure your issue has not been previously addressed. We have provided resources to reduce time wastage and increase productivity. 
Most documentation is currently written in Markdown, making it easy to add, modify, and delete content as necessary.

## Setting up your Environment

⚠️ Heads up! If you'd like to work on issues, please ensure you fork the repository, create a new branch, and work on this branch to avoid pushing your changes directly to the master/main branch. 

- Follow the steps outlined in the repos `ReadMe` file for local development.
- Create a new branch by typing this command:
  
  ```git
   git checkout -b <branch-name>
  ```
- Change the branch name to whatever you want. For example:

  ```git
  git checkout -b update-fixture
  ```

## Creating a Pull Request

To create a pull request, please ensure that an existing issue exists and that you have been assigned to it, unless your change is minor, such as fixing a typo.
This allows the maintainer to provide guidance and prioritize tasks; otherwise, you may risk spending time on something that doesn't get accepted for various reasons.

We acknowledge everyone's contributions and strive for transparent communication. We highly recommend clear communication before undertaking any work. Upon issue assignment, two options are available to you.

1. Using the GitHub interface to fork the repo, make an edit right here in the GitHub client, and then submit a pull request (no code or terminals or IDE required). [This guide](https://guides.github.com/activities/hello-world/) shows just how to do that for a small personal repo. You would simply replace creating a new repository by navigating to this one and forking it instead. This is a great idea if you simply plan to add to or edit one of the Markdown files we use for documentation in this project.
2. The second option is to go the traditional route of forking the repo, creating a local copy of that fork, and working on your changes that way. This is also the only option if the project expands to include an associated application. For that, [we recommend this guide](https://www.dataschool.io/how-to-contribute-on-github).

## Conventional Commits
When creating a Pull Request, it is best practice to use Conventional Commits to describe the purpose of your changes.

- `chore`:  Miscellaneous commits, eg, modifying a file.
- `feat`: Commits that add or remove a feature.
- `docs`: Commits that affect documentation only.
- `fix`: Commits that fix a bug of a preceding feature commit.
- `refactor`: Commits that rewrite/restructure your code.
- `revert`: Creates a new commit that undoes the changes.

## Waiting for Review

Waiting part plays a pivotal role in your contributor journey. Please be patient if the maintainers do not review your pull request immediately after submission. It might take time for one to be in the right condition to review all submitted pull requests. 
We would rather not rush a response after someone has taken the time and effort to submit it. If it has been over one week and you haven't received any acknowledgement, you can post a comment on your PR as a reminder.

The purpose of reviews is to create the best experience we can for our contributors. Please be aware of the following:

1. Reviews are always respectful, acknowledging that everyone did the best possible job with the knowledge they had at the time.
2. Reviews discuss content, not the person who created it.
3. Reviews are constructive and start a conversation around feedback. Embrace the feedback!

If the pull request looks good, a maintainer will typically provide feedback and merge the request immediately. 
Otherwise, they will let you know what questions they have or what needs to change before your work can be accepted. Once it is, you'll see your changes on the master branch, and your open-source contribution will be complete!
