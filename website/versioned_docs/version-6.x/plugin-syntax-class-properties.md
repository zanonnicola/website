---
# Don't edit this file directly, it was copied using scripts/download-readmes.js: 
id: version-6.x-babel-plugin-syntax-class-properties
title: babel-plugin-syntax-class-properties
sidebar_label: syntax-class-properties
original_id: babel-plugin-syntax-class-properties
---

## Installation

```sh
npm install --save-dev babel-plugin-syntax-class-properties
```

## Usage

### Via `.babelrc` (Recommended)

**.babelrc**

```json
{
  "plugins": ["syntax-class-properties"]
}
```

### Via CLI

```sh
babel --plugins syntax-class-properties script.js
```

### Via Node API

```javascript
require("babel-core").transform("code", {
  plugins: ["syntax-class-properties"]
});
```

