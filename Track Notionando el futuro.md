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

En nuestra propuesta se desarrollará un microservicio que hace uso de una integración de la API de Notion para la sincronización de las asignaciones de Classroom, creando tablas para la gestion de materias y asignaciones mediante páginas para cada una de ellas, mejorando la productividad escolar y previniendo posibles retrasos en un flujo de trabajo.

Esta propuesta tiene como objetivo mejorar la experiencia del usuario al integrar de manera más efectiva la plataforma de Notion con Classroom y brindar funciones adicionales para mejorar la gestión de tareas y el seguimiento del rendimiento académico.

## Historia de Usuario:

Ivan es un estudiante que tiene problemas para mantener una organización escolar adecuada, esto le ha provocado que tenga un bajo rendimiento academico al no poder cumplir con todas las asignaciones que tiene pendientes. Aunque su escuela hace uso de la plataforma de Google Classroom este no es suficiente para que Ivan tenga una gestión de sus asignaciones, calificaciones y progreso en la materia.

Ivan esta empezando a usar Notion para llevar un control, sin embargo, piensa que aun no esta preparado para lograr mejorar su rendimiento.

## Objetivo General:

- Desarrollar un microservicio entre Google Classroom y Notion para la sincronización de materias y asignaciones, logrando su gestión eficiente mediante tablas y páginas así implementar herramientas de inteligencia artificial para mejorar el rendimiento académico, facilitando la gestión escolar.

Objetivos Especificos:

- Implementar la API de Google Cloud para la obtención de datos sobre las asignaciones y materias de una clase en Google Classroom.
- Implementar la API de Notion para la creación de tablas y páginas para cada una de las materias y asignaciones extraidas de Google Classroom.
- Implementar la API de Notion para la creación de alertas y recordatorios de las asignaciones extraidas de Google Classroom.
- Implementar la herramienta de Inteligencia Artificial integrada en Notion para la creación de consejos y guias de estudio en la gestión de asignaciones.

## Funcionalidades:

### Vincular materias y asignaciones de Classroom con Notion

Se busca que el usuario de Notion vincule su cuenta de Google Classroom para que nuestro microservicio sea capaz de extraer la información de materias y asignaciones. Para posteriormente enviar esa información a Notion, el cuál creará tablas para gestionar las materias y páginas individuales accesibles para cada una de las materias, así mismo con las asignaciones dentro de una materia.

### Creación de alertas y recordatorios

Con la información de la fecha de entrega extraida de las asignaciones de Google Classroom generar alertas y recordatorios automáticos para obtener notificaciones antes de la fecha de vencimiento de asignaciones.

### Uso de la Inteligencia Artificial en la gestión de asignaciones

Utilizando la Inteligencia Artificial nuestro microservicio analizará los patrones de estudio y rendimiento de cada usuario en sus asignaciones. La IA evaluará factores como el tiempo que el usuario tarda en completar las tareas, las horas del día en las que el usuario es más productivo, y el rendimiento académico del usuario en diferentes materias. Con estos datos, la IA generará consejos y sugerencias personalizadas para ayudar al usuario a mejorar su gestión de las asignaciones. Estos consejos y sugerencias se presentarán en forma de recordatorios o guías de estudio, y estarán diseñados para ayudar al usuario a optimizar su tiempo de estudio, mejorar su comprensión del material, y en última instancia, mejorar su rendimiento académico.

## Tecnologías:

- API Notion
- API Google Cloud
- JavaScript

## Integraciones

- Classroom
- Notion

## Arquitectura

Microservicio

## Seguridad

Hacer uso de las herramientas proporcionadas por la API de Google Cloud como Oauth que sirve para iniciar sesión con Google y así tener una forma de conexion más segura.

- Mantener el software de la API actualizado.

20 de abril de 2024 7:30 entregar el trabajo a las 7:30pm