# Track: Notionando el futuro

Categoria: Desafio de API de Notion

# Integración de Notion para la Sincronización de Asignaciones (INSA)

## Integrantes:

- Daniel Carreño
- Alexis Yafté
- Marco Antonio
- Gael Vivanco
- Israel Espidio

## Descripción general:

En nuestra propuesta se desarrollará una aplicacion intermediaria que hace uso de una integración de la API de Notion para la sincronización de las asignaciones de classroom creando páginas para cada una de ellas, mejorando la productividad escolar y previniendo posibles retrasos en un flujo de trabajo.

Esta propuesta tiene como objetivo mejorar la experiencia del usuario al integrar de manera más efectiva la plataforma de Notion con Clasroom y brindar funciones adicionales para mejorar la gestión de tareas y el seguimiento del rendimiento académico.

## Historia de Usuario:

Luis es un estudiante de la BUAP el cual es muy organizado y hace uso de la aplicación de Notion para mejorar su productividad como estudiante.
El tiene una organización mediante una tabla en Notion, en la cual almacena apuntes, notas de clase, tareas, proyectos, entre otros. Además, cuando se lleva a cabo una asignación en la plataforma de Classroom, Luis tiene que hacer una modificación en su tabla de Notion, para no olvidar realizar y entregar dicha asignacion.

Luis esta contento usando *Notion*, ya que lo ha ayudado en gran manera a mejorar su rendimiento escolar y personal, pero piensa que puede mejorarlo un poco mas…

Alguna mejora que le gustaria implementar seria:

- Vincular las asignaciones de Classroom a Notion.

---

## Objetivo General:

- Desarrollar una aplicación intermediaria entre los sistemas de Classroom y Notion, para la automatización y organizacion de asignaciones.

Objetivos Especificos:

- Implementar la API de Google Cloud para la obtención de datos sobre las asignaciones de una clase.
- Implementar la API de Notion para la creación de páginas para cada una de las asignaciones extraidas.

## Funcionalidades:

### 1. Vincular las asignaciones de Classroom con Notion

Se busca que cuando un profesor asigne una tarea en Classroom nuestra app intermediaria extraiga los datos de la asignación, para posteriormente enviarlo a Notion, el cual creará una pagina, en la cual se pueda realizar la tarea y/o se puedan cargar los archivos necesarios.
La parte más importante viene en que Notion tambien generará alertas o recordatorios para realizar la tarea, tomando en cuenta la fecha de vencimiento de la misma.

## Tecnologías:

- Python
- API Notion
- API Google Cloud

## Integraciones

- Classroom
- Notion
