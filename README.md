# Alura Store Latam - Challenge

Este proyecto contiene un análisis de datos para varias tiendas de la cadena Alura Store. A través de la exploración y visualización de los datos, se busca identificar patrones de ventas, calificaciones de los clientes y otros factores clave para tomar decisiones sobre el rendimiento de cada tienda.

## Contenido

1. **Importación de Datos**  
   - Lectura de archivos CSV en formato pandas.  
   - Librerías principales utilizadas: `pandas`, `matplotlib`, `folium`.

2. **Análisis Exploratorio**  
   - Descripción rápida de cada tienda (`DataFrame.describe()` e `info()`).  
   - Identificación de valores faltantes.  
   - Cálculo de facturación total, calificación promedio, productos más y menos vendidos, y costo de envío promedio por tienda.

3. **Visualizaciones**  
   - Gráficos de líneas, pie charts, radar, histogramas bidimensionales (heatmaps) y mapas interactivos con Folium.  
   - Cada apartado muestra indicadores detallados de rendimiento de las tiendas, comparaciones y hallazgos principales.

4. **Resultados y Conclusiones**  
   - Informe final sobre qué tienda presenta un rendimiento más bajo y se recomienda cerrar.  
   - Justificación basada en ingresos, calificaciones y comportamiento de productos.

5. **Instrucciones de Uso**  
   - Clonar o descargar este repositorio.  
   - Instalar dependencias con:  
     ```
     pip install -r requirements.txt
     ```
     o usando los comandos dentro del archivo Jupyter Notebook (`!pip install ...`).
   - Ejecutar el archivo `AluraStoreLatam.ipynb` en Jupyter Notebook o en VS Code (con la extensión de Jupyter) para reproducir el análisis y generar las visualizaciones.

6. **Posibles Problemas**  
   - Conexión a internet necesaria para leer los archivos CSV desde GitHub.  
   - Asegurarse de tener permisos de escritura para que Folium pueda guardar los mapas interactivos en formato HTML.

¡Gracias por visitar este repositorio y explorar el análisis de Alura Store Latam!
