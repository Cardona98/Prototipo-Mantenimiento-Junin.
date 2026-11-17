# Sistema de Información Web para la Gestión de Solicitudes de Mantenimiento

## Instituciones Educativas de Junín, Cundinamarca

### Proyecto de Grado - Ingeniería de Sistemas
### Universidad Nacional Abierta y a Distancia - UNAD
### Curso: Proyecto de Grado - Código: 202016907
### Fase 4 - Información general del componente practico

---

## Autoras

| Nombre | Rol en Scrum |
| --- | --- |
| Jeny Michelle Cardona Nuñez | Product Owner / Desarrolladora |
| Angie Paola Castañeda Murillo | Scrum Master / Desarrolladora |

## Descripción del Proyecto

Este prototipo funcional fue desarrollado para mejorar la gestión de solicitudes de mantenimiento en las instituciones educativas del municipio de Junín, Cundinamarca.

Actualmente el proceso se realiza de forma manual, en papel o por mensajes, lo que genera pérdida de información, demoras y falta de seguimiento. Con este sistema, las solicitudes quedan registradas en un solo lugar, se pueden clasificar, asignar, consultar y generar reportes.

**Nivel de maduración tecnológica: TRL5** - Prototipo validado en ambiente relevante.

## Objetivo

Desarrollar un prototipo funcional TRL5 que permita registrar, clasificar, asignar, hacer seguimiento y generar reportes de las solicitudes de mantenimiento.

## Tecnologías Utilizadas

- **Lenguaje:** HTML, CSS, JavaScript, Python
- **Base de datos:** MySQL (en versión de demostración se usa almacenamiento local para facilitar la prueba)
- **Control de versiones:** GitHub
- **Metodología:** Scrum + Kanban + CDIO
- **Diseño:** Figma / HTML

## Metodología Ágil - Scrum

El desarrollo se organizó en 4 Sprints:

| Sprint | Objetivo | Entregable |
| --- | --- | --- |
| Sprint 1 | Diseño y base de datos | Modelo ER, arquitectura, interfaces |
| Sprint 2 | Módulo de usuarios y registro | Login por roles + Formulario de registro |
| Sprint 3 | Clasificación, asignación y seguimiento | Listado, cambio de estado, asignación |
| Sprint 4 | Reportes, historial y pruebas | Módulo de reportes, pruebas y correcciones |

**Tablero Kanban:** Por Hacer / En Proceso / En Prueba / Terminado

## Funcionalidades del Prototipo

- Inicio de sesión por roles
- Registro de solicitudes de mantenimiento
- Clasificación por tipo: Infraestructura, Eléctrico, Mobiliario, Plomería, Otro
- Priorización: Alta, Media, Baja
- Asignación de responsable
- Actualización de estado: Pendiente, En Proceso, Atendida, Cerrada
- Consulta e historial de solicitudes
- Generación de reportes por estado, tipo y prioridad

## Cómo Probar el Prototipo

### Opción 1 - En línea (la más fácil)
Abre este link en tu navegador:
**https://Cardona98.github.io/prototipo-mantenimiento-junin/**


### Opción 2 - Descargando el archivo
1. Descarga el archivo `index.html`
2. Ábrelo con doble clic en tu navegador (Chrome, Edge, Firefox)
3. ¡Listo! No necesitas instalar nada.

## Usuarios de Prueba

Para probar los diferentes roles, usa estos usuarios:

| Rol | Correo | Contraseña |
| --- | --- | --- |
| Administrador | admin@junin.edu.co | 1234 |
| Responsable | resp@junin.edu.co | 1234 |
| Solicitante | user@junin.edu.co | 1234 |

## Cómo Hacer una Prueba Completa

1. Ingresa como **Solicitante** (user@junin.edu.co / 1234)
2. Registra una solicitud: Ej: "Daño en el salón 3, toma corriente no funciona"
3. Cierra sesión e ingresa como **Administrador** (admin@junin.edu.co / 1234)
4. Busca tu solicitud en el listado y dale clic en **Cambiar Estado** a **En Proceso**
5. Revisa el **Reporte Rápido** y el **Historial**
6. Se vera como el flujo completo funciona: Registrar -> Clasificar -> Asignar -> Actualizar -> Cerrar

## Estructura del Proyecto
