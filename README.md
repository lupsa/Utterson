# Utterson

Utterson is a minimal and clean [Hugo](https://gohugo.io) theme based on mdo's [Poole](https://demo.getpoole.com) code source and inspired by [bearblog.dev](https://bearblog.dev).

### [Demo](https://mkozaq.com)

___

## Installation
To install Utterson as your default theme, first install this repository in the `themes/` directory:

```bash
cd themes/
git clone https://github.com/lupsa/utterson.git
```

Second, specify `utterson` as your default theme in the `config.toml` file. Just add the line

```toml
theme = "utterson"
```

at the top of the file.

For more information, read the official [setup guide](https://gohugo.io/getting-started/installing) of Hugo.

### Install using Hugo modules

```toml
[[module.imports]]
  path = "github.com/lupsa/Utterson"
```

Check [Hugo docs](https://gohugo.io/hugo-modules/) for more information about modules.


## Options

### Description
The "description" of your website near title.

> _This is used in the meta data of your generated html for SEO purpose._

**TOML**
```toml
theme = "utterson"

[params]
  description = "Your custom description"
```

**YAML**
```yaml
theme: "utterson"

params:
  description = "Your custom description"
```

### Staticman

You can optionally enable a comment system powered by [Staticman](https://staticman.net) for the posts.

**TOML**
```toml
[params.staticman]
    api = "https://<staticman-api-host>/v3/entry/github/<your_username>/<comments-repo>/master/comments"
```

## Google Analytics

Google Analytics can be enabled by assigning your tracking code to the `googleAnalytics` variable in the config file:

**TOML**
```toml
googleAnalytics = "Your tracking code"
```

**YAML**
```yaml
googleAnalytics: Your tracking code
```

## Author
**Mark Otto**
- <https://github.com/mdo>
- <https://twitter.com/mdo>

## Ported By
**Darius Lupșa**
- <https://github.com/lupsa>
- <https://twitter.com/dariuslupsa>

## License

Open sourced under the [MIT license](LICENSE.md).

<3
