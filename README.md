# Indigo Theme

Indigo is a lightweight, responsive, typography-first theme for Hugo, marked up with [microformats2](http://microformats.org) for extra [IndieWeb](https://indieweb.org) goodness, including [IndieAuth](https://indieauth.com).

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for setup and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

This theme is built and tested against the latest version of Hugo and currently requires a minimum version of 0.50. You can check what version you're running with

```
$ hugo version
```

Follow the [upgrade instructions on the Hugo website](https://gohugo.io/getting-started/installing/#upgrade-hugo) if necessary.

### Installing

Follow the [theme-installation instructions on the Hugo website](https://gohugo.io/themes/installing-and-using-themes/#install-a-single-theme); the URL you'll want to use is

```
https://github.com/AngeloStavrow/indigo.git
```

### Setup

There's a sample config.toml file in the root of the indigo theme directory (`config.toml.example`); copy it to the root of your Hugo site, and rename it to `config.toml` _after_ you've made a backup of your current config.toml file (if any).

Set up the parameters in the config file, especially those in the social and `params.indieWeb` section. Social identifiers that you leave out will not be added to the footer of the site.

You can configure the theme to show info about the author; by default, this information is shown; if you'd prefer to leave it out, set `ShowBio` to `false`.

### Customization

Indigo will look for custom CSS in `<YOUR_HUGO_SITE>/static/css/custom.css`. This will let you add/override styling to your heart's content, while making it easy to keep Indigo up-to-date. See it in action on [angelostavrow.com](https://angelostavrow.com).

## Deployment

You can add a line to your `config.toml` file to set this theme as the default:

```
theme = "indigo"
```

Or, if you use `config.yaml`:

```
theme: indigo
```

## Indigo IndieWeb Features

A thorough writeup of the theme has been graciously written by @infominer33.

* [Indigo IndieWeb Features](https://web-work.tools/indieweb/indigo-indieweb-features/)

## Contributing

Please read [CONTRIBUTING.md](https://github.com/AngeloStavrow/indigo/blob/master/CONTRIBUTING.md) for details on the code of conduct, and the process for submitting bug reports, feature requests, and having your changes merged into the project.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/AngeloStavrow/indigo/tags).

## Authors

* **Angelo Stavrow** - *Initial work* - [AngeloStavrow](https://github.com/AngeloStavrow) on GitHub

See also the list of [contributors](https://github.com/AngeloStavrow/indigo/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

The following open fonts are used in this theme:

* [Fira Sans](https://bboxtype.com/typefaces/FiraSans/#!layout=specimen) for heading text
* [Charter](https://practicaltypography.com/charter.html) for body text
* [Fira Code](https://github.com/tonsky/FiraCode) for monospaced text

Licenses are included in the theme’s `static/fonts` folder.

Most icons in the social footer are from [Font Awesome](https://fontawesome.com/). Some come directly from the service itself (e.g., Micro.blog and Glitch).
