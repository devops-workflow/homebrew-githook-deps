# homebrew-devops

[![License][license-img]][license-url]
[![Build][build-img]][build-url]

## Overview

Homebrew is the easiest  and most flexible way to install  the UNIX tools Apple
didn't include with macOS.

[brew.sh](https://brew.sh/)

## Description

Tools dependencies for pre-commit git hooks formulae for the Homebrew
package manager including the following
tools.

This should provide Homebrew formulae for anything that
[pre-commit-hooks]()
or [pre-commit-terraform]() needs and is not found elsewhere

Find a complete & detailed list in [FORMULAE][formulae].

* flint
* git-sweep
* gitlint
* markdownlint (or mdl)
* puppet-lint
* rubocop
* travis
* yaml-lint
* yamllint

## Usage

```bash
# Add tap
brew tap rockyluke/devops

# Install i2cssh
brew install i2cssh

# Install millipede
brew install millipede

# Install puppet-lint
brew install puppet-lint

# Install pylint
brew install pylint

# etc.
```

## Development

Feel free to contribute on GitHub.

## Miscellaneous

```
    ╚⊙ ⊙╝
  ╚═(███)═╝
 ╚═(███)═╝
╚═(███)═╝
 ╚═(███)═╝
  ╚═(███)═╝
   ╚═(███)═╝
```

[license-img]: https://img.shields.io/badge/license-ISC-blue.svg
[license-url]: LICENSE
[build-img]: https://travis-ci.org/rockyluke/homebrew-devops.svg?branch=master
[build-url]: https://travis-ci.org/rockyluke/homebrew-devops
[formulae]: https://github.com/rockyluke/homebrew-devops/blob/master/FORMULAE.md
