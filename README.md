#### Homelab Dotfiles


We add the dotfiles on the "dotfiles" directory on our user's home and run:  

```bash
stow .
```

This will create symlinks at home for all our dotfiles.

We add a `.stow-local-ignore` file to ignore several files when using stow
https://www.gnu.org/software/stow/manual/stow.html#Types-And-Syntax-Of-Ignore-Lists

