# CasoPracticoPython

### Prerrequisitos
Este caso práctico requiere utilizar Python y paquetes asociados.  

### Planteamiento
Usted trabaja para la Organización Mundial de la Salud como analista de información. El consejo directivo se reunirá para revisar los datos más recientes de casos de tuberculosis.  

Los datos han llegado con la información más reciente y necesitan prepararse para mostrar la información a los líderes de la organización.  

El objetivo de la junta es entender la situación actual de la tuberculosis, y las tendencias por región e identificar países que han sido casos de éxito y aquellos que necesiten mayor apoyo con la gestión de la enfermedad.  

Tenga en mente las metas de la ONU para terminar con la Tuberculosis para 2025:  

- Reducción en la tasa de incidencia del 50% (2015 vs. 2025).
- Reducción en 75% el número de muertes (2015 vs. 2025).

### Instrucciones 
- Revisa la documentación de los conjuntos de datos “who” y “population” en: https://tidyr.tidyverse.org/reference/who.html 
- Limpia los datos para colocarlos de acuerdo con la definición de datos ordenados en:  https://cran.r-project.org/web/packages/tidyr/vignettes/tidy-data.html 
- Una vez limpias ambas tablas combínelas para crear un solo conjunto de datos. 
- Elabore un reporte ejecutivo con gráficas que le permitan mostrar los puntos más relevantes de la situación actual, tendencias, y regiones parauna exposición comprensiva de los datos. 
- Realice recomendaciones basado en las conclusiones del análisis.

### Información general del dataset
- Registros: 226,072
- Columnas: 9
- Variables principales:
- country: nombre del país.
- year: año del registro.
- cases: número de casos de tuberculosis.
- gender: género de las personas (masculino, femenino).
- agegroup: grupo de edad (algunas filas no lo tienen).
-method: método de diagnóstico (ej. esputo pulmonar positivo).
- population: población del país en ese año.

### Resumen general de casos y población por año
Casos Totales (cases): Se sumaron los casos de tuberculosis reportados por año.   
Población Total (population): Se sumó la población total registrada para cada año.  
Tasa de Incidencia (incidencia): Se calculó como:  
incidencia = casos / casos totales × 100,000  
Este cálculo permite observar la proporción de casos de tuberculosis en relación con el tamaño de la población, lo que facilita comparaciones entre años. 

Grafica

Tendencia General:  
- Aumento inicial: Entre 1995 y 2006, la tasa de incidencia aumenta significativamente.
- Pico máximo: El año 2007 registra la tasa más alta, con aproximadamente 45 casos por 100,000 habitantes.
- Disminución posterior: Después de 2007, la tasa de incidencia comienza a disminuir gradualmente, aunque permanece elevada.



