# 2.1 Variables y tipo inferido
La palabra reservada `var` permite declarar una lista de variables, en donde el tipo se específica al final de cada sentencia.
```go
var {
    nombre     string
    edad       int
    ubicacion  string
}
```
Incluso es permitido lo siguiente
```go
var {
    nombre, ubicacion  string
    edad               int
}
```
También se pueden declarar las variables una a una:
```go
var nombre     string
var age        int
var ubicacion  string
```
Las variables pueden ser inicializadas con algún valor según el tipo al que pertenezcan, como por ejemplo:
```go
var {
    nombre     string = "Bruce Wayne"
    edad       int    =  33
    ubicacion  string = "Gotham City"
}
```
Si la variable se ha inicializado con un valor, el tipo que representa la variable puede omitirse, en cuyo caso dicha variable tomará el tipo acorde al valor asignado por el inicializador (tipo inferido). 
```go
var {
    nombre     = "Bruce Wayne"
    edad       =  33
    ubicacion  = "Gotham City"
}
```
También se pueden inicializar variables en una sola línea:
```go
var {
    nombre, ubicacion, edad = "Bruce Wayne", "Gotham City", 33
}
```
Dentro de una función, puede utlizarse la sentencia de asignación con el operando `:=` en lugar de una declaración con la palabra reservada `var` como se ha observado hasta ahora.
```go
func main() {
    nombre, ubicacion := "Bruce Wayne", "Gotham City"
    edad := 33
    fmt.Printf("%s (%d) of %s", nombre, edad, ubicacion)
}
```
Una variable pueden contener cualquier tipo que la represente, incluyendo funciones:
```go
func main() {
    accion := func() {
        // hacer algo
    }
    accion()
}
```
Fuera de una función, todas las declaraciones de variables comienzan con una palabra reservada (`var`, `func`, etc), puesto que el operando `:=` no está disponible.

Para mayor información visitar: [Go’s declaration Syntax](https://blog.golang.org/gos-declaration-syntax)

---
<div align="right">

[**Volver a Capítulo 2: Lo Básico**](https://github.com/enriqueabsurdum/golang/blob/master/capitulos/02-capitulo/02-0-capitulo-lo-basico.md)
</div>   