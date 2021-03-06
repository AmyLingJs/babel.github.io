---
layout: docs
title: Stage 2 preset
description: All you need to use stage 2 (and greater) plugins
permalink: /docs/plugins/preset-stage-2/
package: babel-preset-stage-2
---

This preset includes the following plugins:

- <del>[transform-decorators](/docs/plugins/transform-decorators)</del> – *disabled pending proposal update* (can use the [legacy](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy) transform in the meantime)
- [transform-class-properties](/docs/plugins/transform-class-properties)

And all plugins from presets:

- [preset-stage-3](/docs/plugins/preset-stage-3)

## Installation

```sh
$ npm install --save-dev babel-preset-stage-2
```

## Usage

Add the following line to your `.babelrc` file:

```json
{
  "presets": ["stage-2"]
}
```
