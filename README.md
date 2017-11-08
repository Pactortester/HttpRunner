# HttpRunner

[![license](https://img.shields.io/github/license/HttpRunner/HttpRunner.svg)](https://github.com/HttpRunner/HttpRunner/blob/master/LICENSE)
[![Build Status](https://travis-ci.org/debugtalk/HttpRunner.svg?branch=master)](https://travis-ci.org/HttpRunner/HttpRunner)
[![Coverage Status](https://coveralls.io/repos/github/debugtalk/HttpRunner/badge.svg?branch=master)](https://coveralls.io/github/debugtalk/HttpRunner?branch=master)
[![PyPI](https://img.shields.io/pypi/v/HttpRunner.svg)](https://pypi.python.org/pypi/HttpRunner)
[![PyPI](https://img.shields.io/pypi/pyversions/HttpRunner.svg)](https://pypi.python.org/pypi/HttpRunner)

New name for `ApiTestEngine`.

## Design Philosophy

Take full reuse of Python's existing powerful libraries: [`Requests`][requests], [`unittest`][unittest] and [`Locust`][Locust]. And achieve the goal of API automation test, production environment monitoring, and API performance test, with a concise and elegant manner.

## Key Features

- Inherit all powerful features of [`Requests`][requests], just have fun to handle HTTP in human way.
- Define testcases in YAML or JSON format in concise and elegant manner.
- Supports `function`/`variable`/`extract`/`validate` mechanisms to create full test scenarios.
- With `debugtalk.py` plugin, module functions can be auto-discovered in recursive upward directories.
- Testcases can be run in diverse ways, with single testset, multiple testsets, or entire project folder.
- Test report is concise and clear, with detailed log records. See [`PyUnitReport`][PyUnitReport].
- With reuse of [`Locust`][Locust], you can run performance test without extra work.
- CLI command supported, perfect combination with [Jenkins][Jenkins].

## Supported Python Versions

Python `2.7`, `3.4`, `3.5` and `3.6`.

`HttpRunner` has been tested on `macOS`, `Linux` and `Windows` platforms.


[requests]: http://docs.python-requests.org/en/master/
[unittest]: https://docs.python.org/3/library/unittest.html
[Locust]: http://locust.io/
[flask]: http://flask.pocoo.org/
[PyUnitReport]: https://github.com/debugtalk/PyUnitReport
[Jenkins]: https://jenkins.io/index.html
[quickstart]: docs/quickstart.md