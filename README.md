# Taller Práctico 01: Ingeniería Inversa con XQuery y BaseX

## Descripción

En este proyecto realizo una práctica de ingeniería inversa sobre un archivo XML utilizando el lenguaje XQuery y el entorno BaseX.

El objetivo consiste en construir consultas FLWOR capaces de generar resultados concretos a partir de un XML dado (biblioteca.xml), sin modificar su estructura, aplicando lógica de filtrado, agregación y transformación de datos.

## Contenido del repositorio

- biblioteca.xml → Archivo XML con los datos de libros  
- consultas.xq → Consultas XQuery desarrolladas (retos)  
- README.md → Documentación del proyecto  

## Herramientas utilizadas

- Visual Studio Code  
- BaseX (gestor de bases de datos XML)  
- Lenguaje XQuery  

## Objetivo

El objetivo de esta práctica es aprender a:

- Utilizar consultas FLWOR (For, Let, Where, Order by, Return)  
- Filtrar información en documentos XML  
- Aplicar funciones como count(), number() o distinct-values()  
- Generar resultados en formato XML y HTML  
- Manejar correctamente el entorno BaseX  

## Retos realizados

### Reto 1: Filtro y ordenación
Obtener los títulos de los libros de la categoría "programacion" cuyo precio sea superior a 30€, ordenados de forma descendente por título.

### Reto 2: Agregación con LET
Generar un informe mostrando cuántos libros tiene cada autor, filtrando únicamente aquellos autores con más de un libro.

### Reto 3: Transformación a HTML
Construir una lista HTML (<ul>) con todos los libros, indicando "¡Novedad!" en aquellos publicados después de 2022, incluyendo el precio en euros.

## Conclusión

Este taller permite pasar de simplemente leer XML a buscar la información de forma profesional, desarrollando consultas eficientes y estructuradas a tráves de XQuery.
