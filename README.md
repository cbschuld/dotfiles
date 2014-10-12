# Dotfiles (Chris Schuld)

My OS X dotfiles.

![Screenshot of bash prompt](http://i.imgur.com/R1ARoLC.png)

## How to install

First, install Homebrew for OS X (http://brew.sh) This will force the installation of the [XCode Command Line Tools](https://developer.apple.com/downloads) and may overwrite existing dotfiles in your HOME and `.vim` directories.

```bash
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```
Second, set your hostname:

```bash
scutil --set HostName HOSTNAME
```

Next, run the dotfiles binary directly from here via curl

```bash
bash -c "$(curl -fsSL raw.github.com/cbschuld/dotfiles/master/bin/dotfiles)"
```

## How to update

You should run the update when:

* You make a change to `~/.dotfiles/git/gitconfig` (the only file that is copied rather than symlinked).
* You want to pull changes from the remote repository.

Run the dotfiles command:

```bash
$ dotfiles
```


## Ahh Fork it... please

Dotfiles are extremly personal and driven entirely by opinions; if you do not like something in these dotfiles please feel free to fork this repo and bake in your own preferences.  This is EXACTLY while I built this repo.

## Acknowledgements and Thanks
Special thanks to the following awesome people who provided inspiration and source (much of this is mirrored against their original work with my opinion glazed on top):

+ [@necolas](https://github.com/necolas/dotfiles)
+ [@mathiasbynens](https://mths.be/dotfiles)
+ [@holman](http://zachholman.com/2010/08/dotfiles-are-meant-to-be-forked/)
+ [@ryanb](https://github.com/ryanb/dotfiles)
