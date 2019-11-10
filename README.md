# eslint-config

[Shareable config](https://eslint.org/docs/developer-guide/shareable-configs)
for [ESLint](https://eslint.org),
which extends [@form8ion/eslint-config](https://github.com/form8ion/eslint-config)

<!-- status badges -->
[![Build Status][ci-badge]][ci-link]

## Usage

<!-- consumer badges -->
[![npm][npm-badge]][npm-link]
[![MIT license][license-badge]][license-link]

### Using as your own

1. Click the "[Use this template](https://github.com/form8ion/eslint-config-template/generate)"
   button above to [create your own repository from this template](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/creating-a-repository-from-a-template)
1. Change the [package name](https://github.com/form8ion/eslint-config-template/blob/0ae75107cc4c63957ace2bfbf98d73b35fc8564d/package.json#L2)
   to use your own scope and not include the `-template` suffix
1. Change the [installation instructions](#installation) to reference the
   correct name of your package
1. Update all links and badges in the `README.md` to match your new repository
   and package names
1. Remove [this section](#using-as-your-own) from your new `README.md`

### Installation

```sh
$ npm install @form8ion/eslint-config --save-dev
```

## Contributing

<!-- contribution badges -->
[![Conventional Commits][commit-convention-badge]][commit-convention-link]
[![Commitizen friendly][commitizen-badge]][commitizen-link]
[![semantic-release][semantic-release-badge]][semantic-release-link]
[![PRs Welcome][PRs-badge]][PRs-link]
[![Greenkeeper badge][greenkeeper-badge]][greenkeeper-link]

### Dependencies

```sh
$ nvm install
$ npm install
```

### Verification

```sh
$ npm test
```

[npm-link]: https://www.npmjs.com/package/@form8ion/eslint-config-template
[npm-badge]: https://img.shields.io/npm/v/@form8ion/eslint-config-template.svg
[license-link]: LICENSE
[license-badge]: https://img.shields.io/github/license/form8ion/eslint-config-template.svg
[ci-link]: https://travis-ci.com/form8ion/eslint-config-template
[ci-badge]: https://img.shields.io/travis/com/form8ion/eslint-config-template/master.svg
[commit-convention-link]: https://conventionalcommits.org
[commit-convention-badge]: https://img.shields.io/badge/Conventional%20Commits-1.0.0-yellow.svg
[commitizen-link]: http://commitizen.github.io/cz-cli/
[commitizen-badge]: https://img.shields.io/badge/commitizen-friendly-brightgreen.svg
[semantic-release-link]: https://github.com/semantic-release/semantic-release
[semantic-release-badge]: https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg
[PRs-link]: http://makeapullrequest.com
[PRs-badge]: https://img.shields.io/badge/PRs-welcome-brightgreen.svg
[greenkeeper-badge]: https://badges.greenkeeper.io/form8ion/eslint-config-template.svg
[greenkeeper-link]: https://greenkeeper.io/
