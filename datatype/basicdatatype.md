# Tipos de datos básicos
## **Contenidos**
- [Enteros](#enteros)
- [Números de punto flotante](#n%C3%BAmeros-de-punto-flotante)
- [Números complejos](#n%C3%BAmeros-complejos)
- [Lógicos](#l%C3%B3gicos)
- [Cadenas](#cadenas)
    - [Literales de cadena](#literales-de-cadena)
    - [Unicode](#unicode)
    - [UTF-8](#utf-8)
    - [Cadenas y Byte Slice](#cadenas-y-byte-slice)
    - [Conversión entre cadenas y números](#conversi%C3%B3n-entre-cadenas-y-n%C3%BAmeros)
- [Constantes](#constantes)
    - [El generador constante `iota`](#el-generador-constante-iota)
    - [Constantes sin tipo](#constantes-sin-tipo)


## Enteros
| Tipo      | Rango                                                      |
| --------- | ---------------------------------------------------------- |
| `byte`    | Sinónimo para `uint8`                                      |
| `int`     | El rango `int32` o `int64` depende de la implementación    |
| `int8`    | [ `−128`, `127` ]                                          |
| `int16`   | [ `−32768`, `32767` ]                                      |
| `int32`   | [ `−2147483648`, `2147483647` ]                            |
| `int64`   | [ `−9223372036854775808`, `9223372036854775807` ]          |
| `rune`    | Sinónimo para `uint32`                                     |
| `uint`    | El rango `uint32` o `uint64` depende de la implementación  |
| `uint8`   | [ `0`, `255` ]                                             |
| `uint16`  | [ `0`, `65535` ]                                           |
| `uint32`  | [ `0`, `4294967295` ]                                      |
| `uint64`  | [ `0`, `18446744073709551615` ]                            |
| `uintptr` | Un entero sin signo capaz de almacenar un valor de puntero |

## Números de punto flotante
## Números complejos
## Lógicos
## Cadenas
### Literales de cadena
### Unicode
### UTF-8
### Cadenas y Byte Slice
### Conversión entre cadenas y números
## Constantes
### El generador constante `iota`
### Constantes sin tipo