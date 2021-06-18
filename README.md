# DIU: EJERCICIO FINAL

Autora: Inés Nieto Sánchez

# PARTE I: MI EXPERIENCIA UX

# PARTE II: Caso de estudio. [Web YUZIN](https://yuzin.com/)

## INTRODUCCIÓN
Nos encontramos ante la página web de una empresa de divulgación de enventos culturales en Andalucía llamada YUZIN. Esta empresa explica que tiene como objetivo promover e incentivar el consumo de la cultura local convirtiéndose en la unión entre el público y los agentes culturales. Para ello YUZIN a través de su revista mensual o con un listado muestra al usuario los próximos eventos culturales (conciertos, teatro, poesía, visitas guiadas a monumentos...) de las ciudades en las que trabaja la empresa, ofreciendo a sus usuarios ventajas como descuentos o acceso a actividades exclusivas si se suscriben a su club. Además, permite a los promotores culturales subir sus eventos y vender las entradas en la página web.

La página se ha mantenido con un diseño bastante obsoleto desde 2004 hasta 2018, en el año 2019 le dieron un nuevo lavado de cara. En este rediseño la revista que en años atrás poseía mayor protagonismo ha acabado en un segundo plano, pasándole el protagonismo a la muestra de eventos culturales y compra de entradas online. Esto último lo considero un acierto ya que actualmente en comparación a hace unos años no se leen a penas revistas y se prefiere buscar directactamente la información de un evento en concreto.

A continuación se realizará un análisis de este nuevo diseño comprobando si la experiencia de usuario ha sido mejorada y se procederá a realizar un rediseño de la página en base a lo analizado.

### 1.ANÁLISIS

### Usability Review
Para la realización del análisis del sitio web se ha optado por hacer un Usability Review con el cual se ha "diseccionado" la página para extraer las carencias y fallos que presenta ésta, así como sus puntos fuertes. 

De este Usability Review hemos obtenido que la puntuación final de la página ha sido de 62 puntos (Moderado) y hemos comprobado que Yuzin presenta múltiples fallos, siendo los principales los siguientes: 

- No destaca sus funcionalidades principales y da mayor relevancia a secciones secundarias como los articulos de opinión.
- No es posible hacerse miembro del club a no ser que se pase por el proceso de compra de entradas de un evento.
- El menú es poco intutivo para un usuario novato.
- Una de las dos opciones de búsqueda ofrecidas (búsqueda por palabras clave) no cumple con su funcionalidad. 
- No ofrece ningún tour por la página y no es fácil de encontrar una sección de ayuda, pues el FAQ ofrecido se encuentra en el footer y éste sólo resuelve dudas sobre la empresa. Si se necesita ayuda sobre la página hay que acceder a la sección de "Contacta" y rellenar un formulario, escribir un email o llamar por teléfono a uno de los números de contacto. Todo lo anterior resulta poco intuitivo y demasiado complejo para una simple duda sobre la página.
- EL feedback es algo pobre, pues los errores devueltos no especifican claramente qué ha falla y en cuanto a la navegación por la página no se destaca la sección en la que el usuario se encuentra ni se proporciona la ruta de navegación.
- Añade elementos que no tienen ninguna función como al final de la página principal con título "Actualidad Cultural".
- No redimensiona correctamente con la ventana del navegador.
- El constrate elegido de amarillo sobre blanco no es adecuado.

A pesar de estos defectos, también se ha encontrado que Yuzin destaca positivamente por lo siguiente:
- La página web es fácil de encontrar en los buscadores.
- La interfaz es sencilla y no está saturada.
- Presenta un buen rendimiento, la página carga rápido.
- Se priorizan los eventos destacados en las búsquedas de eventos.
- Los formularios utilizan los campos de entrada apropiados.
- La fuente elegida se lee fácilmente.

Para acceder al documento del Usability Review pulse [aquí](Análisis/Usability-review-Yuzin.pdf).

### Accesibilidad
Se ha realizado un estudio de accesibilidad para comprobar que la página permite el acceso a todo el público a pesar de padecer discapacidades como el daltonismo. 

Para este estudio se han hecho uso de los plugins WAVE Web Accessibility Evaluation Tool, Accessibility Insights for Web y Funkify.

El mayor problema encontrado señalado tanto por WAVE como por Accessibility Insights for Web es la falta de constraste. Sólo basta con desaturar la página para darnos cuenta de esto:

<p float="left">
<img src="Análisis/wave_1.png" width="600"/>
<img src="Análisis/wave_4.png" width="600"/> 
<img src="Análisis/accessibility_insights.png" width="600"/> 
</p>

Probando la opción "Trembling Trevor" de Funkify se comprueba que resulta muy difícil hacer click sobre una opción o con "Blurry Bianca" se comprueba que para personas miopes los textos con un tamaño de fuente pequeña son muy complicados de leer.

Sumado a estos problemas, la página no presenta ninguna sección de información sobre Accesibilidad. Por esto se deduce que en este sitio web no se tiene en cuenta la accesibilidad para todos los públicos.


