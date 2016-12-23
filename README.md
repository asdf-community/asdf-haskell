# asdf-haskell

[Haskell](https://www.haskell.org) plugin for [asdf](https://github.com/asdf-vm/asdf) version manager


## Install

```shell
asdf plugin-add haskell https://github.com/vic/asdf-haskell.git
```

## Use

This plugin uses [Stack](https://haskellstack.org) to install GHC versions. If not installed
on your system, this plugin will install it inside asdf-haskell `stack/` directory.

When installing a haskell package that produces executable binaries, be sure to run `asdf reshim` afterwards to get them in your path.


Check [asdf](https://github.com/asdf-vm/asdf) readme for instructions on how to install & manage versions of Haskell.

