# **Manual de Tailwind CSS**

El repositorio tiene el manual de Tailwind y el ejemplo que se realiza para la práctica.

La página que se ha hecho es una tienda de videojuegos online llamada GameStore, donde aparecen tres juego con su descripción, precio y un botón para añadirlos al carrito, aunque no tienen su JavaScript implementado.



##### Requisitos previos

Para poder ejecutar el proyecto se necesita:

* Node.js, que tiene npm para instalar las herramientas necesarias.
* Visual Studio Code.
* Un navegador como Chrome o Firefox.



##### Instalación y ejecución

Primero hay que abrir una terminal dentro de la carpeta del proyecto. Comprobamos que Node.js esté instalado:

**"node -v"**

Luego preparamos el proyecto poniendo:

**"npm init -y"**

Después instalamos las dependencias del proyecto:

**"npm install tailwindcss @tailwindcss/cli"**

Esto instalará Tailwind CSS y las demás dependencias necesarias que aparecen en package.json.



##### Generar el CSS

Para generar el archivo CSS que utiliza la página hay que ejecutar:

**"npm run build"**

Este comando utiliza Tailwind para coger el archivo:

**"src/input.css"**

y generar:

**"dist/output.css"**

El archivo output.css es el que utiliza el HTML para aplicar los estilos de Tailwind.



##### Ejecutar el ejemplo

Una vez generado el CSS, se puede abrir el archivo:

**"index.html"**

con un navegador.

Si se realizan cambios en las clases de Tailwind, hay que volver a ejecutar:

**"npm run build"** 

para volver a generar el archivo output.css

