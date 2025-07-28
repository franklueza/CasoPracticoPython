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

### Fuente de datos
 https://tidyr.tidyverse.org/reference/who.html 

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
 
## Visualizaciones del Dashboard

### Dashboard. Distribución y tendencia de casos
![Dashboard Tuberculosis 1](https://raw.githubusercontent.com/franklueza/CasoPracticoPython/refs/heads/main/Dashboard1.png)

### Dashboard. Incidencia global y grupos vulnerables
![Dashboard Tuberculosis 2](https://raw.githubusercontent.com/franklueza/CasoPracticoPython/refs/heads/main/Dashboard2.png)
# Reporte: Análisis de la Situación de la Tuberculosis (1995–2013)

## Resumen
A través de una revisión integral de datos desglosados por país, edad, género y método diagnóstico, se identificaron tendencias clave en la evolución de la incidencia mundial. Este informe presenta los hallazgos más relevantes y una proyección frente a la meta de la ONU para 2025.

---

## 1. Tendencias globales y tasa de incidencia

- **Incremento acumulado del 509%** entre 1995 y 2008.
- **Disminución del 19%** de 2009 a 2013.
- Proyección 2025: **78.8% de los casos por cada 100,000 habitantes**, alejándose de la **meta ONU (-50%)**.

---

## 2. Distribución geográfica

- **China (20.8%)**, **India (16.8%)** e **Indonesia (6.8%)** concentraron la mayoría de casos en 2013.
- Priorización geográfica es clave para combatir la enfermedad de forma efectiva.

---

## 3. Segmentación por género y edad

- **64.4% de los casos** en las mujeres.
- Grupo más afectado: **15–24 años**, seguido por **25–34** y **35–44**.
- Enfocar estrategias en adultos jóvenes de género femenino.

---

## 4. Métodos de diagnóstico

- **Esputo pulmonar negativo**: 72.4% de los diagnósticos.
- Le siguen esputo positivo (15.3%) y extrapulmonares (7.6%).
- Alta dependencia de pruebas respiratorias.

---

## Recomendaciones Estratégicas

1. Reforzar la vigilancia en países con alta carga.
2. Enfocar intervenciones en población femenina joven.
3. Diversificar métodos diagnósticos en zonas vulnerables.
4. Actualizar políticas frente al escenario proyectado.
5. Impulsar alianzas regionales, educación comunitaria y trazabilidad.


