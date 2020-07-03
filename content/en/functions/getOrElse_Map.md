---
title: getOrElse (Map)
normalized_name: getOrElse_Map
---

# `getOrElse`

For the `Option`'s `getOrElse` function go [here](./getOrElse_Option).

{{< signature getOrElse_Map >}}

`getOrElse` returns the value associated to the key `k` in this `Map`.

@include [figure.html source="images/getOrElse_Map.svg" desc="Diagram of the getOrElse function"]

If this `Map` doesn't contain the key `k` then this function returns the result of the computation `v`.

@include [figure.html source="images/getOrElse_Map.2.svg" desc="Diagram of the getOrElse function"]

