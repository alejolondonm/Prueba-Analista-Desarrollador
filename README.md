# Prueba Técnica – Analista Desarrollador
**Autor:** Luis Alejandro Londoño Martínez  
**Vacante:** Analista de Sección Evolución Operación Financiación (Junior)  
**Fecha:** 12-11-2025

## Descripción General
El objetivo es realizar un proceso completo de carga, limpieza, transformación y análisis de un archivo de ventas, y generar un archivo Excel final con los resultados consolidados.  

El desarrollo fue realizado en un **Jupyter Notebook**, siguiendo buenas prácticas de análisis de datos y versionamiento con Git.


## Archivos Incluidos

- **Notebook_PT.ipynb:** Desarrollo completo de la prueba  
- **datos_ventas.xlsx:** Archivo de datos original  
- **resumen_ventas.xlsx:** Archivo final generado con el resumen  
- **README.md:** Documentación de la prueba  

## Objetivos

1. Cargar los datos desde un archivo Excel.  
2. Realizar limpieza y validación de tipos de datos.
3. Seleccionar únicamente las columnas necesarias.
4. Completar valores nulos en la columna **Total_Venta** usando la fórmula: ***Cantidad x Precio_Unitario***.  
5. Convertir la columna **Fecha** a formato datetime.  
6. Filtrar las ventas del año **2023**.  
7. Crear una columna **Mes** extraída de la fecha.  
8. Calcular:
   - Total de ventas por **vendedor**  
   - Total de ventas por **mes**  
9. Generar un archivo Excel final con dos hojas:
   - **Resumen_Ventas**  
   - **Ventas_Mensuales**  
10. Subir los cambios al repositorio con sus respectivos commits.
