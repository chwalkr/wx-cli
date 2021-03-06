# wx-cli  [![image](https://img.shields.io/npm/v/wx-cli.svg)](https://www.npmjs.com/package/wx-cli)


## Installation

```
$ npm install wx-cli -g
```

## Usage

* help

```
$ wx --help

  Usage: wx [options] [command]

  Commands:

    init [type]  initialize, default: react component

  Options:

    -h, --help     output usage information
    -V, --version  output the version number
```

* init [[type]](#type)

```
$ wx init [type]
```

## Type

#### react *(default)*

> 初始化一个 `react` 基础组件。支持 `less`、`css-modules`

#### react-admin-toolkit

> 初始化一个后台系统页面的项目。支持 `redux`、`redux-saga`、`less`、`css-modules`

#### react-general-toolkit

> 初始化一个通用的项目。支持 `redux`、`redux-saga`、`less`、`css-modules`

#### react-spa-toolkit

> 初始化一个单页面应用的项目。支持 `react-router`、`redux`、`redux-saga`、`less`、`css-modules`

## TODO

- [ ] webpack 升级到 2.x(or 3.x)
