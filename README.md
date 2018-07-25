# Crisp

> Pretty, minimal and fast ZSH prompt

## Overview

Forked from the popular zsh prompt [sindresorhus/pure] as it's easily the best
looking, minimal prompt out there. As pointed in the [pure/readme.md] it makes an
excellent starting point for a custom, personal prompt and I had a few desired
tweaks.

### Features

- Shows full current path, unless in a `git` repo where only the repo name is shown.
- Shows `git` branch and whether it's dirty (with a `✘`).
- Indicates when you have unpushed/unpulled `git` commits with up/down arrows. *(Check is done asynchronously!)*
- Prompt character turns red if the last command didn't exit with `0`.
- Command execution time will be displayed if it exceeds the set threshold.
- Username and host only displayed when in an SSH session.
- Shows the current path in the title and the current folder & command when a process is running.
- Makes an excellent starting point for your own custom prompt.

## Install
### [zplug](https://github.com/zplug/zplug)

Update your `.zshrc` file with the following line:

```sh
zplug sindresorhus/pure, use:pure.zsh, from:github, as:theme
```

[sindresorhus/pure]: https://github.com/sindresorhus/pure
[pure/readme.md]: https://github.com/sindresorhus/pure/blob/master/readme.md
