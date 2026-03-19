[![English](https://img.shields.io/badge/English-Click_to_View-blue)](./README.en.md)
[![中文](https://img.shields.io/badge/中文-当前-green)](./README.md)
[![Install](https://img.shields.io/badge/Install-Guide-orange)](#安装)
[![Structure](https://img.shields.io/badge/Structure-Package-purple)](#仓库结构)
[![Release](https://img.shields.io/github/v/release/harrymarin/structure-spoken-notes?style=flat-square)](https://github.com/harrymarin/structure-spoken-notes/releases)
[![License](https://img.shields.io/badge/License-MIT-lightgrey)](./LICENSE)

# Structure Spoken Notes

`structure-spoken-notes` 是一个把口语化、零散、聊天式表达整理成清晰结构化文本的 skill。它不是改写事实，而是在不改变原意的前提下，把表达变得更清楚、更好发、更适合正式使用。

## 快速导航

- [它能做什么](#它能做什么)
- [适用场景](#适用场景)
- [快速开始](#快速开始)
- [安装](#安装)
- [使用示例](#使用示例)
- [仓库结构](#仓库结构)

## 快速开始

1. 把整个目录复制到本地 skills 目录
2. 在对话里调用 `$structure-spoken-notes`
3. 贴上你的原话，说明要详细版、精简版、正式版、英文版或双语版

示例：

```text
Use $structure-spoken-notes to rewrite this messy spoken note into a clear business-formal Chinese version without changing the meaning.
```

## 它能做什么

- 把口语化表达整理成结构清晰的文字
- 把凌乱的说明重排成自然逻辑
- 输出详细版、精简版、正式商务版
- 输出中文版、英文版、中英双语版
- 在不改变原意的前提下提升可读性和可转发性

## 适用场景

- 你想到哪说到哪，想整理成正式文字
- 你要把一段聊天式表达发给客户、公司或合作方
- 你想保留原意，但不想让文本显得很乱
- 你需要同一段内容的多个版本

## 安装

把整个文件夹复制到本地 skills 目录，例如：

```bash
cp -R structure-spoken-notes ~/.agents/skills/
```

## 使用示例

```text
Use $structure-spoken-notes to turn this rough spoken wording into a concise English version while preserving the meaning.
```

## 仓库结构

```text
structure-spoken-notes/
├── SKILL.md
├── README.md
├── README.en.md
├── LICENSE
└── agents/
    └── openai.yaml
```

## License

MIT
