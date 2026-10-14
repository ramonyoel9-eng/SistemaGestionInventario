# Sistema de Gestión de Inventario

## 1. Descripción del sistema

El Sistema de Gestión de Inventario es un proyecto de software diseñado para facilitar el registro, control y consulta de los productos de un negocio, permitiendo organizar las existencias y los movimientos de mercancía.

## 2. Objetivo

Desarrollar un sistema que permita administrar la información del inventario de manera organizada, reducir errores en los registros y facilitar el seguimiento de los productos.

## 3. Problema que resuelve

El control manual del inventario puede generar errores en las cantidades registradas, pérdida de información y dificultades para conocer las existencias disponibles. Este sistema busca mejorar la organización y el control de esos procesos.

## 4. Funcionalidades principales

- Registro y consulta de productos.
- Gestión de proveedores.
- Registro de entradas de mercancía.
- Registro de salidas de mercancía.
- Consulta de existencias.
- Organización de la información del inventario.

Las funcionalidades deben verificarse en el código para determinar cuáles están implementadas actualmente.

## 5. Arquitectura seleccionada

Se propone una arquitectura por capas compuesta por:

- **Capa de presentación:** contiene los formularios y controles con los que interactúa el usuario.
- **Capa de lógica de negocio:** procesa las operaciones y valida la información.
- **Capa de acceso a datos:** realiza las consultas y operaciones sobre la base de datos.
- **Base de datos:** almacena los productos, proveedores y movimientos del inventario.

## 6. Organización frontend y backend

### Frontend

El frontend corresponde a la interfaz de usuario. En la aplicación de escritorio, esta función se realiza mediante Windows Forms, con formularios para introducir datos, consultar productos y gestionar las operaciones del inventario.

### Backend

El backend comprende la lógica de negocio y el acceso a datos. Se encarga de validar la información, procesar las solicitudes y gestionar la comunicación con la base de datos.

### Comunicación entre frontend y backend

Cuando el usuario realiza una operación desde un formulario, la aplicación procesa los datos mediante la lógica correspondiente. Después, la capa de acceso a datos consulta o actualiza SQL Server y devuelve el resultado para mostrarlo en la interfaz.

Esta separación permite organizar mejor el código y facilita el mantenimiento del sistema.

## 7. Herramientas utilizadas

- C# y Visual Studio.
- Windows Forms.
- Microsoft SQL Server o SQL Server Express.
- Git para el control de versiones.
- GitHub para alojar el repositorio.
- GitHub Issues para el seguimiento de incidencias.
- GitHub Projects para organizar las tareas.
- UML y Visual Paradigm para el modelado del sistema.

## 8. Control de versiones y seguimiento

Git permite registrar los cambios realizados en los archivos del proyecto. GitHub conserva el repositorio remoto, mientras que Issues y Projects permiten organizar las incidencias, mejoras y tareas pendientes.

## 9. Estado actual del proyecto

El proyecto se encuentra en fase de documentación y organización técnica. Se está consolidando la información sobre los requisitos, los modelos UML, la arquitectura, el seguimiento de tareas y los cambios realizados.

El estado real de cada funcionalidad deberá confirmarse mediante la revisión del código y las evidencias del proyecto.

## 10. Próximos pasos

- Completar y revisar la documentación técnica.
- Verificar las funcionalidades implementadas.
- Revisar las incidencias y tareas pendientes.
- Actualizar el tablero de GitHub Projects.
- Registrar los cambios mediante Git.
- Preparar una versión documentada del sistema.
