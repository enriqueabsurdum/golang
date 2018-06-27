# 2.2 Constantes
Las constantes se declaran como variables, pero se deben especificar con la palabra reservada `const`.  

Las constantes solo pueden ser de tipo cadena, lógico o númerico, y no se pueden declarar utilizando la sintaxis del operando `:=`. Una constante a la que no se le específica el tipo asumirá como su tipo el valor asignado según el contexto.
```go
const Pi = 3.14
const (
    StatusOK                   = 200
    StatusCreated              = 201
    StatusAccepted             = 202
    StatusNonAuthoritativeInfo = 203
    StatusNoContent            = 204
    StatusResetContent         = 205
    StatusPartialContent       = 206
)
```
Según específicado en el ejemplo anterior, la constante `Pi` asumirá un tipo de valor númerico de punto flotante.
```go
package main

import "fmt"

const (
    Pi    = 3.14
    Verdad = false
    Big   = 1 << 62
    Small = Big >> 61
)

func main() {
    const Saludo = "Hola mundo"
    fmt.Println(Saludo)
    fmt.Println(Pi)
    fmt.Println(Verdad)
    fmt.Println(Big)
}
```

---
<div align="right">

[**Volver a Capítulo 2: Lo Básico**](https://github.com/enriqueabsurdum/golang/blob/master/capitulos/02-capitulo/02-0-capitulo-lo-basico.md)
</div>   