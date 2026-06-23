# Dashboard de Análisis de Accidentes de Tránsito (2021 - 2022)

## 🌎 Idioma

> 📖 [Read in English](README.md) | [Leer en Español](README_ES.md)

## 📌 Descripción del Proyecto

Este repositorio contiene un Dashboard Interactivo desarrollado en Excel diseñado para analizar los registros históricos de seguridad vial durante los años 2021 y 2022. El objetivo principal de este proyecto es transformar datos brutos en una herramienta de inteligencia visual intuitiva que permita a las partes interesadas identificar perfiles de alto riesgo, monitorear tendencias estacionales y optimizar la asignación de recursos de respuesta ante emergencias.

---

## 💼 Contexto de Negocio y Requerimientos

Para simular un escenario de análisis del mundo real, el cuadro de mando se construyó para cumplir con una matriz de requerimientos específicos solicitada por el **Comité de Seguridad de Operaciones**. Las necesidades operativas principales incluyeron:

- **KPIs Principales:** Una vista centralizada del total de víctimas junto con desgloses específicos por la gravedad del accidente (Fatal, Serio, Leve) y sus respectivos porcentajes sobre el total.
- **Segmentación por Vehículo:** Identificación de los tipos de vehículos de mayor riesgo y distribución completa de las víctimas por categoría de transporte.
- **Análisis Temporal y de Tendencias:** Un sistema de seguimiento mensual que compara directamente las métricas del Año Actual (CY) frente a las líneas base históricas del Año Anterior (PY).
- **Infraestructura y Entorno:** Distribuciones visuales de las víctimas segmentadas por el Tipo de Vía y las condiciones de la Superficie de la Carretera.
- **Matriz Contextual:** Análisis cruzado que interseca las zonas geográficas (Urbano vs. Rural) con las categorías temporales (Día vs. Noche).

---

## 🛠️ Herramientas y Funciones Avanzadas de Excel Utilizadas

- **Limpieza y Transformación de Datos:** Uso de funciones para reemplazar valores, remover duplicados, tratamiento de nulos y lógica personalizada para la segmentación de fechas y horarios.
- **Motor de Agregación:** Tablas Dinámicas y Gráficos Dinámicos para la estructuración de datos multidimensionales.
- **Diseño de Interfaz y UI/UX:** Tarjetas de KPI personalizadas, Segmentadores (Línea de tiempo y filtros cruzados por categoría), Formato Condicional y paletas de colores cohesivas para maximizar la legibilidad y el escaneo visual.

---

## 🚀 Características Clave del Dashboard

1. **Panel de Filtros Interactivo:** Filtra sin esfuerzo todo el reporte por períodos específicos (Años/Trimestres) o zonas geográficas (Urbano vs. Rural).
2. **Líneas de Tendencia Mensual (CY vs PY):** Detecta instantáneamente picos estacionales al observar el comportamiento de las métricas a lo largo de ciclos multianuales.
3. **Métricas de Víctimas a un Vistazo:** Gráficos de anillo dinámicos y tarjetas de métricas que resaltan el peso proporcional de los accidentes fatales, serios y leves.
4. **Mapeo de Riesgo Contextual:** Comparaciones de múltiples ejes que muestran cómo se comportan las víctimas según los diferentes estados de la superficie vial (seco, mojado, nieve) y las condiciones de iluminación.

---

## 📁 Estructura del Repositorio

- `Road_Accident_Dashboard.xlsx` — El libro de trabajo de Excel completo que contiene los datos brutos, la arquitectura de las tablas dinámicas y la capa de presentación final.
- `Road_Accident_Analysis.pdf` — Una previsualización del dashboard para revisión rápida.
- `README.md` — Documentación del proyecto y resumen de los requerimientos del negocio.

---

## 💡 Insights Clave Entregados

- Se aislaron las clases de vehículos específicas que aportan la cantidad máxima absoluta de víctimas registradas.
- Se mapeó la intersección crítica de los tipos de infraestructura (por ejemplo, calzadas únicas frente a rotondas) donde alcanzan su punto máximo los accidentes graves.
- Se resaltaron cambios de comportamiento significativos en el número de víctimas al contrastar los trayectos diurnos urbanos con los viajes nocturnos rurales.

---

_Desarrollado por [Esteban Gomez Ibarra](https://github.com/esteboutlier)_
