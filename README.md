# Project: De patria a patria
### Descripción general    
* Introducción  
* Herramientas
* Imagenes
  
**Introducción**    
  Este proyecto habla sobre las ciudades natales de los trabajadores de Practicum, en esta pagina recreamos una galeria de arte con imagenes de los principales lugares epicos de las ciudades de origen de los colaboradores de practicum.

 Para que este proyecto pudiera ser apresiado en las diferentes resoluciones de pantalla que existen hoy en día, trabajamos las principales resoluciones desde 1280px, 768px y 320px haciendo que nuestra página realice su transición de manera estable y sin romperce en los puntos de quiebre. 

Puedes apreciar en este proyecto los bloques de **Header** donde damos la bienvenida a los lectores con un titulo y subtitulo llamativo, adicional de una imagen en blanco en negro, dando vida a lo sencillo y sutil de la página. 
    
  
**Herramientas** 

Las principales herramientas con las que se trabajo el proyecto fueron las siguientes: 

* HTML5 
* CSS avanzazado
* Grid Layout by CSS
* Flexbox by CSS
* Medias Queries
* Metodología BEM by Yandex

*HTML5:* realizamos la estructura de nuestro proyecto, asignando clases a cada etqueta que utizamos. 

*CSS:* para dar estilos a nuestro proyecto utilizamos una carpeta **pages** con su respectivo archivo **index.css** que contiene todos los **@import** de los estilos, seguimos todas las intrucciones para que las propiedades se fueran ejecutando en orden, de esta manera no causamos disputa con nuestro código. 

*Grid Layout:* nos permitio crear bloques importantes en nuestro proyecto, pudimos realizar una grilla de imágenes, que al momento de bajar a las siguientes resoluciones se ajusta al tamaño:

1. Resolución 1280px la grilla se muestra en **2 filas** y **4 columnas**
2. Resolución 768px la grilla se muestra en **2 columnas**, no fue necesario indicar las filas ya que se colocaron por defecto. 
3. Resolución 320px la grilla se muestra en **1 columna** donde le dimos un valor de 1fr, de esta manera pudimos hacer que nuestra imagen ocupe todo el espacio disponible en la celda.

*Flexbox:* El uso de flexbox en este proyecto fue muy poco y solo para 2 bloques de nuestro proyecto, nos ayudo más que todo a centrar texto en el bloque intro y cover, también lo utilizamos para crear nuestro botón de compra de las NFT. 

*Media query:* nos ayudo a que nuestro proyecto se pueda ajustar a las diferentes resoluciones de pantalla, dandole estilos especifico para que el maquetado del proyecto no se desborde y cree una barra horizontal

*BEM:* Todo nuestro proyecto esta organizado con la metodología BEM, la creación de las clases y carpetas se hizo según el orden **Bloque, Elemento, Modificador** se creo carpeta y archivos para cada selector de estilos, todos se guardaron y ordenaron en su carpeta de *blocks* y se **@import** al archivo *index.css* la cual es la que esta enlazada a nuestro HTML5, adicional se creo el archivo vacío **.nojekyll**. 

**Imágenes**  
  
  Las imagenes que se aprecian en el proyecto se trabajaron en pixel, las imagenes originales tenian una resolución muy alta y para que la página no tardara tanto en cargar, utilizamos tiny.com que nos ayudo a bajar los pixeles sin afectar la calidad de la imágen, adicional usamos la propiedad object-fit: cover; en las medias query para que al momento de cambiar el tamaño no se viera borroso o extendido. 

**Enlace para GitHub**
 https://github.com/SoyIsabelMM/web_project_3_esp/index.html
