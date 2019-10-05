# alfred-aws-vault-workflow

A Alfred workflow to open the AWS Management Console with [aws-vault].

This workflow is inspired by [aws\-vault loginでChromeのウィンドウをAWSアカウント毎に分離する \- Qiita](https://qiita.com/minamijoyo/items/f3cbb003a34954a32970) (written in Japanese).

## Features

TODO: Upload GIF image

## Requirements

* [aws-vault] (**Only support `/usr/local/bin/aws-vault` path**)
* Google Chrome

## Preparation

You need to set up aws-vault credentials.

```
$ aws-vault add [profile]
```

## Installation

Get a latest .alfredworkflow file from [GitHub releases](https://github.com/tsub/alfred-aws-vault-workflow/releases).

[aws-vault]: https://github.com/99designs/aws-vault
