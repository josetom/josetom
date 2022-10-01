# jose.zsh-theme

```sh
PROMPT=''
PROMPT+=' %{$fg_bold[magenta]%}%n%{$reset_color%}'
PROMPT+=' %(?:%{$fg_bold[green]%}➜ :%{$fg_bold[red]%}➜ )'
PROMPT+=' %{$fg[cyan]%}%c%{$reset_color%} $(git_prompt_info)'
PROMPT+='⌚ %{$fg_bold[green]%}%*%{$reset_color%} ➭ '

ZSH_THEME_GIT_PROMPT_PREFIX="%{$fg_bold[blue]%}git:(%{$fg[red]%}"
ZSH_THEME_GIT_PROMPT_SUFFIX="%{$reset_color%} "
ZSH_THEME_GIT_PROMPT_DIRTY="%{$fg[blue]%}) %{$fg[yellow]%}✗"
ZSH_THEME_GIT_PROMPT_CLEAN="%{$fg[blue]%})"
ZSH_THEME_GIT_PROMPT_UNTRACKED="%{$fg[green]%}?"
```

# TL;DR

Install https://github.com/ohmyzsh/ohmyzsh

```sh
touch ~/.oh-my-zsh/custom/themes/jose.zsh-theme
vi jose.zsh-theme
```

Add the above theme snippet

```
omz theme set jose
omz reload
```
