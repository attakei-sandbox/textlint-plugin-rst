# textlint-plugin-rst

reStructuredText(`*.rst`) support for [textlint](https://github.com/textlint/textlint "textlint").

## About Shiguredo's open source software

We will not respond to PRs or issues that have not been discussed on Discord. Also, Discord is only available in Japanese.

Please read https://github.com/shiguredo/oss/blob/master/README.en.md before use.

## 時雨堂のオープンソースソフトウェアについて

利用前に https://github.com/shiguredo/oss をお読みください。

## textlint-plugin-rst について

このリポジトリは `@jimo1001 <https://github.com/johejo/>`_ の https://github.com/jimo1001/textlint-plugin-rst フォークです。

時雨堂がメンテナンスをしています。

## Installation

To install textlint-plugin-rst, the follow python package must be installed.

 - [docutils-ast-writer](https://github.com/shiguredo/docutils-ast-writer "docutils-ast-writer")

And run follow command.

    npm install textlint-plugin-rst

## Usage

- Add `--plugin rst` to command options
- or add following codes to `.textlintrc`
```
{
    "plugins": [
        "rst"
    ]
}
```

## ライセンス

```
The MIT License (MIT)

Copyright (c) 2023-2023 Shiguredo Inc.
Copyright (c) 2016 jimo1001

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```