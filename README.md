# base16-i3status-rust

This repository provides [base16](https://github.com/chriskempson/base16) templates and colorschemes for [i3status-rust](https://github.com/greshake/i3status-rust).

The themes are based in the original ones, [semi-native](https://github.com/greshake/i3status-rust/blob/master/files/themes/semi-native.toml)
and [modern](https://github.com/greshake/i3status-rust/blob/master/files/themes/modern.toml) were used as inspiration.

## Usage

First create themes directory if it doesn't exist:

```bash
mkdir -p ~/.config/i3status-rust/themes
```

Then copy the desired theme to the directory that was created:

```bash
cp themes-powerline/base16-default-dark.toml ~/.config/i3status-rust/themes
```

or

```bash
cp themes/base16-default-dark-powerline.toml ~/.config/i3status-rust/themes
```
>Assuming you are at the root of the repository.

After that, set in your `i3status-rust/config.toml` the theme that was copied:

```toml
[theme]
theme = "base16-default-dark"
```

or

```toml
[theme]
theme = "base16-default-dark-powerline"
```

Reload your i3bar or sway-bar to apply the theme.

## License

[MIT License](./LICENSE)
