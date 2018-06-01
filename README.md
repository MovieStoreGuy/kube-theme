# Kube Theme - Making life easier for a K8s admin
[![asciicast](https://asciinema.org/a/himKx9BgbjArVvbxtAj2vJg2e.png)](https://asciinema.org/a/himKx9BgbjArVvbxtAj2vJg2e)
*Always know what kubernetes context you're in*
# Usage

Once you have cloned this repo down onto your local machine, we can them prepare them for
your terminal.
## Install for ohmyzsh (zsh)
Once checked out and inside this directory, we can run:
```sh
ln -sf $(pwd)/kube.zsh-theme ${ZSH}/themes 
```
Once the theme is there, we can then set it to be our theme inside or `~/.zshrc`.

### Themes avalaible for ohmyzsh
- `kube`

## Install for bash-it

Once checked out and inside this directory, we can run:
```sh
ln -sf $(pwd)/kube.theme.bash ${BASH_IT}/themes/kube/kube.theme.bash
```

Once the theme is there, simple update the `BASH_IT_THEME` inside `~/.bashrc`

### Themes avalaible for bash-it
- `kube`
