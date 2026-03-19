[![English](https://img.shields.io/badge/English-Current-green)](./README.en.md)
[![中文](https://img.shields.io/badge/中文-点击查看-blue)](./README.md)
[![Install](https://img.shields.io/badge/Install-Guide-orange)](#install)
[![Structure](https://img.shields.io/badge/Structure-Package-purple)](#repository-structure)
[![Release](https://img.shields.io/github/v/release/harrymarin/structure-spoken-notes?style=flat-square)](https://github.com/harrymarin/structure-spoken-notes/releases)
[![License](https://img.shields.io/badge/License-MIT-lightgrey)](./LICENSE)

# Structure Spoken Notes

`structure-spoken-notes` is a skill for turning spoken, fragmented, or chat-style wording into clear structured writing. It does not change the facts. It keeps the original meaning while making the text clearer, easier to forward, and more suitable for formal use.

## Quick Navigation

- [What It Does](#what-it-does)
- [Good Fit For](#good-fit-for)
- [Quick Start](#quick-start)
- [Install](#install)
- [Usage Example](#usage-example)
- [Repository Structure](#repository-structure)

## Quick Start

1. Copy the folder into your local skills directory
2. Invoke `$structure-spoken-notes`
3. Paste your original wording and specify whether you want a detailed, concise, business-formal, English, Chinese, or bilingual version

Example:

```text
Use $structure-spoken-notes to rewrite this messy spoken note into a clear business-formal English version without changing the meaning.
```

## What It Does

- turns spoken wording into structured text
- reorganizes messy thoughts into a readable sequence
- supports detailed, concise, and business-formal versions
- supports Chinese, English, and bilingual output
- improves readability without changing meaning

## Good Fit For

- rough notes that need to become proper writing
- chat-style wording that needs to be sent to a client, company, or partner
- content that should stay faithful while becoming clearer
- one source text that needs multiple output styles

## Install

Copy the whole folder into your local skills directory, for example:

```bash
cp -R structure-spoken-notes ~/.agents/skills/
```

## Usage Example

```text
Use $structure-spoken-notes to turn this rough spoken wording into a concise Chinese version while preserving the meaning.
```

## Repository Structure

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
