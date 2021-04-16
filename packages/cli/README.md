@note-tools/cli
===============



[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/@note-tools/cli.svg)](https://npmjs.org/package/@note-tools/cli)
[![Downloads/week](https://img.shields.io/npm/dw/@note-tools/cli.svg)](https://npmjs.org/package/@note-tools/cli)
[![License](https://img.shields.io/npm/l/@note-tools/cli.svg)](https://github.com/rbrcsk/note-tools/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g @note-tools/cli
$ note-tools COMMAND
running command...
$ note-tools (-v|--version|version)
@note-tools/cli/0.0.3 darwin-x64 node-v12.19.1
$ note-tools --help [COMMAND]
USAGE
  $ note-tools COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`note-tools hello [FILE]`](#note-tools-hello-file)
* [`note-tools help [COMMAND]`](#note-tools-help-command)
* [`note-tools roam-export`](#note-tools-roam-export)

## `note-tools hello [FILE]`

describe the command here

```
USAGE
  $ note-tools hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ note-tools hello
  hello world from ./src/hello.ts!
```

_See code: [src/commands/hello.ts](https://github.com/rbrcsk/note-tools/blob/v0.0.3/src/commands/hello.ts)_

## `note-tools help [COMMAND]`

display help for note-tools

```
USAGE
  $ note-tools help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v3.2.2/src/commands/help.ts)_

## `note-tools roam-export`

describe the command here

```
USAGE
  $ note-tools roam-export

OPTIONS
  -h, --help                   show CLI help
  --debug
  --email=email                (required) The email address of your Roam Research account.
  --extract                    Enable to extract the downloaded zip files
  --formats=JSON|EDN|Markdown  [default: EDN]
  --graph=graph                (required) The name of the graph you want to export.
  --output=output              The folder to store downloaded items in. Defaults to ./graph-name
  --password=password          (required) The password of your Roam Research account. Only sent to Roam.

EXAMPLE
  $ note-tools hello
  hello world from ./src/hello.ts!
```

_See code: [src/commands/roam-export.ts](https://github.com/rbrcsk/note-tools/blob/v0.0.3/src/commands/roam-export.ts)_
<!-- commandsstop -->
