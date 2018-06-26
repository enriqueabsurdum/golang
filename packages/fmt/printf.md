# Package fmt
`import "fmt"`

[Resumen](#resumen)  
[Índice](#índice)  
[Ejemplos](#ejemplos)  

## Resumen
El package `fmt` implementa `I`/`O` formateadas con funciones análogas del lenguaje de programación C como `print` y `scanf`. The format 'verbs' are derived from C's but are simpler.

## **Printing**
**General:**  
**Boolean:**  
**Integer:**  
**Flotantes y Complejos:**  
**String y slice de bytes:**  
**Puntero:**   
**El formato predeterminado para `%v` es:**  
```
bool:                      %t
int, int8, etc.:           %d
uint, uint8, etc.:         %d, %#x if printed with %#v
float32, complex64, etc:   %g
string:                    %s
chan:                      %p
pointer:                   %p
``` 
## Índice
## Ejemplos