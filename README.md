# 📊 Análisis Exploratorio y Visualización de Ventas de Vehículos

Este repositorio contiene una práctica integradora dividida en dos partes. En la primera, se realiza un análisis exploratorio de datos (EDA) con Python, aplicando técnicas de limpieza, transformación y visualización. En la segunda, se trabaja en Power BI, generando un informe interactivo con visualizaciones dinámicas basadas en un dataset de ventas de vehículos.

---

## 🧪 Parte I: Análisis Exploratorio de Datos en Python

### 📝 Descripción  
A partir del dataset `car_evaluation.xlsx`, se realiza un análisis exploratorio con `pandas`, `seaborn` y `matplotlib`, abordando la calidad de los datos, renombrado de columnas y generación de visualizaciones. El objetivo es preparar la información y obtener hallazgos relevantes antes de su uso en herramientas de visualización.

### 📂 Archivos incluidos  
- `car_evaluation.xlsx`  
  Dataset original con información categórica sobre evaluación de vehículos.

- `enunciado.HEC_Ventas_Coches.pdf`  
  Documento con la descripción completa de la práctica integradora.

### 🔍 Tareas realizadas  
- Carga y limpieza inicial del dataset  
- Renombrado de columnas a nombres más descriptivos (`buying`, `maint`, `doors`, `persons`, etc.)  
- Análisis exploratorio de datos (EDA)  
- Visualizaciones con `matplotlib` y `seaborn`  
- Generación de informe automático con `pandas-profiling`  
- Conclusiones sobre la calidad de los datos y recomendaciones

---

## 📈 Parte II: Visualización de Datos en Power BI

### 📝 Descripción  
Se trabaja con el archivo `Conjunto de datos (Adquisición de vehículos).xlsx` importado en Power BI. Se aplican transformaciones desde Power Query, se crean medidas DAX y se construyen visualizaciones para analizar las operaciones de venta por categorías clave como número de puertas, tamaño del maletero y rango de precios.

### 📂 Archivos incluidos  
- `Conjunto de datos (Adquisición de vehículos).xlsx`  
  Dataset preparado para ser importado en Power BI.

- `HEC_Ventas_Coches.pbix`  
  Archivo Power BI con todas las visualizaciones y transformaciones aplicadas.

### 🔍 Tareas realizadas  
- Transformación de tipos de datos  
- Creación de nueva columna condicional `Rng_Precios`  
- Conversión y limpieza de campos (`Nº de Puertas`, `Tamaño maletero`)  
- Traducción de categorías al español  
- Ocultación de campos innecesarios  
- Creación de tabla de medidas DAX  
- Visualizaciones: ventas por puertas, maletero y rango de precios  
- Personalización de gráficos, ejes, leyendas y colores  
- Pruebas con distintos tipos de visualización

---

## 🛠️ Habilidades aplicadas  
- Análisis exploratorio de datos (EDA) con Python  
- Limpieza y transformación de datos con `pandas`  
- Visualización con `seaborn` y `matplotlib`  
- Automatización de reportes con `pandas-profiling`  
- Modelado y limpieza de datos en Power Query  
- Creación de medidas DAX y dashboards interactivos en Power BI

---
###⚠️ Notas importantes
Los archivos .xlsx y .pbix deben descargarse para poder visualizarse correctamente. GitHub no ofrece vista previa para estos formatos, por lo que verás el mensaje "Ver en bruto" al intentar abrirlos desde el navegador.

---
## 👤 Autor  
**Esteban Miller**  
Proyecto desarrollado como parte de mi formación en análisis de datos, aplicando herramientas de Python y Power BI.
