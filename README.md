# GitHub Meta Project (.github)

This repository is used to manage community health files, which are relevant for all our projects.
Furthermore, we are providing our default integration configurations for bots and apps via this repository.

Community files are:

- Code of Conduct
- Contributing guidelines
- Security Policy
- etc.

It provides a default for said community files and can be overwritten by each project. See the [GitHub Documentation](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file) regarding community health files for further information.

## Why

Simple it is hard for us at OSPO to check all the repositories for their community health files, but we see them as really important.

Furthermore updating one of those files to a more recent version is painful, when you have to check all the projects.
Now we do have one point of truth for the default, if a project decides to deviate from this default, it is also the project's responsibility to take care of its community files.

## Contents

### Community Health Files

The following files will be used as a fallback for all the projects within the same organization.

- [Code of Conduct](CODE_OF_CONDUCT.md)
- [Contributing Guidelines](CONTRIBUTING.md)
- [Security Policy](SECURITY.md)
- [ISSUE_TEMPLATES](ISSUE_TEMPLATES/) for bug reports and freature requests
- `.github/*.yml` for bot configurations like [Probot](https://probot.github.io/docs/best-practices/#store-configuration-in-the-repository)

### Organization Profile

The `profile/README.md` is used for the basic front text of the Organization.

### Architectural Decision Records

We want to enable people to challenge our ideas, therefore it is important to know what has been evaluated and why.

We are using <https://adr.github.io/madr/> to keep them in an easily readable format.
For further reading check <https://github.com/joelparkerhenderson/architecture-decision-record#how-to-start-using-adrs>

The ADRs can be found within [docs/decisions within the OSPO Organization](https://github.com/dynatrace-innovationlab/.github/tree/main/docs/decisions)

## Automation/Tooling

We are currently using only `markdownlint` to verify our Markdown-files in this repository.
For easier local development we also provide a `makefile` with two targets:

- `markdownlint`: runs the linter
- `markdownlint-fix`: runs the auto fix option
