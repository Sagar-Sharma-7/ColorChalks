<h1 align="center">
	<img  src="./src/img/Color2.png" alt="ColorChalks">
</h1>

> 🖌️Module for terminal string styling

[![PyPI version](https://badge.fury.io/py/ColorChalks.svg)](https://badge.fury.io/py/ColorChalks)
[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)
[![PyPI license](https://img.shields.io/pypi/l/ansicolortags.svg)](https://pypi.python.org/pypi/ansicolortags/)
[![Downloads](https://static.pepy.tech/personalized-badge/colorchalks?period=total&units=international_system&left_color=black&right_color=brightgreen&left_text=Downloads)](https://pepy.tech/project/colorchalks)
---

<br>

## Installation
```sh
pip install ColorChalks
```

## Usage       
```python 
from ColorChalks import ColorChalks

# Print "Hello World!" in yellow color.
print(ColorChalks.FCOLORS.Yellow + "Hello World!")
```
**Note:** Version 1.0.2 comes only with foreground colors (FCOLORS)

-----

## Colors 
- `Black`
- `Red`
- `Green`
- `Yellow`
- `Blue`
- `Magenta`
- `Cyan`
- `White`
- `BrightBlack`
- `BrightRed`
- `BrightGreen`
- `BrightYellow`
- `BrightBlue`
- `BrightMagenta`
- `BrightCyan`
- `BrightWhite`

**NOTE:** Use the following command to reset to default color. Prefer to use this command before jumping from Bright colors to normal colors.
```python
print(ColorChalks.FCOLORS.Reset) 
```