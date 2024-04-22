# objetos_js


## Document

El objeto "document" en JavaScript es una parte fundamental del modelo de objetos del navegador. Representa el documento HTML cargado en una ventana o marco y proporciona una interfaz para interactuar y manipular dicho documento.


El objeto "document" ofrece una amplia gama de propiedades y métodos para acceder y modificar elementos HTML, estilos, eventos y más. Algunos de los métodos y propiedades más comunes incluyen:


- `getElementById()`: Permite acceder a un elemento HTML utilizando su atributo "id". Por ejemplo, document.getElementById("miElemento") devuelve el elemento con el id "miElemento".

- `getElementsByTagName()`: Retorna una lista de elementos que coinciden con el nombre de la etiqueta especificada. Por ejemplo, document.
- `getElementsByTagName("p")`: devuelve una lista de todos los elementos de párrafo en el documento.

- `createElement()`: Crea un nuevo elemento HTML especificado por su etiqueta. Por ejemplo, document.createElement("div") crea un nuevo elemento de división.

- `innerHTML`: Permite acceder y modificar el contenido HTML dentro de un elemento. Por ejemplo, document.getElementById("miElemento").   
- `innerHTML` = "Nuevo contenido" establece el contenido del elemento con id "miElemento" como "Nuevo contenido".

- `addEventListener()`: Permite asignar un controlador de eventos a un elemento HTML. Por ejemplo, `document.getElementById("miBoton")`. 
- `addEventListener("click", miFuncion)` asigna la función "miFuncion" al evento de clic del elemento con id "miBoton".


Estos son solo algunos ejemplos de cómo el objeto "document" se utiliza para interactuar con el contenido HTML en JavaScript. Es una herramienta que sirve para manipular y controlar la estructura y el comportamiento de una página web.