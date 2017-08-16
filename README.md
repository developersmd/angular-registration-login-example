## - AngularJS User Registration and Login Example

### Instalación
* Para ejecutar:
 * <pre><code> npm install </code></pre>
 * <pre><code> npm install webpack -g </code></pre>
 * <pre><code> npm install webpack-dev-server -g </code></pre>

##Instrucciones:

A continuación detallamos las tareas a realizar. Por cada uno de los puntos que se detallan, crea un commit con los cambios realizados.
En el comentario del commit especifica los cambios que has realizado así como explicaciones o aportaciones que consideres importante comentar. Valoraremos especialmente que los commits estén bien documentados

### Tareas
* 1. Crea una página pública que se acceda mediante: localhost:8080/#!/ships o similar.
    * 1.1 - El controlador de esta página debe realizar una petición a un servicio.
    * 1.2 - El servicio realizará la petición a http://swapi.co/api/starships/. --> Ojo con esto.Para que funcione hay que añadir la siguiente Header a la llamada:
    `headers: { 'Authorization': 'none'} `
    * 1.3 - Muestra el resultado por consola.
    * 1.4 - Utiliza Promesas para gestionar el resultado.

* 2. Crea un componente que se llame de la siguiente forma: `<custom-md-list> </custom-md-list>` será una lista de elementos.
    * 2.1 - Este componente recibirá datos del controlador padre ( la página ships).
    * 2.2 - El componente mostrará por pantalla el campo name de cada uno de los elementos.
    * 2.3 - El controlador padre enviará solo 5 elementos al componente.
    * 2.3 - El componente tendrá un campo "más datos". Al pulsarlo, añadirá 5 elementos más a la lista.
    
* 3. Implementa un menú mobile/desktop de bootstrap con las páginas: Home, Register, Ships y Login.
    * 3.0 - Utiliza las opciones de menú que proporciona bootstrap.
    * 3.1 - En función de si estás logueado o no, muestra las páginas a las que se tiene acceso. En el fichero app.js es
    * 3.1 - El menú debe estar oculto (menú hamburguesa) por defecto y abrirse tipo desplegable. 
    * 3.2 - En desktop debe estar en una línea.  
* 4. A la página starships añade  la maquetación adjunta a continuación de la tabla: MAQUETA_NICOLE.jpg
    * 4.1 La maqueta ha de ser responsive. Se adjunta diseño en mobile MAQUETA_NICOLE_MOBILE.png
    * 4.2 No es necesario implementar el play del vídeo de la imágen nº 5.
    * 4.3 Las imagenes han de tener un efecto hover como el que se muestra en la imágen: ejemplo_hover.png
    * 4.4 Los textos que aparecen en la imágen han de sert TEXTO y no imágen.


