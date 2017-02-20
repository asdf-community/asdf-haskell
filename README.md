# asdf-haskell
[![help maintain this lib](https://img.shields.io/badge/looking%20for%20maintainer-DM%20%40vborja-663399.svg)](https://twitter.com/vborja)


[Haskell](https://www.haskell.org) plugin for [asdf](https://github.com/asdf-vm/asdf) version manager


## Install

```shell
asdf plugin-add haskell https://github.com/vic/asdf-haskell.git
```

## Use

This plugin uses a local [Stack](https://haskellstack.org) installation
(inside asdf-haskell `stack/` directory) to manage GHC versions.

After installation, `stack`, `ghc`, `ghci`, and `runhaskell` will be available on your path.

```shell
# If you need to install a package that produces binaries
stack install cabal-install

# Be sure to execute reshim afterwards to get them in your path
asdf reshim haskell
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for instructions on how to install & manage versions of Haskell.

