# Análisis de Planeación de Contenido — Saurylh Studio

Análisis de patrones en la planeación de contenido para redes sociales — qué formatos y objetivos se priorizan, y cómo se distribuyen a lo largo de la semana.

**Proyecto propio — datos reales de negocio** · Autora: Ana Luisa Herrera Hernández

## Objetivo

Entender qué formatos (Historia, Reel, Post, Carrusel) y objetivos (Comunidad, Alcance, Engagement, Autoridad, Conversión) se priorizan en la planeación de contenido de Saurylh Studio, mi propio estudio de diseño y desarrollo web, y cómo se distribuye esa planeación a lo largo de la semana.

## Fuente de datos

Base de datos de producción de Saurylh Studio (MySQL), con **247 publicaciones reales** planeadas entre agosto y diciembre de 2026. Los datos se extrajeron directamente mediante consultas SQL.

## Nota sobre el origen de los datos

La idea inicial de cada publicación se genera con apoyo de inteligencia artificial, pero después pasa por etapas de **análisis, corrección, y finalmente creación y publicación manual** — por lo que el formato y objetivo final de cada pieza reflejan decisiones humanas reales, no una asignación automática.

## Herramientas

- **SQL** — extracción de datos desde la base de producción
- **Excel** — construcción de tablas de resumen con fórmulas `COUNTIF` dinámicas (no valores fijos) y gráficas nativas

## Hallazgos principales

- **Historia domina por completo** el contenido planeado, con 153 de 247 publicaciones (**62%**) — muy por encima de Reel, Post, y Carrusel combinados
- El objetivo **"Comunidad" representa el 71%** de todo el contenido, mostrando una fuerte prioridad por la cercanía con la audiencia sobre metas de conversión o alcance puro
- **Miércoles y Jueves** concentran la mayor cantidad de contenido programado (44 cada uno), mientras que **Viernes** es el día con menos actividad planeada

## Archivo del proyecto

El archivo `analisis-contenido-saurylh.xlsx` está disponible en este repositorio — incluye la hoja de datos crudos (247 filas), y la hoja de resumen con fórmulas dinámicas y gráficas nativas de Excel.

## 🔗 Ver el proyecto completo

El caso de estudio completo está disponible en mi portafolio:
**[saurylhstudio.com/data/analisis-planeacion-contenido-saurylh](https://saurylhstudio.com/data/analisis-planeacion-contenido-saurylh)**
