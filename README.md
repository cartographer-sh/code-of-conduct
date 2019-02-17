# How to Contribute

Looking for active and interested collaborators!

This project is super early stage, so there are lots of leadership opportunities.

## Code of Conduct

Please read the [Code of Conduct](https://github.com/cartographer-sh/contributing/blob/master/CODE-OF-CONDUCT.md) so that you can understand what actions will and will not be tolerated.

## Bugs

Projects use GitHub Issues for public bugs. Before filing a new issue, try to make sure your problem hasn't already been reported.

Each project should use a version of the [Issue Template](https://github.com/cartographer-sh/contributing/blob/master/ISSUE-TEMPLATE.md). Please follow this when submitting issues.

## Branch Organization

All projects should use [GitHub Flow](https://guides.github.com/introduction/flow/) with the Fork & Pull Model:

1. Fork to your own repo
2. Develop your feature on your fork in a feature branch
3. Submit the final PR to upstream (the source repo) from the feature branch in your fork

Sometimes in order to callaborate on a feature it might make sense to push a feature branch to upstream. When using this flow, PRs should be submitted to the feature branch from your fork until the feature is ready. Once all collaborators have signed off on the implementation, the final PR should be submitted to master from the upstream feature branch. Once the feature has been merged into master, the feature branch should be deleted.

One stable release branch should be maintained for each of the three lastest major versions.

## Semantic Versioning

All projects should follow semantic versioning. Patch versions should be reserved for bugfixes, minor versions for new features, and major versions for any breaking changes.

Patches should be back-ported to the three most recent major versions. Major versions prior to the three most recent should include deprecation warnings.

Every significant change should be documented in the changelog file.

## Pull Requests

Enusre all Pull Requests adhere to the guidelines set out in this document as well as any project-specific guidelines. This includes, but is not limited to passing tests and resonable code coverage.

## Contributor License Agreement (CLA)

In order to have a pull request approved, please submit a [CLA](https://github.com/cartographer-sh/contributing/blob/master/CLA.md). You only need to do this once and then you can contribute to any Cartographer project.

## License

All Cartographer open-source projects [including this one](https://github.com/cartographer-sh/contributing/blob/master/LICENSE) are licensed under MIT.
