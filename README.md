[![semantic-release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg)](https://github.com/semantic-release/semantic-release)

# Browserslist config for funda projects

This package stores the default configuration for supported browsers for funda projects.

**This projects uses [semantic-release](https://semantic-release.gitbook.io/semantic-release/).** Be meaningful of this when writing commits.

The current selection is based on **> 0.30% in the Netherlands excluding iOS Safari 9.3 and IE 11**. That results at the time of this selection (15/03/2021) in:

* and_chr 89
* and_ff 86
* and_uc 12.12
* chrome 88
* chrome 87
* edge 88
* firefox 85
* ios_saf 14.0-14.5
* ios_saf 13.4-13.7
* ios_saf 13.3
* ios_saf 12.2-12.4
* ios_saf 10.3
* safari 14
* safari 13.1
* samsung 13.0


## Adding to a new project

At the root of your project add a .browserslistrc:

```
extends @funda/browserslist-config
```


If you are updating an existing project don't forget to update your package `db`

```
npx browserslist@latest --update-db
```

