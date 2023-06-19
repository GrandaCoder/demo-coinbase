# Demostración de una página web con HTML, CSS y SASS

Este proyecto es una demostración de cómo crear una página web utilizando HTML, CSS y SASS. A continuación, se describen los pasos para replicar este proyecto.

## Requisitos

- Editor de texto, como Visual Studio Code, Sublime Text o Atom.
- Git
- NPM
- SASS instalado globalmente en tu sistema. Para instalar SASS, ejecuta `npm install -g sass` en tu terminal.

## Pasos a seguir

1. **Clonar el repositorio**

    Clona este repositorio en tu máquina local utilizando `git clone`. Usa el enlace del repositorio en el lugar de 'LINK':

    ```
    git clone LINK
    ```

2. **Instalar las dependencias**

    Navega hasta el directorio del repositorio en tu sistema y ejecuta el siguiente comando para instalar las dependencias necesarias:

    ```
    npm install
    ```

3. **Compilar SASS**

    SASS es un preprocesador de CSS que te permite usar características que no existen en el CSS puro, como la herencia, las variables, los mix-ins y más. Pero los navegadores no entienden el código SASS, por lo que debes "compilar" tu código SASS en CSS estándar.

    Para hacer esto, ejecuta el siguiente comando:

    ```
    sass --watch ./sass/index.scss  ./css/styles.css
    ```

5. **Visualizar el proyecto**

    Ahora puedes abrir el archivo `index.html` en tu navegador para ver tu proyecto en acción.

## Descripción de los archivos

- `/scss`: Este directorio contiene todos los archivos `.scss` que se compilarán en CSS. En este caso, `index.scss` es tu archivo principal que importa los otros archivos SCSS, `_components.scss` y `_globals.scss`.

- `scss/index.scss`: Este es el archivo "principal" que importa todos los demás archivos SCSS. Cuando ejecutas el comando `sass`, este es el archivo que SASS mirará.

- `/css`: Este directorio contiene los archivos CSS que se generarán cuando compiles tu código SASS. El archivo `styles.css` es el resultado de la compilación de `index.scss`.

- `index.html`: Este es el archivo HTML principal para tu proyecto.

- `README.md`: Este archivo (el que estás leyendo ahora) te da una visión general de tu proyecto.

## Conclusión

Este proyecto es un excelente punto de partida para familiarizarte con HTML, CSS y SASS. Sigue las instrucciones paso a paso para configurar el proyecto en tu sistema local y aprender más sobre cómo se estructuran y organizan los proyectos de desarrollo web.
