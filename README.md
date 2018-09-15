# zend-router

[![Build Status](https://secure.travis-ci.org/zendframework/zend-router.svg?branch=master)](https://secure.travis-ci.org/zendframework/zend-router)
[![Coverage Status](https://coveralls.io/repos/github/zendframework/zend-router/badge.svg?branch=master)](https://coveralls.io/github/zendframework/zend-router?branch=master)

zend-router provides flexible HTTP routing.

Routing currently works against the [zend-http](https://github.com/zendframework/zend-http)
request and responses, and provides capabilities around:

- Literal path matches
- Path segment matches (at path boundaries, and optionally validated using regex)
- Regular expression path matches
- HTTP request scheme
- HTTP request method
- Hostname

Additionally, it supports combinations of different route types in tree
structures, allowing for fast, b-tree lookups.

## Installation

Run the following to install this library:

```bash
$ composer require zendframework/zend-router
```

## Documentation

Browse the documentation online at https://docs.zendframework.com/zend-router/

## Support

* [Issues](https://github.com/zendframework/zend-router/issues/)
* [Chat](https://zendframework-slack.herokuapp.com/)
* [Forum](https://discourse.zendframework.com/)
