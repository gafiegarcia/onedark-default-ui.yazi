# One Dark Syntax with yazi default theme

Yazi flavor with default UI theme and One Dark Syntax-highlighting from [andresmichel/one-dark-theme](https://github.com/andresmichel/one-dark-theme/)

## 👀 Preview

<img src="preview.png" width="600" />

<img src="preview2.png" width="600" />

## 🎨 Installation

```sh
ya pkg add gafiegarcia/onedark-default-ui
```

## ⚙️ Usage

To set it as your dark flavor, change the content of your `theme.toml` to:

```toml
[flavor]
dark = "onedark-default-ui"
```

Make sure your `theme.toml` doesn't contain anything other than `[flavor]`, unless you want to override certain styles of this flavor.

See the [Yazi flavor documentation](https://yazi-rs.github.io/docs/flavors/overview) for more details.

## 📜 License

The flavor is MIT-licensed, and the included tmTheme is also MIT-licensed.

Check the [LICENSE](LICENSE) and [LICENSE-tmtheme](LICENSE-tmtheme) file for more details.
