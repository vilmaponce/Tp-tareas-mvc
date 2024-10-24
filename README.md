

# API de Gestión de Tareas
#### Este proyecto es una API RESTful desarrollada con Node.js y Express que permite gestionar tareas. La API permite crear, leer, actualizar y eliminar tareas (CRUD), y persiste los datos en un archivo de texto (tareas.txt).

## Funcionalidades
**Obtener todas las tareas: Lista todas las tareas almacenadas.**
**Obtener una tarea por ID: Recupera los detalles de una tarea específica.**
**Crear una nueva tarea: Permite agregar una nueva tarea con título, descripción y estado de completado.**
**Actualizar una tarea: Permite modificar los datos de una tarea existente.**
**Eliminar una tarea: Elimina una tarea específica por su ID.**

#### Endpoints de la API
##### 1. Obtener todas las tareas
#### Método: GET
URL: /tareas
Descripción: Retorna una lista de todas las tareas.
2. Obtener una tarea por ID
#### Método: GET
URL: /tareas/:id
Descripción: Retorna una tarea específica por su ID.
3. Crear una nueva tarea
#### Método: POST
URL: /tareas
4. Actualizar una tarea
#### Método: PUT
URL: /tareas/:id
Uso en Postman
Puedes realizar peticiones a la API utilizando Postman con los siguientes endpoints:

*GET /tareas - Obtener todas las tareas*
*GET /tareas/:id - Obtener una tarea específica*
*POST /tareas - Crear una nueva tarea*
*PUT /tareas/:id - Actualizar una tarea*
*DELETE /tareas/:id - Eliminar una tarea*

## Dependencias
Node.js: Entorno de ejecución de JavaScript.
Express: Framework para manejar las rutas HTTP.
fs: Módulo nativo para manejar archivos del sistema.
# Licencia
Este proyecto está bajo la Licencia MIT.
