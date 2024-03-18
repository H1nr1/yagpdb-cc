---
title: Blackjack Main Command
---

This command starts a game of blackjack.

For more information about the blackjack game, see [the overview](overview) page.

## Trigger

**Type:** `Regex`<br />
**Trigger:** `\A(?:\-|<@!?204255221017214977>)\s*(?:b(lack)?j)(?: +|\z)`

:::note Custom prefixes

By default, this regex uses the `-` prefix for commands. If you have a different prefix, change the `-` to your own prefix.
For example, if you wanted to use `!` as the prefix, you would use:

`\A(?:\!|<@!?204255221017214977>)\s*(?:b(lack)?j)(?: +|\z)`

:::

## Usage

- `-blackjack` - Starts a game of blackjack

:::note Aliases

Instead of using `-blackjack`, you can also use `-blackj` or `-bj`.

:::

## Code

```gotmpl file=../../../../src/fun/blackjack/main.go.tmpl

```

## Author

This custom command was written by [Henri](https://github.com/H1nr1).
