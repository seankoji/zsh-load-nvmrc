# zsh-load-nvmrc

`zsh-load-nvmrc` is a zsh plugin that automatically loads the node version specified in `.nvmrc`.

The code is completely taken from the [nvm's GitHub repository](https://github.com/nvm-sh/nvm#zsh).

## Installation

### As an [Oh My ZSH!](https://github.com/robbyrussell/oh-my-zsh) custom plugin
Clone `zsh-load-nvmrc` into your custom plugins repo.

```
git clone git@github.com:seankoji/zsh-load-nvmrc.git ~/.oh-my-zsh/custom/plugins/zsh-auto-nvm-use
```

Then load as a plugin in your `.zshrc`

```
plugins+=(zsh-load-nvmrc)
```
