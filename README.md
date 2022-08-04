# compstyle

[![License](https://img.shields.io/badge/license-MIT-007EC7)](/LICENSE)
[![built for](https://img.shields.io/badge/built%20for-%20%F0%9F%A6%93%20zshzoo-black)][zshzoo]

> A good set of Zsh completion zstyles

## compinit

Note: This plugin does not run compinit. For that, you'll want the zshzoo/compinit plugin.

## Installation

### Install with a Zsh plugin manager

To install using a Zsh plugin manager, add the following to your .zshrc

- [antidote]: `antidote bundle zshzoo/compstyle`
- [zcomet]: `zcomet load zshzoo/compstyle`
- [zgenom]: `zgenom load zshzoo/compstyle`
- [znap]: `znap source zshzoo/compstyle`

### Install manually, without a plugin manager

To install manually, first clone the repo:

```zsh
git clone https://github.com/zshzoo/compstyle ${ZDOTDIR:-~}/.zplugins/compstyle
```

Then, in your .zshrc, add the following line:

```zsh
source ${ZDOTDIR:-~}/.zplugins/compstyle/compstyle.zsh
```


[zshzoo]: https://github.com/zshzoo/zshzoo
[antidote]: https://github.com/mattmc3/antidote
[zcomet]: https://github.com/agkozak/zcomet
[zgenom]: https://github.com/jandamm/zgenom
[znap]: https://github.com/marlonrichert/zsh-snap
