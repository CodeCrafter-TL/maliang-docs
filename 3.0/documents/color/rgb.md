# tkintertools.color.rgb

Support for RGB

## 🔵`_str_to_rgba`


<code style='color: royalblue;'>function</code> <code style='color: orange;'>protected</code>

```python
def _str_to_rgba(
    color: str,
    *,
    reference: str,
) -> tuple[int, int, int]: ...
```
Experimental: Convert color strings(RGBA) to RGB codes

## 🔵`_str_to_rgba`


<code style='color: royalblue;'>function</code> <code style='color: orange;'>protected</code>

```python
def _str_to_rgba(
    color: str,
    *,
    reference: str,
) -> tuple[int, int, int]: ...
```
Experimental: Convert color strings(RGBA) to RGB codes

## 🔵`blend`


<code style='color: royalblue;'>function</code> <code style='color: green;'>public</code>

```python
def blend(
    colors: list[tuple[int, int, int]],
    *,
    weights: list[tuple] | None = None,
) -> tuple[int, int, int]: ...
```
Mix colors by weight

* `colors`: color list
* `weights`: weight list


## 🔵`contrast`


<code style='color: royalblue;'>function</code> <code style='color: green;'>public</code>

```python
def contrast(
    rgb: tuple[int, int, int],
    *,
    channels: tuple[bool, bool, bool] = (True, True, True),
) -> tuple[int, int, int]: ...
```
Get a contrasting color of a color

* `rgb`: a tuple, RGB codes
* `channels`: three color channels


## 🔵`convert`


<code style='color: royalblue;'>function</code> <code style='color: green;'>public</code>

```python
def convert(
    first: tuple[int, int, int],
    second: tuple[int, int, int],
    rate: float,
    *,
    channels: tuple[bool, bool, bool] = (True, True, True),
) -> tuple[int, int, int]: ...
```
Convert one color to another proportionally

* `first`: first color
* `second`: second color
* `rate`: conversion rate
* `channels`: three color channels


## 🔵`gradient`


<code style='color: royalblue;'>function</code> <code style='color: green;'>public</code>

```python
def gradient(
    first: tuple[int, int, int],
    second: tuple[int, int, int],
    count: int,
    rate: float = 1,
    *,
    channels: tuple[bool, bool, bool] = (True, True, True),
    contoller: typing.Callable[[float], float] = flat,
) -> list[tuple[int, int, int]]: ...
```
Get a list of color gradients from one color to another proportionally

* `first`: first color
* `second`: second color
* `count`: number of gradients
* `rate`: conversion rate
* `channels`: three color channels
* `controller`: control function


## 🔵`rgb_to_str`


<code style='color: royalblue;'>function</code> <code style='color: green;'>public</code>

```python
def rgb_to_str(
    color: tuple[int, int, int],
) -> str: ...
```
Convert RGB codes to color strings

## 🔵`rgb_to_str`


<code style='color: royalblue;'>function</code> <code style='color: green;'>public</code>

```python
def rgb_to_str(
    color: tuple[int, int, int],
) -> str: ...
```
Convert RGB codes to color strings

## 🔵`str_to_rgb`


<code style='color: royalblue;'>function</code> <code style='color: green;'>public</code>

```python
def str_to_rgb(
    color: str,
) -> tuple[int, int, int]: ...
```
Convert color strings to RGB codes

## 🔵`str_to_rgb`


<code style='color: royalblue;'>function</code> <code style='color: green;'>public</code>

```python
def str_to_rgb(
    color: str,
) -> tuple[int, int, int]: ...
```
Convert color strings to RGB codes

## 🟣`MAX`


<code style='color: skyblue;'>constant</code> <code style='color: green;'>public</code>

```python linenums="0"
MAX: tuple = (
    255, 255, 255,
)
```


## 🟣`RGB`


<code style='color: skyblue;'>constant</code> <code style='color: green;'>public</code>

```python linenums="0"
RGB: GenericAlias = tuple[int, int, int]
```


