zpnas
=====

easy to build nas system

[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/zpnas.svg)](https://npmjs.org/package/zpnas)
[![Downloads/week](https://img.shields.io/npm/dw/zpnas.svg)](https://npmjs.org/package/zpnas)
[![License](https://img.shields.io/npm/l/zpnas.svg)](https://github.com/zpbc007/zpnas/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g zpnas
$ zpnas COMMAND
running command...
$ zpnas (-v|--version|version)
zpnas/1.0.0 darwin-x64 node-v11.5.0
$ zpnas --help [COMMAND]
USAGE
  $ zpnas COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`zpnas ddns`](#zpnas-ddns)
* [`zpnas help [COMMAND]`](#zpnas-help-command)
* [`zpnas source`](#zpnas-source)

## `zpnas ddns`

update ip on dnspod

```
USAGE
  $ zpnas ddns

OPTIONS
  -c, --config=config  [default: ./config.json] config file dir
```

_See code: [src/commands/ddns.ts](https://github.com/zpbc007/zpnas/blob/v1.0.0/src/commands/ddns.ts)_

## `zpnas help [COMMAND]`

display help for zpnas

```
USAGE
  $ zpnas help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v2.2.3/src/commands/help.ts)_

## `zpnas source`

replace aliyun source

```
USAGE
  $ zpnas source

OPTIONS
  -b, --backup   backup source.list
  -u, --upgrade  update and upgrade apt software
```

_See code: [src/commands/source.ts](https://github.com/zpbc007/zpnas/blob/v1.0.0/src/commands/source.ts)_
<!-- commandsstop -->
