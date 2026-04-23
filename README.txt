## 🌍 Análisis Global de Emisiones de CO₂ (Power BI)
Este repositorio contiene un proyecto de exploración y visualización de datos centrado en las emisiones de dióxido de carbono (CO₂) a nivel mundial. El objetivo es identificar tendencias históricas, principales fuentes de emisión y el impacto relativo por país mediante indicadores per cápita.

📊 Descripción del Dashboard
El análisis permite visualizar la evolución de la huella de carbono global, desglosando la información por:

Fuentes de Emisión: Carbón, petróleo, gas, cemento y flaring.

Geografía: Análisis por país utilizando códigos estándar de región.

Indicadores: Emisiones totales vs. emisiones per cápita para entender la eficiencia y el impacto poblacional.

📂 Estructura de los Datos
Para este proyecto se utilizaron y cruzaron las siguientes fuentes:

Data.csv (Fuente: Kaggle): * Contiene el dataset principal de emisiones de CO₂.

Incluye métricas anuales, datos por tipo de combustible y crecimiento porcentual de emisiones.

all.csv (Data Complementaria): * Archivo de apoyo utilizado para el enriquecimiento de datos.

Permite mapear los nombres de los países con sus códigos Alpha-2 y Alpha-3, facilitando la integración geoespacial en Power BI.

PRACTICA.pbix (Solución):

Archivo maestro de Power BI que contiene el modelo de datos, las medidas DAX y el diseño visual del dashboard.

🛠️ Proceso de ETL y Modelado
Extracción: Carga de archivos CSV y conexión de datos.

Transformación: * Limpieza de valores nulos en registros históricos.

Unión (Join) entre el dataset de emisiones y el archivo complementario mediante el nombre del país para estandarizar códigos ISO.

Modelado: Creación de una jerarquía geográfica y temporal para permitir el filtrado dinámico (Drill-down).

📈 Visualizaciones Clave
El dashboard (basado en la captura de guía proporcionada) incluye:

Mapas Coropléticos: Para identificar rápidamente los países con mayor volumen de emisiones.

Gráficos de Líneas: Para observar la tendencia de crecimiento de CO₂ a lo largo de las décadas.

Treemaps/Gráficos de Barras: Para comparar qué tipo de fuente (ej. Carbón vs. Gas) predomina en cada región.

🚀 Cómo utilizar este repositorio
Descarga el archivo PRACTICA.pbix.

Asegúrate de tener instalado Power BI Desktop.

(Opcional) Si deseas replicar el modelo desde cero, utiliza los archivos Data.csv y all.csv realizando el cruce por la columna de país.
