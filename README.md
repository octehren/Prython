# Prython

Inspired by [Ruby's pry gem](https://raw.githubusercontent.com/pry/pry) and [this snippet](https://gist.github.com/obfusk/208597ccc64bf9b436ed).

Prython is a debugging aid, made to be lightweight (only native modules are imported in Python3.x), very easy to use and completely interoperable amongst both Python 2 & 3 (this package is tested in Python 2.7 & 3.x). If you want to take a look at Python's official debugger, [this is it](https://docs.python.org/3/library/pdb.html).

## Installation

### Python 3
Install from PyPi with:

```bash
pip install prython
```
or, in case you have 2 versions in your system and hasn't mapped Python 3 as the main one:

```bash
pip3 install prython
```

### Python 2
Install the wheel package with:
```bash
pip install prython.whl
```

## Usage

All of this package's methods are listed below (I told you it was lightweight and easy to use).
Remember to `import prython` at the top of your file.

### `pry()`

