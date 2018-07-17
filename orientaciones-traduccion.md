# Orientaciones para la traducción

## I. Aspectos a tener en cuenta para la traducción del texto

__1. La variedad dialectal del español que ocuparemos en la traducción es la de Latinoamérica__ (porque el posible público destinatario que la habla es más amplio). Trataremos de que sea una versión lo más neutra posible, por lo que

* Evitaremos el voseo (vos/vosotros). R4DS está dirigido a una segunda persona, así que para cautelar la neutralidad la traduciremos como tú.
* Preferiremos el pretérito perfecto simple (... en el capítulo anterior revisamos...) por sobre el compuesto (... en el capítulo anterior hemos revisado...), ya que el primero es más común en el español Latinoamericano (el otro lo es en el español peninsular). 


__2. Género gramatical.__ A diferencia del inglés, el español tiene género gramatical (masculino, femenino y muy, pero muy pocos neutros). En general, como R4DS está dirigido a un tú y se habla de datos, variables y funciones, hay pocas situaciones en las que haya que tomar una decisión respecto de cómo manejar este tema; pero las hay. Por ejemplo, acá: “... for collaborating with other data scientists”. Como son pocos casos, la idea es ir resolviéndolos a medida que aparezcan (Slack, canal #dudas-traducción).  En principio, las dos opciones más habituales que se han seguido en traducciones de este tipo son: 

* Usar el femenino para incluir un género gramatical poco representado: para colaborar con otras científicas de datos. 
* Ajustar la redacción para evitar tener que asignar un género: para colaborar con otras personas que trabajan en Ciencia de Datos. 

__3. El español es una lengua menos repetitiva que el inglés.__ Como los verbos tienen marca de persona, género y número, tenemos la flexibilidad de poder omitir el sujeto ya que por contexto se suele entender a qué nos estamos refiriendo. 

Ejemplo:
> The first argument is the name of the data frame. The second and subsequent arguments are the expressions that filter the data frame. 

Traducción:
> El primer argumento es el nombre del data frame. El segundo y los subsiguientes son las expresiones que filtran el data frame. 

O incluso:
> El primer argumento es el nombre del data frame. El segundo y los subsiguientes son las expresiones para filtrarlo. 

En todos los casos, hay que tratar de pensar cómo suena más natural/normal en español y cómo queda más claro para quien lee. 

__4. Hay regularidades que no siempre se cumplen.__ Por ejemplo, en inglés las palabras con función adjetiva se anteponen a los sustantivos (missing values, help pages, etc.), mientras que en español suele ser al revés: ponemos los adjetivos después del sustantivo: valores perdidos, páginas de ayuda, etc. 
Sin embargo, hay casos en que en español la forma “no marcada”, es decir, la que nos suena más natural, es con el adjetivo al principio: 

Ejemplo: 
> this small example helps to understand… > este pequeño ejemplo ayuda a entender...

En general, ante dudas de este tipo, pensar en qué es lo que suena más natural/normal en español

__5. Las expresiones idiomáticas no son traducibles de manera literal.__ En caso de que las hubiere (lo iremos descubriendo en el camino), hay que proponer una traducción que permita entender el sentido de ella. 

Ejemplo:  
> it’s raining cats and dogs > está lloviendo a cántaros

## II. Traducción (o no) de términos técnicos.
Hay términos técnicos que será necesario traducir y otros que no. El criterio suele estar en si existe una versión en español extendida (o entendible), o si se suele utilizar la versión original en inglés. En el caso de los últimos, hay que decidir qué género gramatical asignarle (por ejemplo, ¿el o la dataframe? ¿un o una pipe?) y si ofreceremos una traducción explicativa la primera vez que las utilicemos (por ejemplo, “este dataset (conjunto de datos) contiene las siguientes variables; ...”

[Las Carpentries](https://github.com/Carpentries-ES/board/blob/master/Convenciones_Traduccion.md) tienen algunas convenciones que podemos seguir, pero hay otros términos que irán apareciendo en la medida que avancemos. Por lo tanto, iremos desarrollando las siguientes listas de términos:

#### Traducción de términos técnicos

| término en inglés | traducción a utilizar |
| ----------- | ----------- |
| assignment operator | operador de asignación |
| console | consola |
| dataset | conjunto de datos |


#### Términos técnicos que se mantienen

| términos que no se traducen |
| ----------------------------|
| el output |

## III. Traducción del código: 

__1. Nombres de funciones.__ Se debe ofrecer una traducción la primera vez que aparecen. 

Original:
> * Pick observations by their values (`filter()`).
> * Reorder the rows (`arrange()`).

Traducción:
> * Escoger observaciones según sus valores (`filter()`  — del inglés filtrar—).
> * Reordenar las filas (`arrange()`  — del inglés organizar).

__2. Datos.__ Este proyecto tiene asociado el desarrollo de un paquete con la traducción de todos los datos. Por lo tanto, es necesario instalarlo para el proceso de traducción. Revisa el repositorio correspondiente para ver las indicaciones: https://github.com/cienciadedatos/datos

Aún queda por resolver lo que haremos en el capítulo sobre manejo de strings. Lo mejor sería que los ejemplos estuviesen en español, pero el dataset utilizado (`factors::sentences) es muy grande (720 oraciones). Una opción es traducir una muestra de esos datos. 

__3. Los objetos/variables creados a partir de los datos se traducen, al igual que las títulos, etiquetas y nombres de ejes en los gráficos.__

Por ejemplo:

__original__
```r
not_cancelled <- flights %>% 
  filter(!is.na(dep_delay), !is.na(arr_delay))
  ```
  
  __traducción variable + datos__
```r
no_cancelados <- vuelos %>% 
  filter(!is.na(atraso_salida), !is.na(atraso_llegada))
  ```
