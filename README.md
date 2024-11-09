# Proyecto Biblioteca en HTML, CSS y JavaScript

Este proyecto es una aplicación web que permite consultar y mostrar libros en una biblioteca. Utiliza un servidor local con Node.js para simular una API que devuelve información sobre libros y sus autores.

Debido a que el enlace de la API sugerido en el planteamiento del laboratorio no funciona, se creo una API para ejecutar en servidor local, teniendo en cuenta la informacion obtenida del video de la clase, 
cuando el instructor logro acceder a dicha API durante la explicacion de la actividad.

## Características del Proyecto

- **HTML**: Estructura de la página.
- **CSS**: Estilos de la página.
- **JavaScript**: Consulta a la API y visualización de los datos en una tabla.
- **Servidor Local**: Implementado en Node.js para simular una API REST.

## Estructura del Proyecto

- `index.html`: Página principal con la estructura HTML.
- `styles.css`: Archivo de estilos CSS.
- `script.js`: Archivo JavaScript que maneja la consulta a la API.
- `BibliotecaAPI/`: Contiene los archivos del servidor en Node.js para la API simulada.

## Configuración del Servidor Local

1. **Instalar dependencias**: Módulos necesarios (Express y CORS). Ya estan cargados los modulos dentro de `BibliotecaAPI`
2. **Ejecutar el servidor**: Ejecuta `node server.js` dentro de `BibliotecaAPI` para iniciar el servidor en `http://localhost:3000`.

## Endpoints de la API

La API cuenta con el siguiente endpoint para obtener los datos de los libros y autores:

- **GET `/api/autor/getLibAut`**: Devuelve un objeto JSON con una lista de libros.

Cristian Orlando Mercado Perilla
Laboratorio 2 - Full Stack Basico
TalentoTech
