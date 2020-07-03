---
title: forall
---

# `forall`

{{< signature forall >}}

`forall` comprueba si todos los elementos de esta colección satisfacen el predicado `p`, devolviendo `false` si `p` no es satisfecho para al menos un elemento.

@include [figure.html source="../images/forall.svg" desc="Diagrama de la función forall"]

En colecciones vacías, no existe ningún elemento que no satisfaga `p`, por lo que esta función devuelve `true`.

@include [figure.html source="../images/forall.2.svg" desc="Diagrama de la función forall"]
