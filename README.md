checkmee
========

A simple todo cli app

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/checkmee.svg)](https://npmjs.org/package/checkmee)
[![Downloads/week](https://img.shields.io/npm/dw/checkmee.svg)](https://npmjs.org/package/checkmee)
[![License](https://img.shields.io/npm/l/checkmee.svg)](https://github.com/shkhaider2015/checkmee/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g checkmee
$ checkmee COMMAND
running command...
$ checkmee (-v|--version|version)
checkmee/0.0.0 win32-x64 node-v14.17.1
$ checkmee --help [COMMAND]
USAGE
  $ checkmee COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`checkmee add [FILE]`](#checkmee-add-file)
* [`checkmee hello [FILE]`](#checkmee-hello-file)
* [`checkmee help [COMMAND]`](#checkmee-help-command)
* [`checkmee list [FILE]`](#checkmee-list-file)
* [`checkmee remove [FILE]`](#checkmee-remove-file)

## `checkmee add [FILE]`

describe the command here

```
USAGE
  $ checkmee add [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print
```

_See code: [src/commands/add.ts](https://github.com/shkhaider2015/checkmee/blob/v0.0.0/src/commands/add.ts)_

## `checkmee hello [FILE]`

describe the command here

```
USAGE
  $ checkmee hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ checkmee hello
  hello world from ./src/hello.ts!
```

_See code: [src/commands/hello.ts](https://github.com/shkhaider2015/checkmee/blob/v0.0.0/src/commands/hello.ts)_

## `checkmee help [COMMAND]`

display help for checkmee

```
USAGE
  $ checkmee help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v3.2.3/src/commands/help.ts)_

## `checkmee list [FILE]`

describe the command here

```
USAGE
  $ checkmee list [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print
```

_See code: [src/commands/list.ts](https://github.com/shkhaider2015/checkmee/blob/v0.0.0/src/commands/list.ts)_

## `checkmee remove [FILE]`

describe the command here

```
USAGE
  $ checkmee remove [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print
```

_See code: [src/commands/remove.ts](https://github.com/shkhaider2015/checkmee/blob/v0.0.0/src/commands/remove.ts)_
<!-- commandsstop -->
