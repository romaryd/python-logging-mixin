# Logging Mixin

[![Build Status](https://travis-ci.org/romaryd/python-logging-mixin.svg?branch=master)](https://travis-ci.org/romaryd/python-logging-mixin)
[![Coverage Status](https://coveralls.io/repos/github/romaryd/python-logging-mixin/badge.svg?branch=master)](https://coveralls.io/github/romaryd/python-logging-mixin?branch=master)
[![Maintainability](https://api.codeclimate.com/v1/badges/b03f759c2a1d62011a6d/maintainability)](https://codeclimate.com/github/romaryd/python-logging-mixin/maintainability)
[![Code Health](https://landscape.io/github/romaryd/python-logging-mixin/master/landscape.svg?style=flat)](https://landscape.io/github/romaryd/python-logging-mixin/master)

## Installation

```
pip install python-logging-mixin
```

## Usage

```python
class Example(object, LoggingMixin):
  def __init__(self):
    pass

  def do_something(self):
    self.logger.info('do_something')
```
