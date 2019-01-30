# Loggy

[![Build Status](https://travis-ci.org/jocic/BASH.Loggy.svg?branch=master)](https://travis-ci.org/jocic/BASH.Loggy) [![Coverage Status](https://coveralls.io/repos/github/jocic/BASH.Loggy/badge.svg?branch=master)](https://coveralls.io/github/jocic/BASH.Loggy?branch=master) [![Codacy Badge](https://api.codacy.com/project/badge/Grade/3b9ab2b0a8ea495282b99e00d47cb189)](https://www.codacy.com/app/jocic/BASH.Loggy?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=jocic/BASH.Loggy&amp;utm_campaign=Badge_Grade)

**Note:** This is purely for academic purposes to prove that even BASH can be used for creating a keylogger.

**Project is still under development...slow ride...take it easy...**

## Alias

If you plan to use the script frequently and set it up manually, you should probably create an alias.

### Temporary Alias

```bash
alias loggy="/path/to/your/folder/loggy.sh"
```

### Permanent Alias

```bash
echo alias loggy="/path/to/your/folder/loggy.sh" >> ~/.bash_aliases
```

## Installation

Alternatively, you can add my personal APT repository to your machine and install **Loggy** like you would anything else.

Add the repository.

```bash
wget -nc https://www.djordjejocic.com/files/apt/Release.key
sudo apt-key add Release.key
sudo echo "deb http://apt.djordjejocic.com general main" >> "/etc/apt/sources.list"
sudo apt-get update
```

Install project.

```bash
sudo apt-get install loggy
```

## Contribution

Please review the following documents if you are planning to contribute to the project:

*   [Contributor Covenant Code of Conduct](code-of-conduct.md)
*   [Contribution Guidelines](contributing.md)
*   [Pull Request Template](pull-request-template.md)
*   [MIT License](license.md)

## Support

Please don't hesitate to contact me if you have any questions, ideas, or concerns.

My Twitter account is: [@jocic_91](https://www.twitter.com/jocic_91)

My support E-Mail address is: [support@djordjejocic.com](mailto:support@djordjejocic.com)

## Copyright & License

Copyright (C) 2018 Đorđe Jocić

Licensed under the MIT license.
