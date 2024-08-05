# Conversor de Texto a Código Binario

## Descripción

El programa **Conversor de Texto a Código Binario** es una aplicación en Java que convierte una cadena de texto en su representación en código binario. Utiliza la codificación binaria estándar ASCII para representar caracteres alfanuméricos y signos de puntuación.

## Funcionalidades

- **Conversión de Texto**: Convierte cada carácter de una cadena de texto a su representación en código binario.
- Cualquier carácter que no esté en el conjunto se ignorará (excepto los **espacios**, que se convertirán en 00100000).

## Uso

1. Al ejecutar el programa, se te pedirá que ingreses una cadena de texto.
2. El programa convertirá cada carácter de la cadena de texto en su correspondiente código binario y lo imprimirá en la consola.

## Ejemplo de Ejecución

```plaintext
=================================================== <[Entrada]> ==================================================
Escriba la palabra a convertir: Hello World
=================================================== <[Codificacion]> ===============================================
01001000 01100101 01101100 01101100 01101111 00100000 01010111 01101111 01110010 01101100 01100100 
==================================================================================================================
