# MARKDOWN

Markdown es un lenguaje de marcado ligero, una forma de agregar formatos como encabezados, negritas, cursivas, listas... a un texto sin formato utilizando un editor de texto simple. Es decir, una forma rápida de coger apuntes con ordenador y pasarlos a limpiuo en un solo paso.

> - Elementos de bloque
>    - Párrafos
>    - Saltos de línea
>    - Encabezados
>    - Citas
>    - Listas
>    - Códigos de bloque
>    - Líneas horizontales
> - Elementos de línea
>    - Énfasis
>    - Links o enlaces
>    - Código
>    - Imágenes
> - Otros elementos
>    - Links automáticos
>    - Omitir Markdown
>    - Símbolos matemáticos

# Saltos de bloque (=Párrafos)

Para generar un nuevo párrafo en Markdown simplemente separa el texto mediante una línea en blanco (pulsando dos veces INTRO). `Ejemplo:`

Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolor commodi sint eligendi, nisi aliquam cumque ad ullam fugiat architecto culpa eveniet fuga obcaecati, nobis dolores accusantium pariatur ab dolore? Tempore?

# Saltos de línea (=lineas de texto)

Para realizar un salto de línea y empezar una frase en una línea siguiente dentro del mismo párrafi, tendras que pulsar **dos veces** la barra espaciadora antes de pulsar una vez INTRO. `Ejemplo:`

Nombre:  
Apellidos:  
Dirección:  

# Encabezados

Las almohadillas o hashtag `#` es el método utilizado en Markdown para crear encabezados. Debes usarlos añadiendo uno por cada nivel y dejando un espacio en blanco. `Ejemplo:`
## Encabezado 2
### Encabezado 3
#### Encabezado 4
##### Encabezado 5
###### Encabezado 6

# Enfatizar: negritas y/o cursivas

Para poner cursivas encierra entre 1 asterisco Para poner negritas encierra entre 2 asteriscos
Para poner negritas y cursiva encierra entre 3 asteriscos `Ejemplos:`

Lorem ipsum *dolor* sit **amet** consectetur adipisicing elit. Dolor commodi sint eligendi, nisi aliquam cumque ad ullam fugiat architecto culpa ***eveniet fuga obcaecati***, nobis dolores accusantium pariatur ab dolore? Tempore?

# Líneas horizontales

Para crearlas, en una línea en blanco deberás incluir `tres` de los siguientes elementos: 3 asteriscos, 3 guiones, o 3 guiones bajos. `Ejemplo:`
***

# Citas

Las citas de generar utilizando el carácter mayo que `>` al comienzo del bloque de texto. `Ejemplo:`

 >Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolor commodi sint eligendi, nisi aliquam cumque ad ullam fugiat architecto culpa eveniet fuga obcaecati, nobis dolores accusantium pariatur ab dolore? Tempore?

 # Listas

 Para crear listas desordenadas podemos utilizar 3 tipos de simbolos por cada item de la lista: Un asterisco `*`, un guión medio `-` o un símbolo más `+`. `Ejemplo:`
 
 * Ítem 1
 * Ítem 2
 * Ítem 3

Para crear listas ordenadas debes utilizar la sintaxis de tipo: `1.`.

1. Ítem 1
2. Ítem 2
3. Ítem 3

Para generar listas anidadas (desordenadas u ordenadas) dentro de otras, simplemente tendrás que añadir `dos (o cuatro) espacios en blanco`. `Ejemplo:`

* Ítem 1
  * Ítem 12
    * Ítem 121
*  Ítem 2

1. Ítem 1
   1. Ítem 12
      1. Ítem 121
2. Ítem 1

# Links o enlaces

Se crean escribiendo la palabra o texto enlazada entre `[]` corchetes y el link en cuestión entre `()` paréntesis.

Sin texto enlazado escribe la URL Entre ángulos `< URL >` Enlace de ejemplo como referencia: [3con14](https://www.3con14.com), y al final del texto escribir la etiquetea seguida de dos puntos.

# Imágenes

Insertar una imagen con Markdown se realiza de una manera idéntica a insertar links. En este caso, debes añadir un símbolo de `!` exclamación al principio y el enlace que es la ubicación de la imagen.

~~~
![Texto alternativo](ruta/imagen.jpg "Título alternativo")
~~~

`Ejemplo:`
![Pato](https://kellogggarden.com/wp-content/uploads/2018/11/raising-ducks-winter.jpg "Pato")

![Nútria](https://www.nps.gov/common/uploads/grid_builder/aknatureandscience/crop16_9/D1C90B2A-0741-A84F-28BC17F51F08BB9B.jpg?width=465&quality=90&mode=crop "Nútria")

# Tablas

Markdown permite dibujar tablas mediante pleacs `|`. Cada celda está separada por uno de estos caracteres. Para crear encabezados que se distingan visualmente del resto del contenido, se subrayan las celdas correspondientes con guiones `-`. `Ejemplo:`

| Columna 1 | Columna 2 |
|---|---|
| uno | dos |
| tres | cuatro |
| cinco | seis |

# Línea de Código

Encerrando el código entre acentos graves `<html lang="es">`

# Bloque de Código

Para crear un bloque entero que contenga código lo único que tienes que hacer es encerrar dicho párrafo entre dos líneas formadas por tres ~ virgulillas o tres acentos grave. La otra manera de añadir código en Markdown es comenzar el párrafo con `cuatro espacios en blanco`. `Ejemplo:`
~~~ html
<heard>
 <meta charset="UTF-8" />
 <meta htto-equiv="X-UA-Compatible" content="IE=edge" />
 <title>Document</title>
</head>
~~~

# Omitir Markdown

Cómo escribir ciertos símbolos como `*` o `#`, sin que Markdown los interprete para convertirlos en negritas...  
Escribiendo justo delante del símbolo la barra invertida `\`. `Ejemplo:` Esto es un asterisco \*

# Escritura matemática

En línea encerrando la fórmula entre signos de `$` En párrafos centrados, encerrando la fórmula entre dos signos `$$`
* Fórmulas en línea: $(a + b)² = a² + b² + 2ab$
* Fórmulas centradas: $$a² - b² = (a + b)*(a-b)$$
* Radicales: $$\sqrt{a² - b²}$$
* Fracciones $$x = \frac {-b \pm \sqrt{b² - 4ac}}{2a}$$
* Paréntesis grandes: $$\left (\sqrt{x²}\right)²$$
* Colores: $${\color{purple}{A}}abc123$$
