# Vue.js Simple CRUD - Todo List

Este es un proyecto de CRUD (Create, Read, Update, Delete) simple, creado para practicar conocimientos de Vue.js. Es una aplicación de lista de tareas (Todo List) en la que puedes agregar, actualizar y eliminar tareas, además de organizarlas por categoría.

## Características

- **Añadir Tareas**: Los usuarios pueden agregar nuevas tareas con un título y una categoría (Business o Personal).
- **Categorías Personalizadas**: Las tareas se pueden clasificar en categorías y cada una tiene un color distintivo.
- **Completar Tareas**: Las tareas pueden marcarse como completadas, lo que las tacha de la lista.
- **Eliminar Tareas**: Las tareas pueden eliminarse de la lista.
- **Persistencia Local**: La lista de tareas y el nombre del usuario se almacenan en `localStorage`, por lo que los datos se mantienen incluso después de cerrar el navegador.

## Tecnologías Utilizadas

- **Vue.js**: Framework frontend utilizado para desarrollar la funcionalidad de la lista de tareas.
- **Vite**: Herramienta utilizada para la creación del proyecto de Vue.js.
- **CSS personalizado**: Estilos personalizados para darle una apariencia clara y moderna a la aplicación.

## Instrucciones de Instalación

1. **Clonar el repositorio**:
   ```bash
   git clone <URL del repositorio>
   cd <nombre-del-repositorio>

2. **Instalar dependencias**:
   ```bash
   npm install

3. **Ejecutar la aplicación**:
   ```bash
   npm run dev

## Estructura de Archivos
- main.js: Archivo de configuración de Vue.js y montaje de la aplicación.
- App.vue: Componente raíz que contiene la estructura de la aplicación.
- Todo List Components: Contiene los métodos y la lógica de Vue.js para añadir, actualizar, eliminar, y completar tareas.
CSS personalizado: Los estilos están definidos en el archivo .vue y variables CSS en la raíz del proyecto para consistencia de colores y efectos de sombras.

## Notas sobre el Proyecto
- Este proyecto se desarrolló con fines de aprendizaje en Vue.js, por lo que carece de conexión a una base de datos.
- La persistencia de datos es manejada localmente con localStorage, lo que permite mantener la lista de tareas hasta que se borre el almacenamiento del navegador.
- La interfaz está diseñada para ser minimalista y fácil de navegar.