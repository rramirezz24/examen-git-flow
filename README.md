Lista de Tareas (To-Do List)
Aplicación web interactiva y minimalista para la gestión de tareas diarias, desarrollada con tecnologías web nativas (HTML5, CSS3 y JavaScript vainilla). Permite organizar pendientes de manera visual, dinámica y eficiente directamente desde el navegador.

Características Principales
Creación Dinámica: Agrega nuevas tareas escribiendo en el campo de texto y haciendo clic en el botón con el símbolo +.

Gestión Activa: Cada tarea en curso cuenta con controles rápidos e intuitivos para editar, borrar o tachar (completar).

Sección de Completados: Al tachar una tarea, esta se reubica automáticamente en un contenedor independiente para elementos finalizados.

Restauración y Eliminación: Las tareas tachadas pueden ser destachadas (regresarlas a pendientes) o eliminadas permanentemente.

Tecnologías Utilizadas
HTML5: Estructura semántica de la interfaz de usuario.

CSS3: Diseño responsivo, estilos modernos, tipografía y distribución visual de los contenedores de tareas.

JavaScript (ES6+): Manipulación del DOM, gestión de eventos y lógica de estado para las acciones de añadir, editar, tachar, destachar y borrar.

Estructura del Proyecto
El repositorio está compuesto por los siguientes archivos esenciales:

├── index.html    # Estructura principal de la interfaz y contenedores
├── style.css     # Estilos visuales, diseño y disposición de elementos
└── script.js     # Lógica de la aplicación y manipulación del DOM

Guía de Instalación y Uso
1. Clonar o descargar este repositorio en tu computadora:

git clone https://github.com/rramirezz24/examen-git-flow.git

2. Abrir el proyecto en tu editor de código preferido (como Visual Studio Code).

3. Ejecutar la aplicación: Abre el archivo index.html directamente en cualquier navegador web moderno (Google Chrome, Firefox, Edge, etc.).

Instrucciones de Uso
Escribe tu pendiente en el campo de texto (input) superior.

Haz clic en el botón + para añadir la tarea a la lista de pendientes activos.

Utiliza los iconos situados al lado de cada tarea para:

✏️ Editar: Modifica el texto de la tarea.

✅ Tachar: Marca la tarea como completada (se moverá automáticamente al div de tareas tachadas).

🗑️ Borrar: Elimina la tarea por completo.

En el contenedor de tareas tachadas, puedes hacer clic en destachar para regresarlas a pendientes o eliminarlas definitivamente.
