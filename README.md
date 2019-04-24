* [![Master Build Status](https://travis-ci.org/d0c-s4vage/pfp.svg?branch=master)](https://travis-ci.org/d0c-s4vage/pfp) - master
* [![Develop Build Status](https://travis-ci.org/d0c-s4vage/pfp.svg?branch=develop)](https://travis-ci.org/d0c-s4vage/pfp) - develop
* [![Documentation Status](https://readthedocs.org/projects/pfp/badge/?version=latest)](https://readthedocs.org/projects/pfp/?badge=latest)

# Why StegoVeritas Branch?
PFP requirements are jacked. See the py010parser for info: https://github.com/bannsec/py010parser/tree/stegoveritas. Mainly need to modify this so that it installs my version of py010parser with the updated requirements.txt.

# pfp

`pfp` is a python-based interpreter for 010 template scripts.

See the main documentation on [Read the Docs](http://pfp.readthedocs.org/en/latest/)

## Installation

Install pfp with

	pip install --upgrade pfp

## Tl;DR

You don't feel like going to read the docs? This should get you
started parsing something using 010 templates:

```python
import pfp

dom = pfp.parse(
	data_file="~/Desktop/image.png",
	template_file="~/Desktop/PNGTemplate.bt"
)
```
