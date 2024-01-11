# Prueba Técnica: Aplicación de Lista de Tareas en React (Básica)

## Descripción

Esta es una prueba técnica básica diseñada para evaluar las habilidades de un desarrollador en React y TypeScript. El objetivo es crear una aplicación de lista de tareas con funcionalidades básicas como visualizar, agregar, marcar como completadas y eliminar tareas.

## Nivel de Dificultad

Básico

## Funcionalidades Básicas

### Visualizar Tareas
- Mostrar una lista de tareas.
- Cada tarea debe tener un título y, opcionalmente, una descripción.

### Agregar Nuevas Tareas
- Un formulario para ingresar el título y la descripción de la nueva tarea.
- Un botón para añadir la tarea a la lista.

### Marcar Tareas como Completadas
- Opción para marcar una tarea como completada (por ejemplo, un checkbox).
- Las tareas completadas pueden mostrarse de manera diferente (e.g., texto tachado).

### Eliminar Tareas
- Botón para eliminar tareas individuales de la lista.

### Eliminar tareas completadas
- Función para eliminar de la lista y el storage las tareas completadas.

### Persistencia de Datos
- Guardar las tareas en el local storage.

### Estilos y Responsividad
- Diseño básico

## Estructura Técnica

### Lenguaje
- TypeScript

### Componentes
- Un componente para el formulario de añadir tareas.
- Un componente para mostrar cada tarea.
- Un componente para la lista de tareas, que utiliza el componente de tarea individual.

### Estado y Manejo de Datos
- Uso de `useState` para manejar el estado de la lista de tareas.
- Uso de `useEffect` para cargar/guardar tareas del almacenamiento local.

### Manejo de Eventos
- Funciones para manejar la adición, eliminación, y marcado de tareas como completadas.

### Estilos
- Uso de CSS Vanilla.

### Wireframe
![image](https://github.com/handxr/envy-academy/assets/88827764/e3aeb3d5-3279-4f2b-82eb-b58c9569cc5a)

