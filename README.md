# Guía de estilo en CSS
Realiza las siguientes actividades y sube los cambios a tu repositorio.

## **1. Lee la guía de estilos para CSS propuesta por Google**
Lee el punto 4 de la [guía de estilos de CSS propuesta por Google](https://google.github.io/styleguide/htmlcssguide.html#CSS).

## **2. Detecta y corrige los errores de estilo en el código CSS del fichero css-no-valido.html**

**A. Usa nombres de clases e id significativos.**
* Trata de evitar nombres sin significado y que sean lo más genéricos posibles. 

**B. Usa nombre de clases e ID los más cortos posibles**
* Siempre y cuando sean representativos con el nombre original. 
* Ejemplo: Para poner .author {} no usar .atr ya que podría dar a entender que se refiere a un atributo.

**C. Evita selectores de antecesores en la medida de posible.**
* Ayuda al rendimiento. 

**D. Usa las versiones cortas para definir las propiedas.**
* Ayuda a la eficiencia y comprensión del código.

**E. No uses la unidad después del valor 0.**

**F. No coloques ceros delante de valores entre -1 y 1.**

**G. Usa tres valores en el código hexadecimal cuando sea posible.**

**H. Usa prefijos en proyectos grandes.**
* Use prefijos (como espacios de nombres) para los nombres de ID y clases. 
* Utilice identificadores únicos y cortos seguidos de un guión.
* El uso de espacios de nombres ayuda a prevenir conflictos de nombres y puede facilitar el mantenimiento, por ejemplo, en las operaciones de búsqueda y reemplazo.

**I. Separa las palabras en ID y nombres de clases con un guión.**
* No concatenar palabras y abreviaturas en los selectores con ningún carácter (incluido ninguno) que no sean guiones, para mejorar la comprensión y la capacidad de escaneo.

**J. Evitar hacer uso de los detectores de navegadores y "hacks de CSS.**

**K. Ordenar alfabéticamente las declaraciones.**

**L. Sangra el contenido de cada bloque.**
* Las reglas dentro de las reglas y las declaraciones, para reflejar la jerarquía y mejorar la comprensión.

**M. Utiliza un punto y coma después de cada declaración.**

**N. Usa un espacio después de los dos puntos del nombre de una propiedad.**
* Pero ningún espacio entre la propiedad y los dos puntos.

**Ñ. Utiliza un espacio entre el último selector y el bloque de declaración.**
* La llave de apertura debe estar en la misma línea que el último selector en una regla.

**O. Siempre empieza una nueva línea por cada selector.**

**P. Separar una regla de otra por una línea en blanco.**

**Q. Uso de comillas:**
* Utiliza comillas simples ('') en lugar de dobles ("") para los selectores de atributos y los valores de la propiedad.
* No utilices comillas en los valores de URI (url ()).
* Excepción: si necesita utilizar la regla @charset, utilices comillas dobles ya que las comillas simples no están permitidas.

**R. Uso de comentarios:**
* Si es posible, agrupa las secciones de la hoja de estilo mediante comentarios.
* Separa secciones con nuevas líneas.

## **3. Valida el código de ambas páginas.**
* Haz uso del validador de la W3C https://jigsaw.w3.org/css-validator/.
* ¿Hay algún error o "warning" detectado en alguna de las hojas de estilo que ya has corregido?
* Corrígelos y vuelve a validarlo.

## **Referencias:**

- [Guía de estilos de CSS propuesta por Google](https://google.github.io/styleguide/htmlcssguide.html#CSS) 
