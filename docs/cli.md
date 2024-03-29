# CLI

https://primer.style/cli/

## Syntax

Field | Convention
:-- | :--
Naming | snake_case
Indentation | 2 spaces

Text | Format
:-- | :--
Placeholder | `<value>`
Optional | `[flags]`, `[<domain> \| <ip_address>]`
Mutually exclusive | `{start \| stop}`
Repeatable | `<open_port>...`

## Prompts

Input | Format
:-- | :--
Yes/No (default in caps) | `[y/N]`
Short text | `(auto-fill)`
Long text | `[(key) action]`

## Colors

[`shell-colors.md`](https://github.com/rxtz/md/blob/main/docs/shell-colors.md)

Color | Meaning | Code
:-- | :-- | :--
Reset | - | `\e[0m`
Black | Mute | `\e[30m`
Red | Error | `\e[31m`
Green | Success | `\e[32m`
Yellow | Warning | `\e[33m`
Blue | Web | `\e[34m`
Magenta | Ready | `\e[35m`
Cyan | Code | `\e[36m`
White | - | `\e[37m`
Bold | Header | `\e[1;37m`

## State

```text
✓ Success
- Neutral
✗ Failure
+ Requested
! Alert
```

## Progress

```
⠷ ⠯ ⠟ ⠻ ⠽ ⠾
```

## Help

```cli
$ cli --help
<description>

USAGE
  cli <command> [subcommand | flags]

COMMANDS
  <command>: <command_description>

FLAGS
  --<flag>: <flag_description>

EXAMPLES
  $ cli ...

LEARN MORE
  Use `cli <command> --help`
  <manual_url>

FEEDBACK
  <feedback_url>
```
