# README.md
# Análisis Automatizado y Consolidado de Datos Presupuestarios y Cotizaciones Oficiales de Paraguay

Este repositorio contiene notebooks y scripts para la descarga, procesamiento, consolidación y análisis multianual de datos presupuestarios y de cotizaciones oficiales del Paraguay. El flujo de trabajo es completamente reproducible y automatizado, facilitando la obtención de información lista para análisis y conciliaciones.

---

## Características Principales

- **Descarga automática** de archivos ZIP de datos presupuestarios desde fuentes oficiales, organizados por año.
- **Extracción y organización** de archivos CSV por año y eliminación de archivos comprimidos para optimizar el almacenamiento.
- **Filtrado y consolidación** de datos presupuestarios relevantes (ejemplo: Ministerio de Defensa Nacional) en un único archivo multianual.
- **Extracción automatizada** de cotizaciones oficiales del Banco Central del Paraguay, manejando particularidades históricas de formato.
- **Consolidación** de todos los archivos de cotizaciones en un único DataFrame y archivo CSV para su análisis.
- **Exportación** de resultados en archivos CSV para análisis posteriores.

---

## Estructura del Repositorio

- `PYTHON_DATALCH_FINAL.ipynb`: Proceso ETL completo (descarga, extracción, filtrado y consolidación de datos presupuestarios y cotizaciones).
- `Obtener montoVigente.ipynb`: Análisis consolidado del presupuesto vigente multianual.
- `Obtener montoEjecutado.ipynb`: Análisis multianual del monto ejecutado por objeto de gasto y mes.

---

## Requisitos

- Python 3.x
- Selenium
- pandas
- beautifulsoup4
- Google Colab para ejecución en la nube. En caso de que se desee correr en un entorno local, se debe modificar el código acorde a la necesidad.

---

## Instrucciones de Uso

1. Ejecuta `PYTHON_DATALCH_FINAL.ipynb` para descargar y preparar los datos presupuestarios y de cotizaciones.
2. Utiliza los notebooks de análisis (`Obtener montoVigente.ipynb` y `Obtener montoEjecutado.ipynb`) para generar reportes consolidados.
3. Los resultados se exportan en archivos CSV listos para análisis adicionales.

---

## Resultados Esperados

- Archivos CSV consolidados con datos presupuestarios y cotizaciones oficiales.
- Reportes tabulares que permiten comparar la evolución del presupuesto y la ejecución por año y objeto de gasto.
- Base sólida para auditoría, control de gestión y análisis financiero.

---

## Licencia

Este proyecto se distribuye bajo licencia MIT. Consulta el archivo LICENSE para más detalles.
