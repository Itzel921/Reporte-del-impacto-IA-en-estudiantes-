#Análisis de Impacto de la IA en Estudiantes de la carrera de ISI

## 🎯 Propósito del Programa
Este programa, implementado en un Jupyter Notebook (`logica/reporte.ipynb`), tiene como objetivo procesar, limpiar, analizar y visualizar los datos obtenidos de una encuesta sobre el impacto y uso de la Inteligencia Artificial (IA) en estudiantes. El script calcula estadísticas descriptivas, genera visualizaciones clave para cada variable y evalúa las correlaciones matemáticas entre ellas.

---

## 📚 Librerías Utilizadas
El análisis hace uso de las siguientes librerías de Python:
- **`pandas` (`pd`)**: Para la lectura, manipulación y limpieza de datos estructurados (DataFrames).
- **`numpy` (`np`)**: Para cálculos numéricos y generación de arreglos/intervalos.
- **`matplotlib.pyplot` (`plt`) y `matplotlib.ticker`**: Para la creación de gráficas 2D (histogramas, gráficos de barras) y configuración de ejes.
- **`seaborn` (`sns`)**: Para aplicar estilos visuales avanzados y construir el mapa de calor de correlaciones.

---

## ⚙️ Flujo de Trabajo (Pipeline de Datos)

### 1. Configuración de Visualización
Se establecen los parámetros globales (`rcParams`) para garantizar la uniformidad de todas las gráficas generadas:
- Tamaño de figura estándar: `10x5`.
- Fuente base: `'DejaVu Sans'`.
- Eliminación de bordes superior y derecho.
- Tema visual: `whitegrid` con paleta `muted` de *Seaborn*.

### 2. Carga y Limpieza Inicial de Datos
El programa busca y lee el archivo `encuestaf.csv`. Durante la carga:
- Se eliminan columnas irrelevantes para el análisis estadístico, tales como: `"Marca temporal"`, `"Género"`, `"¿Qué semestre estás cursando?"`, `"¿Cuántos años tienes?"` y `"expediente"`.

### 3. Renombramiento y Normalización de Variables
Para facilitar la manipulación del código, las preguntas

