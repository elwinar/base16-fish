# base16-fish

This repository is meant to work with
[chriskempson/base16](https://github.com/chriskempson/base16). It provides a
simple template that can be used with the base16 color schemes to generate a
functional config file for
[fish-shell](https://github.com/fish-shell/fish-shell).

To use, you can copy one of the config files in colors/ or use curl:

```
curl https://raw.githubusercontent.com/elwinar/base16-fish/master/colors/base16-default-dark.fish >> ~/.config/fish/colors.fish
```

Then source the file in your fish configuration 

```
. (dirname (status -f))/colors.fish
```
