# alias

What's an alias?

```console
tldr alias
```
```
  Create aliases - words that are replaced by a command string.
  Aliases expire with the current shell session unless defined in the shell's configuration file, e.g. `~/.bashrc`.
  More information: <https://tldp.org/LDP/abs/html/aliases.html>.

  List all aliases:

      alias

  Create a generic alias:

      alias word="command"

  View the command associated to a given alias:

      alias word

  Remove an aliased command:

      unalias word

  Turn `rm` into an interactive command:

      alias rm="rm --interactive"

  Create `la` as a shortcut for `ls --all`:

      alias la="ls --all"

```

If using [Oh My Zsh](https://ohmyz.sh/), put aliases in the directory set by `$ZSH_CUSTOM`.
