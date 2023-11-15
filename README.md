# zsh-insulter
Randomly insults the user when typing wrong command.
This is heavily based on [hkbakke's](https://github.com/hkbakke/bash-insulter) work.

Change insults as needed :)

![zshInsults](https://github.com/NoobGajen/zsh-insulter/blob/master/zshInsultsgnu.png)

# Installation

    git clone https://github.com/NoobGajen/zsh-insulter.git ~/.zsh-insulter
    grab the zsh.command-not-found and paste it where-ever you want. 
    (e.g. ~/.zsh-insulter to keep it for you. and not bothering other users)

Then source the file automatically for new logins by adding the following to `/etc/bash.bashrc` for bash and `~/.zshrc` for zsh:
```
if [ -f ~/.zsh-insulter/src/zsh.command-not-found ]; then
    . ~/.zsh-insulter/src/zsh.command-not-found
fi
```
Start a new zsh shell and type some invalid commands for the effects to be visible.
