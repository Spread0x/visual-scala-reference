---
title: reduceLeftOption
---

# `reduceLeftOption`

{{< signature reduceLeftOption >}}

`reduceLeftOption` applies the binary operator `op` to each element, going from left to right, and the previous `op` result.
The first time `op` is applied it's fed with the two first elements.
The final result is wrapped with `Some`.

@include [figure.html source="images/reduceLeftOption.svg" desc="Diagram of the reduceLeftOption function"]

On empty collections this function returns `None`.

@include [figure.html source="images/reduceLeftOption.2.svg" desc="Diagram of the reduceLeftOption function"]
