#Taller Práctico 01: Ingeniería Inversa con XQuery y BaseX**

## Descripción

En este proyecto realizo una auditoría sobre un archivo XML que contiene información de infraestructura cloud. Para ello utilizo **XPath**, con el objetivo de extraer datos concretos de forma eficiente sin afectar al rendimiento del sistema.

## Contenido del repositorio

* **practica20260319.xml** → Archivo con los datos de la infraestructura
* **practica20260319.xsd** → Esquema de validación del XML
* **consultas_xpath.xbook** → Archivo con las consultas XPath realizadas
* **README.md** → Explicación del proyecto

## Herramientas utilizadas

* Visual Studio Code
* Extensión **XPath Notebook**
* Lenguaje **XPath**

## Objetivo

El **objetivo** de esta práctica es aprender a:

* Navegar por documentos XML
* Utilizar expresiones XPath
* Filtrar información mediante condiciones
* Obtener datos específicos de forma eficiente
* Repaso de expresiones regulares 

## Retos realizados

### **Reto 1:** 
Filtrado por contenido y estado. El departamento de desarrollo necesita actualizar su bibliografía sobre diseño. Obtén los títulos de todos los recursos cuya categoría sea 'CSS' y que, además, estén marcados como disponibles (true).
### **Reto 2:** 
Atributos y negaciones. No todos nuestros recursos son documentos estándar. Queremos identificar aquellos materiales que tienen un formato especial. Selecciona los ID (el atributo id) de todos los recursos cuyo formato no sea "PDF".
### **Reto 3:** 
Manejo de múltiples nodos (Autores). La colaboración es clave en la ciencia. Localiza y muestra únicamente el nombre del primer autor de aquellos recursos que han sido publicados después del año 2015.
### **Reto 4:** 
Consultas de complejidad técnica (Nivel y Categoría). Buscamos material para un seminario avanzado de arquitectura de datos. Necesitamos los títulos de los recursos que pertenezcan a las categorías de "XPath" o "XSLT" y que tengan un nivel de dificultad de 5.
