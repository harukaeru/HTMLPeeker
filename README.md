# HTMLPeeker

## Requirements
- Mac OS X
- Chrome
- Python3.x (Maybe it can be installed with python2.x)

## Install

```sh
$ pip install htmlpeeker
```

## Usage

### On Command Line

```sh
$ python3 -c 'import sys; from peeker import peek; peek(sys.argv[1])' "<h1>xxx</h1>"
```

### As a Library

```python
>>> from peeker import peek
>>> peek("<h1>Hello :)</h1>")
Start Chrome
```

->

![chrome](https://raw.github.com/harukaeru/HTMLPeeker/master/chrome.png)

->

```python
^C>>>
```

->

![deleted](https://raw.github.com/harukaeru/HTMLPeeker/master/deleted.png)
