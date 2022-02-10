# python-color-getter
Color getter (including method to get random color or complementary color) made out of Python

## Setup
```pip3 install git+https://github.com/yjg30737/python-color-getter.git --upgrade```

## Method Overview
* ```get_random_color() -> tuple```
* ```get_color_from_stylesheet(code: str) -> None```
* ```get_complementary_color(r: int, g: int, b: int) -> tuple```

## Example
Code Sample
```python
print(PythonColorGetter.get_random_color())
print(PythonColorGetter.get_complementary_color(255, 0, 0))
```

Result
```
(211, 195, 123)
(0, 255, 255)
```
