# Open Source Cities Website

> A directory of companies, people, and projects that are Open Source.

Visit our [**Website**](https://opensourcecities.github.io/)

## Table of Contents

- [Build](#build)
- [License](#license)

## Build

This site is built with [Hugo](https://gohugo.io/) and uses an external theme from [https://github.com/opensourcecities/osc-theme](https://github.com/opensourcecities/osc-theme) as submodule.

- To run the site locally:

```bash
git clone --recurse-submodules https://github.com/opensourcecities/opensourcecities.github.io.git
cd opensourcecities.github.io
./hugow server
```

- To generate the site:

```bash
git clone --recurse-submodules https://github.com/opensourcecities/opensourcecities.github.io.git
cd opensourcecities.github.io
rm -rf public/
./hugow
```

## License

This list is licensed under a [CC-BY 4.0 Unported License](https://creativecommons.org/licenses/by/4.0/), © 2017 Richard Littauer. If this isn't great for you, get in touch.