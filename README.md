# Ormo-GnuPG.Config

A collection of configuration boilerplates implementing best practise for use with setting up and configuring GnuPG.

## Getting Started

Simply use PowerShell to download the raw configuration files required from the Git repository:

```PowerShell
Invoke-WebRequest -Uri 'https://raw.githubusercontent.com/spdx/license-list-data/master/text/MIT.txt' -UseBasicParsing -OutFile '.gpgconf'
```

### Prerequisites

The latest version of [GnuPG](https://www.gnupg.org/) must be installed. For Windows this can be downloaded from [Gpg4win](https://gpg4win.org/download.html) or installed with Chocolatey:

```PowerShell
choco install gpg4win
```

## Built With

* [VSCode](https://code.visualstudio.com/) - IDE
* [Gpg4win](https://www.gpg4win.org/) - OpenPGP implementation for Windows

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags).

## Authors

* **Ross Newton** - *Developer* - [Ormo](https://github.com/ross-at-ormo)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

* Contributors to Open Source software used in this project.