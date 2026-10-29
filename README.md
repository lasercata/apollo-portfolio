# apollo-portfolio

Fork of the [apollo](https://github.com/not-matthias/apollo) theme, focusing on portfolio, and adding multilingual configuration.

Modern and minimalistic theme powered by [Zola](https://getzola.org). See a live preview of the original apollo theme [here](https://not-matthias.github.io/apollo).

<sub><sup>Named after the greek god of knowledge, wisdom and intellect</sup></sub>

<details open>
  <summary>Dark theme</summary>

![blog-dark](./screenshot-dark.png)

</details>

<details>
  <summary>Light theme</summary>

![blog-light](./screenshot.png)

</details>

## Features

- [x] Pagination
- [x] Themes (light, dark, auto)
- [x] Projects page
- [X] Analytics using [GoatCounter](https://www.goatcounter.com/) / [Umami](https://umami.is/)
- [x] Social Links
- [x] MathJax Rendering
- [ ] Taxonomies
- [x] Meta Tags For Individual Pages
- [x] Custom homepage
- [x] Comments
- [ ] Search
- [x] RSS feeds
- [x] Mermaid diagram support
- [x] Table of Contents
- [x] Configurable cards layout
- [X] Multiple languages

## Installation

1. Download the theme

```
git submodule add https://github.com/lasercata/apollo-portfolio themes/apollo-portfolio
```

2. Add the following to the top of your `config.toml`

```toml
theme = "apollo-portfolio"
default_language = "en"

# Add languages here, e.g for italian:
[languages.it.translations]

[extra]
theme = "auto"
socials = [
  # Configure socials here
]

[extra.en]
menu = [
  # Configure menu bar here
]

[extra.it]
menu = [
  # Configure menu bar here for the Italian language
]

# See this for more options: https://github.com/lasercata/apollo-portfolio/blob/main/config.toml
```

3. Copy the example content

```
cp -r themes/apollo/content/* content/
```

## References

This theme is a fork of [apollo](https://github.com/not-matthias/apollo/), that is itself based on [archie-zola](https://github.com/XXXMrG/archie-zola/).
