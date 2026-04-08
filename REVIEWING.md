# Reviewing Guide

This document covers who may review pull requests for this project, and provides guidance on how to perform code reviews that meet our community standards and code of conduct. All reviewers must read this document and agree to follow the project review guidelines. Reviewers who do not follow these guidelines may have their privileges revoked.

# Table of Contents

* [The Reviewer Role](#the-reviewer-role)
* [Values](#values)
* [Process](#process)
  * [1. Submit a Pull Request (PR)](#1-submit-a-pull-request-pr)
  * [2. Assign Reviewers](#2-assign-reviewers)
  * [3. Review Checklist](#3-review-checklist)
  * [4. Feedback and Iteration](#4-feedback-and-iteration)
  * [5. Approval and Merging](#5-approval-and-merging)
  * [6. Closing PRs](#6-closing-prs)
* [Checklist](#checklist)
* [Reading List](#reading-list)

  
## The Reviewer Role

Only **maintainers** review pull requests. The reviewer’s responsibilities include:

- Ensuring the contribution meets **project standards** for code, documentation, UX, or design  
- Verifying that contributions do not break existing functionality or workflows  
- Providing **constructive, respectful feedback** in line with the ADP Code of Conduct  
- Confirming that all commits are properly signed or authorized, if required  
- Making sure pull requests include **clear descriptions** and relevant context for changes  

> Note: Reviewers should not assume intent or skill level. Always be patient, polite, and supportive, especially for first-time contributors.

## Values

All reviewers must abide by the [Code of Conduct](CODE_OF_CONDUCT.md) and are also protected by it. A reviewer should not tolerate poor behavior and is encouraged to report any behavior that violates the Code of Conduct. All of our values listed above are distilled from our Code of Conduct.

Below are concrete examples of how it applies to code review specifically:

### Inclusion

Be welcoming and inclusive. You should proactively ensure that the author is successful. While any particular pull request may not ultimately be merged, overall we want people to have a great experience and be willing to contribute again. Answer the questions they didn't know to ask or offer concrete help when they appear stuck.

### Sustainability

Avoid burnout by enforcing healthy boundaries. Here are some examples of how a reviewer is encouraged to act to take care of themselves:

* Authors should meet baseline expectations when submitting a pull request, such as writing tests.
* If your availability changes, you can step down from a pull request and have someone else assigned.
* If interactions with an author are not following code of conduct, close the PR and raise it up with your Code of Conduct committee or point of contact. It's not your job to coax people into behaving.

### Trust

Be trustworthy. During a review, your actions both build and help maintain the trust that the community has placed in this project. Below are examples of ways that we build trust:

* **Transparency** - If a pull request won't be merged, clearly say why and close it. If a pull request won't be reviewed for a while, let the author know so they can set expectations and understand why it's blocked.
* **Integrity** - Put the project's best interests ahead of personal relationships or company affiliations when deciding if a change should be merged.
* **Stability** - Only merge when then change won't negatively impact project stability. It can be tempting to merge a pull request that doesn't meet our quality standards, for example when the review has been delayed, or because we are trying to deliver new features quickly, but regressions can significantly hurt trust in our project.

## Process

The ADP review process ensures all contributions are checked for quality, clarity, and alignment with project standards. This applies to code, documentation, tutorials, UX, designs, and tooling contributions.

### 1. Submit a Pull Request (PR)

- Contributors should open a PR from a feature branch in their fork or in the repo.  
- PRs must include a **clear title** and **description** explaining:
  - What was changed or added  
  - Why the change is needed  
  - Any relevant references (issues, docs, examples)  

### 2. Assign Reviewers

- Only **maintainers** are authorized to review PRs.  
- The contributor may optionally **request a specific maintainer** if guidance is needed.  

### 3. Review Checklist

Reviewers should evaluate PRs based on:

- **Scope:** Changes are limited to the issue or task described  
- **Correctness:** Code works as intended, documentation is accurate  
- **Clarity:** Instructions, comments, and naming are clear  
- **Quality:** Code style, formatting, and testing meet project standards  
- **Inclusivity:** Feedback is respectful, constructive, and aligns with the ADP Code of Conduct  

> Tip: For non-code PRs (docs, tutorials, UX, designs), focus on clarity, formatting, and adherence to ADP style guidelines.

### 4. Feedback and Iteration

- Reviewers provide **specific, actionable comments**  
- Contributors update the PR with requested changes  
- Reviewers **re-check changes** to ensure feedback has been addressed  

### 5. Approval and Merging

- Once all feedback is addressed, maintainers **approve** the PR  
- Maintainers handle **merging**, ensuring the branch is up-to-date with `main`  
- For larger changes, maintainers may **merge with squash or rebase** to keep history clean  

### 6. Closing PRs

- PRs that are outdated, abandoned, or not aligned with project goals may be **closed by maintainers** with an explanation  
- Contributors are encouraged to **re-open** or submit a **new PR** if they want to continue work  


## Checklist

Below are a set of common questions that apply to all pull requests:

- [ ] Is this PR targeting the correct branch?
- [ ] Does the commit message provide an adequate description of the change?
- [ ] Does the affected code have corresponding tests?
- [ ] Are the changes documented, not just with inline documentation, but also with conceptual documentation such as an overview of a new feature, or task-based documentation like a tutorial? Consider if this change should be announced on your project blog.
- [ ] Does this introduce breaking changes that would require an announcement or bumping the major version?


## Reading List

Reviewers are encouraged to read the following articles for help with common reviewer tasks:

* [The Art of Closing: How to closing an unfinished or rejected pull request](https://blog.jessfraz.com/post/the-art-of-closing/)
* [Kindness and Code Reviews: Improving the Way We Give Feedback](https://product.voxmedia.com/2018/8/21/17549400/kindness-and-code-reviews-improving-the-way-we-give-feedback)
* [Code Review Guidelines for Humans: Examples of good and back feedback](https://phauer.com/2018/code-review-guidelines/#code-reviews-guidelines-for-the-reviewer)

## Acknowledgment
This Reviewing guide is adapted from the **CNCF Reviewing Guide** https://github.com/cncf/project-template/blob/main/REVIEWING.md
