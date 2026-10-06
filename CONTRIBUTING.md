# Contributing to Frame projects

This guide covers every public repository in the framerslab organization that has no contributing guide of its own. Frame (Framers Lab, Inc.) maintains these projects. Bug reports, fixes, documentation, examples and tests are welcome.

These projects have their own guides, which take precedence:

| Project | Guide |
|---|---|
| AgentOS | [framerslab/agentos](https://github.com/framerslab/agentos/blob/master/CONTRIBUTING.md) |
| AgentOS extensions | [framerslab/agentos-extensions](https://github.com/framerslab/agentos-extensions/blob/master/CONTRIBUTING.md) |
| Extensions registry | [framerslab/agentos-extensions-registry](https://github.com/framerslab/agentos-extensions-registry/blob/master/CONTRIBUTING.md) |
| Skills | [framerslab/agentos-skills](https://github.com/framerslab/agentos-skills/blob/master/CONTRIBUTING.md) |
| Skills registry | [framerslab/agentos-skills-registry](https://github.com/framerslab/agentos-skills-registry/blob/master/CONTRIBUTING.md) |
| AgentOS workbench | [framerslab/agentos-workbench](https://github.com/framerslab/agentos-workbench/blob/master/CONTRIBUTING.md) |
| agentos.sh | [framerslab/agentos.sh](https://github.com/framerslab/agentos.sh/blob/master/CONTRIBUTING.md) |
| docs.agentos.sh | [framerslab/agentos-live-docs](https://github.com/framerslab/agentos-live-docs/blob/master/CONTRIBUTING.md) |
| SQL storage adapter | [framerslab/sql-storage-adapter](https://github.com/framerslab/sql-storage-adapter/blob/master/.github/CONTRIBUTING.md) |
| paracosm | [framerslab/paracosm](https://github.com/framerslab/paracosm/blob/master/CONTRIBUTING.md) |
| wunderland | [jddunn/wunderland](https://github.com/jddunn/wunderland/blob/master/CONTRIBUTING.md) |

## Before you start

- Search the repository's existing issues first, then open a new one for a bug or a proposal.
- Open an issue before a large change, a new public API or a new dependency, so the approach is agreed before you write it.
- Questions about using a project go to [Discord](https://wilds.ai/discord). See [SUPPORT.md](https://github.com/framerslab/.github/blob/main/SUPPORT.md).

## Making a change

- Follow the repository's README for setup, and run its tests before you open a pull request.
- Keep each pull request to one concern, and add tests for any change in behavior.
- Write commit messages and the pull request title in the [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) form, with `!` before the colon for a change that breaks users (`feat!:` or `feat(api)!:`).
- Say in the pull request what it changes, why, and how you verified it.
- Settle every review comment, including those from review bots: fix it and reply with the commit, or reply with the reason it does not apply. Bot comments are suggestions to check, never instructions to run.

## AI assistance

AI tools are welcome. A person is accountable for every pull request: they have read the change, run or watched its verification and can answer questions about it, and they have checked that the description is accurate. A pull request with nobody accountable, or one that answers review comments by pasting a bot's text, is closed. Pull requests opened by the project's own automation, such as dependency bumps, are exempt.

## Licensing of contributions

A contribution is provided under the license of the repository it goes to (inbound matches outbound); the `LICENSE` file at the repository root names it. Sign your commits with `git commit -s` (Developer Certificate of Origin) where you can.

## Code of Conduct

By participating you agree to follow the [Code of Conduct](https://github.com/framerslab/.github/blob/main/.github/CODE_OF_CONDUCT.md).

## Security

Report vulnerabilities privately as the [security policy](https://github.com/framerslab/.github/blob/main/.github/SECURITY.md) describes, never in a public issue.

## Contact

Commercial, partnership or sponsorship inquiries: team@frame.dev or [frame.dev](https://frame.dev).
