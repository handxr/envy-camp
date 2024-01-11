# Prueba Técnica: Aplicación de Lista de Tareas en React

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

## Funcionalidades Avanzadas (Opcionales)

### Edición de Tareas
- Posibilidad de editar el título y la descripción de las tareas existentes.

### Filtrado de Tareas
- Opciones para filtrar las tareas (todas, activas, completadas).

### Persistencia de Datos
- Guardar las tareas en el local storage.

### Estilos y Responsividad
- Diseño básico

## Estructura Técnica

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