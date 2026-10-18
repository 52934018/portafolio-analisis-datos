# 📊 Proyecto Final de Business Intelligence: Análisis de Gestión de Talento Humanos (HR)

Repositorio oficial del proyecto integral de Business Intelligence aplicado al análisis y gestión del talento humano, combinando modelado relacional, transformación de datos, cálculo de métricas avanzadas y visualización ejecutiva.

---

## 🚀 Descripción del Proyecto
Este proyecto simula un caso real de análisis de recursos humanos utilizando un conjunto de datos (*Dataset* de RRHH) y su respectivo diccionario de datos. El objetivo principal fue transformar datos crudos en información estratégica para la toma de decisiones gerenciales, abarcando desde la preparación y el modelado de datos hasta la creación de un informe interactivo de dos páginas en Power BI y la generación de recomendaciones de negocio.

---

## 🛠️ Tecnologías y Herramientas Utilizadas
* **Microsoft Excel (Power Pivot):** Creación del modelo analítico relacional, definición de tablas de hechos y dimensiones, y validación de claves primarias/foráneas.
* **Fórmulas y Transformaciones en Excel:** Limpieza, normalización de textos, corrección de tipos de datos, manejo de fechas y creación de columnas derivadas directamente en el entorno de Excel.
* **Lenguaje DAX:** Creación de medidas calculadas (Antigüedad promedio, Tasa de ausentismo, Total de empleados activos, Satisfacción laboral, etc.).
* **Power BI Desktop:** Desarrollo de un dashboard ejecutivo interactivo de dos páginas con enfoque en KPIs, segmentadores y buenas prácticas de diseño y jerarquía visual.

---

## 📋 Estructura y Desarrollo del Proyecto

### 1. Modelado Analítico y Limpieza de Datos
* Se estructuró el modelo de datos identificando claramente la **Tabla de Hechos** y las **Tablas de Dimensiones** (`EmpleadoDim`, `RendimientoDim`, etc.).
* Se aplicaron procesos de limpieza y normalización: corrección de tipos de datos (fechas, textos, numéricos), estandarización de nombres propios, estados civiles, géneros y posiciones, asegurando la integridad de las claves (`DeptID`, `ManagerID`, `PositionID`).

### 2. Análisis con Medidas DAX
Se desarrollaron medidas analíticas clave para evaluar el comportamiento del personal, tales como:
* **Antigüedad Promedio / Años en el Puesto**
* **Nivel de Satisfacción Laboral**
* **Tasa de Ausentismo**
* **Conteo de Empleados Activos y Desvinculados**

### 3. Reportes y Dashboards Interactivos (Power BI)
El desarrollo incluye un reporte ejecutivo estructurado en dos páginas principales:
* **(Dashboard 1 De Talento Humano - Resumen General):** Tarjetas de KPIs clave (Total de empleados, satisfacción, empleados activos, antigüedad y ausentismo), segmentadores interactivos por ubicación (estados), área, género y estado del empleado, junto con gráficos de distribución por departamento y diversidad étnica.
* **(Dashboard 2 Análisis de Desempeño y Compensación):** Evaluación del rendimiento promedio por departamento, análisis del salario promedio, distribución por fuentes de reclutamiento (*Indeed*, *LinkedIn*, etc.) y un gráfico de dispersión cruzando compensación vs. desempeño.

---

## 📈 Informe y Conclusiones Estratégicas

* **Resumen Ejecutivo:** El análisis de la fuerza laboral revela áreas críticas de oportunidad en la retención del talento y la optimización de las fuentes de reclutamiento de alto rendimiento.
* **Hallazgos Principales:** Se observan diferencias en el desempeño general y los niveles de satisfacción laboral según la fuente de reclutamiento y el departamento, lo que permite identificar patrones relevantes para el análisis de la gestión del talento humano.
* **Recomendaciones para RRHH:** 
  1. Potenciar los canales de atracción que arrojan empleados con mayor permanencia y mejor desempeño.
  2. Implementar planes de acción en los departamentos con mayor tasa de ausentismo o menor satisfacción laboral.

---

## 📁 Archivos del Repositorio
* `HRDataset_DATA.xlsx`: Archivo de Excel con el modelo relacional (Power Pivot) y los datos limpios.
* `Proyecto_Final_Excel_Avanzado_PowerBl.pbix`: Archivo fuente del reporte interactivo en Power BI.

---
*Desarrollado como parte del portafolio profesional de análisis de datos y Business Intelligence.*
