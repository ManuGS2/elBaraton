	EL BARATÓN v1.0

Proyecto desarrollado por:
	JOSÉ EMMANUEL GUZMÁN SÁNCHEZ. 
	https://github.com/ManuGS2
	emaguzsan@gmail.com

Todos los archivos necesarios para la ejecución de este proyecto sen ecuentran en la carpeta que contiene al mismo.
En la carpeta del proyecto se encontrará con lo siguiente:

Archivos

	* README.txt: Archivo con la descripción e instrucciones para ejecutar el proyecto.	
	* index.html: El archivo fuente de nuestro proyecto
	* challenge.pdf: Archivo con la descripción del problema
	
Carpetas
	
	* css:	Carpeta que contiene las hojas de estilo utilizadas para el proyecto y de jQuery UI v1.12.1
	* js:	Carpeta que contiene el framework de jQuery v3.3.1
	* fonts: Carpeta que contiene las fuentes utilizadas
	* json:	Carpeta que contiene los datos necesarios de la tienda
	* img:	Carpeta con las imagenes utilizadas en el proyecto

Para poder ejecutarlo es necesario hacerlo desde un servidor. Si no se cuenta con uno se puede correr desde un servidor local.
Para hacerlo se puede apoyar del módulo SimpleHTTPServer que nos provee Python.

Pasos para correr un servidor local con Python.

	1. Instalar Python en su versión 3.xx
	2. Abril la linea de comandos y posicionarse en la carpeta principal del proyecto
	3. Ejecutar el siguiente comando:
		Para Mac y Linux: python -m SimpleHTTPServer
		Para Windows:	  python -m http.server
	
	Por defecto el servidor local se ejecutará en el puerto 8000
	Para acceder al servidor abra su navegador preferido e ingrese la siguiente URL
		localhost:8000
	Una vez hecho esto en su navegador podrá ver el proyecto desarrollado y funcionando.

FUNCIONAMIENTO DE LA PÁGINA

	En la ventana principal se muestra un entrada en donde se podrá buscar algun producto por su nombre. Si hay coincidencias
	se irá a la ventana de "Productos" y desplegará la sección que contiene al producto seleccionado. Si no se encuentran coicindencias
	se mostrará un mensaje indicandolo y se podrá navegar a través de las categorias.

	En la ventana de productos se muestran las categorías disponibles y los productos de dichas categorías, los cuales se pueden agregar al
	carrito presionando el icono naranja que está detro de cada uno. Esto lo guardará en el carrito.
	Además, se muestran dos menús que permiten filtrar y ordenar los productos de acuerdo a su precio, número en stock, disponibilidad y
	subnivel al que pertenecen.

	En la sección del carrito se muestran todos los productos que se agregaron al mismo. Para poder mantenerlos en la sesión del usuario
	aún cerrando el navegador opté por usar el almacenamiento local para guardar los datos necesarios de cada producto.
	Se puede seleccionar la cantidad de elementos y también se puede eliminar un elemento del carrito si se desea.
	Al final se muestra un botón que simula la realización del pago de los productos que está en el carrito. Presionando este botón elimina
	a todos los productos del carrito.




