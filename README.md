# webview

- [Goal](#goal)
- [Structure](#structure)
- [Naming Conventions](#naming)
- [CODEOWNERS](#codeowners)
- [Semantic Versioning](#versioning)
- [RFCs](#rfcs)
- [Licensing](#licensing)
- [Contributing](#contributing)
- [Code of Conduct](#conduct)
- [Social Contract](#contract)

## Our Goal
[goal]: goal

The webview organisation is dedicated to the problem that is using a Web Stack as a application GUI. We are the maintainers of full-stack solutions, core implementations, binding libraries, and other supplements to projects that take this approach. It's our objective to share knowledge and empower each other's pursuits.

## Structure
[structure]: structure

There are five main code components of the webview organization:
- core
- bindings
- supplements
- documentation
- testing

Core consists of [the main webview repository](https://github.com/webview/webview) which provides the backbone for all the language specific bindings, and eventually each language binding should depend on it for providing similar underlying behavior.

## Repository Naming Conventions
[naming]: naming

- `webview` - the core headers
- `docs` - the documentation for the core library (structure to be determined)
- `rfcs` - the RFC library
- `webview_testing` - a testing harness for all devices
- `webview_actions` - common actions for repositories
- `webview_%language%` - a binding to the core headers, where `%language%` is `nim`, `rust`, `python` etc.
- `webview_%supplement%` - a supplement to webview, where `%supplement%` is `tray`, `notifications` etc.

## CODEOWNERS
[codeowners]: codeowners
Every repository in this organization is required to have at minimum two code owners.

## Semantic Versioning
[versioning]: versioning
All repositories are required to strictly follow [Semantic Versioning 2.0.](https://semver.org/).

## RFCs
[rfcs]: rfcs

Additions or modifications to the core that are likely to have changes "trickle down" to bindings and consumers deserve special attention. 

## Licensing
[licensing]: licensing

All repositories are required to maintain license files and a notice in the readme, as well as placing it in appropriate packaging files such as but not limited to a `package.json` or `Cargo.toml`. Please follow the dual licensing model of MIT and Apache 2.0.

## Contributing
[contributing]: contributing

We consider all types of contributions to be important additions to this organization. Filing issues, maintaining bindings, reviewing pull-requests and participating in discussions are all activities that we expect to follow the rules set out in the following code of conduct.

## Code of Conduct
[conduct]: conduct

Please take a moment review our Code of Conduct. Your participation in this community requires that you follow these rules.

## Social Contract
[contract]: contract

In addition to the Code of Conduct, we also abide with a Social Contract as regards this project and our community. Please take a moment to review it.

# License
2020 (c) The Webview Contributors
This document is licensed under CC-BY-INTL 2.0.
