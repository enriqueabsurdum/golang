# 2.4 Sobre `package` e `import`
Todo programa en Go contiene paquetes (`package`). Los programas comienzan su ejecución en el paquete `main`.
```go
package main

func main() {
    print("¡Hola, Mundo!\n")
}
```
Ejemplos de como importar un paquete en Go de uno en uno:
```go
import "fmt"
import "math/rand"
```
O bien, de manera agrupada:
```go
import (
    "fmt"
    "math/rand"
)
```
En ambos ejemplos se utilizan los paquetes con rutas de importación `fmt` y `math/rand`.

---
<div align="right">

[**Volver a Capítulo 2: Lo Básico**](https://github.com/enriqueabsurdum/golang/blob/master/capitulos/02-capitulo/02-0-capitulo-lo-basico.md)
</div>  