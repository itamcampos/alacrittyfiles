# My Alacritty configuration files

This repository replicates the [official Alacritty project theme repository on GitHub](https://github.com/alacritty/alacritty-theme), so make sure to also update the "themes" repository, explained later...

This repository currently applies the [Catppuccin Mocha theme](https://github.com/alacritty/alacritty-theme/blob/master/themes/catppuccin_mcha.toml) and also uses a small opacity with 95% visibility.

## Important

Make sure you have Alacritty installed and working

## How to use

Close Alacritty and then clone the repository

```bash
  git clone https://github.com/itamcampos/alacrittyfiles.git ~/.config/alacritty
```

Change to the cloned directory:

```bash
  cd ~/.config/alacritty
```

Initialize the submodule of this repository:

```bash
  git submodule init
```
Update the submodule to pull the updated themes:

```bash
  git submodule update
```

Reopen Alacritty and check if the changes have been applied.
