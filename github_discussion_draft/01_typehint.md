# Typehint

## Basic

```python
def HintedFun(num: int, op: Optional /, *args: list[123], **kwargs: dict) -> str:
    return "Hi"
```
### Union
### Callable

## Generic & TypeVar

### Type aliases & NewType

Concatenate

```python
from collections.abc import Callable
from threading import Lock
from typing import Concatenate, ParamSpec, TypeVar
```

## TypedDict

```python
from typing import TypedDict
class MyHintedType(TypedDict):
    x: int
    y: int
    label: str
```

### Match-Case
Explicit runtime type checking

