# Test with [Huxley](https://github.com/facebook/huxley)

## Installation

Huxley works on python `2.7`.

```sh
$ pyenv install 2.7
$ pyenv global 2.7
```

Install `huxley`.

```sh
$ pip install huxley
```

## Test

Before executing test, you have to run [Selenium Server](http://docs.seleniumhq.org/download/) and localhost.

```sh
$ java -jar selenium-server-standalone-2.x.x.jar
$ python -m SimpleHTTPServer
```

Run huxley.

```sh
$ huxley --record
```
