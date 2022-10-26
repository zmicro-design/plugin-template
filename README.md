# TEMPLATE - Template Manager Plugin for [ZMicro](https://github.com/zcorky/zmicro)

[![Release](https://img.shields.io/github/tag/zmicro-design/plugin-template.svg?label=Release)](https://github.com/zmicro-design/plugin-template/tags)
[![Build Status](https://github.com/zmicro-design/plugin-template/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/zmicro-design/plugin-template/actions/workflows/test.yml)
[![GitHub issues](https://img.shields.io/github/issues/zmicro-design/plugin-template.svg)](https://github.com/zmicro-design/plugin-template/issues)

## Installation

To install the package, run:

```bash
zmicro plugin install template
```

### If you donot install [ZMicro](https://github.com/zcorky/zmicro):

```bash
# CURL
curl -o- https://raw.githubusercontent.com/zmicro-design/plugin-template/master/install | bash

# WGET
wget -qO- https://raw.githubusercontent.com/zmicro-design/plugin-template/master/install | bash
```

## Usage

```markdown
Template Manager (v0.0.0)

Template Manager is a tool for creating zmicro plugin/package/service ...

Usage:
  zmicro template <action> [args...]

Action:
  create              - Create a instance from template
  ls                  - List all avaliable templates
  help                - Show help

Example:
  zmicro template create
```

## License

ZMicro Design is released under the [MIT License](./LICENSE).
