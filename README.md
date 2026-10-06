# Reto: misma lógica, otro lenguaje

## Objetivo

Investigar cómo expresar en otro lenguaje un algoritmo que ya conocemos en Python. Compararemos qué se mantiene en la lógica y qué cambia en la sintaxis.

## Organización

Trabajaréis en los grupos de la tabla. Cada grupo tiene asignados un lenguaje y **un solo reto**: condicionales o bucles.

| Grupo | Integrantes | Lenguaje | Reto |
| --- | --- | --- | --- |
| 1 | ADRIAN_LAZARO (MDIA) · ANTONIO_NAVARRO (MDES) · JORGE_OLIVER (MDIA) | Java | A - Condicionales |
| 2 | IGNACIO-PINAZO (MDIA) · CARLOS_GUTIERREZ (MDES) · PABLO_CUNAT (MDIA) | C# | B - Bucles |
| 3 | ANGEL_CARLOS_PEREZ (MDIA) · DAVID_GALLART (MDES) · LORENZO_SABBATINI (MDIA) | Go | A - Condicionales |
| 4 | JAVIER_MARTINEZ (MDIA) · IGNACIO_IBÁÑEZ-RIZO (MDES) · RAFA_BROTONS (MDIA) | PHP | B - Bucles |
| 5 | FRAN_ALAPONT (MDIA) · JAIME_SANFELIX (MDES) · MANOLO_TORTAJADA (MDIA) | C++ | A - Condicionales |
| 6 | ALEJANDRO-CERVERA (MDIA) · MARIO_GONZALEZ (MDES) · Jana Mei Cervera Monzó (MDIA) | Ruby | B - Bucles |
| 7 | JADE_LOPEZ (MDIA) · NICO_GOMEZ (MDES) · Laura Soler Úbeda (MDIA) | Kotlin | A - Condicionales |
| 8 | LOLA_BONET (MDIA) · RAUL_FERRIS (MDES) | Java | B - Bucles |
| 9 | PABLO_LEGORBURO (MDIA) · RICARDO_ROMAN (MDES) | C# | A - Condicionales |
| 10 | ANDRES_GIMENO (MDIA) · JOAQUIN_VILLALOBOS (MDIA) · OSCAR_HERREROS (MDIA) | JavaScript | B - Bucles |
| 11 | CHRISTIAN_VAZQUEZ (MDIA) · JORGE_DURA (MDIA) · LUCAS_OSEJO (MDIA) | PHP | A - Condicionales |
| 12 | HUGO_GAVILAN (MDIA) · INGRID (MDIA) · JUANJO_PRADES (MDIA) | Go | B - Bucles |

## Reto A — Condicionales

Investigad cómo escribir en vuestro lenguaje el equivalente a este código:

```python
edad = 20

if edad >= 18:
    print("Mayor de edad")
else:
    print("Menor de edad")
```

1. Cread una variable `edad` con un valor fijo. No hace falta pedir datos al usuario.
2. Mostrad `Mayor de edad` si su valor es mayor o igual que 18; en caso contrario, mostrad `Menor de edad`.
3. Ejecutad el programa con `edad = 17`, `edad = 18` y `edad = 20`.
4. Explicad qué condición se comprueba y cuándo se ejecuta cada rama.

Resultados esperados:

| Edad | Mensaje |
| --- | --- |
| 17 | Menor de edad |
| 18 | Mayor de edad |
| 20 | Mayor de edad |

## Reto B — Bucles

Investigad cómo mostrar los números del 1 al 5 en vuestro lenguaje. **Podéis elegir entre `for` o `while`; solo tenéis que hacer una versión.**

Ejemplos en Python para elegir:

```python
# Versión con for
for i in range(1, 6):
    print(i)
```

```python
# Versión con while
i = 1

while i <= 5:
    print(i)
    i += 1
```

1. Elegid `for` o `while`, escribid el código en vuestro lenguaje y ejecutadlo.
2. Identificad cómo empieza el recorrido, cómo se avanza y cuándo termina.
3. Si elegís `while`, explicad qué pasaría si no aumentaseis `i`. No ejecutéis un bucle infinito.
4. Modificad vuestro bucle para mostrar los números del 1 al 10 y comprobad el resultado.

Salida esperada del programa inicial:

```text
1
2
3
4
5
```

## Investigación y comparación

Podéis consultar documentación, tutoriales o herramientas de IA, pero **todos los integrantes deben poder explicar el código**.

Responded en vuestro documento:

1. ¿Cómo se declara la variable o el contador?
2. ¿Cómo se muestra información por consola?
3. ¿Cómo se delimitan los bloques de código? Comparadlo con la indentación de Python.
4. ¿Qué símbolos o palabras cambian respecto al ejemplo en Python?
5. ¿Qué decisiones o repeticiones se mantienen? Explicad el algoritmo en castellano, sin usar código.
6. ¿Habéis necesitado algún elemento adicional para ejecutar el programa, como una función principal? Separadlo de la estructura que estáis investigando.

## Entrega

Cread **un repositorio de GitHub por grupo** y subid a él:

- **El ejemplo de código que hayáis hecho** en el lenguaje asignado.
- **Un `README.md` contestando las preguntas** del apartado «Investigación y comparación». Indicad también los nombres de los integrantes, el lenguaje y el reto asignado.

**Un integrante de cada grupo debe enviar el enlace del repositorio por correo a [scpinilla@edem.es](mailto:scpinilla@edem.es).**

- **Asunto:** `Reto otros lenguajes — Grupo XX`.
- **Cuerpo del correo:** nombres de los integrantes, lenguaje asignado y enlace al repositorio.
- Aseguraos de que la profesora pueda acceder al repositorio.

## Puesta en común

Cada grupo preparará una explicación breve en la que participen todos sus integrantes:

- Enseñad el código y el resultado.
- Explicad cómo funciona la condición o el bucle.
- Señalad una semejanza y una diferencia respecto a Python.

**Pregunta final:** ¿qué parte de lo aprendido en Python os ha servido para resolver el ejercicio en otro lenguaje?
