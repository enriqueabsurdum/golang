# 2.3 Impresión de constantes y variables
Para imprimir el valor de una variable o constante utilice las funciones destinadas para ello del package `fmt`.
```go
func main() {
    number := 6
    fmt.Println(number)
}
```
`fmt.Println` imprime los valores de la variable y agrega una nueva línea luego de mostrar el valor por pantalla.   
`fmt.Printf` es utilizado para imprimir uno o más valores usando un especificador de formato definido.
```go
func main() {
	nombre := "Caprica-Six"
	aka := fmt.Sprintf("Número %d", 6)
	fmt.Printf("%s es también conocido como %s\n", nombre, aka)
}
```
Para mayor información visitar: [Package fmt](https://golang.org/pkg/fmt)

---
<div align="right">

[**Volver a Capítulo 2: Lo Básico**](https://github.com/enriqueabsurdum/golang/blob/master/capitulos/02-capitulo/02-0-capitulo-lo-basico.md)
</div>  