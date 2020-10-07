# Color-Py

Color handling library written in Python.

## Installation
**Windows:** `pip install color-py`

**Linux/macOS:** `pip3 install color-py`

You can also view this project on [PyPi](https://pypi.org/project/Color-Py/)

## Usage
```py
from color-py.Color import Color

colors = [
    new Color(0x38, 0x5d, 0xc6)
]

Color.mix(colors).toARGB()
```
