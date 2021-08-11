
# Observaciones

Caro, felicitaciones por tu TP. Que lindo quedó tu portfolio, qué hermosa la elección de colores y tipografías, que lindos detalles agregaste, y qué impresionante la atención al detalle que ponés en la web, en su aspecto visual y también en el código. 

Tengo, lamentablmemente, pocos comentarios para hacerte, ya que el nivel de este trabajo es realmente muy alto. Pero siempre hay algo que comentar! :) Como dije en clase, este trabajo no se hace para que constates conocimientos, sino para que aprendas: en ese sentido, mi intencion es que estos comentarios te sirvan para aprender, mejorar tu codigo a futuro e ir apreciando mejor qué se espera de nosotras como desarrolladoras front end.

## Estructura correcta de documento HTML

Tu HTML esta realmente excelente. Claro, prolijo, muy bien comentado e identado. Lo unico a comentar aquí es que usas los atributos del `form` en el primer `label`: no me preocupa demasiado porque repasaremos formularios más adelante, pero tenelo en cuenta para futuras ocasiones. 

## Respeta la consigna

- El portfolio cuenta con las secciones solicitadas
- Al clickear en los links de navegación, debe llevar a la sección correspondiente
- Al clickear en los links de contacto, debe llevar a la página externa
  correspondiente
- El portfolio debe tener un diseño responsivo y verse correctamente en distintos dispositivos
- El portfolio debe estar deployado y ser accesible desde una URL
- El repositorio en GitHub debe tener un readme adecuado

Todos estos puntos están cumplidos. Menciono especialmente tu responsive: es increíble lo bien que solucionaste las distintas resoluciones, siguiendo casi a la perfección el modelo y preocupandote para que todo se vea hermoso, veamos tu web desde cualquier dispositivo. 

El único comentario que te haría al respecto es que en las resoluciones de celulares más pequeñas (menor a 350px) aparece una barra blanca a la izquierda que fuerza un scroll horizontal. Ese problema es muy habitual, y ocurre cuando tenemos un elemento que rebalsa el tamaño del celular por algun motivo. En tu caso, contact-right-bar tiene un width de 100% en mobile, pero le queda un margin-left: 1.5rem del desktop. 100% de width + un margin es obviamente mas grande que el tamaño del body, asi que ese margen fuerza ese scroll horizontal. 

### Respeta el diseño dado

Cumplido a la perfección. 

### Buena estructura de proyecto

Cumplido, con excepción del favicon, que siempre debería ir en la carpeta principal y no en la de recusos externos. 

### Código bien indentado

Tabulas muy bien, lo cual parece un detalle extra cuando una recien comienza pero ayuda un monton a su legibilidad, y que lo hayas logrado en esta etapa es un gran mérito. 

### Comentarios que permiten mejorar la legibilidad del código

Impecables. 

### Uso correcto de etiquetas semánticas

En general usas bien las etiquetas semánticas. Me llama la atención que hayas usado `div` para las tarjetas de Mis Conocimientos y Mis Proyectos: yo diría que deberían ser `article`. Pero es el único detalle a comentar aquí (y hay quien podría discutirme que deberían ser divs)

### Buenos nombres de clases

En general está cumplido, aunque noto algunas clases que tienen identidades confusas. Tendés a usar la etiqueta html en el nombre de la clase, lo que es repetitivo y además incorrecto, ya que el nombre de la clase debe ser descriptivo en sentido funcional (qué función cumple el elemento dentro de la página). Considerá "top-nav-li" o "top-nav-a", privilegiá nombres que describan qué son en la página (list-item y link en este caso). Mismo en el footer. 

Lo que hoy está a la derecha mañana puede estar a la izquierda, los diseños de las webs son muy dinámicos. No identifiques a elementos por su posición, ya que está puede cambiar (fijate como la sección de la presentación que identificás como "left" se va arriba en el responsive: su posición no es un buen descriptor)

### Código CSS bien estructurado

Cumplido. Noto algunos estilos innecesarios o confusos, que te voy indicando en tu archivo de css.

### Reutilización de estilos

Cumplido en general, ya que noto muchas veces que usas dos nombres de clase, uno general y otro más específico, para evitar repeticiones innecesarias, como en los íconos de mis proyectos.

### Cumple con criterios básicos de accesibilidad

- Los colores tienen un contraste adecuado

No cumplido, tus colores no son aptos para usarse con texto blanco, ni el rojo ni el violeta del hover. Siempre chequeá con herramientas del tipo https://webaim.org/resources/contrastchecker/

- Las imágenes tiene el atributo `alt` que corresponde

Muy correctos. 

- Los íconos y elementos que no presentan texto agregan la información correspondiente por otros medios (etiquetas aria, texto oculto)

Cumplido

- Los íconos y elementos que no necesitan ser anunciados por un lector de pantalla tienen la etiqueta aria
  correspondiente

No cumplido. 

- Commits con mensajes adecuados

Cumplido, noto muchos y buenos commits en tu proyecto, lo que siempre se agradece.

- Cuenta con un favicon

Cumplido, aunque debería estar en la carpeta principal. 

### Nota: 9
