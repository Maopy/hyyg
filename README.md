# hyyg
A generator for Haoyayi

[![NPM version][npm-image]][npm-url]
[![js-standard-style][standard-image]][standard-url]

# Features

- 执行命令时，判断是否在项目根目录

# Install

```sh
  $ [sudo] npm install hyyg -g
```

# Usage

## 生成 model
```sh
  $ hyyg patientAddInfo -m
```

## 生成 controller
```sh
  $ hyyg patientManagement -c
```

# TODO

- 添加Controller时，通过参数添加Model
- 添加日期，添加人
- 添加前判断是否已存在

[npm-image]: https://img.shields.io/npm/v/hyyg.svg?style=flat-square
[npm-url]: https://npmjs.org/package/hyyg
[standard-image]: https://img.shields.io/badge/code%20style-standard-brightgreen.svg
[standard-url]: http://standardjs.com
