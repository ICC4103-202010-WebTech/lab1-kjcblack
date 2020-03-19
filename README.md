#Laboratorio 01


——
***3 Actividad***

3. A grandes rasgos podemos identificar las distintas partes de la estructura *HTML*: 
a) Elemento html.
b) Head.
c) Body.

En la primera línea podemos contemplar ***<html op=“news”>*** este elemento html encierra todo el documento, indica el inicio y final de este. Sus etiquetas <html> se ubican al comienzo y </html> al término.

 En ***head*** están contenido los elementos que entregan los metadatos del documento:
 * **meta** * en esta etiqueta se introducen los metadatos en el documento, la primera línea enviará solo el origen del documento como referente en todos los procesos, en la siguiente línea indica las dimensiones de la página.
 * **link rel** * aquí se puede agregar información externa relacionado al documento, por ejemplo una de estas es *favicon* que es un gráfico en la barra de direcciones del navegador cuando se ingresa en la página web.
 * **tittle** * en el cual se ingresa un título al documento.
Head también está compuesta de la etiqueta <head> al inicio y </head> al final.

En ***body*** se define el contenido del documento, *center* el contenido estará centrado en un bloque, *table* se crea una tabla con varias características. El elemento *<tbody>* comprende un bloque de filas (*<tr>* fila de celdas en una tabla) donde estará el cuerpo de la tabla y *<td>* se especifica el contenido de la celda. Como se puede ver en este caso el primer tbody la página “entera” desde el rectángulo naranja hasta el final de la página, dentro de este se ubica otra tabla con su tbody que nos da los atributos del rectángulo naranja ubicado al inicio de la página (sus dimensiones, color) y sus enlaces de referencias. La siguiente tabla contiene todas las referencias de los números del 1-30, usando tr para cada mini cuerpo de la tabla (para cada número con su contenido) y el td para cada objeto en particular (número, triángulo, referencias, horas, comentarios, etc). Finalmente se puede apreciar el último td grande que comprende la última tabla de la página en donde se puede buscar, contactar, soporte, seguridad etc. Cabe destacar que también contiene *<a>* que es un hipervínculo o enlace.

4. ***hn.js***: Este archivo tiene como propósito la definición de funciones de la página web.En el momento de que el usuario presiona y hace click dependiendo de dónde lo haga se le enviará una respuesta.


 ***news.css***: En este archivo se añaden los estilos a la página, es decir qué aspecto tendrá (colores, tipo de letra, tamaño de la fuente).

Se diferencian en que uno es para la definición de funciones en la página web (hn.js) y el otro es para la definición de la estética (news.css).


5. Ha requerido 7 solicitudes para descargar la página principal de Hacker News.

* **favicon.ico** * Request Method: GET
* **hn.js?S5Ty60GFbTgUrObD86pQ** * Request Method: GET
* **grayarrow.gif** * Request Method: GET
* **news.css?S5Ty60GFbTgUrObD86pQ** * Request Method: GET
* **s.gif** * Request Method: GET
* **y18.gif** * Request Method:GET
* **news.ycombinator.com** * Request Method: GET


Tipo de servidor web que se utiliza en este sitio web: nginx.



