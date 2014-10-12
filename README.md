# Dotfiles (Chris Schuld)

My OS X dotfiles.

## How to install

The installation step requires the [XCode Command Line
Tools](https://developer.apple.com/downloads) and may overwrite existing
dotfiles in your HOME and `.vim` directories.


First, set your hostname:

```bash
$ scutil --set HostName HOSTNAME
```

Next, run the dotfiles binary from

```bash
$ bash -c "$(curl -fsSL raw.github.com/cbschuld/dotfiles/master/bin/dotfiles)"
```

