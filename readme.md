# @umar28dec/my-test-package

A simple multi-language "Hello World" package that greets users in over 100 languages.

## Overview

The package, implemented in [`index.js`](index.js), exports a single function, `hello(name, lang)`, which returns a greeting in the specified language. If the language code isn't recognized, it defaults to English.

The greetings dictionary contains ISO 639-1 language codes as keys along with their respective greetings.

## Features

- **Multi-Language Support:** Over 100 languages available.
- **Simple API:** Just one function to get greetings.
- **Graceful Fallback:** Defaults to English if an unsupported language code is provided.

## Installation

Install the package via npm:

```sh
npm install @umar28dec/my-test-package
```
