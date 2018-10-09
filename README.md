heymptestcli
============



[![oclif](https://img.shields.io/badge/cli-oclif-brightgreen.svg)](https://oclif.io)
[![Version](https://img.shields.io/npm/v/heymptestcli.svg)](https://npmjs.org/package/heymptestcli)
[![Downloads/week](https://img.shields.io/npm/dw/heymptestcli.svg)](https://npmjs.org/package/heymptestcli)
[![License](https://img.shields.io/npm/l/heymptestcli.svg)](https://github.com/heyMP/heymptestcli/blob/master/package.json)

<!-- toc -->
* [Usage](#usage)
* [Commands](#commands)
<!-- tocstop -->
# Usage
<!-- usage -->
```sh-session
$ npm install -g heymptestcli
$ heymptestcli COMMAND
running command...
$ heymptestcli (-v|--version|version)
heymptestcli/0.0.1 darwin-x64 node-v10.10.0
$ heymptestcli --help [COMMAND]
USAGE
  $ heymptestcli COMMAND
...
```
<!-- usagestop -->
# Commands
<!-- commands -->
* [`heymptestcli hello [FILE]`](#heymptestcli-hello-file)
* [`heymptestcli help [COMMAND]`](#heymptestcli-help-command)
* [`heymptestcli wutup [FILE]`](#heymptestcli-wutup-file)

## `heymptestcli hello [FILE]`

describe the command here

```
USAGE
  $ heymptestcli hello [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print

EXAMPLE
  $ heymptestcli hello
  hello world from ./src/hello.ts!
```

_See code: [src/commands/hello.ts](https://github.com/heyMP/heymptestcli/blob/v0.0.1/src/commands/hello.ts)_

## `heymptestcli help [COMMAND]`

display help for heymptestcli

```
USAGE
  $ heymptestcli help [COMMAND]

ARGUMENTS
  COMMAND  command to show help for

OPTIONS
  --all  see all commands in CLI
```

_See code: [@oclif/plugin-help](https://github.com/oclif/plugin-help/blob/v2.1.2/src/commands/help.ts)_

## `heymptestcli wutup [FILE]`

describe the command here

```
USAGE
  $ heymptestcli wutup [FILE]

OPTIONS
  -f, --force
  -h, --help       show CLI help
  -n, --name=name  name to print
```

_See code: [src/commands/wutup.ts](https://github.com/heyMP/heymptestcli/blob/v0.0.1/src/commands/wutup.ts)_
<!-- commandsstop -->
