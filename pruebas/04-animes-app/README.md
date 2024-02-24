# Prueba técnica - Animes App

Esta aplicación es una prueba técnica diseñada para evaluar las habilidades en React. Consiste en una aplicación de animes simplificada que permite a los usuarios visualizar una lista de animes, acceder a su contenido detallado y añadirlos a favoritos.

## Nivel de Dificultad

Intermedio

## User Stories

1. **Visualizar Animes:** Como usuario, quiero ver una lista de animes para poder elegir cuál ver.

2. **Detalles del Anime:** Como usuario, quiero poder clickear en un anime para ver su contenido completo.

3. **Agregar a Favoritos:** Como usuario, quiero poder añadir un anime a favoritos para poder verlo más tarde.

4. **Buscar Animes:** Como usuario, quiero poder buscar animes por su nombre para encontrarlos más fácilmente.

5. **Paginación:** Como usuario, quiero ver solo un número limitado de resultados por página y poder navegar entre las diferentes páginas de resultados.


## Engineer Stories

1. **Crear Componente de Lista de Animes:** Como ingeniero, necesito diseñar un componente que muestre todas los animes disponibles.

2. **Implementar Paginación:** Como ingeniero, necesito agregar paginación al componente de lista de animes para mostrar solo un número limitado de resultados por página y permitir a los usuarios navegar entre las diferentes páginas de resultados.

3. **Implementar Búsqueda:** Como ingeniero, necesito agregar un campo de búsqueda al componente de lista de animes para permitir a los usuarios buscar animes por su nombre.

4. **Implementar Navegación:** Como ingeniero, debo implementar la navegación entre la lista de animes y su detalle utilizando React Router.

5. **Gestionar Favoritos:** Como ingeniero, necesito implementar una forma para que los usuarios puedan añadir y visualizar animes en favoritos utilizando el [Context API](https://react.dev/reference/react/useContext) de React.

6. **Custom Hooks:** Como ingeniero, debo utilizar custom hooks para encapsular la lógica de negocio y mantener los componentes lo más simples posible.

7. **Aplicar Estilos:** Como ingeniero, debo aplicar estilos CSS para mejorar la experiencia del usuario. Solo se permite el uso de CSS puro.

## Stack Tecnológico

- [React](https://reactjs.org/)
- [React Router](https://reactrouter.com/)

## Requisitos del Código

Es obligatorio el uso de las siguientes herramientas para asegurar la calidad y consistencia del código:

- **ESLint:** Para garantizar un estilo de codificación consistente y evitar errores comunes. Debe configurarse siguiendo las mejores prácticas estándar de la comunidad de React.
- **Prettier:** Para formatear automáticamente el código. Se espera que todos los archivos del proyecto estén formateados utilizando Prettier.

Estas herramientas ayudan a mantener un alto estándar de calidad en el código y son esenciales para el trabajo en equipo y la escalabilidad del proyecto.

## Integración con la API REST

Esta aplicación consume datos de una API REST para obtener los animes. La API utilizada es `jikan` y puede ser encontrada [aquí](https://docs.api.jikan.moe/).

Nota: Asegúrate de revisar la documentación de la API para entender completamente cómo interactuar con ella.

## Recomendaciones

- **Metodología BEM:** Se recomienda utilizar la metodología BEM para nombrar las clases CSS y mantener un estilo de codificación consistente. Puedes encontrar más información sobre BEM [aquí](http://getbem.com/naming/).
