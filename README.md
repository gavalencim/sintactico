**Analizador Sintáctico con NLTK y ChartParser**

Este proyecto implementa un analizador sintáctico para expresiones aritméticas básicas utilizando la biblioteca Natural Language Toolkit (NLTK) en Python. Emplea una gramática de contexto libre (CFG) y el parser ChartParser para analizar y representar visualmente el árbol sintáctico de una expresión ingresada.

**Estructura del Código

-Definición de la Gramática:**
Se utiliza una gramática de contexto libre para definir las reglas sintácticas de expresiones aritméticas. La gramática permite operaciones de suma (+), resta (-), multiplicación (*), y división (/). También permite variables representadas por letras (a - z) y números (0 - 9).

-**Expresión Objetivo:**
La expresión que se desea analizar debe ingresarse como una cadena y dividirse en tokens (elementos) separados por espacios. En este ejemplo, se analiza la expresión "4 + ( a - b ) * x".

-**Creación del Analizador:**
Se utiliza ChartParser de NLTK, que toma la gramática definida y la usa para analizar la expresión.

-**Generación del Árbol de Derivación:**
Una vez que la expresión se ha analizado, el programa genera el árbol sintáctico y lo muestra en dos formas:

En consola, con una representación estructurada del árbol.
En una ventana gráfica, mostrando el árbol de derivación completo.
Requisitos
Para ejecutar este código, necesita instalar NLTK:


**pip install nltk
Uso**
Simplemente ejecute el script para ver el árbol de derivación de la expresión definida. Puedes cambiar la expresión objetivo para analizar otras expresiones aritméticas que cumplan con las reglas de la gramática.

**Ejemplo de Salida**
Al ejecutar el código con la expresión "4 + ( a - b ) * x", se obtiene un árbol de derivación que representa la estructura de la expresión en función de las reglas de la gramática.
