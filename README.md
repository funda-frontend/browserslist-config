[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/)

# Browserslist config for funda projects

This package stores the default configuration for supported browsers for funda projects.

The current selection is based on [**> 0.30% in the Netherlands excluding iOS Safari 8**](https://browserl.ist/?q=%3E+0.30%25+in+NL%2C+not+ios_saf+8). That results at the time of this selection (1/05/2019) in:

* and_chr 73
* and_uc 11.8
* chrome 73
* chrome 72
* chrome 71
* edge 18
* edge 17
* firefox 66
* firefox 65
* ie 11
* ios_saf 12.0-12.1
* ios_saf 11.3-11.4
* ios_saf 11.0-11.2
* ios_saf 10.3
* ios_saf 9.3
* opera 58
* safari 12
* safari 11.1
* samsung 8.2
* samsung 9.2

# This projects uses semantic-release

Commiting to this repo without using the commandline is not tested.
Whenever you want to make a commit you should just run `git commit` after you staged your changes.
There are a bunch of checks to make sure you are commiting with a proper message.

## Local configuration

At the root of your project add a .browserslistrc file
with the content ```extends @funda/browserslist-config```

