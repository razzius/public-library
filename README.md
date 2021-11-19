# Public Library

A library of functions across languages.

## Data Structures

### Array

### `intersperse`

Intersperses an element among each pair of elements in an array.

```
> intersperse(0, (sequence(3)))
[1, 0, 2, 0, 3]
```

#### Implementations

- Haskell: [`intersperse`](https://www.haskell.org/hugs/pages/libraries/base/Data-List.html#v%3Aintersperse) [(source)](https://hackage.haskell.org/package/base-4.16.0.0/docs/src/Data.OldList.html#intersperse)

### `sequence(n)`

Create an array of numbers from `1` to `n`.

```
> sequence(3)
[1, 2, 3]
```

#### Implementations

- Python: [`range`](https://docs.python.org/3/library/stdtypes.html#range) [(source)](https://github.com/python/cpython/blob/main/Objects/rangeobject.c#L718)
  - Implemented as a class, and starts at 0. To start at 1, use range(1, n)
