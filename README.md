# versioned-with-actions

A mini-project to set up commit-driven releases via GitHub actions.

Releases are managed using the [semantic-release](https://semantic-release.gitbook.io/) tool.

A Twitter thread tracking progress can be found at: https://twitter.com/theotherelliott/status/1370846650411978757

## Creating a Release

The default [Angular commit format](https://github.com/angular/angular/blob/master/CONTRIBUTING.md#-commit-message-format) is used along with default release rules, so you can create
releases as described in the [How Does It Work](https://semantic-release.gitbook.io/semantic-release/#how-does-it-work) page in the semantic-release docs.

Commit analysis is also configured to allow released to be prevented by setting the scope to `no-release`. Such as `fix(no-release): small fix, hold off on releasing`.