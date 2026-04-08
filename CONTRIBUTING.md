# ADP (AI Docs Project) — Contributing Guide

* [Ways to Contribute](#ways-to-contribute)
* [Good First Contributions](#good-first-contributions)
* [Find an issue](#find-an-issue)
* [Asking for Help](#asking-for-help)
* [Pull Request Process](#pull-request-process)
* [Development Environment](#development-environment)
* [Sign Your Commits](#sign-your-commits)
* [Pull Request Checklist](#pull-request-checklist)
* [Notes](#notes)


Welcome! We’re excited that you want to contribute to ADP 💖

Whether it’s improving documentation, UX, designs, tooling, automation, tutorials, or contributing code for our agents or tools, your input helps make ADP better and more usable for everyone.

If anything doesn't make sense, or doesn't work when you run it, please open issue under that repo and let us know!

## Ways to Contribute

We welcome many different types of contributions including:

* New features
* Builds, CI/CD
* Bug fixes
* Documentation
* Issue Triage
* Web design
* Communications / Social Media / Blog Posts
* Release management

## Good First Contributions

If you’re new to ADP, these are great ways to start:

- **Fix typos or grammar** in documentation  
- **Improve formatting or clarity** in guides or tutorials  
- **Add examples** to help users understand features  
- **Suggest small UX improvements** like labeling, button placement, or accessibility fixes  
- **Test automation scripts** and report bugs  
- **Refactor or clean code** in small, isolated sections  

> Each of these is a manageable task for first-time contributors and helps you get familiar with our workflow.


## Find an Issue

We have good first issues for new contributors and help wanted issues suitable
for any contributor. [good first issue](TODO) has extra information to
help you make your first contribution. [help wanted](TODO) are issues
suitable for someone who isn't a core maintainer and is good to move onto after
your first pull request.

Sometimes there won’t be any issues with these labels. That’s ok! There is
likely still something for you to work on. If you want to contribute but you
don’t know where to start or can't find a suitable issue, you can open a new issue explaining what you want to work on.

Once you see an issue that you'd like to work on, please post a comment saying
that you want to work on it. Something like "I want to work on this" is fine.

## Asking for Help
If you get stuck or have questions:

- Comment directly on the GitHub issue you’re working on  
- Reach out to the maintainers via **contactadp@zohomail.com**
- Ask on our Github discussion forum in the appropriate channel 

We encourage asking for help early rather than waiting — it helps everyone.

## Pull Request Process

1. Fork the repository (if needed) and make your changes in a branch.  
2. Make sure your changes are clear and focused on one issue or topic.  
3. Submit a pull request describing what you changed and why.  
4. Maintain a collaborative mindset — reviewers may suggest improvements or ask questions.  
5. Update your PR if needed and respond to feedback constructively.  



## Development Environment

For code contributions (agents, tools, scripts):

- Clone the repository and create a new branch for your work  
- Install dependencies listed in the project’s `README` or setup scripts  
- Test your changes locally before submitting a PR  

> Exact setup details will be provided in the repo for each project or tool.

### Creating a New Repository Using the ADP Project Template

If your contribution involves creating a **new repository**, follow these steps:

1. Go to the **project template repository** in the organization: *The AI Docs Project*.  
2. Click the **“Use this template”** button at the top of the repository.  
3. Fill in the **Create a new repository from template** form:
- **Owner:** Select *The-AI-Docs-Project* from the dropdown.  
- **Repository name:** Enter the name for your new project repository.  
- **Visibility:** Choose Private or Public depending on your project needs.  
4. Click **Create repository from template**.  
5. Clone your new repository locally:
```bash
git clone git@github.com:The-AI-Docs-Project/<new-repo>.git
cd <new-repo>
```


## Sign Your Commits

To acknowledge your contributions and agree that you have the right to submit them, follow the steps below:

### Code Contributions
Licensing is important to open source projects. It provides some assurances that
the software will continue to be available based under the terms that the
author(s) desired. We require that contributors sign off on commits submitted to
our project's repositories. The [Developer Certificate of Origin
(DCO)](https://probot.github.io/apps/dco/) is a way to certify that you wrote and
have the right to contribute the code you are submitting to the project.

You sign-off by adding the following to your commit messages. Your sign-off must
match the git user and email associated with the commit.

    This is my commit message

    Signed-off-by: Your Name <your.name@example.com>

Git has a `-s` command line option to do this automatically:

    git commit -s -m 'This is my commit message'

If you forgot to do this and have not yet pushed your changes to the remote
repository, you can amend your commit with the sign-off by running 

    git commit --amend -s 

### For Documentation, Tutorials, UX, or Designs
No sign-off is required for non-code contributions. You can submit pull requests or updates to documentation, tutorials, UX improvements, or design assets **without adding a DCO**.  

> Note: Even for non-code contributions, make sure your work respects copyright and that you have the right to submit it.



## Pull Request Checklist

Before submitting a pull request, make sure:

- Your contribution works as intended  
- Documentation is updated  
- Code is formatted consistently  
- Tests (if any) pass successfully  
- The PR description clearly explains your changes  



## Notes

- Everyone is welcome, regardless of experience level  
- Contributions of any size are appreciated 
- Respectful and constructive communication is expected at all times  
- For questions or reporting issues, contact **contactadp@zohomail.com**

## Acknowledgements
This Contributing guide is adapted from the **CNCF Contibuting Guide** https://github.com/cncf/project-template/blob/main/CONTRIBUTING.md
