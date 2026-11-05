# Capo for Neos (`neos-capo`)

Reorders the `<head>` of your Neos pages which helps improve FCP and web performance.

> Created by [3m5.de - The Neos Agency](https://www.3m5.de/systeme/neos)
> | Based upon: 
[rviscomi/capo.js](https://github.com/rviscomi/capo.js) | [rviscomi/capo-wp](https://github.com/rviscomi/capo-wp)

---

## Installation

---

[![Latest Version](https://img.shields.io/packagist/v/3m5/neos-capo.svg)](https://packagist.org/packages/3m5/neos-capo)


Install with composer
```bash
composer require 3m5/neos-capo
```

## Usage

---

Each `<head>` will now automatically be optimised before it is sent out.

Capo will also output warnings to the logs, if it detects any mistakes in the page `<head>`, i.e. a duplicate `<title>` tag. This behaviour can be turned off in your `Settings.yaml`.

Default Configuration:
```yaml
Capo:
  options:
    debug: false
    debug_comment: false
    display_warnings: true
    display_weights: false
```