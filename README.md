# alfred-aws-vault-workflow

[![version](https://img.shields.io/github/v/release/tsub/alfred-aws-vault-workflow?color=blue&sort=semver)](https://github.com/tsub/alfred-aws-vault-workflow/releases)

A Alfred workflow to open the AWS Management Console with [aws-vault].

This workflow is inspired by [aws\-vault loginでChromeのウィンドウをAWSアカウント毎に分離する \- Qiita](https://qiita.com/minamijoyo/items/f3cbb003a34954a32970) (written in Japanese).

for Google Chrome

![Features for Google Chrome](https://i.gyazo.com/33341687e0419d3863f913a00997744c.gif)

for Firefox

![Features for Firefox](https://i.gyazo.com/a68e0d4cd6f9a80b659cfc1694cd85dd.gif)

## Requirements

* [aws-vault] (**Only support `/usr/local/bin/aws-vault` path**)
* One of the supported browsers
    * Google Chrome
    * Firefox (**Require [Multi-Account Containers](https://addons.mozilla.org/firefox/addon/multi-account-containers/) extension and [Open external links in a container](https://addons.mozilla.org/firefox/addon/open-url-in-container/) extension**)

## Preparation

You need to set up aws-vault credentials.

```
$ aws-vault add [profile]
```

And for the first time, browser setup is required.

![Setup browser step 1](https://i.gyazo.com/114406d83dd25a3cfd9c9474019ce9e6.png)

![Setup browser step 2](https://i.gyazo.com/f82862478d266d258e5d52126dc3c2b0.png)

## Installation

Get a latest .alfredworkflow file from [GitHub releases](https://github.com/tsub/alfred-aws-vault-workflow/releases).

[aws-vault]: https://github.com/99designs/aws-vault
