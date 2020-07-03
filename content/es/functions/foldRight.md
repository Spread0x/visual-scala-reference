---
title: foldRight
---

# `foldRight`

{{< signature foldRight >}}

`foldRight` aplica, de derecha a izquierda, el operador binario `op` a cada elemento y al resultado del anterior `op`.
La primera vez que `op` es aplicado es alimentado con el valor inicial `z`.

@include [figure.html source="../images/foldRight.svg" desc="Diagrama de la función foldRight"]

En colecciones vacías, esta función ni siquiera aplica `op` y el valor inicial `z` es devuelto directamente.

@include [figure.html source="../images/foldRight.2.svg" desc="Diagrama de la función foldRight"]

