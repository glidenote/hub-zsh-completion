# hub-zsh-completion

`hub-zsh-completion` is zsh completion for [hub](https://github.com/defunkt/hub).   
I customize zsh completion of git.  
It complement hub command(`browse` , `compare`, `create` ,`fork` , `pull-request`)

## How To Use

### install [hub](https://github.com/defunkt/hub).

### Add alias setting to `.zshrc`

`hub` works best when it wraps `git`.

    alias git='hub'

### put `_git` file in the zsh function directory

put `_git` file to zsh functions directory (/usr/share/zsh/site-functions/ or /usr/local/share/zsh/site-functions/)

    git clone git://github.com/glidenote/hub-zsh-completion.git
    sudo cp hub-zsh-completion/_git /usr/share/zsh/site-functions/
    exec zsh

