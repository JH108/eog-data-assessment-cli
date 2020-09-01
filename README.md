# EOG Data Assessment

CLI for the EOG Data Assessment

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/eog-data-assessment-cli.svg)](https://npmjs.org/package/eog-data-assessment-cli)
[![Downloads/week](https://img.shields.io/npm/dw/eog-data-assessment-cli.svg)](https://npmjs.org/package/eog-data-assessment-cli)
[![License](https://img.shields.io/npm/l/eog-data-assessment-cli.svg)](https://github.com/jh108/eog-data-assessment-cli/blob/master/package.json)

<!-- toc -->

- [EOG Data Assessment](#eog-data-assessment-assessment)
- [Usage](#usage)
- [Commands](#commands)
<!-- tocstop -->

# Usage

<!-- usage -->

```sh-session
$ npm install -g eog-data-assessment-cli
$ eog-data-assessment-cli COMMAND
running command...
$ eog-data-assessment-cli (-v|--version|version)
eog-data-assessment-cli/2.0.1 darwin-x64 node-v10.12.0
$ eog-data-assessment-cli --help [COMMAND]
USAGE
  $ eog-data-assessment-cli COMMAND
...
```

<!-- usagestop -->

# Commands

<!-- commands -->

- [`eog-data-assessment-cli create`](#eog-data-assessment-cli-create)
- [`eog-data-assessment-cli help [COMMAND]`](#eog-data-assessment-cli-help-command)
- [`eog-data-assessment-cli preview`](#eog-data-assessment-cli-preview)

## `eog-data-assessment-cli create`

EOG Data Assessment

```
USAGE
  $ eog-data-assessment-cli create

OPTIONS
  -n, --name=name  Your Name

DESCRIPTION
  ...
  This is a way to initially create your assessment. It wil ask you your name and create you a
  local repository to start you off.
```

_See code: [src/commands/create.js](https://github.com/jh108/eog-data-assessment-cli/blob/master/src/commands/create.js)_

## `eog-data-assessment-cli help [COMMAND]`

display help for eog-data-assessment-cli

```
USAGE
  $ eog-data-assessment-cli help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/master/src/commands/help.ts)_

## `eog-data-assessment-cli preview`

Preview

```
USAGE
  $ eog-data-assessment-cli preview

OPTIONS
  -r, --repo=repo  GitHub Repo URL

DESCRIPTION
  ...
  A way to preview your assessment. Will clone, install and run.
```

_See code: [src/commands/preview.js](https://github.com/jh108/eog-data-assessment-cli/blob/master/src/commands/preview.js)_

<!-- commandsstop -->

## Special Thanks

A special thanks to [jwo](https://github.com/jwo) for allowing me to use his work as the base for this.
