# Plarzom

Platzom es un idioma inventado para el [curso de fundamentos de JavaScrit ] (platzi.com) de platzi, educacion online

## Descripcion de idioma

- Si la palabra termina con "ar", se le quitan esas dos letras
- Si la palabra inicia con Z, se le añade "pe" al final
- Si la palabra traducida tiene 10 o más letras, se debe partir en dos por la mitad y unir con un guión medio
- Por último, si la palabra original es un palíndromo, ninguna regla anterior cuenta y se devuelve la misma palabra pero intercalando letras mayúsculas y minúsculas

## instalacion

```
npm install platzom

```

## Como usar

```
import platzom from 'platzom'

platzom("Programar") // Program
platzom("Zorro") // Zorrope
platzom("Zarpar") // Zarppe
platzom("abecedario") // abece-dario
platzom("sometemos") // SoMeTeMoS

## Creditos

- Sacha Lifszyc
- Luis Fernando

## licencia

[MIT]