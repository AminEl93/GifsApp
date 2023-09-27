# GifsApp

Esta aplicación consiste en un buscador de Gifs de cualquier ámbito con persistencia local. Se ha generado con la versión 16.0.0 de [Angular CLI](https://github.com/angular/angular-cli), con la versión 18.16.0 de NodeJS y con la versión 9.6.6 de npm.

## Iniciar la aplicación

Ejecutar el comando `npm start` y acceder a la URL `http://localhost:4200/`.

## Obtención de la información de la API

Se ha de acceder a la página de [GIPHY Developers](https://developers.giphy.com). En la cuenta personal, clicar en el botón `Create an App`, seleccionar `Select API` y automáticamente se generará una **API Key** que se tendrá que añadir a la URL `https://api.giphy.com/v1/gifs/search?api_key=API_KEY&q=TEXTO_A_BUSCAR`.

Los gifs que se generan al buscarlos tienen muchos campos. Por eso, la mejor herramienta para crear la interfaz es con [Quicktype](https://app.quicktype.io). Su función es que se le pasa un JSON (por ejemplo, obtenido desde la consola del navegador) y los transforma automáticamente en los tipos de TypeScript que se desea.