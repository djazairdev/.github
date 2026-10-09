# djazairdev/.github

The default community files for every repository in the [djazairdev](https://github.com/djazairdev) organisation, and the organisation's profile page.

GitHub uses a file from here only when a repository doesn't have its own:

| File | What it's for |
|---|---|
| [`CODE_OF_CONDUCT.md`](CODE_OF_CONDUCT.md) | How we treat each other, and how to report a problem: conduct@djazair.dev |
| [`SECURITY.md`](SECURITY.md) | How to report a vulnerability privately: security@djazair.dev |
| [`SUPPORT.md`](SUPPORT.md) | Where to ask a question |
| [`.github/ISSUE_TEMPLATE/`](.github/ISSUE_TEMPLATE/) | The issue forms: a bug, an idea |
| [`.github/pull_request_template.md`](.github/pull_request_template.md) | What a pull request description asks for |
| [`profile/README.md`](profile/README.md) | The organisation's page on GitHub |

A repository that adds its own file of a kind overrides the default. For issue forms, it is all or nothing: a repository with any form of its own in `.github/ISSUE_TEMPLATE/` gets none of these, so copy the ones you still want.

Defaults don't cover everything. Each repository still needs its own licence, README and CONTRIBUTING (the [Hub](https://djazair.dev/en/hub/) reads them from the repository itself). The [project template](https://github.com/djazairdev/project-template) has those files, and a prompt that sets them up with a coding agent.

## Changing a default

A change here reaches every repository at once, so open a pull request and say why. The issue forms only use GitHub's built-in labels (`bug`, `enhancement`), because a label a form sets must exist in every repository that shows it.

## Licence

[MIT](LICENSE). The code of conduct is adapted from the [Contributor Covenant](https://www.contributor-covenant.org/version/2/1/code_of_conduct/), version 2.1, under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
