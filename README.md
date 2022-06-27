# Prython

Inspired by [Ruby's pry gem](https://raw.githubusercontent.com/pry/pry) and [this snippet](https://gist.github.com/obfusk/208597ccc64bf9b436ed).

Prython is a debugging aid, made to be lightweight and very easy to use. If you want to take a look at Python's official debugger, [this is it](https://docs.python.org/3/library/pdb.html).

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

## Usage

All of this package's methods are listed below (I told you it was lightweight and easy to use).
Remember to `import prython` at the top of your file.

### `pry()`

```python
import prython

a = "Are you prying?"
def example_function():
    b = "With prython?"
    prython.pry()
    c = "Yep!"
```

If you run this file, say, from the command line, a REPL interpreter will pop up at the context of the line calling `prython.pry()`, which means you will have access to variables `a` and `b` but not `c`, as the line wasn't ran when prython was called.

### TODO:
- [] [Add stack trace printer](https://stackoverflow.com/questions/1156023/print-current-call-stack-from-a-method-in-code)
- [] Drop Python 2 support
- [] Tests


